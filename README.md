# 猜数字游戏 (Guess Number)

一个用 C++ 编写的控制台猜数字小游戏。

## 功能
- 随机生成 1~100 的整数
- 玩家输入猜测，程序提示"偏大"或"偏小"
- 带输入校验，非法输入会提示重新输入
- 统计猜对所用次数

## 编译运行

### Windows (MinGW / MSVC)
```bash
g++ main.cpp -o guess.exe
guess.exe
