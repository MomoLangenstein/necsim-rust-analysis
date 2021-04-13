# necsim-rust analysis

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
