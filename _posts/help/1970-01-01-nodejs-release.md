---
category: help
layout: help
mirrorid: nodejs-release
---

本文由清华大学 TUNA 协会提供，原文链接：<https://mirrors.tuna.tsinghua.edu.cn/help>


## Nodejs Release 镜像使用帮助

Nodejs Release 为各平台提供预编译的 nodejs 和 npm 等二进制文件，是
[https://nodejs.org/dist/](https://nodejs.org/dist/) 的镜像。

### 使用方法

可以手工选择下载所需的版本，也可以搭配 `n` 使用，方法如下：

```
# 设定环境变量

export NODE_MIRROR=https://mirrors.tuna.tsinghua.edu.cn/nodejs-release/

# 然后正常使用 n 即可

sudo n stable
```
