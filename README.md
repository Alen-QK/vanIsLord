![testIcon](https://user-images.githubusercontent.com/55415793/173568881-43b09052-592d-412d-b3c2-e4e7c310cb4e.png)

# VanIsLord: NightTown Online Cloud System/夜镇系统

这是一个基于Vue2.0·Java Springboot·MongoDB开发的在线资源分享与管理系统。具有：
- 较为完备的线上网盘(支持大文件，复数文件传输，暂不支持文件夹上传，支持各类批量操作以及拖动等文件管理功能)
- 文件在线预览（图片基于viewer.js，部分文件类型基于kkFileView）
- 支持大部分视频在线预览，基于后台ffmpeg硬件转码（若目的为大规模串流，建议选用真正的流媒体服务器如Emby，plex，jellyfin）
- 音乐播放器
- 用户间文件分享
- 用户间聊天室·留言
- 为其他流媒体服务（如jellyfin，emby）提供资源输入重命名规范（使用TMDB）
等功能。前后端分离。适合为中小用户群提供自由交换资源/共用流媒体服务器资源整合的平台。

目前网盘系统/分享/音乐播放器/文件预览已基本开发完成，用户间聊天室/重命名等其他服务仍在开发中，现版本仅为alpha测试版本且仅支持docker镜像部署。

![image](https://user-images.githubusercontent.com/55415793/173569340-9c1efaa2-3329-4129-a4f0-aa33165f1473.png)
![image](https://user-images.githubusercontent.com/55415793/173570282-483bc72d-0d5b-40a7-874b-78e9cf775a20.png)


## 现有docker版本 V0.0.9
```
wzl778633/vanislord_server:latest //后端服务器
wzl778633/vanislord_web:latest //web_client服务器
需要自行获取mongoDB 4.4.0镜像
```


