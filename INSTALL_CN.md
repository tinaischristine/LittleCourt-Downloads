# 安装小朝会

需要 macOS 14.0 或更新版本。v0.1.0 安装包包含 Apple Silicon 和 Intel 两种架构。本次验收使用 Apple Silicon，Intel 真机启动待验证。

1. 从 [Releases](https://github.com/tinaischristine/LittleCourt-Downloads/releases) 下载最新版的 `LittleCourt-v版本号.zip`。草稿测试期间请使用提供给你的测试包。
2. 在访达中双击 ZIP 解压。
3. 将「小朝会.app」拖入「应用程序」。
4. 在「应用程序」中双击小朝会。运行只需 macOS。

当前开发包使用 ad-hoc 签名，尚未公证，macOS 首次启动时可能拦截。确认文件来源可信后，可以先在访达中按住 Control 点击应用，若系统提供「打开」确认项，按提示操作。较新的 macOS 请先尝试打开应用，再进入「系统设置 → 隐私与安全性」，使用系统提供的「仍要打开」。若系统没有提供此选项，请通过下方渠道反馈。[Apple 的安全打开说明](https://support.apple.com/zh-cn/102445)

### 备份与更新

在小朝会工具栏打开「备份」菜单，选「导出备份」，把 JSON 存到便于找回的位置。导入将替换当前工作台，确认前可查看摘要。应用会在替换前保存本地备份。

更新时先导出一份备份，退出小朝会，再将新版拖入「应用程序」并选择「替换」。相同应用标识的新版继续使用原来的本地数据。再次打开后检查现有项目及任务。

### 反馈

请在 [Issues](https://github.com/tinaischristine/LittleCourt-Downloads/issues) 提供 macOS 版本、芯片类型、应用版本和复现步骤。提交截图前请隐去私人项目名称与内容。
