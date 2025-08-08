# LibCodeGen
[QBE](https://c9x.me/compile/), the "Quick Back-End", is a code generator and optimizer that supports multiple processors and operating system ABI formats. Sadly, its text based language parser and assembly source output format made it not-so-quick and despite targetting hobbyist-level equipment, was unsuitable for some types of usage, such as JIT compilation.

## SQBE
The current attempt at reformatting the code base from QBE to something suitable for use in a library format, is [SQBE](https://github.com/LibCodeGen/sqbe).
