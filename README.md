# 小黑子专用Python包 #
**制作者：**

*B站账号：[我是老王0518](https://space.bilibili.com/670741291)*

*GitHub:[ziyin-wang](https://github.com/ziyin-wang/)*

*Pypi:[114514W1919810（W0518）](https://pypi.org/project/KunTimeChange/11.5/)*

---
## 基本语句： ##
```python
KunTimeChange.ikuntime(hour,minute)
```

---
## 注意： ##

*一定要在开头加上下面代码*
```python
import time
import KunTimeChange
```


---
## 示例： ##
```python
import time
import KunTimeChange as kun

kun.ikuntime(10,30)
#示例代码
```
输出结果：“4.0坤时12.0坤分”


---
## 示例程序 ##
```python
import time as t
import KunTimeChange as k

hour = int(input("请输入小时：    （時を入力してください:）"))
minute = int(input("请输入分钟：      （分を入力してください:）"))

if hour >= 24 or hour < 0 or minute >= 60 or minute < 0:
	print ("Error 101: 输入数据错误   (エラー 101: データ入力エラー)")
	t.sleep(5)
	exit()

kun.ikuntime(hour,minute)
```


---
## 备注： ##
***输出结果后的.0仍然是个bug。后续我会修改的。具体什么时候看心情。。。***

**下载链接：[Pypi](https://pypi.org/project/KunTimeChange/11.5/)**

**Bilibili视频链接：[我是老王0518—坤坤时间转换器](https://b23.tv/f13R627)**

***
