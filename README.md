# Knorpel

Knorpel is a scripting language for Rust. It is inspired by [notes on smaller Rust](https://boats.gitlab.io/blog/post/notes-on-a-smaller-rust/) by Boats.

Knorpel lets you write applications in a dynamic Rust-like language, that exposes less of annoying low-level details, while enjoying the ecosystem of high-performance high-assurance libraries written in Rust.

## Highlights

* **Familiar syntax:** curly braces, `fn`, ugly closure syntax etc.
* **Familiar memory ownership semantics:** moving, sharing, borrowing values.
* **Dynamic type system:** algebraic data types, pattern matching, const generics, dynamically constructucted types and expressions.
* **Fully async:** launch and pause coroutines from anywhere, all I/O is asynchronous. 
* **Excellent embedding API:** instead of linking your Rust crate through C FFI that throws away all type details into `%your_scripting_language%`, embed the Knorpel script inside your pure-Rust application.
* **Publish Knorpel libraries on crates.io:** a tool (TBD) packages your script into a build.rs that compiles it into the Rust code and connects it with the dependencies, so you don't have to write any boilerplate.

## Status

Join bikeshedding on Telegram: [@rustscript](https://t.me/rustscript).
