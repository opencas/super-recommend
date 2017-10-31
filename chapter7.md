# [7. Riot Full Text Search Engine](https://github.com/go-ego/riot)

### 标签：

`go` `ir` `distributed`

### 简介：

Riot 是基于高度可定制的全文搜索引擎 [wukong](https://github.com/huichen/wukong) 实现的支持中文与拼音搜索的全文搜索引擎，采用 [go](https://github.com/golang/go) 语言实现。在继承了如下：

- 高效索引和搜索（1M 条微博 500M 数据28秒索引完，1.65毫秒搜索响应时间，19K搜索 QPS）
- 支持中文分词（使用 [gse](https://github.com/go-ego/gse) 分词包并发分词，速度 27MB/秒）
- 支持计算关键词在文本中的紧邻距离（token proximity）
- 支持计算BM25相关度
- 支持自定义评分字段和评分规则
- 支持在线添加、删除索引
- 支持多种持久存储
- 支持分布式索引和搜索
- 可实现分布式索引和搜索
- 采用对商业应用友好的 Apache License v2 发布

功能特性的情况下，还引入了如下几个新的特性：

- 支持逻辑搜索
- 支持中文转拼音搜索
- 增加分布式
- 分词改进
- 支持 heartbeat
- 修复 bug
- 移除对 cgo 存储引擎的依赖，增加 badger 和 leveldb 持久化引擎

借助 riot，你可以用不到两百行 [go](https://github.com/golang/go) 代码实现一个微博搜索网站！


更详细的内容请参见项目主页

## 项目地址：

https://github.com/go-ego/riot

## 中文文档：

https://github.com/go-ego/riot/blob/master/README_zh.md

## 入门教程：

https://github.com/go-ego/riot/blob/master/docs/zh/codelab.md

## 参考链接：

- https://github.com/go-ego/riot/blob/master/docs/zh/codelab.md
- 作者：李庚旺
