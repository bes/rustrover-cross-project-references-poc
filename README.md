# Proof-of-concept for broken cross-project references in RustRover

In RustRover, when using a multi-project Rust setup, it's currently not possible
to do "Find Usages" to find all usages of the given symbol.

Just open this project in RustRover, go to `project1/src/lib.rs` and try to do
"Find Usages" on the `add` function used inside the `add2` function.
