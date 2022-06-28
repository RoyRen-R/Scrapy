# Scrapy
some probles

在运行代码时会出现一些问题
在spiders的自定义spider函数中需要导入外文件夹下items.py的定义类。会出现无法导入的问题
解决方法一：
添加类似sys.path.append("G:\PracticalT\doubanmovie\doubanmovie")的文件路径
解决方法二：
导入的方法为from ..items import Item类

此问题是在第二个doubanmovie文件下打开造成的问题
