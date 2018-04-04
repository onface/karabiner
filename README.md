# 释放你的双手

> 提高按键效率，避免双手大幅运动

> 减少右下角方向键和右上角<kbp>delete</kbp>使用频率

**本教材只支持 MacOS，不过Windows 也可以用 karabiner 配置。**

1. 安装 [karabiner](https://pqrs.org/osx/karabiner/)
2. 下载 [https://raw.githubusercontent.com/onface/relax-your-hands/master/karabiner.json](https://raw.githubusercontent.com/onface/relax-your-hands/master/karabiner.json)
3. 将下载文件替换 `~/.config/karabiner/karabiner.json` 文件

## 组合键

- <kbd>right_commnad</kbd> + <kbd>i</kbd><kbd>k</kbd><kbd>j</kbd><kbd>l</kbd> 上 下 左 右
- <kbd>right_commnad</kbd> + <kbd>x</kbd><kbd>c</kbd><kbd>v</kbd> 撤销 剪贴 复制 粘贴
- <kbd>right_commnad</kbd> + <kbd>z</kbd><kbd>y</kbd> 撤销(undo) 重做(redo)


## 技巧

- <kbd>right_command</kbd> + <kbd>a</kbd> 移动到行首
- <kbd>right_command</kbd> + <kbd>e</kbd> 移动到行尾
- <kbd>right_command</kbd> + <kbd>left_command</kbd> + <kbd>i</kbd> 移动到第一行
- <kbd>right_command</kbd> + <kbd>left_command</kbd> + <kbd>k</kbd> 移动到最后一行
- <kbd>right_command</kbd> + <kbd>h</kbd> 向前删除
- <kbd>right_command</kbd> + <kbd>d</kbd> 向后删除  (解决[Atom emmet 冲突](https://github.com/onface/relax-your-hands/issues/1))
- <kbd>right_command</kbd> + <kbd>return_or_enter</kbd> 换行
- <kbd>right_command</kbd> + <kbd>fn</kbd> 换行

## 替换键

### right_command  （必须）

<kbd>right_command</kbd> ~ <kbd>left_control</kbd> 配合组合键

### caps_lock

<kbd>caps_lock</kbd> ~ <kbd>delete_or_backspace</kbd> (切换大小写改为删除)

编码时候右手距离删除键太远，<kbd>caps_lock</kbd>更方便，用 <kbd>right_shift</kbd> 替换 <kbd>caps_lock</kbd>

### right_shift

<kbd>right_shift</kbd> ~ <kbd>caps_lock</kbd>

### fn

<kbd>fn</kbd> ~ <kbd>return_or_enter</kbd> 在右手控制鼠标需要按 <kbd>enter</kbd> 时非常不方便，替换成 <kbd>fn</kbd> 右手控制鼠标，左手按 <kbd>fn</kbd>

非必须项均可以通过 `Karabiner-Elements` 软件中的 `Simple Modifcations` 删除


[Github:onface/relax-your-hands](https://github.com/onface/relax-your-hands)
