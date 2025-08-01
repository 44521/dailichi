<!--
 * @Author: wzdnzd
 * @Date: 2022-03-06 14:51:29
 * @Description: 
 * Copyright (c) 2022 by wzdnzd, All Rights Reserved.
-->

## 功能
打造免费代理池，爬一切可爬节点
> 拥有灵活的插件系统，如果目标网站特殊，现有功能未能覆盖，可针对性地通过插件实现

> 欢迎 Star 及 PR。对于质量较高且普适的爬取目标，亦可在 Issues 中列出，将在评估后选择性添加

## 使用方法
> 可前往 [Issue #91](https://github.com/wzdnzd/aggregator/issues/91) 食用**共享订阅**，量大质优。**请勿浪费**
 
略，自行探索。我才不会告诉你入口是 `collect.py` 和 `process.py`。**强烈建议使用后者，前者只是个小玩具**，配置参考 `subscribe/config/config.default.json`，详细文档见 [DeepWiki](https://deepwiki.com/wzdnzd/aggregator)

准备好 Python3.9 环境

下载项目代码：git clone https://github.com/wzdnzd/aggregator.git

安装依赖： pip3 install pyYAML tqdm geoip2 pycryptodomex

运行代码：终端里进入到项目的 aggregate 目录下，执行命令 python -u subscribe/collect.py -s
## 免责申明
+ 本项目仅用作学习爬虫技术，请勿滥用，不要通过此工具做任何违法乱纪或有损国家利益之事
+ 禁止使用该项目进行任何盈利活动，对一切非法使用所产生的后果，本人概不负责

## 致谢
1. <u>[Subconverter](https://github.com/asdlokj1qpi233/subconverter)</u>、<u>[Mihomo](https://github.com/MetaCubeX/mihomo)</u>

2. 感谢 [![YXVM](https://support.nodeget.com/page/promotion?id=250)](https://yxvm.com)
[NodeSupport](https://github.com/NodeSeekDev/NodeSupport) 赞助了本项目
