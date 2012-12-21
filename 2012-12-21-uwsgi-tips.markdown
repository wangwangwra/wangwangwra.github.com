---
layout: post
sidebar: true
title: "uwsgi tips"
date: 2012-12-21 22:28
comments: true
categories: ['python']
---

### 有关参数

#### 启动参数

+ 监视模块，改变后重载，方法一

		uwsgi --master --enable-threads --py-auto-reload <secs> \

		--py-auto-reload-ignore /path/to/ignored/file1 \

		[--py-auto-reload-ignore /path/to/ignored/file2]

	每隔 <secs> 秒扫描一次。可以设置忽略某些模块。

+ 监视模块，改变后重载，方法二

		uwsgi --touch-reload /path/to/file1 [--touch-reload /path/to/file2]


-------------------------------
