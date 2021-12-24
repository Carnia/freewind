## 主题信息

> **名称：**freewind 自由之风 
>
> **版本：**V1.4
>
> **描述信息：**仅700多k的体积，拥有相册、说说、时间轴、友链、更换配色等功能，更多信息请移步至官网查看
>
> **作者：**[冷文学习者](https://kevinlu98.cn)
>
> **预览：**[https://kevinlu98.cn/](https://kevinlu98.cn/)
>
> **主题手册：**[Freewind使用说明](http://doc.kevinlu98.cn/)

---

## 主题插件

Freewind主题音乐播放器: [传送门](https://kevinlu98.cn/archives/92.html)


Freewind主题专属打赏插件: [传送门](https://kevinlu98.cn/archives/86.html)


Freewind主题专属站点公告插件: [传送门](https://kevinlu98.cn/archives/72.html)

---




## 安装方法

站点一定要设置伪静态，至于怎么设置自行百度一下，很简单
一定要在永久链接中启用地址重写功能

- 下载文末附件
- 上传并解压到`站点根目录/usr/themes`下
- 进入站点后台更换外观选择该主题即可
- **注:** 若实在不会更换`typecho`主题请自行百度，有详细说明

---

## 更新详情
### V1.4

- **传送门：** [Freewind 1.4]更新(https://kevinlu98.cn/archives/103.html)

- 对默认编辑器做了增强，freewind主题也有了自己内置的编辑器了，请参考： [Freewind主题编辑器展示](https://kevinlu98.cn/archives/101.html)，在`markdown`之外做了如下扩展
  - 加入了提示组件
  - 加入了消息组件
  - 加入了Tab分栏组件
  - 加入了彩色分割线组件
  - 加入了分组卡片组件
  - 加入了跳转按钮组件
  - 加入了B站视频组件
  - 加入了音乐组件

- 加入了SEO优化
- 由于说说图文分离，图片抽离到另外的字段中了，说说有3种模式
  - 普通图文(类朋友圈)
  - 音乐分享
  - B站视频分享
- 说说图片、评论头像、相册等加入懒加载机制，流量能省一点是一点
- 附件下载样式更换，取消了之前的独立下载页
- 在设置中加入了站点背景设置，大家可以在设置页面看到
- 上次jsDelivr挂了一次，这次加入了自定义CDN的设置，请参考：[Freewind设置CDN](https://kevinlu98.cn/archives/102.html)

- 友情链接样式更改，请参考：[我的邻居](https://kevinlu98.cn/page/20.html)(**PS: 我好像每次更新都要改一次，以后不了**)
- 以前文章最下面的版权说明太丑了，这次样式重新设计了一下

### V1.3

**传送门：** [Freewind 1.3更新](https://kevinlu98.cn/archives/87.html)

**重要**

如果之前有使用公告插件与音乐插件，请重新下载，新插件及重制插件下载地址
- 公告：[Freewind主题专属站点公告插件](https://kevinlu98.cn/archives/72.html)
- 音乐：[Freewind主题专属音乐插件](https://kevinlu98.cn/archives/73.html)
- 音乐(重制)：[Freewind主题音乐播放器(重制版)](https://kevinlu98.cn/archives/90.html)
- 有朋友帮忙在重制款的基础上支持网易云、QQ音乐等第三方音乐平台的歌单，大家有需要可以下载：[Freewind主题音乐播放器(老王重制版)](https://kevinlu98.cn/archives/92.html)
- 打赏：[Freewind主题专属打赏插件](https://kevinlu98.cn/archives/86.html)

**更新详情**
- 主题大小仅有**679 KB**
- 全站开启Pjax异步调用，引入**pjax**后比较直观的改变就是整个网站变成单页应用，在一定程度上会提高用户体验且已经加载过的表态资源不会再重复加载，站点的响应速度会有进一步的改善
- 重构了相册功能，由以前的集成别人的功能改成自己写，比之前更加美观且更符合主题风格，使用方式见[相册说明](https://kevinlu98.cn/archives/85.html)
- 优化了图片展示功能，之前是我自己写的js控制展示，总感觉有问题，这次更用了第三方扩展
- 删除了时间归档功能，我感觉这个功能和时间轴比较像，所以就删除了该功能，同时也重构了时间轴功能，预览地址：[时间轴](https://kevinlu98.cn/page/10.html)
- 重构了友情链接页面，预览地址：[友情链接](https://kevinlu98.cn/page/20.html)
- 修复之前说说不能分页只能显示前N条
- 修复了不能用一些插件的问题，这个之前特意发文解释过
- 美化了提示框样式大家可以点个赞或者评论试试看看提示框
- 去除主题自带的打赏功能，提供了打赏插件，大家可根据需要来下载
- 增加了页面自定义右键功能
- 增加了复制版权提醒功能，大家可以随便复制几个文字试试
- 修复了移动端点开侧栏的展示问题
- 优化了外观设置页面，之前是自已写的结构，这次改成了第三方框架
- 重构了代码结构，回头发布之后大家下载后可以看看，我给模块都归类了方便大家阅读参考
- 新主题删除了两个挂载点，以前以为`typecho`没有提供前台页面的挂载点，所以自定义了几个，后来大家说插件用不了的时候我发现是有提供的，我就把之前的两个挂载点删除了，所以音乐插件和公告插件大家在更新主题时如果需要请重新下载一次

### V1.2

**传送门：** [Freewind1.2更新](https://kevinlu98.cn/archives/74.html)

- 修复了在随便一条评论那里点n个回复，就会出现n个取消回复

- 加入更换配色功能，站长可以在后台设置站点配色且可选择是否允许用户在站点右下角的设置图标选择本地站点配色，同时用户自己如按照规范编写自己主题配色文件，主题也会自动识别，自定义配色见：[传送门](https://kevinlu98.cn/archives/76.html)

- 将一些被我改过的第三方js库转到jsdelivr，减小主题文件大小到9M左右

- 当评论用户有设置gravatar时会显示gravatar，无gravatar头像时如果是QQ邮箱则显示QQ头像，且加入了邮箱到头像的一周缓存

- 在主题中加入几个挂载点，方便后期通过插件的方式扩展主题
  - 公告功能插件化，安装插件后会在站点右侧多个小铃铛，同时在首页与详情页面也会有显示，首页与详情页面的公告在点击关闭后一个小时内不会弹出，插件地址：[传送门](https://kevinlu98.cn/archives/72.html)
  - 音乐插件，封装了aplayer库，开启后会在右侧栏显示，插件地址：[传送门](https://kevinlu98.cn/archives/73.html)
  - 通过插件自定义右侧见：[传送门](https://kevinlu98.cn/archives/77.html)
  
- 将以前左侧样显示的友情链接移到右侧栏

- 将站点左上角logo由图片变为文字

### V1.1

**传送门：** [Freewind1.1更新](https://kevinlu98.cn/archives/59.html)

- **重要：这次更新前请一定先做好备份，因为在设计交互时为了统一属性名称，把以前的部分自定义属性的属性名改了**
- 相册使用说明：[传送门](https://kevinlu98.cn/archives/61.html)
- 修复了首页博文过多出现省略号无样式的问题
- 替换部分js插件的cdn，之前用的一些cdn不太稳定导致进入页面一直未响应
- 之前的在线更新功能不完善，这次版本取消该功能，在后续版本会重新上线
- 取消首页推荐功能，替换为首页轮播图，具体请看下文
- 在站点右下角加入返回顶部及联系我
- 加入首页轮播图功能
- 加入相册功能，此功能为集成功能，集成了[photo page for typech](https://github.com/zzd/photo-page-for-typecho/)功能到本站主题
- 优化创建文章的freewind相关属性操作，加入级联显示
- 优化导航栏页面设置

### V1.0

- freewind 主题的第一个版本,
- 支持ajax登录注册,
- 加入附件功能，支持回复可见，登录可见等模式,
- 加入评论邮件通知功能,
- 文章类型加入说说，来像发朋友圈一样使用说说功能,发布文章页面选择说说后发布页面会自动变为说说模式,
- 自定义页面加入导航可见属性，可指定其是否在左侧导航栏显示,
- 自定义HTML页面可自由配合HTML+CSS+JS展示内容,
- 首页显示说说+博文，同时有独立的说说页面,
- 加入一些动态图表,
- 主题设置页面，自定义你的freewind主题,
- 点击图片进入图片列表,
- 支持在线更新，不用每次更新都重新下载一遍主题






## 主题介绍

请参考主题使用说明 [http://doc.kevinlu98.cn/](http://doc.kevinlu98.cn/)