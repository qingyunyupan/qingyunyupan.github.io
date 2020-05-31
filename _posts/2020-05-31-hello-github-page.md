---
date: 2020-05-31 06:34 +0000
layout: post
title: 如何添加创建github page
update_date: 2020/05/31 15:41:30

---

# 创建 github 仓库

创建 github 仓库时候，`仓库名字`需要注意和自己 github 名字一样。
例如我的 github.io: [qingyunyupan.github.io](https://qingyunyupan.github.io)

# 本地项目添加 git 后 push

通过下面命令，可以把项目 push 到 github 上.

```sh
echo "# qingyunyupan.github.io" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/qingyunyupan/qingyunyupan.github.io.git
git push -u origin master
```