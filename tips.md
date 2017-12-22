# vim 使用tip

### 编写python程序

1. 自动插入头信息：
    - `#!/usr/bin/env python`
    - `# coding=utf-8`
- 输入`.`或按`TAB`键会触发代码补全功能
- `:w`保存代码之后会自动检查代码错误与规范
- 按`F6`可以按`pep8`格式对代码格式优化
- 按`F5`可以一键执行代码


### 多窗口操作

1. 使用`:sp + 文件名`可以水平分割窗口
- 使用`:vs + 文件名`可以垂直分割窗口
- 使用`Ctrl + w`+(h/j/k/l)可以快速在窗口间切换
2. vim-tmux(normal mode)
- 使用Ctrl+l在右侧打开终端
- 使用Ctrl+j在底部打开终端
- 使用Shift+l清除所打开终端屏幕
- vim-tmux模式下，Ctrl+a+(h/j/k/l)进行切换当前工作区
3. vim YouCompleteMe自动补全
- 使用<up> <down>或者<tab>键进行选择

### 编写markdown文件

1. 编写markdown文件(`*.md`)的时候，在normal模式下按 `md` 即可在当前目录下生成相应的`html`文件
- 生成之后还是在normal模式按`fi`可以使用firefox打开相应的`html`文件预览
- 当然也可以使用万能的`F5`键来一键转换并打开预览
- 如果打开过程中屏幕出现一些混乱信息，可以按`Ctrl + l`来恢复

### 快速注释

- 按` \ ` 可以根据文件类型自动注释