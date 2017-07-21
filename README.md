# VOCMaker
自动化标注工具，用来制作VOC格式的数据集

### 使用方法

1.环境需求：opencv，python（numpy,cv2)

python中也用到了opencv，安装了opencv后可以在它的python目录下找到cv2.pyd，将其放在python的库搜索目录下。另外还要依赖numpy库。

2.将所有的图片放在程序目录下的imgs文件夹中，然后运行`rename.py`脚本来生成基本目录并将图片命名转换成标准格式存放在`JPEGImages`中

3.打开VS工程，运行程序并开始标注，记得切换为英文输入。命令如下：

按键|功能|
:---|:---|
空格|下一张图|
a   |上一张图|
c   |清除当前图片的所有标注|
o	|完成标注并自动生成xml|

4.运行`txt.py`在Main文件夹下生成txt文件

5.完成数据集的制作

演示：

![demo](https://github.com/whlook/VOCMaker/blob/master/pics/test.gif)

#### 说明

工具比较简陋，本机环境可以正常使用，主要是opencv环境，如果无法运行，可以检查一下opencv环境和文件目录是否正确。

本人也会不断优化这个小工具，如有问题可以联系我的邮箱:wuhui1634@gmail.com