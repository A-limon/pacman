# Pacman

pacman是为hexo设计的一款主题。
可以访问[Alimon's Blog](http://yangjian.me)查看效果。
关于Hexo及其主题请参考[文档](http://zespia.tw/hexo/)。

##概述

这只是一款练习作品。主题中没有把logo，页脚的个性化设置分离出来，很多地方没有完善。不太适合个人使用。
**仅作为主题制作的参考。**

##配置

主题配置文件位于主题根目录下的`_config.yml`文件中。

	menu: 对应博客的菜单项

	widgets: 默认开启三个右侧部件

	excerpt_link: 用于分隔文章`<!--more-->`

	google_analytics: 填写Google Analytics 的账户ID

	duoshuo: 多说账户ID

	google_plus: Google Plus账户ID

	weibo_url: 新浪微博的完整URL 如：http://weibo.com/436062867

	twitter_url: Twitter的完整URL 如：https://twitter.com/yangjiansky

	github_url: Github账户的完整URL 如：https://github.com/A-limon

	facebook_url: Facebook的完整URL 如：https://www.facebook.com/yangjian

	jiathis: 加网代码

	enable: true 是否开启
	id: 1501277 加网账户ID
	tsina: 1664838973 新浪微博账户ID，可以进入自己的微博查看
  
	rss: RSS地址，如果你安装了RSS插件直接填写 http://你的网站/atom.xml 即可。或者是填写你的自定义RSS地址

##说明
* HTML5+CSS3+jQuery2.0.1 响应式设计，大小屏幕通吃。
* 代码高亮使用Google的[prettify](https://code.google.com/p/google-code-prettify/)插件.
* 自定义字体使用的是[Fontello](http://fontello.com/)提供的服务。
* logo使用的是SVG文件，头像是内嵌到CSS中的Data URI scheme。
* `languages`文件夹中是国际化文件，只提供了简体中文和英文。
* about.ejs是一个自定义页面示例，请把对应的`index.md`文件放到网站更目录下的`source`>`about`中，并在`index.md` 文件头部定义 `layout`

	layout: about
	title: "关于"

