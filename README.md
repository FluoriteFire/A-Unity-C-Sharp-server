# A-Unity-C-Sharp-Server
使用socket实现C#服务器，可用于unity服务端，目标支持大规模MMO游戏

目前实现了一个网络框架，通讯协议已经完成，可连接Mysql（需导入特定的包）。

通讯基于Json，使用了微软的Json解析库

可自行构造Proto,即用于交流的类

对于特定的消息，想要实现对应操作，只需要写MsgHander,在其实现

## TODO
1. 目前是select服务器，后续想改成异步服务器（需解决锁的问题）
2. 优化逻辑，提高并行数
