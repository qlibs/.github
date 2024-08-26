> Can running tests at compile-time be disabled for faster compilation times?

  When `-DNTEST` is defined static_asserts tests wont be executed upon inclusion. Note: Use with caution as disabling tests means that there are no guarantees upon inclusion that the given compiler/env combination works as expected.
