# LisaHelp: 这里是 Lisa 的帮助文档

**Lisa 的命令主要分为 2 类**

2. [以 '!' 为前缀的命令](#带有前缀的命令) 例如: `!aqi 北京`
3. [直接输入命令 ](#直接触发的命令) 例如: `割一下`


带有前缀的命令
------
### 帮助命令
```
!help
```
带您来到这里 ^\_^

### 查询空气质量
```
!aqi { cityname|zip code }
```
查询相应城市的空气质量，其中 cityname 为地名，语种任选

### 查询维基百科
```
!enwiki entry
```
查询英文维基百科词条
```
!zhwiki entry
```
查询中文维基百科词条
```
!jawiki entry
```
查询日语维基百科词条

### 查询 arch wiki
```
!wiki entry
```
查询 arch wiki 中相应的词条，只在 #archlinux-cn 频道响应此命令

### 落絮搜索
```
!luoxu 关键词
```
使用[落絮](https://github.com/lilydjwg/luoxu)搜索群消息，返回搜索用的网页链接。只在 #archlinux-cn 和 #archlinux-cn-offtopic 频道响应。


### 查询 ip 归属地
```
!ip ip_addr
```
返回 ip\_addr 所在的粗略地理位置, 暂不支持 ipv6

### idea generator
```
!idea
```
无参数返回一条[ideaGenerator](http://www.matrix67.com/ideagen/)的话语

直接触发的命令
------
### fortune
```
lisalisa
```
不需要参数 ，返回一条发人深省的内容

### 讲段子
```
割一下
```
从糗事百科抓取一条段子，每两次抓取之间有一定的冷却时间
