# x64dbg

<img width="100" src="./src/bug_black.png"/>

一个开源的Windows二进制调试器，旨在进行恶意软件分析和你没有源代码的可执行文件的逆向工程。有许多可用的功能和一个全面的插件系统 来添加你自己的功能。你可以在博客上找到更多信息!

## 屏幕截图

<!-- TODO: recreate Chinese screenshots -->

![main interface (light)](https://github.com/x64dbg/x64dbg/.github/screenshots/cpu-light.png)

![main interface (dark)](https://github.com/x64dbg/x64dbg/.github/screenshots/cpu-dark.png)

| ![graph](https://github.com/x64dbg/x64dbg/.github/screenshots/graph-light.png) | ![memory map](https://github.com/x64dbg/x64dbg/.github/screenshots/memory-map-light.png) |
| :--: | :--: |

## 安装与使用

1. 下载快照，并将其解压缩到您的用户具有写权限的位置。
2. _可选择_ 使用 `x96dbg.exe` 来注册一个shell扩展，并在桌面上添加快捷方式。
3. 如果你想调试一个32位的可执行文件，你现在可以运行 `x32\x32dbg.exe` 或者 `x64\x64dbg.exe`来调试一个64位的可执行文件。如果你不确定，你可以随时运行 `x96dbg.exe` 并在那里选择你的架构。

你也可以通过几个简单的步骤 自己编译 x64dbg!

## 软件特色
1.开源
2.直观和熟悉的新用户界面
3.类似C的表达式解析器
4.DLL和EXE文件的全功能调试(TitanEngine)
5.IDA般的侧边栏与跳跃箭头
6.IDA样的指令令牌高亮(高亮寄存器等)
7.存储器映射
8.符号观
9.线程视图
10.内容敏感的注册查看
11.完全可定制的配色方案
12.动态识别模块和串
13.进口重构集成(青蟹)
14.快反汇编(BeaEngine)
15.用户数据库(JSON)征求意见，标签，书签等。
16.不断增长的API插件的支持
17.可扩展的，可调试的脚本语言自动化
18.多数据类型的内存转储
19.基本调试符号(PDB)的支持
20.动态堆栈视图
21.内置汇编(XEDParse)
22.查看你的补丁，并将它们保存到磁盘
23.内置的十六进制编辑器
24.查找内存模式

## 链接
[Github Snapshot](https://github.com/x64dbg/x64dbg/releases/latest)
