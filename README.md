# My Portainer App Templates 
自用的docker设置模板，里面路径和端口均为自定义 如使用请自行修改
端口映射从10000开始。文件夹路径在/opt目录下

在portainer的设置里设置一下即可在模板中找到

Settings - APP Templates - URL

适用平台为openwrt_x86_64

关于nginx：
注意第一次使用请不要挂载etc目录，挂载本地空etc目录的话会导致nginx启动失败。需要到container内把配置目录拷贝出来再挂载

20201217更新：加入了mysql方便安装nextcloud。有可能会出现2个（我这里暂时没有显示第一个）。请使用container类型的即第二个。
如提示caching_sha2_password.可参考这篇文章解决：https://www.cnblogs.com/jonrain0625/p/11306412.html
