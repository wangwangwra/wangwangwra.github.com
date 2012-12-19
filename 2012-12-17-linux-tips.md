---
layout: post
title: "linux tips"
tagline: 
description: 
categories: [tools]
tags: [linux, tips]
---

+ 以16进制方式查看文件

		xxd <file>

	也可以用vim查看

		vim -b <file>
	
	转换为16进制

		:%!xxd

	最后再转换回来

		:%!xxd -r
