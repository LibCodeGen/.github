# Lib Code Gen
The focus of this organization is to be the instruction set generating porition of a small, modular and reusable code generation framework called [Lib Code Quick](https://github.com/LibCodeQuick). It serves as the master repo for instruction set generation independent of the ABI, runtime libraries or final hardware targets.

The largest address space for the smallest version of the library set is intended to be able to generate code succeessfully in 8 MiB of RAM. Larger versions can be added later but even newer platforms benefit from having codebases that fit into the level-1 code cache anyway so why make things huge for no reason?

## Companion Organizations
- [Lib Link Gen](https://github.com/LibLinkGen) repos holds the object code, library code, startup code and other related codes for each target.
- [Lib Build Gen](https://github.com/LibBuildGen) houses a reusable backend for making an implementation-independent library for making Make utilities and their equivalents.
