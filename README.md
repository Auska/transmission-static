## 简介
基于国内日渐严峻的BT环境，一些吸血客户端（类PCDN）导致的做种者的带宽大量被浪费，才出现了此项目。

## 屏蔽范围
基于`peer-id`识别，屏蔽`XL SD XF QD BN DL TS DT HP tt XM GT0003`,参考此[PR](https://github.com/transmission/transmission/pull/1062)实现。

## 特性
- 屏蔽吸血客户端
- 全静态编译
- 使用`mimalloc`分配内存
