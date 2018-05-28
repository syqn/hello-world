<h1>智能行李箱

生活中行李箱已经成为每个人不缺少的生活工具。虽然市场上行李箱越来越轻便，但时时刻刻拖动行李箱行走对我们来说很不便利。智能行李箱这款设计就是针对这个问题开发的出来的作品——一种可以自动跟随使用者的智能行李箱。本作品以Sysnopsys公司的ARC EM系列处理器开发板作为智能行李箱的核心控制模块，L298N模块作为智能行李箱的供电模块，采用UWB定位系统，能够使行李箱在人群中精准跟随使用者，还原跟随。采用了超声波测距模块，感测非接触式距离，从而具有壁障功能，并针对防止行李箱被盗取的问题，添加了检测行李箱与使用者距离的功能，当超出预设的安全距离时，将自动发出警报，提示使用者行李箱已超出预设范围。这一款智能行李箱的设计就是为了给出行的人们带来便利，让我们一起看看他是如何做到的吧！

- [Introduction](#1)   
    - [Function](#1.1)
	- [System Architecture](#1.2)
- [HW/SW Setup](#2)
	- [Required Hardware](#2.1)
	- [Required Software](#2.2)
	- [Hardware Connection](#2.3)
- [User Manual](#3)
	- [Before Running This Application](#3.1)
	- [Run This Application](#3.2)
		- [Makefile](#3.2.1)
		- [Main Entry](#3.2.2)
		- [Driver](#3.2.3)
		- [Function Module](#3.2.4)

<h2 id='1'>Introduction

**“”智能行李箱**


<h3 id='1.1'>Function

- 自动跟随功能：当使用者行走时，行李箱会自动跟随使用者移动，并保持在一个安全的范围之内。
- 防盗报警功能：当行李箱与使用者之间的距离超出安全范围（被别人提走）或者行李箱遇到障碍无法移动时会发出警报提醒使用者。
- 称重功能：能够测量行李的重量，以免出现超重的情况。
- 电量显示功能：能够显示电池电量以提示使用者及时充电。
- 移动电源功能：能够当做移动电源供手机、平板等移动设备充电。


<h3 id='1.2'>System Architecture



<h2 id='2'>HW/SW Setup

<h3 id='2.1'>Required Hardware

<h3 id='2.2'>Required Software

<h3 id='2.3'>Hardware Connection

<h2 id='3'>User manual
<h3 id='3.1'>Before Running This Application
<h3 id='3.2'>Run This Application
<h4 id='3.2.1'>Makefile
<h4 id='3.2.2'>Main Entry
<h4 id='3.2.3'>Driver
<h4 id='3.2.4'>Function Module

