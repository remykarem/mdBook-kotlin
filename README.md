# mdBook-kotlin

mdBook-kotlin is a fork from [mdBook](https://github.com/rust-lang/mdBook) that lets you create modern online books from Markdown files and run Kotlin examples from code snippets.

## Quick start

1. Install Rust [here](https://www.rust-lang.org/tools/install).

2. Install mdBook-kotlin:

    ```bash
    cargo install mdbook --git https://github.com/remykarem/mdBook-kotlin --bin mdbook-kotlin
    ```

3. Create a book:

    ```bash
    mkdir my-kotlin-book
    cd my-kotlin-book
    mdbook-kotlin init
    ```
   
## Development

1. Append `-dev` to `version = x.x.x` in `Cargo.toml`.

2. Install

   ```bash
   cargo install --path .
   ```

## License

All the code in this repository is released under the ***Mozilla Public License v2.0***, for more information take a look at the [LICENSE] file.

[User Guide]: https://rust-lang.github.io/mdBook/
[contribution guide]: https://github.com/rust-lang/mdBook/blob/master/CONTRIBUTING.md
[LICENSE]: https://github.com/rust-lang/mdBook/blob/master/LICENSE
