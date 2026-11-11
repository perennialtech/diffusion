# Diffusion runtime for Koharu

Prebuilt [stable-diffusion.cpp](https://github.com/leejet/stable-diffusion.cpp) shared libraries for [Koharu](https://github.com/perennialtech/koharu), built from the commit of [perennialtech/stable-diffusion.cpp](https://github.com/perennialtech/stable-diffusion.cpp) pinned in the release workflow.

The release workflow builds CUDA, HIP, Vulkan, and Metal variants for Windows, Linux, and macOS on pushes to `main` and when started manually. Linux builds run on Ubuntu 24.04 so the libraries load on hosts with glibc 2.39.

Generated binaries are published through this repository's [releases](https://github.com/perennialtech/diffusion/releases).

## License

This repository is dual-licensed under the [MIT License](LICENSE-MIT) or the
[Apache License, Version 2.0](LICENSE-APACHE), at your option.

Third-party code and dependencies retain their respective licenses.
