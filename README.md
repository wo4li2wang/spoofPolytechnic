狂搞理工大
==========
刚上大一写的小游戏，当时确实花了点心思，偶然翻出来整理了一下发上来，做个小纪念吧……

as2.0 + swfkit 开发的,基本游戏框架还是做出来了，也支持地图，角色，怪物的扩充。

当时不懂编程习惯，也没什么编程模式，代码确实写的很不规范，有的变量也是乱取名字的，但还好关键地方是加了注释的……

其实就是学着DNF的样子恶搞的游戏，黑了下我们学校，闲得无聊嘛……<br>
下载地址：<br>
百度网盘：http://pan.baidu.com/s/1pJ9bM3p<br>
酷盘：http://kanboxshare.com/link/sgtRxOtZHC98oUMRAM2f0z1V8J5HWkuDYUgyKKkguGmpvErRcfmCRidGK7oygXYxtjMbI<br>
微云：http://url.cn/JJfIL8<br>
360网盘：http://yunpan.cn/Q7Srs4ZqwXzXz （提取码：dd85） <br>
华为网盘： http://dl.vmall.com/c0al1aoyt4<br>


## src目录 ##
程序源码

as2.0为as部分

- addition：游戏中的一些附加物，如雾气，桌子
- bg：各场景背景图片，学校照片，jpg格式
- character：角色模块，可以扩充角色，但大二就没精力做了
- gameblock：游戏的一些基本模块，比如生命值，游戏菜单，技能栏等
- map：游戏地图，当时写得很乱，把许多不是地图的界面也扔进去了
- monster：怪物模块，目前就8种(2个BOSS)


ffscript为外部fscommand的扩充，比如存档加密/解密，读取/保存

- launch：基本游戏所有的外部fscommand都在里面，但写得很乱，很多代码冗余，也没时间重构
- 存档解码器：可以解码游戏存档
- 存档生成器：生成游戏存档



## bin目录 ##
游戏的可执行程序，5.53 MB(解压后6.64 MB)，主要占空间是由于用了不少位图
文件夹下的模块和src名字是一样的
双击launch 可开始游戏，和DNF差不多，↑↓←→控制方向，X攻击，ASD技能

## 游戏截图 ##


