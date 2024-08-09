## Qlibs++ - Modern C++ libraries

> ### Mission

- #### Quality

  - C++20+ ([gcc](https://gcc.gnu.org), [clang](https://clang.llvm.org), [msvc](https://visualstudio.microsoft.com/vs/features/cplusplus)\*)
  - Compile-time self testing upon include/import (can be disabled with `-DNTEST`)
    - Compiles cleanly with `-Wall -Wextra -pedantic -fsantize=memory/undefined/thread`
  - Focused on composability and declarativeness (`Easy to use hard to misuse`)

- #### Performance

  - Compile-time driven optimizations (`Don't pay for what you don't use`)
  - Arch\* driven optimizations and benchmarks (no [RTTI](https://en.wikipedia.org/wiki/Run-time_type_information))
  - Optimized compilation times ([benchmarks](https://qlibs.github.io/mp/))

- #### Simplicity

  - Single header/module (including `documentation` and `tests`)
  - Single purpose ([unix philosophy](https://en.wikipedia.org/wiki/Unix_philosophy))
  - Minimal dependencies (none or [STL](https://en.wikipedia.org/wiki/Standard_Template_Library)*)
  - Minimal API (available on https://compiler-explorer.com)

---

##### \* Selected libraries

<p align="right">
<a href="https://opensource.org/license/mit">MIT License</a>
</p>
