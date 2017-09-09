# MinGW-and-Clang
MinGW and Clang

  - MinGW with gcc 4.9.2
  - Clang 3.7.1

MinGW是将GCC编译器和GNU Binutils移植到Win32平台下的产物，包括一系列头文件（Win32API）、库和可执行文件。简而言之，MinGW是Windows下的GCC。

Clang是一个C、C++、Objective-C和Objective-C++编程语言的编译器前端。它采用了底层虚拟机（LLVM）作为其后端。它的目标是提供一个GNU编译器套装（GCC）的替代品。Clang性能优异，还能针对用户发生的编译错误准确地给出建议。

## 安装 MinGW

  1. 解压后将 MinGW 文件夹复制到 C: 盘根目录。
  2. 添加 PATH 搜索路径 `C:\MinGW\bin`。
  3. 启动命令窗口，执行 `gcc --version`，看到 gcc 版本信息，则安装成功。

## 安装 Clang

  1. 执行 LLVM 安装程序，并选择将 LLVM 添加到 PATH。
  2. 启动命令窗口，执行 `clang -v`，看到 clang 版本号，则安装成功。
