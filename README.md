本卡五星麻将 基于ET框架 请先能正常运行ET的demo  

# [ET链接](https://github.com/egametang/ET)  

# 介绍： 
   一款麻将游戏,基于ET框架开发,基本和市面上的,房卡麻将一样,功能基本实现 有匹配模式,房卡模式 录像功能 亲友圈  
   接入了百度地图sdk,微信登陆,分享和支付  

# 运行：
   开发Unity版本:2018.4.2  
   下载项目直接打开Unity工程,进入Init场景 直接点击运行就可以运行, 服务器租用的是阿里云 预计8月20日到期  
   云服务器到期后,连不上服务器,需要自己开启本地服务器  
   注：ETModel.Init.isNetworkBundle 这个字段控制是否 使用本地资源 还是使用网络资源  
   [打好包apk下载](https://gamegather.oss-cn-beijing.aliyuncs.com/kwx.apk)  
   安卓和IOS工程暂时没有上传,因为涉及到开放平台,见谅!  
   
#  本地启动
   服务器端要重新生成一下解决方案  
   要本地开启Monodb服务器  
   选择LocalAllServer启动 或者直接打开服务器解决点击启动 效果是一样的  
   
   注意事项:  
   1.第一次上传的LocalAllServer配置文件 配置不对 熟悉自己改 不熟悉的可以重新下载  
   2.服务器每次启动都会默认添加一些配置数据 但是如果检测到数据库已经有数据了 就不会添加了 启动失败可以尝试清空本地数据库  
   
   
   

