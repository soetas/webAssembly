# C

C编译器:

- [MinGW](https://www.mingw-w64.org/)
- [GCC](https://gcc.gnu.org/)
- [Visual C++](https://www.visualstudio.com/)
- [Clang](https://clang.llvm.org/)

> 实现定义行为(Implementation-defined behavior)

```sh
nodemon --exec gcc -o output -std=c11 main.c

nodemon --exec g++ -o output -O4 main.cpp

```

C标准版本: K&R C、C89(ANSI C)、`C99`、C11、C17、C23等

C程序运行机制: 编码 -> 编译生成后缀名为`.obj`的目标程序 -> 链接相关库函数生成`.exe`可执行文件 -> 运行

```c
// 预处理头文件
#include <stdio.h>
#include "stdlib.h"

int main() {
  wchar_t gender = '男';

  return 0;
} 

```

C标准头文件:

- stdio.h
- stdlib.h
- string.h
- stdint.h
- math.h
- stddef.h

> 溢位(overflow)

## C++

[c++ shell](https://cpp.sh/)

```cpp
#include <iostream>


int main() {


  
}

```

> 链接器
