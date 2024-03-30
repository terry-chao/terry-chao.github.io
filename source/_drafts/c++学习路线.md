---
title: c++学习路线
date: 2023-11-26 16:00:37
tags:
---
```c++
#include <iostream>
int main () {
    std::cout << "hello world" << std::endl;
}
```
# 简介
## 标准委员会 

c++有两部分组成，语言和标准库
c++和部分语言不同的是，大多数使用的不是官方（标准委员会）实现。
虽然目前委员会主席为微软背景。
c++有三大编译器，也就是三大实现。

- 微软主导的MSVC 
    由于MSVC集成在Visual Studio所以
    一般使用Visual Studio进行开发。

- 开源软件主导的GCC
    在Linux平台上，一般自带gcc，由于linux和gcc都属于GUN下，所以大部分的gcc都在linux下开发。也有开发者将gcc移植到windows上，参考MinGW，推荐msys2配置。

- 苹果主导的Clang
    和gcc属于GUN相似但是不同的是，Clang项目属于LLVM。作者是大名鼎鼎的Latner。clang在windows和unix-like系统都可以开发。Clang项目完全兼容gcc而且提供了更宽松的lisense和更友好的提示。由于该特性，在Mac上，`gcc`命令甚至只是clang的别名。

领域：
由于c++语言的时代背景和高性能的特性，决定了其复杂的领域。大致覆盖到了军工，航天，银行，游戏引擎，图形，AI等等。大部分依赖c++的公司为需要较高实时性和高性能，如果大部分的比较底层。比如彭博社（财经类），微软（系统内核），UE（游戏引擎），OpenCascade（几何引擎）。

国内现状：

1. Qt
2. 音视频
3. 游戏引擎
3. 图形开发
4. 机器人

## 资料 

- 书籍：
《C++ Primer》 第五版
《Effctive C++》
- 视频：
Cherno系列视频
- 网站
[编程指北](https://csguide.cn/cpp/)
[c++全栈](https://www.stibel.icu/)
