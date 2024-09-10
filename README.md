# XCoder - 易用的Supercell资产处理程序
可以多平台处理来自任何Supercell家游戏资产文件。

### 特性:
- SC和PNG互转格式;
- 压缩或解压CSV数据文件。

### 安装使用教程（大陆最好开梯子）：
- Windows端:
  - 到[官网](https://www.python.org/downloads/)下载 Python 3.7 或更新版本;
  - 安装 Python。在安装过程中，勾选以下选项："Add Python to PATH"、"Install pip"、"Install py launcher"、"Associate files with Python" 以及 "Add Python to environment variables";
  - 从发布页面下载 XCoder，并解压缩；
  - 找到解压后的目录，安装所需模块: pip install -r requirements.txt;
  - 运行 "main.py" 文件。

### 启用 KTX 模块

**Supercell 在游戏的新版本中也使用了 KTX 纹理，因此建议执行此步骤。

要启用 KTX 模块，你需要从官方网站获取 "PVRTexToolCLI" 二进制文件: https://developer.imaginationtech.com/pvrtextool/。

然后将 CLI 放置在主脚本文件夹中的 "system/bin/" 目录下。

## 致谢
该工具基于原版 [XCoder](https://github.com/MasterDevX/xcoder), 作者：[MasterDevX](https://github.com/MasterDevX)</br>

特别感谢 [spiky_Spike](https://github.com/spiky-s) 提供的开发支持。
