# 【0.96INCH_OLED_IIC_SSD1306】在Arduino开发板上的运用

本教程目的是指导如何通过Arduino UNO开发板对0.96英寸SSD1306的OLED进行显示图像操作。
资料包下载：[0.96inch_BULE_OLED_IIC12864_SSD1306.zip]( https://pan.baidu.com/s/11ICDnNLR6PhNCGKNSY45iQ?pwd=f1w2)

# 1. 硬件需求
>* OLED：0.96inch IIC接口 SSD1306
![](../../vx_images/9013000235854.png)
 
>* Arduino开发板：Arduino UNO Rev3 开发板一块及对应的USB数据线一条
![](../vx_images/362152300247854.png)

>* 杜邦线：一公一母的2.54mm杜邦线一排
![](../vx_images/28102400240988.png)

>* 电脑：Windows/Mac 电脑一台（本教程使用Windows 11 64位系统）
![](../vx_images/171102400231518.png)


# 2. 软件需求
>* 编程软件：Arduino IDE 1.8.19 （仅代表本教程测试版本，可以使用其他版本）
如果还未安装，请在Arduino官网链接进行Arduino IDE下载安装：[Arduino software](https://www.arduino.cc/en/software)
>* Arduino库：Adafruit_GFX && Adafruit_SSD1306（标准库形式需要进行部分修改。请确保您正在使用上方提供的资料包（里面更改了一些定义部分）。如果这些文件已经在库中，建议先更换）

U8glib库安装说明：

1. 在Arduino IDE中，转到 **File** >  **Preferences**  
![](../vx_images/370532600234022.png)

2. 转到红色框中所指向的文件夹 
![](../vx_images/566772600242969.png)

3. 解压缩上方资料包，把路径 **0.96inch_BULE_OLED_IIC12864_SSD1306\Arduino Example\heltec0.96OLED-master** 文件夹里的“Adafruit_GFX”、“Adafruit_SSD1306”两个文件夹复制到步骤2中的位置
![](../vx_images/574673100263418.png)


# 3. 硬件接线说明
0.96inch OLED同Arduino UNO接线示意图
![](../vx_images/322833100236463.png)

# 4. 例程测试
按如上接好线后打开一个例程进行测试。

1. 打开一个**DIYmall_Logo**例程，在Arduino IDE中，转到 **File** >  **Examples** >  **Adafruit_SSD1306** >  **DIYmall_Logo**。
![](../vx_images/259543600245631.png)

2. 选择对应的开发板**Arduino UNO**以及对应的COM口。
![](../vx_images/93853800234929.png)

3. 进行编译烧录
![](../vx_images/242613900231180.png)

# 5. 测试
此次例程会在OLED屏幕上显示一个LOGO。
![](../vx_images/154384200231319.png)