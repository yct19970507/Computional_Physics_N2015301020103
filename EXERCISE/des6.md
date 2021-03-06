## EXEXCISE 3.12    
* 姓名：王硕
* 学号：2015301020103
* 班级：物基二班    
#### 1.摘要：
* 混沌现象：指发生在确定性系统中的貌似随机的不规则运动，一个确定性理论描述的系统，其行为却表现为不确定性一不可重复、不可预测，这就是混沌现象
* 用Euler-Cromer方法模拟计算混沌现象    
#### 2.正文：    
用Euler-Cromer方法模拟计算如下驱动力下的混沌现象：    
<div align=center>

<img src="http://latex.codecogs.com/gif.latex?\frac{\mathrm{d}\,\theta\,^{2}}{\mathrm{d}\,t^2}=-\frac{g}{l}sin\theta\,-q\frac{\mathrm{d}\,\theta\,}{\mathrm{d}\,t}+F_{D}sin(\Omega\,_{D}t)">    
</div>
即：    
<div align=center>

<img src="http://latex.codecogs.com/gif.latex?\frac{\mathrm{d}\,\omega}{\mathrm{d}\,t}=-\frac{g}{l}sin\theta\,-q\frac{\mathrm{d}\,\theta\,}{\mathrm{d}\,t}+F_{D}sin(\Omega\,_{D}t)">    
</div>
运用Euler-Cromer方法：    
<div align=center>

<img src="http://latex.codecogs.com/gif.latex?\omega_{i+1}=\omega_{i}-[(\frac{g}{l})sin\theta_{i}-q\omega_{i}+F_{D}sin(\Omega_{D})]\Delta\,t">    
</div>
<div align=center>

<img src="http://latex.codecogs.com/gif.latex?\theta_{i+1}=\theta_{i}+\omega_{i+1}\Delta\,t">     
</div>
<div align=center>

<img src="http://latex.codecogs.com/gif.latex?t_{i+1}=t_{i}+\Delta\,t">    
</div>    

#### 3.图像
* 1.theta-t图: FD=0.5(L)    FD=1.2(R)    

![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/F6_c_1.png)![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/F6_c_2.png)    

* 2.Delat_theta-t图:[代码](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/temp6a.py)    

![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/F6_a_1.png)
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/F6_a_2.png)    

* 3.omege-theta图:    

![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/F6_b_1.png)
![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/F6_b_2.png)    

* exercise3.12:[代码](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/temp6b.py)

![](https://github.com/March0ns/Computional_Physics_N2015301020103/blob/master/EXERCISE/F6_d_2.png)    

#### 4.结果分析     
FD=0.5时运动有一定的周期性，是非混沌的。FD=1.2时运动无规律，是混沌的。说明阻尼的大小在这个实验中影响很大

   
       


    

