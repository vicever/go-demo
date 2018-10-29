# 用Go实现常用设计模式

## 1. 策略模式

**意图:**
定义一系列的算法,把它们一个个封装起来, 并且使它们可相互替换。

**关键代码:**
实现同一个接口

**如何解决:**
将这些算法封装成一个一个的类，任意地替换。
- 应用实例： 
1. 主题的更换，每个主题都是一种策略
2. 旅行的出游方式，选择骑自行车、坐汽车，每一种旅行方式都是一个策略。 
3. JAVA AWT 中的 LayoutManager。

