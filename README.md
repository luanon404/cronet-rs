> This project is considered 'complete' and is therefore no longer maintained. Contact me if you want to unarchive this project for whatever reason.

# cronet-rs 🦀

Bindings to the Chromium Networking Stack (a.k.a cronet) in Rust.

## Developers

First of all, clone the project:

```bash
$ git clone https://github.com/sleeyax/cronet-rs.git
$ cd cronet-rs
```

Then, follow the steps to build the project:

1. Get the latest cronet binaries: [build from source](https://chromium.googlesource.com/chromium/src/+/refs/heads/main/components/cronet/build_instructions.md) or download prebuilt binaries from [here](https://github.com/sleeyax/cronet-binaries/releases).
2. Place all `.h` header files in `src` and all binaries (`.so`, `.dll`, `.dylib`) in `bin`.
3. Run `cargo build`. This should trigger `bindgen` to (re)generate the bindings.

## Related projects

Other projects that are related to this project and might interest you:

- [Cronet bindings for C#](https://github.com/sleeyax/CronetSharp)
- [Cronet bindings for go](https://github.com/sleeyax/cronet-go)
- [NaïveProxy](https://github.com/klzgrad/naiveproxy)
