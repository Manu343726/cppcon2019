This repository contains the slides of my CppCon 2019 talk "Next Generation
Unit Testing Using Static Reflection". The recorded talk is available at
YouTube [here](https://www.youtube.com/watch?v=8adO3fN1Igg).

## Talk description


> Unit testing is a widely accepted practice in the software engineering
> industry, which has been demonstrated to help reduce bugs in production and
> provide faster iteration cycles for development, helping with development
> trends such as agile development or continuous deployment.
>
> While being part of the core of modern development, C++ due to its current
> language limitations lacks a unit testing framework that's expressive and
> concise enough to keep developers focused around tests themselves and not
> around all the code needed to support the tests. Current unit testing
> solutions for C++ usually require arcane constructions through macros,
> intrusive changes in the tested codebase in the form of class hierarchies for
> easy mocking, and in some cases manual test registration.
>
> I present unittest, a proof of concept unit testing framework for C++14 based
> on Python's standard unittest package. unittest avoids the problems described
> above by using static reflection to figure out what code describes a unit
> test, and what library functions should be mocked as part of the test.
> Current C++14 implementation is based on tinyrefl, a libclang based static
> reflection tool, but the same concept will be possible to implement through
> future C++ reflection features like those proposed by the Reflection
> Technical Specification.

([link to schedule](https://cppcon2019.sched.com/event/SfsM?iframe=no))

## Contents

 - [`slides.md`](https://github.com/Manu343726/cppcon2019/blob/master/slides.md): Slides markdown sources 
 - [`slides.pdf`](https://github.com/Manu343726/cppcon2019/blob/master/slides.pdf): Slides rendered to PDF

The slides were rendered using the [Marp plugin for
VS-Code](https://github.com/marp-team/marp-vscode).

## References

 - [`tinyrefl` static reflection system](https://github.com/Manu343726/tinyrefl).
 - [`unittest` C++ proof of concept implementation](https://github.com/Manu343726/unittest).
 - [Python 3 `unittest` documentation](https://docs.python.org/3/library/unittest.html).

## License

All code snippets shown in the talk are published under the MIT Open Source
License. Check `tinyefl` and `unittest` repositories for the license details of
these projects.
