[Mac 效率神器 - 葵花宝典](https://rain120.github.io/study-notes/#/resources/mac-software)

#### 提示：'软件已损坏，打不开' 或 '不是Mac Appstore下载'

```sh
// 显示
sudo spctl --master-disable

// 隐藏
sudo spctl --master-enable
```

#### Xxx已损坏，无法打开。您应该将它移到废纸篓。

在 **系统偏好设置 - 安全与隐私 - 通用标签** 中选择来自任何来源选项。

##### 命令行执行

```sh
sudo spctl --master-disable
```
执行下面命令，将 `XMind\ ZEN.app` 换成 `xxx`

```sh
sudo xattr -r -d com.apple.quarantine /Applications/XMind\ ZEN.app
```
