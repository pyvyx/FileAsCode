# File as code

## A program to convert files into C arrays
Raw conversion supports every single file type, that conversion is just to get the binary representation of a file as an array. Uncompressed files `-u` or `--uncompress` are currenty only supported for following image formats:  
 - JPEG
 - PNG
 - GIF (*comp always reports as 4-channel)

If you need support for more image types checkout the [c++ version](https://github.com/pyvyx/FileAsCode/tree/cpp).

# Build
``` bash
git clone https://github.com/pyvyx/FileAsCode.git
```
``` bash
cd FileAsCode
```
``` bash
go build -ldflags "-s -w" -o fac.exe
```

# Troubleshooting

If you encounter any issues while building or using FileAsCode checkout the [c++ version (preferred)](https://github.com/pyvyx/FileAsCode/tree/cpp) or the [zig version](https://github.com/pyvyx/FileAsCode/tree/zig). Build instructions are in their respective READMEs.

```bash
git checkout cpp
```
```bash
git checkout zig
```