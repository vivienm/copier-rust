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
* [Nix](https://nixos.org/) flake.
* Support for [GitHub actions](https://github.com/features/actions) and [GitHub pages](https://pages.github.com/).

## Quickstart

First, [install Copier](https://copier.readthedocs.io/en/stable/#installation).

Then, to create a new project based on this template, run the following command and fill in the form:

```bash
copier copy 'https://github.com/vivienm/copier-rust' path/to/your/project
```

Go to the project directory, update the dependencies and format the code:

```bash
cargo upgrade --incompatible
cargo update
cargo fmt
```

Run the tests:

```bash
just ci
```

You are now ready to start coding!

Later, to update your project as this template evolves, run:

```bash
copier update --skip-answered
```
