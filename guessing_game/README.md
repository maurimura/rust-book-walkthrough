# Notes about guessing game

```rust
use std::io;
```

Brings `io` library into scope. (Similar to JS `import` ?)

`io` comes from the standar library (`std`)

```rust
    let mut guess = String::new();
```
The `::` syntax in the `::new` line indicates that `new` is an _assosiated function_ of the type `String`. (_static method_ in some languages) 

To use an external dependency, include it inside `[dependencies]` in the `Cargo.toml`


`cargo doc --open` looks good
