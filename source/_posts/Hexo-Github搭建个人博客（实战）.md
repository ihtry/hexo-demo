title: Hexo搭建个人博客（实战）
author: 拾叁柒
tags:
  - hexo
  - Github
  - 网站
categories:
  - 实战
abbrlink: 1863780867
date: 2022-09-04 00:58:00
---
> 今天闲来无事，无意中刷视频看见了一个博主发布的**Hexo**的一个插件，然后就突发奇想来搭建一个个人博客，话不多说开干

***

### 环境要求（默认已经安装好）

- window10
- [Node.js](https://nodejs.org) 版本需不低于 10.13，建议使用 Node.js 12.0 及以上版本
- [Git](https://git-scm.com/)

---

#### 1. 安装hexo

```sh
npm install hexo
```

#### 2. 初始化项目

`推荐使用`**npx**`指令,windows环境下`**hexo**`比较麻烦(个人喜好)`

```sh
# 初始化文件夹
npx hexo init <folder>
# 切换到指定目录
cd <folder>
# 安装
npm install
```

#### 3. 配置`_config.yml`

> 官方文档：[传送门](https://hexo.io/zh-cn/docs/configuration)
>
> 这里的配置详细的有很多,具体就不多讲述了

|     参数      |                             描述                             |
| :-----------: | :----------------------------------------------------------: |
|    `title`    |                           网站标题                           |
|  `subtitle`   |                          网站副标题                          |
| `description` |                           网站描述                           |
|  `keywords`   |                网站的关键词。支持多个关键词。                |
|   `author`    |                           您的名字                           |
|  `language`   | 网站使用的语言。对于简体中文用户来说，使用不同的主题可能需要设置成不同的值，请参考你的主题的文档自行设置，常见的有 `zh-Hans`和 `zh-CN`。 |
|  `timezone`   | 网站时区。Hexo 默认使用您电脑的时区。请参考 [时区列表](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones) 进行设置，如 `America/New_York`, `Japan`, 和 `UTC` 。一般的，对于中国大陆地区可以使用 `Asia/Shanghai` |

#### 4. 本地运行测试

> 访问本地路径：[http://localhost:4000](http://localhost:4000)

```sh
npx hexo server
```
