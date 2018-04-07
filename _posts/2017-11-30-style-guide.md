---
layout: post
cover: 'assets/images/shiva.jpg'
title: 参考
date: 2017-11-30 04:00:00
tags: guide
author: hanuman
---

# 日常写作须知

以下内容基本能满足 90% 的写作需求。

##  Markdown 常用标记

### 使用标题

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

### 链接

#### 直接使用

<https://github.com/soraom>

#### 文字链接

[JOJO 我不做人了](http://v.youku.com/v_show/id_XMjg1MDY0ODg4NA==.html?spm=a2h0j.11185381.listitem_page1.5!3~A&s=1ffc848adc6011e19498)

### 图片

![图片的注释，随便写点什么](/assets/images/favicon.png)

### 代码

#### 行内使用

比如这样 `(eval '((λ (x) (+ x 1)) 1))`

#### 代码段

在前面按一下 tab
```markdown
	code ...
```

或者

	```选择你要用的语言hl，比如 Go
	code...
	```

### 杂项

#### 插入一条下划线

	---

#### 加粗

__粗了__

#### 斜体

_斜了_

#### 删除线

~~我删~~

### 使用 html 的 tag

原则上一切 tag 都可以照用

#### 图片超链接

<image src="/assets/images/favicon.png" href="soraom.github.io" />

#### 插入 Youtu 视频

<amp-youtube width="480" height="270" layout="responsive" data-videoid="lBTCB7yLs8Y">
</amp-youtube>

## git 使用

把 git 仓库的代码 `clone` 到本地：

随便找一个目录，`cd` 进去或者右键 `git bash here`

```bash
git clone repo地址.git
```

写完文章后上传：

cd 进去 repo 的根或者在跟目录 `git bash here`
```bash
git add .            # `add` 所有内容
git commit -m "注释"  # 为上一次的添加创建一个 `commit`
git push             # 将所有 `提交` 所有上传到真正的 git 仓库
```
