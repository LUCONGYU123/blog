---
title: "再见VPN！无魔法如何访问github?"
date: 2024-1-20
---

因为一些不可抗拒力，大部分地区无法直接访问Github。这时候有来自霍格沃茨的学生表示：找个VP嗯就行。

话说咱们为了github，还犯不着翻墙，那还有什么办法呢？

是的，修改hosts文件！绕过DNS直接访问。然而我们又从何得知在大陆可以访问的github服务器IP呢？作为大自然的搬运工，我找到了一个伟大的库：[Github520](https://gitee.com/klmahuaw/GitHub520)

这位大佬帮我们找好了IP，并且会定期更新。

如何使用？首先你要知道自己系统的hosts文件的路径
win：`C:\Windows\System32\drivers\etc\hosts`
linux/mac：`/etc/hosts`

windows在资源管理器中输入这个地址并选择用记事本打开，然后追加到hosts中保存即可
linux/mac使用如下命令：
`sudo nano /etc/hosts`
ctrl+x 保存退出
