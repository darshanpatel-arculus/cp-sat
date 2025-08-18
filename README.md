This is a fork of the original [cp_sat](https://github.com/KardinalAI/cp_sat) repository. As of writing, the original repo supports OR-TOOLS v9.0 where as this fork is updated to support v9.14

# Google CP-SAT solver Rust bindings

Rust bindings to the Google CP-SAT constraint programming solver.

## Prerequisites
- A C++ compiler (e.g. clang)
- protobuf compiler + libprotobuf

Invoke Cargo using `RUSTFLAGS='-Clink-arg=-lprotobuf' cargo <command>`.
The environment variable `ORTOOLS_PREFIX` is used to find include files and library files. If not setted, `/opt/ortools` will be added to the search path (classical search path will also be used).
