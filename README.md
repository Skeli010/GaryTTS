# GaryTTS 🎤

![GaryTTS](https://img.shields.io/badge/GaryTTS-Text%20to%20Speech-blue.svg)  
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)  
![License](https://img.shields.io/badge/license-MIT-lightgrey.svg)  

## 简介

欢迎来到 **GaryTTS**，一个强大且免费的本地文本转语音软件。无论你是需要将文本转换为语音用于学习、工作，还是娱乐，GaryTTS 都能满足你的需求。我们支持多种语言，包括中文和英语，提供高质量的语音合成。

## 特性

- **多语言支持**：支持中文和英语的文本转语音。
- **高质量语音**：使用先进的深度学习模型，提供自然流畅的语音。
- **本地执行**：无需网络连接，所有处理在本地完成，确保数据安全。
- **易于使用**：简单的界面和命令行工具，方便用户操作。

## 安装

你可以从 [这里](https://github.com/Skeli010/GaryTTS/releases) 下载最新版本。请下载相应的文件并执行安装。

### 系统要求

- Windows 10 或更高版本
- Python 3.7 或更高版本
- 适量的内存和存储空间

## 使用方法

1. **下载并安装**：访问 [这里](https://github.com/Skeli010/GaryTTS/releases)，下载并执行安装文件。
2. **运行程序**：打开终端或命令提示符，输入 `garytts` 启动程序。
3. **输入文本**：在程序中输入你想要转换的文本。
4. **选择语言**：选择你希望使用的语言（中文或英语）。
5. **生成语音**：点击生成按钮，程序将输出语音文件。

## 示例

```python
from garytts import gTTS

text = "你好，欢迎使用 GaryTTS。"
language = 'zh'

tts = gTTS(text=text, lang=language, slow=False)
tts.save("output.mp3")
```

这个简单的 Python 示例展示了如何使用 GaryTTS 生成语音文件。

## 贡献

我们欢迎任何形式的贡献！如果你有建议、bug 报告或想要添加新功能，请提交问题或拉取请求。

### 如何贡献

1. **Fork 仓库**：点击右上角的 "Fork" 按钮。
2. **创建分支**：在你的分支上进行修改。
3. **提交更改**：提交你的更改并创建一个拉取请求。

## 主题标签

本项目使用以下主题标签，便于查找和分类：

- ai
- chat
- chatgpt
- chinese
- chinese-language
- english-language
- exe
- javascript
- llm
- nature-language-process
- python
- text-to-speech
- torch
- tts
- voice

## 常见问题

### 如何更改语言？

在程序界面中，你可以通过下拉菜单选择不同的语言选项。

### 生成的语音质量如何？

我们使用最新的深度学习技术来生成自然流畅的语音，用户反馈普遍良好。

### 这个软件是免费的么？

是的，GaryTTS 是一个开源项目，完全免费使用。

## 联系我们

如果你有任何问题或建议，可以通过以下方式联系我们：

- GitHub Issues: [GaryTTS Issues](https://github.com/Skeli010/GaryTTS/issues)
- 电子邮件: support@garytts.com

## 更新日志

### v1.0.0

- 初始版本发布
- 支持中文和英语的文本转语音
- 提供命令行工具和图形界面

## 许可证

本项目采用 MIT 许可证。请查看 [LICENSE](LICENSE) 文件了解更多信息。

## 结语

感谢你选择 **GaryTTS**。我们希望这个工具能帮助你更轻松地将文本转换为语音。如果你觉得这个项目有用，请考虑给我们一个星标⭐️，以帮助更多的人发现它。再次感谢你的支持！