
Do you want to get started writing clientside applications in rust? Are you new to any or all of the following?

* Rust
* Compiling rust to WebAssembly
* Yew
* using ant-design-rust components

This folder is for you! This folder is an extremely simple example of using all four of the above technologies, so if you are new you can use this as the foundation for your web app or component.

Start with downloading this folder, compiling this folder successfully, then edit the source and iterate from there! Instructions for linux or Mac OS are below:

```bash
## download this folder
curl ... #TODO


# If you have not installed rust, add it. Don't
# worry about the host triple or toolchain selected.
#
# You do NOT need to use "sudo" to to do this step
# instead just run this command just as below
# as your default terminal user.
curl https://sh.rustup.rs -sSf | sh

# You'll need to add the WASM toolchain if you haven't
# done this step already. When this was written
# I do not think it was possible to get this target
# in the initial install but that may have changed.
rustup target add wasm32-unknown-unknown --toolchain nightly
```