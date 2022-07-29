# 🦀 Rust Template Project

:man: **Author:** @moralespanitz

*Follow me* :arrow_down:

<a href="https://twitter.com/moralespanitz">
<img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white"></a>

## Folder structure

This template contains the following parts:
- :file_folder: **book:** for data
- :file_folder: **doc:** for documentation
- :file_folder: **src:** for .rs code
- :file_folder: **tests:** for each test of code (with coverage)
- :file_folder: **tools:** addtional dependencies for project
- 📔 **Makefile.toml** like Makefile, but only execute `cargo make <task>`

## How to add code

Following the principle of Test Driven Development, the first part consist in create the test file and the implementation for fix this error.

## How to test code

```
moralespanitz$ cargo test
# For testing with foo word included in the name
moralespanitz$ cargo test foo

# Generate code coverage with
moralespanitz$ cargo make coverage
```

## How to generate documentation

```
moralespanitz$ cargo doc
```
Then, search inside target/doc folder index.html 

## How to generate book

First, need to install mdbook:

```
moralespanitz$ cargo install mdbook
```
For more information, see 🔗 [Documentation](https://rust-lang.github.io/mdBook/index.html)
