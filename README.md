# 爬虫搜索[![Build Status](https://travis-ci.org/nashaofu/dingtalk.svg?branch=master)](https://travis-ci.org/nashaofu/dingtalk)[![Build status](https://ci.appveyor.com/api/projects/status/jptk80n78gdogd18/branch/master?svg=true)](https://ci.appveyor.com/project/nashaofu/dingtalk/branch/master)


Django2.2 搭建一套搜索引擎,用于展示数据显示和关键词搜索

---


## 安装步骤

本环境是在python3.6下安装配置的,支持windows、macos、linux

此环境还需要安装redis，数据库,这个可参考网上教程如何安装redis,因为项目中redis 连接没有设置密码，只是本地连接，所有如何设置密码的，需要在源码中更改下redis连接

还有需要安装上一个项目的Elasticsearch,不然无法搜索

```bash
1. git clone https://github.com/jusk9527/LcvSearch.git
2. 在该目录下创建一个虚拟环境
3. pip install -r requirements.txt -i https://pypi.douban.com/simple
4. 启动django 即可,服务端部署可参数考我其他django项目服务端部署,或者利用docker部署都可以
```


## 截图效果s

1. 首页效果
   ![](https://raw.githubusercontent.com/jusk9527/images/master/data/20200223114011.png)
2. 搜索结果
   ![2.png](./screenshot/2.png)
3. 点击跳转详情页面


## 功能说明

1. 热词搜索排行
   - 解决全部搜索排行问题
2. 我的搜索记录
   - 解决了忘词、历史记录问题
4. 词条问题
5. 搜索时间问题
6. 分词问题
7. 关键字高亮问题



## 联系方式
1. qq群 297599213
2. 提 issue 请尽量到[GitHub](https://github.com/jusk9527/LcvSearch/issues)