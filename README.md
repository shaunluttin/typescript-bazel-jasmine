Windows Set Up Steps

1. Install `bazel` for Windows: `choco install bazel`
2. Install Visual C++ Tools (the `VC/tools/MSCV/` full path is relevant to `BAZEL_VC`)
3. Run `bazel build ...:all` from the repository root.
4. If that doesn't work, set `BAZEL_SH` and `BAZEL_VC`.

Note that Bazel does not currently work with WSL or the WSL bash.

See also: https://docs.bazel.build/versions/master/install-windows.html
