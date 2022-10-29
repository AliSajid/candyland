
# Candyland

[![Continuous integration](https://github.com/AliSajid/candyland/actions/workflows/ci.yaml/badge.svg?branch=main&event=push)](https://github.com/AliSajid/candyland/actions/workflows/ci.yaml)
![crates.io package](https://img.shields.io/crates/v/candyland.svg)
![GitHub tag (latest SemVer)](https://img.shields.io/github/v/release/AliSajid/candyland)
![Crates.io](https://img.shields.io/crates/l/candyland)

[![Contribute with Gitpod](https://img.shields.io/badge/Contribute%20with-Gitpod-908a85?logo=gitpod)](https://gitpod.io/#AliSajid/candyland)
[![Code of Conduct: Contributor Covenant](https://img.shields.io/badge/code_of_conduct-contributor_covenant-14cc21)](https://github.com/EthicalSource/contributor_covenant)



This project aims to develop a small cross-platform command line interface (CLI) for playing the game Candyland. The game is a simple board game for children, and the goal of this project is to provide a simple and fun way to play the game and to simulate the game for large scale data analysis

## Builds

| Platform | Rust Version |Status |
| -------- | ------ | ------ |
| Linux    | stable <br/> beta <br/> nightly <br/> MSRV (1.64.0) | ![Ubuntu x Stable Rust](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/8efd954bf5e8bf390d2795885dcdfd05/raw/ubuntu-stable.json) <br/> ![Ubuntu x Beta Rust](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/8efd954bf5e8bf390d2795885dcdfd05/raw/ubuntu-beta.json) <br/> ![Ubuntu x Nightly Rust](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/8efd954bf5e8bf390d2795885dcdfd05/raw/ubuntu-nightly.json) <br/> ![Ubuntu x MSRV Rust](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/8efd954bf5e8bf390d2795885dcdfd05/raw/ubuntu-msrv.json) |
| Windows  | stable <br/> beta <br/> nightly <br/> MSRV (1.64.0) | ![macos x Stable Rust](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/8efd954bf5e8bf390d2795885dcdfd05/raw/windows-stable.json) <br/> ![macos x Beta Rust](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/8efd954bf5e8bf390d2795885dcdfd05/raw/windows-beta.json) <br/> ![macos x Nightly Rust](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/8efd954bf5e8bf390d2795885dcdfd05/raw/windows-nightly.json) <br/> ![macos x MSRV Rust](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/8efd954bf5e8bf390d2795885dcdfd05/raw/windows-msrv.json) |
| macOS    | stable <br/> beta <br/> nightly <br/> MSRV (1.64.0) | ![Windows x Stable Rust](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/8efd954bf5e8bf390d2795885dcdfd05/raw/macos-stable.json) <br/> ![Windows x Beta Rust](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/8efd954bf5e8bf390d2795885dcdfd05/raw/macos-beta.json) <br/> ![Windows x Nightly Rust](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/8efd954bf5e8bf390d2795885dcdfd05/raw/macos-nightly.json) <br/> ![Windows x MSRV Rust](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/AliSajid/8efd954bf5e8bf390d2795885dcdfd05/raw/macos-msrv.json) |

## Current Status

The current status of the project is planning. I will rapidly iterate over the basic design implementation and then move on to the more complex features. The current plan is to implement the following features:

* [ ] Basic game play without special spaces
* [ ] Add special rules including character cards
* [ ] Basic game simulation with unattended play
* [ ] Basic game statistics
* [ ] Basic game analysis
* [ ] Basic game AI
* [ ] Add the decision rules for the AI



## License

`candyland` is distributed under the terms of both the MIT license and the Apache License (Version 2.0).
Please see [LICENSE-APACHE](LICENSE-APACHE) and [LICENSE-MIT](LICENSE-MIT) for details.

## Contributing

While this is a single crate with a single focus, We're happy to accept contributions. Pull Requests are welcome. Please see [CONTRIBUTING.md](CONTRIBUTING.md) for details.
You can also use the link below to open an IDE in the cloud to contribute to this project.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#AliSajid/candyland)
