# Operating Systems / Deployment

* Linux. duh.
* BSD: not Linux^TM
  * Probably FreeBSD is best for personal use?
* TinyCoreLinux: everything is always in memory \(`tmpfs`\), persistence on boot / shutdown
* QubesOS: based on Xen hypervisor, run everything in separate VMs for maximum security
* Redox: open-source, not-Unix, written in Rust from scratch
* Fuchsia:
  * "Fuchsia is an open-source capability-based operating system currently being developed by Google."
  * "The GitHub project suggests Fuchsia can run on many platforms, from embedded systems to smartphones, tablets, and personal computers."
* RebbleOS: community effort to write a new OS for the discontinued Pebble smartwatches
* Nebulet: toy prototype of WASM based OS
  * "Under the hood, Nebulet is a microkernel that executes WebAssembly modules in ring 0 and a single address space to increase performance. This allows for low context-switch overhead, syscalls just being function calls, and exotic optimizations that simply would not be possible on conventional operating systems. The WebAssembly is verified, and due to a trick used to optimize out bounds-checking, unable to even represent the act of writing or reading outside its assigned linear memory.      The Cranelift compiler is used to compile WebAssembly to native machine code. Once compiled, there are no complex interactions between the application and the runtime \(unlike jit compilers, like v8\) to reduce surface area for vulnerabilities."



* Build tools:
  * Bazel: Open-source release of Google's build tool Blaze
    * distributed, multi-language, reproducible
    * like a modern `make`
  * Nix: Declarative package management
  * Bazel + Nix: [https://github.com/tweag/rules\_nixpkgs](https://github.com/tweag/rules_nixpkgs)
* Version control:
  * Git. duh.
  * Pijul: a patch/change-oriented VCS designed to fix issues with Git, while still maintaining performance



