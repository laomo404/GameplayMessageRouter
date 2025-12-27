# GameplayMessageRouter
- The Gameplay Message Router, originally by Epic Games, was designed for communication between unconnected gameplay objects but only supported Unreal Engine 5.0.
- This version has been updated to ensure compatibility with Unreal Engine 5.3+, while retaining the original functionality. Compatible with Windows.

## 已编译版本下载  (Supported Engine Versions)
- The release below is the compiled plugin.
- 如果你只想使用，而不需要源码，点这里下载对应的版本即可
 <p align="left"> 
  <a href="https://github.com/laomo404/GameplayMessageRouter/releases/tag/5.7"> <img src="https://img.shields.io/badge/5.7-Download-success?style=for-the-badge&logo=unrealengine"> </a> <br>
  <a href="https://github.com/laomo404/GameplayMessageRouter/releases/tag/5.6"> <img src="https://img.shields.io/badge/5.6-Download-success?style=for-the-badge&logo=unrealengine"> </a> <br>
  <a href="https://github.com/laomo404/GameplayMessageRouter/releases/tag/5.5"> <img src="https://img.shields.io/badge/5.5-Download-success?style=for-the-badge&logo=unrealengine"> </a> <br>
  <a href="https://github.com/laomo404/GameplayMessageRouter/releases/tag/5.4"> <img src="https://img.shields.io/badge/5.4-Download-success?style=for-the-badge&logo=unrealengine"> </a> <br>
  <a href="https://github.com/laomo404/GameplayMessageRouter/releases/tag/5.3"> <img src="https://img.shields.io/badge/5.3-Download-success?style=for-the-badge&logo=unrealengine"> </a> <br>
</p>


## 源码用法 （Source Code Getting Started）
- 如果想要下载源码自行编译，可以参考下面的方法
- To integrate the Gameplay Message Router into your project, follow these simple steps:

1. Obtain the Lyra game project from the [Fab](https://www.fab.com/zh-cn/listings/93faede1-4434-47c0-85f1-bf27c0820ad0) .

2. Copy the 'GameplayMessageRuntime' plugin from the Lyra project's plugins folder and paste it into your project's plugins folder (YourProject/Plugins/GameplayMessageRuntime).
![WhereIsFolder](https://raw.githubusercontent.com/laomo404/GameplayMessageRouter/docs/Docs/WhereIsFolder.png)

3. Add 'GameplayMessageRuntime' to your `YourProject.Build.cs` file.
![WhereIsFile](https://raw.githubusercontent.com/laomo404/GameplayMessageRouter/docs/Docs/WhereIsFile.png)
![HowToAdd](https://raw.githubusercontent.com/laomo404/GameplayMessageRouter/docs/Docs/HowToAdd.png)

4. Regenerate your project's solution files.

## Supported Platforms

- ✅Windows
- ✅Mac
- ✅Linux

## Network Replication Support

Not Supported

---
#### Reference Github @imnazake
- [API Example](https://github.com/imnazake/gameplay-message-router)
