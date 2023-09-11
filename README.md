# disas

A beautiful (albeit slow) `objdump`-based disassembler.

![Example screenshot](screenshot.png)


## Usage

```shell
$ disas path/to/file
```

Instead of an absolute path or a relative path, you can use the name of any executable in PATH (e.g. `bash`) or the name of any library known by ldconfig (e.g. `libcrypto.so`).
