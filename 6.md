# [6.chatbot](https://github.com/warmheartli/ChatBotCourse)

### 标签：

`lucene` `python` `IKAnalyzer` 

### 简介：

该项目基于影视剧字幕聊天语料库开发了一个“小二兔”聊天机器人，用到的工具主要为：Lucene和IKAnalyzer。Lucene是一款开源免费的搜索引擎库，java语言开发。IKAnalyzer则是一个开源中文切词工具。我们可以利用这两个工具来对语料库做切词建索引，并通过文本搜索的方式做文本相关性检索，然后把下一句取出来作为答案候选集，再做答案排序，找到最优答案。


聊天机器人包括三个模块：

1. 提问处理模块

2. 检索模块

3. 答案抽取模块

提问处理模块又包括：查询关键词生成、答案类型确定、句法和语义分析。

检索模块主要是根据问题的关键词或信息，进行信息检索，返回句子和段落。

答案抽取模块基于检索得到的原料，通过分析和推理从检索出的句子和段落里抽取与提问一致的实体。


更多详细的介绍和用法参见项目主页和相关blog。

## 项目地址：

https://github.com/warmheartli/ChatBotCourse

## 项目文档：

- http://www.shareditor.com/blogshow?blogId=113

## 参考链接：

- http://www.shareditor.com/blogshow?blogId=73
- 作者：蒋济莲

