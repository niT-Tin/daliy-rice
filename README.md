## 我自己的 Linux 配置文件以及一些重新安装系统需要的东西防止忘记

![](./images/tapes/gifs/ncu_has_you.gif)

> 模仿黑客帝国matrix, Trinity发送给Neo的电子屏幕显示。我记得是看了哪个文章来着不记得了，至少是一年前的事情了😁，当时还是疫情时期要做核算。用vhs实现的录制。

- 目前还是使用 i3wm, 在速度上比 python config 的 qtile 还是有提升的

- 目前正在使用 zsh, lunarvim(日常代码文档) 和 emacs(用于 agenda 实际大部分也是在用 evil-mode)

### 记得去看 `note.md` 文件

### Font Awesome Cheat Sheet

https://fontawesome.com/v4/cheatsheet/

### 目前一些情况

~~已经将终端从 kitty 换到了 st(simple terminal), 不得不说 suckless 的的软件太强了，st 支持 ligtaure 也支持 emoji,而且还很小。~~，系统库字体问题，现在仍然在使用kitty。窗口管理器还是使用 i3wm,之后有时间的话想换成 dwm(也是 suckless 下的一个软件，非常小的窗口管理器)试试

### 日常系统使用图片

**_Daily One_**

![sys_daily_one](./images/sys_two.png)

**_Blog Things_**

![sys_daily_one](./images/day_fi.png)

**_Neovim Things_**

![sys_vim](./images/sys_editor.png)

![sys_vim](./images/dy.png)

#### 重新折腾一下
1. 顶部bar改用polybar(之前一直是xmobar)
2. 使用有动画效果的picom的folk版本(也添加了blur效果，具体见第四张图，终端背景的模糊效果)
3. 重新配置tmux以及starship

**_Daily Three_**
![sys_daily_three](./images/daily3.png)

**_Daily Four_**
![sys_daily_three](./images/daily4.png)

**_Renew Tmux And Prompt_**

![](./images/nowaf.png)

---

![sys_he](./images/sys_he.png)

### 无聊的事(这个事情肯定不是最近的，但是我也忘记这是啥时候了，懒得查看了😁)

最近在一块多余的硬盘上安装了 gentoo,不得不说，编译 chromium 是真的花时间..., 还有忘记打开i2c导致笔记本触控板不能用我是真的...(下次直接用现成的内核配置文件)

在这之前还折腾了lfs(Linux From Scratch 不是Large File System哦😄)，找个时间再来一次吧。

---

突然想起自己之前哈哈哈哈哈，凌晨看Linus发布第一个版本的Linux时写的说明，确实能感觉到他的热情，当时我也真的开心，没有为什么，只是觉得他做了一件十分了不起的事情。

哦对了，这个是为了防止我忘记才写的，因为我接触过也不少东西(主要是觉得有意思)，但是也忘记了很多了。(such as nginx 这种东西。还有啥来着？rancher?)

![gentoo](./images/gentoo.jpg)
