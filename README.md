# 百万英雄答题助手
----------------------------------------------------------------------------------------------

# 用的是python3.6版本
参考微信跳一跳助手，使用adb截图。文字教程👉[参考](https://zhuanlan.zhihu.com/p/32813854)

# 把问题区域裁剪出来后用汉王的ocr识别出文本，然后调用百度搜索（把搜索到的前两个答案显示在屏幕）

# 整个程序运行完估计5秒左右，还可以有时间答题（---）

汉王ocr：https://market.aliyun.com/products/57124001/cmapi011523.html?spm=5176.730005.0.0.B1mZNd#sku=yuncode552300000

![截图](http://chuantu.biz/t6/198/1515261841x-1566687351.png)


一开始也想要tesseract来识别，但是经过测试太慢了要用10秒左右。

# 大家有时间的话可以试试把它弄成全自动的
有一个思路 就是把问题的选项答案也给识别出来，然后把百度搜出来的答案匹配选项答案，如果有答案直接一个模拟点击.

# 交流学习（微信群）
![截图](https://github.com/wuditken/MillionHeroes/blob/master/baiduSearch/de_qrcode.gif?raw=true)



