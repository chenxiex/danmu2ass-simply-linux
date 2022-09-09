# danmu2ass
弹幕转ass

fork自danmu2ass-simply，原仓库代码的路径中有多余的'\\'，无法在linux下正常使用，故开此仓库。

简化了操作步骤

若文件夹结构如图
```
--danmaku2ass.py
--danmaku2ass.exe
--/xml文件
  |--a.xml
  |--/xmlwenjian
     |123xml4.xml
```

在命令行中运行
```
python danmaku2ass.py ./xml文件
```
可将 /xml文件 的文件夹（包括子文件夹）下的所有xml文件转为ass并保存在各自的xml目录下

或者
```
python danmaku2ass.py ./xml文件/a.xml
```
则只转换这一个文件并保存在与xml同目录下
