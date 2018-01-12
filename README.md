# million-heroes
百万英雄辅助开挂  python2.7 

## 方案：

1. 手机截图、ADB 连接windows
2. 百度OCR
3. 百度知道问题搜索，选项匹配。最高投票得出最佳答案

## 效果：

 ![result1](https://github.com/RainHxj/million-heroes/blob/master/result/result1.png)



![result2](https://github.com/RainHxj/million-heroes/blob/master/result/result2.png)



![result3](https://github.com/RainHxj/million-heroes/blob/master/result/result3.png)



## 结果分析：

通过百度知道进行搜索，对于 “\*\*\*又被称为？、\*\*\*是什么属性？...”这一类通过题目可得到确定性答案的问题具有很高的成功率。

但是，对于，“一下哪一个是\*\*\*对的/错的....”这一类通过题目不能检索到确定性答案的不确定性问题，似乎黔驴技穷。

## 思路：

设法将问题分为以上两类，第二类问题，通过问题+答案的形式进行搜索。

## 参考：

https://github.com/wuditken

