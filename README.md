**Quick Start**

需要环境：node.js + mongoDB

安装命令：node nodepad [数据库名称] [数据库地址] [cookie密钥]

运行命令：node nodepad

================================================================

**自定义主题**

主题文件夹存放位置：`/public/themes/`,主题文件夹名字请以`JLT_`开头，文件
夹拷贝到指定目录下后可到控制台设置，控制台会自动加载，选择主题后保存生效，
无需重新部署项目。

默认主题：NPT_JerryLee_1.0。开发主题时请参照默认主题开发，主题文件夹内包
括css、javascript、font以及ejs文件。

================================================================
#####0.0.1版本特性:

1. 一句话安装（包括下载modules）
2. 发布和修改文章
3. 采用Markdown写作
4. 支持文章分享到微博
5. 支持上传图片到文章中
6. 自动文章归档
7. 支持文章标签
8. 控制台修改全局设置，包括博客设置、管理员设置和密码修改
9. 支持更换主题和自定义主题

================================================================
#####0.0.2版本更新日志(2014-10-29):

1. 修复session非本机数据库存储问题（rphaha123修复）
2. 改用mongoose连接mongoDB
3. 添加评论模块
4. 文章图片添加lightbox
5. 添加默认第一篇博文
6. 文章url拼音风格改变，去掉声调，避免部分浏览器url乱码无法访问问题
7. 修复其他显示bug
8. 优化代码

================================================================
#####0.0.3版本更新日志(2014-11-04):

1. 添加Markdown可视化编辑器
2. 文章编辑、发布页面添加文章预览功能
3. 优化显示细节
4. 控制台使用Font-awesome字体图标

================================================================
#####0.0.4版本更新日志(2014-11-10):

1. 新添新主题lingyong，修改自lingyong.me
2. 修改安装和启动程序，exec=》spawn，显示实时进度信息
3. 新增subtitle博客副标题
4. 首页提供近期文章数据
5. 主题API细节调整

================================================================
#####0.0.5版本更新日志(2014-11-18):

1. 解决网站图标问题
2. 全局设置settings添加副标题（详细参看wiki里的主题开发指南）
3. 文章数据提供每篇文章的第一张图片（详细参看wiki里的主题开发指南）
4. 图片使用绝对路径（为RSS功能铺路）
5. 添加pv和评论统计（详细参看wiki里的主题开发指南）

