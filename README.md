

# lz4

## Build with MSVC

### 构建Release

```bash
> cd build/cmake
> cmake -B build -G Ninja  -DCMAKE_BUILD_TYPE=Release -DCMAKE_INSTALL_PREFIX=D:\devtools\lz4.1.9.4
```

### 构建Debug
```bash
> cmake -B build -G Ninja  -DCMAKE_BUILD_TYPE=Debug -DCMAKE_INSTALL_PREFIX=D:\devtools\lz4.1.9.4\debug\
```


## mingw64环境编译

```bash
> cd build/cmake
> mkdir build & cd build
> cmake .. -G Ninja  -DCMAKE_BUILD_TYPE=Release -DCMAKE_INSTALL_PREFIX=D:\devtools\lz4.1.9.4
```