原理图：

![image-20201103202252284](C:\Users\86189\AppData\Roaming\Typora\typora-user-images\image-20201103202252284.png)

芯片周围0.1uF电容作用是用来滤波，开关时电源波动

### 供电电路：

###### 充电电路：

![image-20201103212823561](C:\Users\86189\AppData\Roaming\Typora\typora-user-images\image-20201103212823561.png)

![image-20201103212902196](C:\Users\86189\AppData\Roaming\Typora\typora-user-images\image-20201103212902196.png)

###### 升压电路：

![image-20201103213237227](D:\文件\单片机相关\Project-Drone\PCB-designer\image-20201103213237227.png)

###### 降压电路：给主芯片和8266分开供电

![image-20201103213545986](D:\文件\单片机相关\Project-Drone\PCB-designer\image-20201103213545986.png)

![image-20201103213636924](D:\文件\单片机相关\Project-Drone\PCB-designer\image-20201103213636924.png)

左边检测锂电池电压，分压输出一半；右边检测工作电压是否正确，正确灯亮；

### NRF2401电路：

Si24R1

![image-20201103213952477](D:\文件\单片机相关\Project-Drone\PCB-designer\image-20201103213952477.png)

FB1和FB2保证单独输入输出，不被高频影响

### mpu电路：

![image-20201103215421864](D:\文件\单片机相关\Project-Drone\PCB-designer\image-20201103215421864.png)



### pcb绘制：

把所有间距改为6

线宽改为6 6 50

过孔孔径（从上往下）12 15 12

过孔直径（从上往下）24 25 24

孔径默认 1 100

孔间距改为4（板子较小）

最小化阻焊层裂口 4

文字到焊盘距离 1

丝印层与其他层间距 1



### 注意：：

滤波电容放在主芯片旁；

shift+s 只看单层

![image-20201106143733009](D:\文件\单片机相关\Project-Drone\PCB-designer\image-20201106143733009.png)

shift+空格 改变走线方式S

空格 改变走线方向

可以隐藏接地的线，铺铜会全部接上

N选择隐藏

ctrl+鼠标左键双击 取消高亮显示

