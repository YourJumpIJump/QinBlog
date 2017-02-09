
### QinBlog
An open source of blog
> 基于codeigniter、UIKIT、editormd的一款开源个人博客系统
> 用于个人发布、管理、展示博客，遵循MIT协议


### 主页
[www.qinblog.net](http://www.qinblog.net "www.qinblog.net")


### 实现的功能
- 发布、更新、删除、置顶文章
- 关键字、分类搜索查看文章
- 添加、修改、删除分类
- 评论管理 
- 留言管理 
- 后台新消息提醒
- 网站信息修改
- 友情链接添加、修改、删除、
- 管理员信息、密码修改
- 查看、导出、清空管理员操作日志
- 备份站点数据 (整站、上传文件、MYSQL数据库，打包下载)
- 按照分类、月份归档备份文章为.md文件 (打包下载)

### 运行环境

| 服务器  |  脚本语言  | 数据库 |
| ------------ | ------------ | ------------ |
| apache2.x/IIS8.x  | PHP5.6  | Mysql5.1+  |

#### 需要的额外PHP扩展
openssl、mbstring


### 作者
| UI设计  |  程序设计  |
| ------------ | ------------ |
| MrQin  | MrQin  | 


### Dependents
 [codeigniter](http://www.codeigniter.com/ "codeigniter") 
 
 [jQuery](http://jquery.com/ "jQuery")
 
 [UIKIT](https://getuikit.com/ "UIKIT") 
 
 [editormd](https://pandao.github.io/editor.md/ "editormd") 
 
 [HeadJS](http://headjs.com/ "HeadJS") 
 
 [particles.js](http://vincentgarreau.com/particles.js/ "particles.js") 
 
 [cryptoJS](https://github.com/brix/crypto-js "cryptoJS") 

### 如果你想使用这个开源博客
> ##### 配置

> 修改application/home/config/config.php 的$config['base_url'] 为你的站点

> 修改application/admin/config/config.php 的$config['base_url'] 为你的站点

> 修改application/home/config/database.php 添加你的数据库信息

> 修改application/admin/config/database.php 添加你的数据库信息

> 将qinblog.sql导入你的数据库

> 后台默认账户：admin，密码：adminqinblog

> ##### 权限

> application/common/cache 需要读写的权限

> Public/Upload 需要读写的权限

## Browser Support

![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![IE](https://raw.github.com/alrra/browser-logos/master/src/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png)
--- | --- | --- | --- | --- | --- |
Latest ✔ | Latest ✔ | Latest ✔ | 10+ ✔ | 7.1+ ✔ | Latest ✔ |


#### Changes


License

The MIT License.

Copyright (c) 2015 QinBlog
