# 实验名称
搭建对象存储
# 实验环境
|操作系统	|Windows 11 专业版|
| ------- | ------- |
|设备名称|LAPTOP-Q8LHEHM1|
|处理器	 |     AMD Ryzen 7 5800H with Radeon Graphics         3.20 GHz|
|机带 RAM	|  16.0 GB (15.9 GB 可用)|
|服务器端	|  MinIO Server|
|系统类型	|  64 位操作系统, 基于 x64 的处理器|


# 实验记录
1.直接在Minio官网下载Minio Server的windows版本
![alt text](figure/image.png)
2.进入minio.exe存放路径，打开cmd, 输入命令 minio.exe  server path,path是minio.exe所在的文件路径
![alt text](figure/image-1.png)
3.复制一个WebUI，在浏览器中打开，然后输入用户名和密码，minioadmin,进入Minio Server界面。
![alt text](figure/image-2.png)
4.界面如下：（Minio Server会把与minio.exe同目录下的文件夹初始化为空桶）
![alt text](figure/image-3.png)
# 实验小结