---
status: translated
title: "ABI testing symbols"
author: Linux Kernel Community
collector: tttturtle-russ
collected_date: 20240718
translated: ElizaXiao
translated_date: 20240803
link: https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/Documentation/admin-guide/abi-testing.rst
---

# ABI 测试符号

文档记录了被认为已经稳定的接口，因为这些接口的主要开发已经完成。

接口可以更改以添加新的功能，但当前接口不会因此被破坏，除非在它们当中发现了严重错误或安全问题。

用户空间程序可以开始依赖这些接口，但它们必须清楚在这些接口被标记为稳定之前可能会发生的变化。

强烈鼓励使用这些接口的程序将其名称添加到这些接口的描述中，以便内核开发者在发生任何变化时可以轻松通知它们。
