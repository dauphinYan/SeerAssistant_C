# SeerAssistant

基于C++的赛尔号巅峰辅助。

### 声明

本项目仅用于**技术研究与学习交流**，请勿用于任何商业用途。

所有相关资源版权归**上海淘米网络科技有限公司**所有。

如因滥用本项目造成法律纠纷，**责任由使用者自行承担**。

### 功能

- 捕获赛尔号（Flash端）网络通信中的数据包。
  
- 实时获取巅峰对战信息。

### 说明
- `SocketHook.dll`仅用作捕获网络通信中的数据包。

- `Injector.exe`为主程序。

- `Log/System`目录下存放程序运行时日志，日志等级分为`LogTemp`与`Error`两种。
  
- `Log/User`目录下存放对战信息。

### 运行

#### 编译 `SocketHook.dll`

编译 `SocketHook.dll` ，在终端中运行

```
mingw32-make（根据实际情况修改）
```

> 编译前，请确保你已安装 MinGW-w64，并已配置环境变量

#### 运行`Injector.cpp`

运行`Injector.cpp`（主程序），注意修改`targetExePath`为游戏启动路径。

### 环境

| 环境项   | 说明               |
| :------- | ------------------ |
| 操作系统 | Windows 11         |
| 编辑器   | Visual Studio Code |
| 编译器   | MinGW-w64          |