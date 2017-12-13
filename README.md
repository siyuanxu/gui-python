# GUI Python -- python 图形编程实践

## 1. 选择工具

在没有深入了解 Python 的 GUI 编程之前，我选择了 TKinter，wxpython，pyside，pyqt 等四种 GUI 工具进行筛选。在暗中观察了这四种工具的官网之后，我毅然决然的选择了 [pyqt](https://www.qt.io) 作为学习对象，其他几种工具的格子衫风太浓厚。而且在深入了解之后，可以发现 pyqt 的易用性和完备性都非常的好，crossplateform 做的也比较不错。

## 2. 配置环境

Python 的环境管理我一直使用的是 conda，环境的配置还是比较简单，新建了一个 python=3.6 的虚拟环境，不会和其他项目发生冲突。pyqt 的安装也非常简单。

~~~
pip install pyqt5
~~~

## 3. Tutorial

我主要 follow 的是 Zetcode 上的 pyqt5 教程，http://zetcode.com/gui/pyqt5/。同时发现已经有热心人士将该教程翻译为中文版，https://www.gitbook.com/book/maicss/pyqt5/details，非常感谢 @maicss 的工作。不过由于程序中总是有很多词语难以用汉语表达准确，我还是建议参考 zedcode 的教程。

当然，教程的路线并不一定适合我，而我学习 Python GUI 的主要动力也是完成一些自己工作中的项目，所以 step by step 的跟着教程也不满足我的时效要求，还是以问题为导向吧。