# Rust project template

An opinionated [Copier](https://copier.readthedocs.io/en/stable/) template for Rust projects.

## Features

* Pre-configured tools for code formatting, quality analysis, documentation and testing:
  * [rustfmt](https://rust-lang.github.io/rustfmt/)
  * [clippy](https://doc.rust-lang.org/nightly/clippy/)
  * [rustdoc](https://doc.rust-lang.org/rustdoc/)
  * [typos](https://github.com/crate-ci/typos)
  * [cargo-deny](https://github.com/EmbarkStudios/cargo-deny)
* Tests run with [just](https://github.com/casey/just).
* Support for [GitHub actions](https://github.com/features/actions) and [GitHub pages](https://pages.github.com/).

## Quickstart

Make sur all the [requirements](#requirements) are met, then:

```shell
copier 'https://github.com/vivienm/copier-rust.git' path/to/your/project
```

Or even shorter:

```shell
copier 'gh:vivienm/copier-rust' /path/to/your/new/project
```

## Requirements

To use this Copier template, you will need:

* [Git](https://git-scm.com/)
* [Python 3](https://www.python.org/)
* [Copier](https://copier.readthedocs.io/en/stable/)

### Copier

To install copier, you may follow its [installation instructions](https://copier.readthedocs.io/en/stable/#installation) or use [pipx](https://pipxproject.github.io/pipx/):

```shell
pipx install copier
```
