# 释放你的双手

> 提高按键效率，避免双手大幅运动

> 减少右下角方向键和右上角<kbp>delete</kbp>使用频率

**本教材只支持 MacOS，不过Windows 也可以用 karabiner 配置。**

1. 安装 [karabiner](https://pqrs.org/osx/karabiner/)
2. 下载 [https://raw.githubusercontent.com/onface/relax-your-hands/master/karabiner.json](https://raw.githubusercontent.com/onface/relax-your-hands/master/karabiner.json)
3. 将下载文件替换 `~/.config/karabiner/karabiner.json` 文件

## 组合键

- <kbd>right_commnad</kbd> + <kbd>i</kbd><kbd>k</kbd><kbd>j</kbd><kbd>l</kbd> 上 下 左 右
- <kbd>right_commnad</kbd> + <kbd>u</kbd><kbd>o</kbd> 向上翻页，向下翻页
- <kbd>right_commnad</kbd> + <kbd>;</kbd> 向前删除（使用 right_command ikjl 时候使用）
- <kbd>right_commnad</kbd> + <kbd>x</kbd><kbd>c</kbd><kbd>v</kbd> 撤销 剪贴 复制 粘贴
- <kbd>right_commnad</kbd> + <kbd>z</kbd><kbd>y</kbd> 撤销(undo) 重做(redo)
- <kbd>left_commnad</kbd> + <kbd>e</kbd> 回车
- <kbd>left_option</kbd> + <kbd>w</kbd> 切换大小写



## 技巧

- <kbd>right_command</kbd> + <kbd>a</kbd> 移动到行首
- <kbd>right_command</kbd> + <kbd>e</kbd> 移动到行尾
- <kbd>right_command</kbd> + <kbd>left_command</kbd> + <kbd>i</kbd> 移动到第一行
- <kbd>right_command</kbd> + <kbd>left_command</kbd> + <kbd>k</kbd> 移动到最后一行
- <kbd>right_command</kbd> + <kbd>h</kbd> 向前删除
- <kbd>right_command</kbd> + <kbd>d</kbd> 向后删除  (解决[Atom emmet 冲突](https://github.com/onface/relax-your-hands/issues/1))

## 替换键

### right_command  （必须）

<kbd>right_command</kbd> ~ <kbd>left_control</kbd> 配合组合键

### caps_lock

<kbd>caps_lock</kbd> 改为 向前删除


非必须项均可以通过 `Karabiner-Elements` 软件中的 `Simple Modifcations` 删除


[Github:onface/relax-your-hands](https://github.com/onface/relax-your-hands)
