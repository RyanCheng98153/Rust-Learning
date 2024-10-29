# Rust Tutorial

## Library 
- install package
  - add by shell
    ```shell
    cargo add rand
    ``` 
  - or add dependency in `Cargo.toml`
    ```toml
    [package]
    name = "guessing_game"
    version = "0.1.0"
    edition = "2021"

    [dependencies]
    rand = "0.8.5"
    ```
- use package
  `use std::cmp::Ordering;`
