+++
title = "Hallo World"
date = 2022-12-24

[taxonomies]
tags = ["Changelog","草稿"]
+++

12.11晚，突然心血来潮想建Blog，然后就这样忙活十二天到现在终于粗糙的出来一个。纯小白一路磕磕绊绊掉进各种坑，其实在第七天最开始的兴奋感已经消磨了个干净。网站还远没达到预期，但我已经很疲倦了。那就先这这样吧，得忙活正事了。以下是我粗糙的总结。
<!-- more -->

# 我学到了什么
Powershell、VScode、zola、Git、Github、Netlify

### GIT
- [系统的Git教程](https://www.liaoxuefeng.com/wiki/896043488029600)
- [git add命令行添加文件、文件夹以及撤销文件add的方法](https://cloud.tencent.com/developer/article/1537931)
- [HTML架構基础](https://www.sun-exp.com/blog01?id=5)
- [网页字体是否侵权问题和解决](https://zhuanlan.zhihu.com/p/420848770)
- [利用CSS的@font-face属性,在网页中嵌入字体](https://www.cnblogs.com/hnyei/archive/2012/02/20/2360306.html)
- [HTML字体或Web字体完整指南](https://www.wbolt.com/html-fonts.html)
- [网站加载速度影响因素](https://blog.51cto.com/u_15410286/4536227)
- [网站加载速度影响因素2](https://zhuanlan.zhihu.com/p/31224108)


### 遇到的问题
1. 安装zola，安装zola 需要chocolatey，安装chocolatey需要powershell，安装powershell需要winget。纯小白的我一开始就面对这种绝望的套娃，折腾半天才发现，wwinget，powershell win11早就装上了。
2. zola serve怎么都不行，最后发现需要在目录下执行命令。要：cd 目录。
3. 配置git的时候，望着我的c盘中文用户名无语凝噎。最后干脆重开一个账户，折腾半天。
4. [Git错误:连接到远程存储库时，主机密钥验证失败](https://cloud.tencent.com/developer/ask/sof/75662)。
5. 在VScode里推送git提交的时候要输入信息。
6. 注册Netlify莫名其妙账号冻结
7. 部署完Netlify神经病又在别的地方买了个域名（Lynntags.com），现在还不知到怎么整。
8. 网站嵌入字体 IA-Writer 失败

### 网站
1. 网站只有主页和tags页。所有信息用tag分类，导航栏也会根据一时的兴趣添加相应标签作为快捷入口。
2. 网站字体，IA-writer，仓耳云黑。ia-writer会直接嵌入网页，但仓耳云黑可能只能自己看了。（和它相比别的正文字太丑太僵硬了）
3. 网页导航栏，以后做一个滚轮唤出的效果.
4. 标签页显示数量，添加排序方式。
5. 无更多内容的短文鼠标触标题碰不应该有连接效果。有更多内容的文章鼠标触碰最好标题和摘要同时有效果。
6. 上下页按钮没做。网页logo没做，嵌入图片不会。