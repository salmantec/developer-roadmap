# String

In Rust, `String` is a growable, mutable, owned, UTF-8 encoded string type. When Rustaceans refer to 'strings' in Rust, they usually mean the `String` and the string slice `str` types, not just one of those types. Both types are UTF-8 encoded. A `String` in Rust is similar to a string in other languages, but is not null-terminated at the end. Creation of a `String` can be done from a literal string with `String::from("Hello, world!")` or by converting a string slice with `"Hello, world!".to_string()`. String concatenations and manipulations are achieved via a multitude of methods such as `push_str()`, `push()`, `+` operator, `format!()` macro, etc.

Learn more from the following links:

- [What Is a String?](https://doc.rust-lang.org/book/ch08-02-strings.html?highlight=String#what-is-a-string)