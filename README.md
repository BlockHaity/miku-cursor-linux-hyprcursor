# miku-cursor-linux-hyprcursor

> 构建与Xcursor主题[hatsune-miku-windows-linux-cursors](https://github.com/supermariofps/hatsune-miku-windows-linux-cursors)

这是一个初音未来风格的hyprcursor光标主题，详细信息请看原Xcursor主题

感谢[supermariofps](https://github.com/supermariofps)制作的Xcursor主题

## 如何使用

### Git 安装

进入`~/.local/share/icons` 或 `/usr/share/icons`

> 来自Hyprland Wiki
> 
> 不建议将光标主题放在系统范围的`/usr/share/icons` 以免遇到潜在的权限问题。

然后，克隆本仓库

``` bash
git clone https://github.com/blockhaity/miku-cursor-linux-hyprcursor.git
```

然后，在 `~/.config/hypr/hyprland.conf` 中，添加以下两行于 ENVIRONMENT VARIABLES 中。

``` config
env = HYPRCURSOR_THEME,miku-cursor-linux
env = HYPRCURSOR_SIZE,24
```

### 手动安装

点击 **code** 然后点击 **Download ZIP** 下载zip文件

将其解压到 `~/.local/share/icons` 或 `/usr/share/icons` 中

> 来自Hyprland Wiki
> 
> 不建议将光标主题放在系统范围的`/usr/share/icons` 以免遇到潜在的权限问题。

然后，在 `~/.config/hypr/hyprland.conf` 中，添加以下两行于 ENVIRONMENT VARIABLES 中。

``` config
env = HYPRCURSOR_THEME,miku-cursor-linux
env = HYPRCURSOR_SIZE,24
```

大功告成！！！