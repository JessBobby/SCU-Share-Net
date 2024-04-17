### SCU-Share-Net
解决SCU望江校园网有线连接无法形成热点
### 说明
望江不同于江安（2024-4-17为止北苑是这样）。
在江安西苑可以使用WiFi和拨号两种认证方式上网。WiFi跳校园网认证界面，拨号是办校园卡。
在望江北苑可以使用WiFi和锐捷客户端认证上网，同上。
### WiFi连接模式
WIN10 WIN11在WiFi连接后，可以直接在WIN 网络和Internet设置中打开热点即可。
### 有线连接（插网线）模式
望江采用的锐捷客户端认证，认证上网后锐捷会检测WIFI热点的开启和第三方热点软件，一旦检测到就会强制下线。
因此可如此解决：
##### 1 正常完成认证连接
##### 2.1 打开任务管理器-2.2 性能-2.3 打开资源监视器
##### 3.1 CPU-3.2 找到8021x.exe和suservice.exe进程-3.3 暂停这两进程
![](https://github.com/JessBobby/SCU-Share-Net/blob/main/1.png)  
## 4 享受pc、pad、phone多设备上网！
