# CloudMusic
 仿网易云音乐的qml版本，实现了网易云音乐其中的一小点功能，并实现本地音乐频谱显示，网络音乐由于采用旧的API，获取不了MP3文件的直链，所以现在不能播放网络音乐了(本来想加载python来实现新的API的参数加密功能，无奈windows端怎么都加载python库失败，只好暂时放弃)。
 -------------------------------------------------------------------------------------------
 2017-08-31
 在编译运行的时候要确保libzplay库的路径对不对，有没有libzplay.dll存在
 2018-02-08
 另一个网易云音乐与虾米音乐的结合[MyCloudMusic](https://github.com/shenjing023/MyCloudMusic)
 -------------------------------------------------------------------------------------------
### Dependencies
- Qt >= 5.8
-  QtCreator + MinGW
-  音频编码解码器库libZPlay(只能在windows下运行)
### Screenshots
![](http://ord6anrvd.bkt.clouddn.com/201706171648_106.png)

![](http://ord6anrvd.bkt.clouddn.com/201706171649_508.png)

![](http://ord6anrvd.bkt.clouddn.com/201706171651_758.png)

![](http://ord6anrvd.bkt.clouddn.com/201706171651_191.png)

![](http://ord6anrvd.bkt.clouddn.com/201706171653_798.png)

![](http://ord6anrvd.bkt.clouddn.com/201706171654_63.png)
### License
GNU GENERAL PUBLIC LICENSE Version 2
