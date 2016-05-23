# Homework-10
##封闭区域中的碰撞
##背景
考虑一个刚性小球，可视为质点在不同的封闭区域中碰撞，来回反弹，来描绘小球的运动轨迹，通过研究小球的运动来探究混沌条件，讨论了小球在不同
封闭区域中的运动情况和混沌条件。
##正文
质点与边界发生碰撞可由以下方程给出  
![](https://github.com/Wangzhengwhu/Homework-10/blob/master/%E5%85%AC%E5%BC%8F1.png)  
碰撞点的法向量为n=ai+bj  

可以求得反射后的速度方向，由下式给出  
![](https://github.com/Wangzhengwhu/Homework-10/blob/master/%E5%85%AC%E5%BC%8F2.png)  

接下来给出在矩形边界，不同初始条件下的碰撞图  
[计算程序1](https://github.com/Wangzhengwhu/Homework-10/blob/master/1.py)   
1.x=y=0,vx/vy=1/2  
![](https://github.com/Wangzhengwhu/Homework-10/blob/master/1%EF%BC%9A2.png)  
2.x=y=0,vx/vy=1/3  
![](https://github.com/Wangzhengwhu/Homework-10/blob/master/1%EF%BC%9A3.png)  
3.x=y=0,vx/vy=2/3   
![](https://github.com/Wangzhengwhu/Homework-10/blob/master/2%EF%BC%9A3.png)  
4.x=0,y=0.2,vx/vy=1/2  
![](https://github.com/Wangzhengwhu/Homework-10/blob/master/1%EF%BC%9A2%EF%BC%9A0.2.png)  
5..x=0,y=0.2,vx/vy=pi  
![](https://github.com/Wangzhengwhu/Homework-10/blob/master/pi.png)  
[计算程序2](https://github.com/Wangzhengwhu/Homework-10/blob/master/2.py)  
可以描绘出圆形边界轨迹的相图  
![](https://github.com/Wangzhengwhu/Homework-10/blob/master/%E5%9C%86%E8%BE%B9%E7%95%8C%E7%9B%B8%E5%9B%BE.png)  
[计算程序3](https://github.com/Wangzhengwhu/Homework-10/blob/master/3.py)    
在磁场中运动的轨迹，给定初始条件 x=1.2,y=0,vx/vy=1/2 ,T=0.9  

![](https://github.com/Wangzhengwhu/Homework-10/blob/master/%E5%A5%97%E5%9C%86.png)  



##致谢
感谢刘星辰同学


