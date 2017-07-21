## 个人简介
欢迎来到我的Github Page，我是郝华青，2016年6月在四川大学医学信息工程系获得学士学位，2016年9月至今在上海交通大学生物医学工程学院攻读硕士学位。

## 项目经历

### 槽式抛物聚光器的面形检测
2014年9月-2015年3月，参与四川大学导师的横向项目，槽式抛物聚光器的面形检测，在该项目中负责Matlab仿真。项目内容为在甘肃玉门大唐集团的新能源基地，通过建立数学模型计算集热管在曲面板上的理论投影，然后与实际拍摄的不同角度的聚光器（相机固定，聚光器旋转，使得可以看到集热管在反射镜上的投影走过整个聚光器）进行对比，来计算聚光器的面型抛物线完美程度。

![yumen](HaoHuaqing.github.io/images/yumen.jpg) 

### 西昌网络监测
2015年3月-2016年1月，参与四川大学导师的横向项目，为四川西昌某企业开发网络监管软件，在该项目中负责数据采集和网页可视化。该项目内容为基于简单网络管理协议（SNMP）对流量等网络数据进行采集，存储到数据库后在网页上对流量等网络数据进行可视化。

![xichang](HaoHuaqing.github.io/images/xichang.jpg) 

### Robomaster全国大学生机器人大赛
2015年6月，我作为四川大学代表队的一员参加了大疆创新科技有限公司举办的Robomaster全国大学生机器人大赛，并在比赛中获得了全国三等奖。我们在此前花费了大约三个月时间来设计和制造机器人战车。比赛就好像一场第一人称射击游戏，双方各派出五名选手在电脑前以摧毁对方基地为目的操纵机器人进行对抗。最终我们败给了电子科技大学代表队，而他们也在那一年收获了全国总冠军。

![Robomaster](HaoHuaqing.github.io/images/Robomaster.jpg) 

### 基于Kinect的运动捕捉设备在临床康复中的应用
我在2015年10月获得了上海交通大学的保研资格，并于2016年3月-2016年5月，赴上海交通大学进行本科毕业设计。毕业设计的内容是基于Kinect for Xbox One对卒中病人的关节角度进行快速、无接触的测量，用于在康复治疗前后评估患者的改善情况。工程文件已上传至Github: [KinectMeasureJointAngle](https://github.com/HaoHuaqing/KinectMeasureJointAngle)    
    
![kinect](HaoHuaqing.github.io/images/kinect.jpg)   

### 卒中患者的风险感知能力评测平台
我在上海交通大学读研的方向是生物医学工程，2016年9月-2017年2月我完成了我研究生期间的第一个项目，脑卒中患者上肢的风险意识控制的性能分析。先前有研究表明，人类为了应对环境的不确定性会不断调整自己的运动行为，我们建立了一个测试平台，让卒中患者进行一个模拟驾驶游戏，我们关注的是当汽车被越来越大的高斯噪音所干扰时控制行为是如何变化的。利用这个平台，我们成功地收集了4位健康受试者和4位卒中患者的数据。结果表明，中风患者在提高高斯扰动水平时，相比于正常人未能很好调整他们的表现。工程文件已上传至Github: [JoystickCarGame](https://github.com/HaoHuaqing/joystickcargame)。论文发表在2017年7月11日-15日在韩国举行的[EMBC会议](http://embc.embs.org/2017/)上：Performance analysis of risk-aware control in upper limb of patients with post-stroke hemiparesis。

![risk](HaoHuaqing.github.io/images/risk.jpg)   

### Vultr + Shadowsocks科学上网服务
2016年11月，由于当时使用的无论是免费还是付费的科学上网软件都不够稳定，而访问国际互联网却是刚需，决心自己使用vultr + Shadowsocks 的方案搭建一个自己的科学上网方案。成功后将搭建过程写作博客发表在[简书](http://www.jianshu.com/u/cce6fba84fba)，获得了6297 的阅读量，是我所有写过的博客中访问量最多的一个。该文章后来由于审查制度于2017年7月6日被和谐掉，访问量也就此定格在6297。

![ss](HaoHuaqing.github.io/images/ss.png) 

### neuro-grinder开发
2017年3月-2017年7月，当时实验室所进行的卒中病人实验需要使用的肌电采集设备和运动捕捉设备，而这些数据的处理和保存没有一个统一规范的流程，于是我负责开发了一个基于Python的数据管理和处理平台，代号neuro-grinder。该平台实现了在flask开发的网页上进行卒中病人的信息增加、删除、修改和查询，也就是通常所说的CRUD，然后可以对两个不同设备的数据进行滤波，重采样，组内对齐和组间对齐，并且可以对自动识别不准确的对齐点手动拖拽对齐，使整个数据处理操作变得规范和流程化。工程文件已上传至Github: [neuro-grinder](https://github.com/HaoHuaqing/neuro-grinder)。

![flask](HaoHuaqing.github.io/images/flask.png) 

### Udacity机器学习纳米学位
2017年1月-2017年6月，对机器学习很感兴趣，正好Udacity推出了机器学习互助班，有一位导师在群里专门负责答疑，于是我就参加了这一期机器学习纳米学位，并于2017年6月成功毕业。对监督学习、非监督学习、强化学习和深度学习有了一定的了解，最后的毕业项目是完成Kaggle上的一个比赛，Dogs vs. Cats，通过 Keras 搭建一个深度卷积神经网络来识别一张图片是猫还是狗，由于运算量较大该项目使用AWS上的主机完成。

![nano](HaoHuaqing.github.io/images/nano.png) 

## 联系方式
GitHub:  @HaoHuaqing   
Twitter: HaoHuaqing   
Gmail:   mobeimao@gmail.com   