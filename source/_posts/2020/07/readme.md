---
title: 如何使用这个 Hexo 的默认主题
tags:
  - Hexo
categories:
  - Hexo
date: 2020-07-14 19:00:39
author: shenxianpeng
---

在使用 Hexo 博客的默认主题已经三年了，这期间也修复了不少使用过程中不太满意的地方。

## 如何使用

### 创建文章

```bash
hexo new "README"
```

然后会在 `source/_post` 目录下生成了 `readme.md` 文件和 `readme` 目录。填写相应的属性:

####  `readme.md` 文件
```
---
title: README
tags:
  - null
  - null
categories:
  - null
date: 2020-07-14 19:06:33
author:
---
```

手动更新一些属性，例如本篇文章我更如下

```
---
title: 如何使用这个 Hexo 的默认主题
tags:
  - Hexo
categories:
  - Hexo
date: 2020-07-14 19:00:39
author: shenxianpeng
---
```
#### `readme` 目录

目录是用来存放内容配图的。可以这样使用

![QR code](readme/qrcode.jpg)

### 创建目录（可选）

为了方便管理，我会在 `source/_post` 目录下面根据年和月份创建目录来对文章进行分类，比如 `source/_post/2020/07/`。如果文章不多也可以缩减仅创建为年的目录 `source/_post/2020/` 或是直接在 `source/_post` 下面写都是可以的。

这里我将 `readme.md` 移动到 `source/_post/2020/07/` 目录下

### Tips

1. 如果文章很长，只想显示部分内容，其余内容以阅读更多来显示，可以在文章内容中加上如下代码

    ```
    <!-- more -->
    ```

2. 


