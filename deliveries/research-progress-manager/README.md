# 科研进度管理器 · Windows 便携版

适用于 **Windows 10 / 11，64 位 x64**。已包含 Python 和界面运行环境，无需另外安装 Python，解压后即可离线使用。

## 下载与启动

1. [点击下载完整便携包（约 28 MB）](https://github.com/quocquangnguyen66-cmyk/codex-workspace/raw/refs/heads/delivery-research-progress-manager-20261016/deliveries/research-progress-manager/ResearchProgressManager-Windows-portable.zip)。
2. 在 Windows 的“下载”文件夹找到 `ResearchProgressManager-Windows-portable.zip`，右键选择“全部解压缩”，目标目录填写 `C:\Users\hh\Desktop\互动软件`。
3. 解压后打开该文件夹，双击 **科研进度管理器.exe**。首次启动时，可以选择是否导入默认科研任务。

请完整解压后再运行。EXE、`research_progress_manager` 文件夹和 `rpm-root.json` 需要放在一起。

## 数据与使用

- 默认内容包含 2 个研究体系、134 个叶子任务和 6 个 PDA 样品；初始进度均为 0。
- 你的科研数据库保存在 `user_data`，备份保存在 `backups`，导出文件保存在 `exports`。
- 下载包不含用户数据库。升级已有版本前请备份原文件夹，并保留原来的数据目录。
- 如果启动没有反应，运行解压目录中的 `诊断启动.bat`，将窗口里的错误文字反馈给开发者。
- `运行自检.bat` 可以检查本机运行环境，不会修改长期科研数据库。

## 完整性与验证范围

文件：`ResearchProgressManager-Windows-portable.zip`

大小：28,152,822 字节

SHA-256：

```text
fa474235e72734a3db78e0c222d894d7f8cd796481b3b963e65a5dbfa38fab85
```

应用测试已通过；Windows 便携运行环境和启动器已在 Wine 下通过自检，包括中文及空格路径。尚未在实体 Windows 电脑验证显示缩放及系统文件关联。

软件源码随便携包提供。第三方组件的许可证说明也包含在包内。
