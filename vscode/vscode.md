## 完全卸载VScode

### Windows

- 卸载，删除`C:\Users\username\.vscode` `C:\Users\username\AppData\Roaming\Code`

### Mac

- 删除`VScode.app`
- 删除`~/.vscode` `~/Library/Application Support/Code` `~/Library/Caches/com.microsoft.VSCode` `~/Library/Preferences/com.microsoft.VSCode-xxxxx` `~/Library/Logs/Code` `~/Library/Saved Application State/com.microsoft.VSCode.savedState`
## VScode

1. Windows添加一个自定义系统环境变量，e.g. name = myos value = win  
```shell
# cmd
echo %myos%
# powershell
$env:myos
```

2. 

## 插件

```
- C/C++ | C/C++ Extension Pack | C/C++ Themes
- Cmake | Cmake Tools
- IntelliCode | IntelliCode API Usage Examples
- latex workshop
- makefile tools
- markdown pdf | markdown preview enhanced
```

## 技巧

#### 标签页

- 新文件在新标签页打开

> `VScdoe`的预览模式，标签是斜体，此时打开新文件不打开新标签页，当有编辑之后，即退出预览模式，若不想启用预览模式，则按照以下设置：
取消勾选`workbench.editor.enablePreview`,`workbench.editor.showTabs`设置为`multiple`

- 在标签页之间切换
> `Ctrl(Cmd) + Tab`, `Ctrl + PageUp/PageDown`