# JYSDL

基于游泳的鱼开发的JYSDL的lua模块，由C++主程序调用。
C++主要提供游戏需要的视频/音乐/键盘等API函数，供Lua调用。
Lua提供全部游戏逻辑代码，以方便代码的修改与测试。
显示主地图/场景地图/战斗地图部分用C++ API实现以保证运行效率。
