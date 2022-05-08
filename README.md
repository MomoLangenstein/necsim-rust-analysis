# necsim-rust analysis &emsp; [![Gitpod Ready-to-Code]][gitpod]

[Gitpod Ready-to-Code]: https://img.shields.io/badge/Gitpod-ready-blue?logo=gitpod
[gitpod]: https://gitpod.io/#https://github.com/MomoLangenstein/necsim-rust-analysis

## Introduction

`necsim-rust-analysis` contains the analysis scripts and results for the neutral coalescence biodiversity simulation library [`necsim-rust`](https://github.com/MomoLangenstein/necsim-rust).

The build and run the analysis scripts, you have to modify the attached version of `necsim-rust`:
```shell
$ git submodule init
$ git submodule update

$ git apply Cargo.toml.patch --allow-empty
$ git apply Cargo.lock.patch --allow-empty

$ rm -rf necsim-rust/analysis
$ cp -r analysis necsim-rust/analysis
```
Now, you can find all the analysis scripts and results in the `necsim-rust/analysis` folder.

## License

Licensed under either of

 * Apache License, Version 2.0
   ([LICENSE-APACHE](LICENSE-APACHE) or http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license
   ([LICENSE-MIT](LICENSE-MIT) or http://opensource.org/licenses/MIT)

at your option.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.
