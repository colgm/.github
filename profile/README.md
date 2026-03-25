# <img src="https://raw.githubusercontent.com/colgm/colgm/0cfeb8a67d7a98543cf06d108f07b5ed45508e41/doc/colgm.svg" height="50px"/> Welcome to Colgm Compiler Project

Colgm aims to be a simple, easy-to-use and easy-to-maintain programming language.
It will let you write relatively safe code without too much cognitive load.

Mainly support native targets.
Target supported now is [__LLVM (text IR)__](https://llvm.org/).

Now nightly-builds are available:

- [__macos-aarch64-nightly-build__](https://github.com/colgm/colgm/releases/tag/macOS_nightly)
- [__linux-x86_64-nightly-build__](https://github.com/colgm/colgm/releases/tag/linux_nightly)
- [__windows-x86_64-nightly-build__](https://github.com/colgm/colgm/releases/tag/windows_nightly)

```rust
use std::io::{ io };

func main() -> i32 {
    io::stdout().out("hello world!).endln();
    return 0;
}
```

## Language Guide

See simple language guide in:

- [language guide (English)](https://github.com/colgm/colgm/blob/main/doc/guide/tutorial.md)
- [语言指南（中文版）](https://github.com/colgm/colgm/blob/main/doc/guide/tutorial_zh.md)

See library reference in:

- [standard library reference](https://github.com/colgm/colgm/blob/main/doc/guide/std_library_reference.md)
- [compiler library reference](https://github.com/colgm/colgm/blob/main/doc/guide/compiler_library_reference.md)
