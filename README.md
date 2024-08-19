# Rust project template

An opinionated [Copier](https://copier.readthedocs.io/en/stable/) template for Rust projects.

## Features

* CLI and autocompletion with [clap](https://github.com/clap-rs/clap).
* Logs with [tracing](https://github.com/tokio-rs/tracing).
* Pre-configured tools for code formatting, quality analysis, documentation and testing:
  * [rustfmt](https://rust-lang.github.io/rustfmt/)
  * [clippy](https://doc.rust-lang.org/nightly/clippy/)
  * [rustdoc](https://doc.rust-lang.org/rustdoc/)
  * [typos](https://github.com/crate-ci/typos)
  * [cargo-audit](https://github.com/RustSec/rustsec/tree/main/cargo-audit)
* Task automation with [just](https://github.com/casey/just).
* Support for [GitHub actions](https://github.com/features/actions) and [GitHub pages](https://pages.github.com/).

## Quickstart

To install Copier, please follow the installation instructions [here](https://copier.readthedocs.io/en/stable/#installation).

Then, to create a new project based on this template, run:

```shell
copier copy 'https://github.com/vivienm/copier-rust' path/to/your/project
```

and fill in the form.

Go to the project directory, update the dependencies and format the code:

```shell
cargo upgrade --recursive
cargo fmt
```

Run the tests:

```shell
just ci
```

You are now ready to start coding!

Later on, if this template evolves and you want to update your project, run:

```shell
copier update --skip-answered
```
