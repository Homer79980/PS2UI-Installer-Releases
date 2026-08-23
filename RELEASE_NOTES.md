# PS2UI Engine Installer 0.1.1

这是首个公开的 Windows 多引擎离线安装器版本。

## 本版内容

- 自动识别项目，或手动选择 Unity、Godot、Cocos Creator、Unreal Engine。
- 支持一次勾选多个引擎，并分别选择项目目录。
- 安装、重复检查、修复、备份、回滚和卸载边界保护。
- 已安装项目显示“已经安装、未做修改”，不会误报为新的安装完成。
- 安装完成页按引擎给出启用、导入、生成目录和九宫拉伸步骤。
- 安装器离线运行，不全盘扫描，不上传项目路径，不执行项目脚本。

## 内置版本

- Unity：Ps2Unity 2.1.1，Unity 2022.3
- Godot：Ps2Godot 0.1.1，Godot 4.6.2
- Cocos Creator：Ps2Cocos 0.1.1，Creator 3.8.5 至 3.8.8
- Unreal Engine：Ps2Unreal 0.1.1，Epic Launcher UE 5.7/5.8 Win64

## 下载后

1. 下载 `PS2UI-Engine-Installer-0.1.1.exe` 和同名 SHA-256 文件。
2. 校验 EXE 后双击运行。
3. 关闭目标编辑器，选择项目并安装。
4. 安装完成后按页面提示，在对应编辑器中启用插件并导入 PS2UI 导出包。

Photoshop 导出插件不包含在本 EXE 中，请从 [PS2UI Releases](https://github.com/Homer79980/PS2UI/releases/latest) 单独安装 PS2UI CCX。

## 已知边界

当前 EXE 未进行 Authenticode 签名，Windows SmartScreen 可能显示未知发布者。请以本 Release 的 SHA-256 为准。Unreal 只保证 Epic Launcher 的 5.7/5.8 Win64，源码编译版和其它平台不在本版支持范围内。

完整安装、使用、字体、资源复用、九宫、卸载和故障排查说明见仓库 [README.md](./README.md)。
