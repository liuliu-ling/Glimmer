# Glimmer
GlimmerGame[微光游戏]，是从登陆注册，到服务大厅，乃至具体游戏的一体化网站
最后，它会有属于它的一套游戏编辑标准以及框架

#所用技术栈
前端部分 html+CSS+bootstrap+jq+ajax(计划改由axios以及vue进行样式的多元化以及前后端交互)
后端部分 node.js,mysql数据库

#开发环境
	操作系统:	windows10家庭版
	pc:				火狐80.0.1(64位)
	界面大小: 1366px*626px

##0.0.1

##目前进度&下个版本的目标
  1.最初版仅仅实现了登录注册功能，健壮性也较差，在下个版本要实现注册的完全健壮性
  2.同时，在下个版本要实现聊天功能的初步实现，以及发送好友申请&好友管理功能
  3.页面的优化，指定相关标准
	4.鉴于Layx(最新版)插件没有准确的api文档,而老版本又无法消除目前的项目痛点，
所以统一改用Layui插件,先解除对Layx的依赖，之后使用Layui实现原本的功能


##0.0.2

###版本变动
	1.更改所有的ajax,统一使用axios
	2.更改所有的layX框架(无论版本),统一使用LayUI的Layer框架
	3.把GlimmerLI(登录页面)从public(静态文件夹)下移动至views文件夹下,
旧网页依旧可以通过Glimmer.html访问，但以后不会在维护,改由127.0.0.1:3000直接访问
	4.优化了登录页面的逻辑,登录注册时的健壮性和容错率大大加强。

###下个版本的目标
	1.实现该版本未完成的聊天页面以及具体功能
	2.实现用户重复登录等用户状态逻辑的优化,以及具体应对方法
	3.服务页面实现Vue化,将动画以及数据绑定等实现改由Vue实现
	4.开始计划布局移动端的登录页面布局
	
###优化BUG
	1.注册完成度进度条会因为重复的选取,导致注册进度条进度显示错误,达不到预期功能效果的bug
	
	
##0.0.2

###版本变动
		1.篇幅较长的回调方法,使用ES6的Promise对象运行,避免晦涩难懂的回调长句出现
		2.用户的登录逻辑得到初步的加强,重复登录的用户只有当上一个用户登出时才能实现登录
		3.
###下个版本的目标

###优化BUG
		