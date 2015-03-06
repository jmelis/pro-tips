---
title: Tranfer files from the shell
date: 2015-02-25 17:05 +0000
tags: linux, bash
---

Use [transfer.sh](https://transfer.sh/) to upload files to an online service.

```shell
# Upload using cURL
$ curl --upload-file ./hello.txt https://transfer.sh/hello.txt
https://transfer.sh/66nb8/hello.txt

# Using the alias
$ transfer hello.txt
##################################################### 100.0%
https://transfer.sh/eibhM/hello.txt
```

