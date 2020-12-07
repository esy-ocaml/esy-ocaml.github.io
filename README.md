# Esy OCaml

Esy OCaml is a collection of tools and libraries that help consume
tools and libraries from the OCaml ecosystem, with as little
modifications. 

## Why?

A lot of components are involved in making native development with
Reason and OCaml a seamless experience. While [`esy`](https://esy.sh)
support opam packages out-of-the-box, there are tools like `libffi`,
`pkg-config` etc. that need to be packaged in a way users can
conveniently and reliably consume.

One way of making sure these tools are present, with the same version
installed, is to package them for esy.

Along with such packages that form the toolchain, some opam packages
need patches so that 

1. They work on Windows
2. They install inside Esy Sandbox.

## Consolidating these problems under a single project

This project is an attempt to address these problems. Currently, it
contains

1. [Esy Opam Overrides](https://github.com/esy-ocaml/esy-opam-override)
2. [The OCaml compiler](https://github.com/esy-ocaml/ocaml)
3. [The Multicore compiler](https://github.com/esy-ocaml/ocaml-multicore)
4. [Esy Solve CUDF](https://github.com/esy-ocaml/esy-solve-cudf)
5. [pkg-config](https://github.com/esy-ocaml/yarn-pkg-config)
6. [libffi](https://github.com/esy-ocaml/libffi)
7. [Bos](https://github.com/esy-ocaml/bos)
8. [Angstrom](https://github.com/esy-ocaml/angstrom)
9. [Flow parser](https://github.com/esy-ocaml/flow-parser)

## Contributing

   Please see individual projects for more info. Feel free to ask on
   the [Reason server](https://discord.gg/reasonml) on the Discord
