## 简介
基于国内日渐严峻的BT环境，一些吸血客户端（类PCDN）导致的做种者的带宽大量被浪费，才出现了此项目。

基于`peer-id`识别，参考此[PR](https://github.com/transmission/transmission/pull/1062)实现。

## 特性
- 屏蔽吸血客户端（白名单模式）
- 全静态编译
- 使用`mimalloc`分配内存

## 更新
- 2024-08-08 变更为白名单模式
