# 感谢大家抽时间参与RT-Thread Studio首次内测活动
:heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart: :heart:
# RT-Thread Studio内测活动说明
## 1.  测试软件准备
通过如下地址下载内测版RT-Thread Studio安装程序（安装程序为Windows 64bit版本）


## 2.  测试硬件准备

RT-Thread Studio目前支持两种类型项目创建  

* 裸板项目  
  支持STM32F10x系列MCU的裸板项目创建  

* RT-Thread项目  
  支持基于BSP的RT-Thread项目创建  
  (实际测试可以不用局限于以下几款开发板，对于测试点灯的话，相近MCU型号的板子也可以)  

    | BSP | 开发板 |
    | ------ | ------ |
    | stm32f103-dofly-M3S | 德飞莱 M3S开发板 |
    | stm32f401-st-Nucleo | ST Nucleo开发板 | 
    | stm32f407-atk-explorer | 正点原子探索者 | 
    | stm32f429-atk-apollo | 正点原子阿波罗 | 
    | stm32f429-fire-challenger | 野火挑战者 | 
    | stm32f767-atk-apollo | 正点原子阿波罗 | 
    | stm32l475-atk-pandora | 正点原子潘多拉 | 
	
RT-Thread Studio目前支持J-Link和ST-Link两种调试器  
板载的或者独立的调试器都适用  

所以理论上只要你有一块上述MCU型号的ST板子再加上一个J-Link或ST-Link调试器  
就可以体验RT-Thread Studio的所有功能  

## 3.  测试小目标
*  通过以下步骤：创建项目，代码编辑，项目构建，程序下载，实现板子的闪灯效果  
*  通过启动调试后操作，让灯以受控的方式，亮一会熄一会（断点和全速结合）
*  单步调试并在程序挂起的时候，通过相应功能窗口查看调试过程中的汇编，寄存器，外设寄存器，变量，内存，表达式  
*  新建RT-Thread项目，通过双击项目内Kconfig文件打开RT-Thread配置界面，体验强大的RT-Thread配置管理功能  

实现小目标后大家开始自由探索RT-Thread Studio的其它功能吧

## 4.  问题反馈
大家可以随时在内测群里反馈使用时出现的问题，  
如果问题比较复杂，微信描述不方便，也可以通过邮件反馈  
邮件反馈地址：shiwei@rt-thread.com

## 5.  相关文档
*  《RT-Thread_Studio用户手册.pdf》  
该文档在安装完RT-Thread Studio后，通过点击欢迎页的 “帮助文档” 打开，如下图所示  
![image](/uploads/3a624363f1482c92bfe29c2b095d4664/image.png)  
也可以在安装完RT-Thread Studio后，直接在安装目录的docs目录中找到该pdf文档  
![image](/uploads/0ec46944942e2d56fd6bafe6621a3e1a/image.png)  
该用户手册目录结构预览如下：  
![image](/uploads/6e4957261f2ff5d1170cfb17fee95adb/image.png)
