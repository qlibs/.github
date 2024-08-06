## [Qlibs++ - Modern C++ libraries](https://qlibs.github.io)

> ### Mission

- #### Quality

  - C++20+ ([gcc](https://gcc.gnu.org), [clang](https://clang.llvm.org), [msvc](https://visualstudio.microsoft.com/vs/features/cplusplus)\*)
  - Compile-time self testing (can be disabled with `-DNTEST`)
  - Compiles cleanly with `-Wall -Wextra -pedantic -fsantize=memory/undefined | /WX /W4`
  - Focused on composability and declarativeness (easy to use hard to misuse)

- #### Performance

  - Compile-time driven optimizations
  - x86-64\* driven optimizations and benchmarks (No `virtual`, No `RTTI`)
  - Optimized compilation times

- #### Simplicity

  - Single header/module (including `documentation` and `tests`)
  - Single purpose ([unix philosophy](https://en.wikipedia.org/wiki/Unix_philosophy))
  - Minimal dependencies (none or [STL](https://en.wikipedia.org/wiki/Standard_Template_Library)*)
  - Minimal API (available on https://compiler-explorer.com)

\* Selected libraries

> MIT License - https://opensource.org/license/mit

---

### FAQ

- Are Qlibs libraries free to use?

    > Yes, free forever.

- Can Qlibs libraries be used in comercial projects?

    > Yes, license permits comerical usage - see License for details.

- Is the aim for Qlibs libraries to be standarized?

    > The main goal for the libraries is to solve specific problem in the best possible way.
      Standarization, in some cases, may or may not follow but it's not the goal.

- Are Qlibs libraries ABI stable?

    > ABI stability is not the main priority for the libraries - see Mission.

- How to report bugs/issues?

    > Github issues are prefered way for reporting bugs/issues.

- How to contribute?

    > Contriubutions are always welcome -
      see https://docs.github.com/en/pull-requests for details.

      Note: `main` branch is the stable branch.

- How to add/request a new feature/library?

    > Github discussions - https://github.com/orgs/qlibs/discussions -
      sre prefered way to discuss/add/request new features/libraries.

      Note: Mission goals are required to be fulfiled for new libraries.

- How Qlibs libraries differ from Boost/Poco/... libraries?

    > Both: Boost and Poco libraries are established and powerful C++ libraries.
      Qlibs libraries have different, more narrowed, focus and goals.
