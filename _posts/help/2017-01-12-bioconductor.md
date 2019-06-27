---
category: help
layout: help
mirrorid: bioconductor
---

本文由清华大学 TUNA 协会提供，原文链接：<https://mirrors.tuna.tsinghua.edu.cn/help>


[Bioconductor](https://www.bioconductor.org) 镜像使用帮助
===================

Bioconductor 镜像源配置文件之一是 `.Rprofile` (linux 下位于 `~/.Rprofile` )。


在文末添加如下语句:

```
options(BioC_mirror="https://mirrors.tuna.tsinghua.edu.cn/bioconductor")
```

打开R即可使用该 Bioconductor 镜像源安装 Bioconductor 软件包。
