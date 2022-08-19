说明文档：http://leiyanhui.com/typecho_AllsitePasswd_Plugin/

适合日记站或者内部通知站，输入密码后方可查看网站内容，兼容v1.1 (17.10.30)

第一次写typecho的插件，花了几个小时看文档。功能如图

只有一个文件 Plugin.php 。上传到/usr/plugins/AllsitePasswd/目录，然后在后台启用即可

密码提示语言 提示图片均可以修改，也可以 在main_fun函数内编辑前台显示样式。

值得注意的是，
1、默认密码：123456，请修改强壮一些
2、因为入口是index.php，后台操作可能会被拦截，建议前台登陆后再进行后台操作
3、如忘记密码，建议直接删除/usr/plugins/AllsitePasswd/目录 后进入后台删除插件，然后重新安装即可

下载地址：
https://u2397981.ctfile.com/fs/2397981-314917776