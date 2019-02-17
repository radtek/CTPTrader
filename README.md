# CTPTrader

一. 项目简介
1. CTPTrader是一个商品期货与股指期货交易软件，封装CTP接口，内含C++源码（QT开发）和编译好的.exe文件，可以直接使用。
2. 如果想要在此基础上更改，需要安装VS2013 和 qt-opensource-windows-x86-msvc2013-5.8.0。
3. 通过这个项目我学会了封装CTP接口和理解了事件驱动编程核心本质。


二. 项目说明
1. 该项目参考了github上的cppvnpy，cppvnpy是C++版本的VNPY，详细内容见cppvnpy。
2. 起初我想学习python版本的期货交易框架VNPY，但VNPY环境配置复杂，学习效果不佳，直到有一天我在github上看到了cppvnpy，通过对cppvnpy的学习，我学会了事件驱动编程的核心，起初我使用qt-opensource-windows-x86-mingw530-5.8.0.exe直接开发，但导入CTP库一直错误，只能使用msvc版本开发，需要先装VS2013作为msvc版QT的编译器。
3. 目前该项目由我一个人开发，很多功能还没有实现，将在后期完善。
4. CTPTrader的设计初衷是给不会编程的量化投资者使用，项目内有编译好的.exe文件，可双击直接使用，双击显示缺少dll文件请先安装VS环境。对于有编程功底的人来说，可以在此基础上增加你想要的功能。

三. 项目致谢
1. 感谢cppvnpy项目作者。

四. 联系方式
1. 微信： 17512015950
