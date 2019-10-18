NNPACK for Unikraft
===================

This is the port of NNPACK for Unikraft as external library.

## Build
NNPACK depends on the following libraries, that need to be added to `Makefile` in this order:
* `pthreads`, e.g. `pthread-embedded`
* CXX standard library, e.g. `libunwind`, `compiler-rt`, `libcxxabi`, `libcxx`
* `libc`, e.g. `newlib`
* `intel intrinsics`, e.g. `intel-intrinsics`
* `pthreadpool`
* `fxdiv`
* `psimd`
* `fp16`


Please refer to the `README.md` as well as the documentation in the `doc/`
subdirectory of the main unikraft repository.
