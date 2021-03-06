# Cesium
A C-like type-, memory- and thread-safe systems programming language with zero-cost object-orientation.

Its name is after the chemical element Cesium(Cs).

It is heavily inspired by C, and tries to support all its features. It is also inspired by Java, and implements a subset of its object-orientation model, while trying to remove the space- and time-costs of such abstractions. Some of its syntax is inspired by Kotlin, Python, JavaScript/TypeScript and Rust.

## Design Principles
In decreasing order of importance:
1. Type-safety;
2. Memory-safety;
3. Thread-safety;
4. [Suckless philosophy](https://suckless.org/philosophy);
5. <q>Keep it simple stupid</q>;
6. Principle of least astonishment;
7. C interoperability;
8. Runtime space efficiency;
9. Runtime time efficiency;
10. Binary size efficiency;

## Building
To build the most recent Syntax.md file, first make sure you have the Alchemist grammar2md submodule initialized properly. You can use the `--recursive` flag when cloning the project to do this:

```shell
git clone --recursive https://github.com/cesium-language/lang-spec.git
```

Alternatively, if you already have the project checked out, you can initialize the submodules manually:

```shell
git submodule update --init
```

Once you have the most recent Alchemist grammar2md submodule, run the build script:

```shell
./build.py
```

## License
<pre>
Copyright (c)  2021-2022  Natan Junges.
Permission is granted to copy, distribute and/or modify this document
under the terms of the GNU Free Documentation License, Version 1.3
or any later version published by the Free Software Foundation;
with no Invariant Sections, no Front-Cover Texts, and no Back-Cover Texts.
A copy of the license is included in the section entitled "<a href="LICENSE.FDL">GNU
Free Documentation License</a>".
</pre>

The code snippets and the build script are licensed under the [Unlicense](UNLICENSE).
