# My Portainer App Templates 
自用的docker设置模板，里面路径和端口均为自定义 如使用请自行修改
端口映射从10000开始。文件夹路径在/opt目录下

在portainer的设置里设置一下即可在模板中找到

Settings - APP Templates - URL

适用平台为openwrt_x86_64

关于nginx：
注意第一次使用请不要挂载etc目录，挂载本地空etc目录的话会导致nginx启动失败。需要到container内把配置目录拷贝出来再挂载
