# FscanViz
FscanViz 是一款专为安全工程师打造的可视化工具，用于解析和展示 fscan 扫描结果。通过直观的网络拓扑图和交互式漏洞报告，帮助您快速识别网络中的安全风险点。

前两天打内网的时候，发现内网段量一旦大起来以后，fscan扫描后的结果需要整理，想到了fscan_parse,但是编译版本只有exe，还得多开一台虚拟机，于是乎萌生了写一个纯html实现的整理工具，用ai搓了一个，开源供大家使用，有什么建议可以提提issue喔

功能:
 1. 导入txt 整理汇总B段和C段
 2. 识别其中的漏洞信息（后面有空的话也许会加上常见poc对应的下一步操作建议/直接接入mcp/ai）
 3. 搜索框（没别的就是方便搜）
 4. 形成拓扑图（只能装B目前）
 5. 备注 & checkbox（我比较健忘，需要写一些打到哪里和对应的数据笔记；还可以存放一些附件，例如heapdump）

![截屏2025-05-24 16.34.07](https://github.com/g1an123/blogimage/blob/main/%E6%88%AA%E5%B1%8F2025-05-24%2016.32.59.png)

![截屏2025-05-24 16.34.07](https://github.com/g1an123/blogimage/blob/main/%E6%88%AA%E5%B1%8F2025-05-24%2016.34.07.png)

![截屏2025-05-24 16.34.07](https://github.com/g1an123/blogimage/blob/main/%E6%88%AA%E5%B1%8F2025-05-24%2016.51.17.png)

