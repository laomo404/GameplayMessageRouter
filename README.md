# GameplayMessageRouter
- The Gameplay Message Router, originally by Epic Games, was designed for communication between unconnected gameplay objects but only supported Unreal Engine 5.0.
- This version has been updated to ensure compatibility with Unreal Engine 5.3+, while retaining the original functionality. Compatible with Windows.

## Supported Engine Versions
The release below is the compiled plugin.
- [5.7](https://github.com/laomo404/GameplayMessageRouter/releases/tag/5.7) 
- [5.6](https://github.com/laomo404/GameplayMessageRouter/releases/tag/5.6) 
- [5.5](https://github.com/laomo404/GameplayMessageRouter/releases/tag/5.5) 
- [5.4](https://github.com/laomo404/GameplayMessageRouter/releases/tag/5.4) 
- [5.3](https://github.com/laomo404/GameplayMessageRouter/releases/tag/5.3)

## Source Code Getting Started

To integrate the Gameplay Message Router into your project, follow these simple steps:

1. Obtain the Lyra game project from the [Fab](https://www.fab.com/zh-cn/listings/93faede1-4434-47c0-85f1-bf27c0820ad0) .

2. Copy the 'GameplayMessageRuntime' plugin from the Lyra project's plugins folder and paste it into your project's plugins folder (YourProject/Plugins/GameplayMessageRuntime).
![WhereIsFolder](https://raw.githubusercontent.com/laomo404/GameplayMessageRouter/docs/Docs/WhereIsFolder.png)

3. Add 'GameplayMessageRuntime' to your `YourProject.Build.cs` file.
![WhereIsFile](https://raw.githubusercontent.com/laomo404/GameplayMessageRouter/docs/Docs/WhereIsFile.png)
![HowToAdd](https://raw.githubusercontent.com/laomo404/GameplayMessageRouter/docs/Docs/HowToAdd.png)

4. Regenerate your project's solution files.

## Supported Platforms

- Windows
- Mac
- Linux

## Network Replication Support

Not Supported

---
#### Reference Github @imnazake
- [API Example](https://github.com/imnazake/gameplay-message-router)
