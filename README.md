# Awesome-github-repo-cn
github上优秀的项目（C++、Python、名校课程……）

## 资源大合集
**各领域各语言资源大合集**[https://github.com/sindresorhus/awesome](https://github.com/sindresorhus/awesome)

 **GitHub的每日榜单** 
 
 C++[https://github.com/trending/c++?since=daily](https://github.com/trending/c++?since=daily)
 
 Python[https://github.com/trending/python?since=daily](https://github.com/trending/python?since=daily)
 
 

### Jobbole(伯乐在线）整理中文版
C++资源大全中文版 [https://github.com/jobbole/awesome-cpp-cn](https://github.com/jobbole/awesome-cpp-cn)

Python资源大全中文版[https://github.com/jobbole/awesome-python-cn](https://github.com/jobbole/awesome-python-cn)

机器学习资源中文版[https://github.com/jobbole/awesome-python-cn](https://github.com/jobbole/awesome-python-cn)

程序员练手小项目[https://github.com/jobbole/ProgrammingProjectList](https://github.com/jobbole/ProgrammingProjectList)


设计师资源大全[https://github.com/jobbole/awesome-design-cn](https://github.com/jobbole/awesome-design-cn)

Python技术书籍[https://github.com/jobbole/awesome-python-books](https://github.com/jobbole/awesome-python-books)

## 优秀项目

### 3D打印
#### 切片
[**CuraEngine**:](https://github.com/Ultimaker/CuraEngine) CuraEngine是一个3D打印切片引擎，即把输入的STL、DAE或OBJ模型文件切片输出成gcode文件，其采用C++开发，特点是完全开源，可运用于多种打印机，对电脑配置要求很低，切片速度最快。配套界面软件为[Cura](https://github.com/Ultimaker/Cura)。Cura是一个python语言实现，使用wxpython图形界面框架的3D打印切片界面软件。兼容主流打印机：ultimaker 、iMaker

[**Slic3r**:](https://github.com/slic3r/Slic3r) 3D打印切片引擎，采用C++开发，特点是可调参数多，例如填充图案，支持可变层高设定，切片速度较快，容错性较高，知名的Makerbot家的makerware用的就是该引擎，Repeiter-Host默认也是该引擎；

[**Clipperlib**:](http://www.angusj.com/delphi/clipper.php) 提供了对线段和多边形的裁剪(clipping)以及偏置(offseting)功能。
和其他裁剪库相比，Clipper具有以下特征：
1. 它能够接受各类多边形输入，包含自交的多边形；
2. 它支持多种填充原则(奇偶填充、非零填充、正填充、负填充)；
3. 它相较于其他库来说效率极高；
4. 它数值稳定（鲁棒性强）；
5. 它支持多边形和线段的偏置；
6. 它对于商用以及免费软件来说都是免费使用的。

#### 网格处理
##### C++
[**CGAL**:](https://github.com/CGAL/cgal) 计算几何算法库(CGAL)是一个c++库，旨在提供方便的访问高效和可靠的计算几何算法。

[**VCGlib**:](https://github.com/cnr-isti-vclab/vcglib) Visualization and Computer Graphics Library (VCGlib for short) 是一个开源的、可移植的、c++、模板化的、无依赖的、用于操作、处理、清理、简化三角形网格的库。该库由超过10万行代码组成，是在GPL许可下发布的，并且它是意大利国家研究委员会ISTI可视化计算实验室的大多数软件工具的基础，如MeshLab、metro和许多其他软件。VCG库专门用于管理三角网格：该库相当大，并提供许多用于处理网格的最新功能，例如：基于高质量二次误差边缘折叠的简化；高效的空间查询结构（统一网格，哈希网格，kdtree等）； 先进的平滑和整流算法；计算曲率；优化纹理坐标；Hausdorff距离计算；测地线；网格修复功能；等值面提取和先进的前网格划分算法；Poisson Disk采样和其他工具来采样网格上的点分布；细分曲面。

[**libigl**:](https://github.com/libigl/libigl) libigl是一个简单的C ++几何处理库，其具有广泛的功能，包括构造稀疏的离散微分几何算子和有限元矩阵，例如切线拉普拉斯和对角质量矩阵，简单的基于面和边的拓扑数据结构，用于OpenGL和GLSL的网格查看实用程序以及许多核心功能矩阵处理函数，使Eigen感觉更像MATLAB。
##### Python
[**PyMesh**:](https://github.com/PyMesh/PyMesh) PyMesh是由纽约大学博士周庆南开发的代码库。它是一个专注于几何图形处理的快速原型平台。PyMesh是用c++和Python两种语言编写的，在这两种语言中，计算密集型的功能是用c++实现的，而Python则用于创建最小化且易于使用的接口。

### 运动控制

机器人书籍、课程及其他资源 [https://github.com/kiloreux/awesome-robotics](https://github.com/kiloreux/awesome-robotics)

[**Robotics Library**:](https://www.roboticslibrary.org/) 机器人库(RL)是一个自包含的c++库，用于机器人运动学、运动规划和控制。它涵盖了数学、运动学和动力学、硬件抽象、运动规划、碰撞检测和可视化。

[**ROS**:](https://github.com/ros/ros) Robot Operating System (ROS)

[**OROCOS**:](https://github.com/orocos/orocos_kinematics_dynamics) Orocos (Open Robot Control Software) 是一个用来构建实时控制软件的C++框架，适合开发机器人或者机器的控制软件。Orocos 实时工具包提供了一个基础框架，以快速开发可运行在实时操作系统的应用，如RTAI和Xenomai ，当然它也支持 Linux 系统。

[**GRBL**:](https://github.com/grbl/grbl) Grbl是一个轻量的嵌入式的，高性能，低成本的替代平行端口为基础的数控铣削运动控制。这个版本的Grbl在Arduino上运行，带有328p处理器(Uno、Duemilanove、Nano、Micro等)。控制器是用高度优化的C语言编写的，利用了avr芯片的每一个巧妙的特性来实现精确的定时和异步操作。它能够保持高达30kHz的稳定，无抖动控制脉冲。类似运动控制项目还有：
- [Marlin](https://github.com/MarlinFirmware/Marlin) 专攻3D打印，SD卡脱机
- [TinyG](https://github.com/synthetos/TinyG) 简单的CNC控制，机械手控制，S型加减速
- [Smoothieware](https://github.com/Smoothieware/Smoothieware) 3D打印，激光切割，SD卡脱机

[**PythonRobotics**:](https://github.com/AtsushiSakai/PythonRobotics) 由Python编写的**移动机器人**算法，特别是自主导航算法；

### 图像视觉处理

[**Sherlock**:](https://github.com/sherlock-project/sherlock) 高级机器视觉软件，可以用于广泛的自动化检测应用。它提供了最大的设计灵活性，丰富的已验证的工具和功能。

[**FaceSwap**:](https://github.com/deepfakes/faceswap) 是个基于dlib的换脸程序。模型训练速度较快，同样配置下更快的到达低loss值，而且有gui界面版本。

[**DeepFaceLab**:](https://github.com/iperov/DeepFaceLab) 这是一个github上的开源项目，所有人都可以查看源代码也能免费使用。个人认为这个项目的最大优点就是安装超级简单，几乎是无需安装，使用过程也不复杂，可实现换脸、换头、改变唇动等功能。

[**Face Recognition**:](https://github.com/ageitgey/face_recognition) 本项目是世界上最简洁的人脸识别库，你可以使用Python和命令行工具提取、识别、操作人脸。本项目的人脸识别是基于业内领先的C++开源库 dlib中的深度学习模型，用Labeled Faces in the Wild人脸数据集进行测试，有高达99.38%的准确率。但对小孩和亚洲人脸的识别准确率尚待提升。

[**FFmpeg**:](https://github.com/FFmpeg/FFmpeg) 多媒体处理工具库，包括：音频、视频、字幕和相关元数据。

### 机器学习、人工智能
[**Dlib**:](https://github.com/davisking/dlib) Dlib是一个现代的C ++工具箱，其中包含机器学习算法和工具，这些工具和工具可以用C ++创建复杂的软件来解决实际问题。

[**TensorFlow**:](https://github.com/tensorflow/tensorflow) Google出品

[**PyTorch**:](https://github.com/pytorch/pytorch) Facebook出品


### 图形界面
#### c++
[**libQGLViewer**](https://github.com/GillesDebunne/libQGLViewer) libQGLViewer是一个基于Qt的c++库，它简化了OpenGL 3D查看器的创建。它提供了一些典型的3D查看器功能，比如可以使用鼠标移动相机，这是其他大多数api所不具备的。其他功能包括鼠标操作帧，内插关键帧，对象选择，立体显示，屏幕截图保存和更多。它可以被OpenGL初学者使用，也可以用来创建复杂的应用程序，完全可定制且易于扩展。

#### Python
[**Kivy**:](https://github.com/kivy/kivy) Kivy是一个开源的、跨平台的Python框架，用于开发利用创新的、多点触摸的用户界面的应用程序。这样做的目的是为了实现快速、简单的交互设计和快速原型设计，同时使您的代码可重用和可部署。Kivy用Python和Cython编写，基于OpenGL ES 2，支持各种输入设备，并具有丰富的小部件库。使用相同的代码库，您可以运行在Windows，macOS，Linux，Android和iOS系统上。所有Kivy小部件都具有多点触控支持。

### 其他
#### C++
[**Ceres Solver**:](http://www.ceres-solver.org/) Ceres Solver是由Google开发的非线性最小二乘问题求解工具包，被用于Google产品多年，强大、快速、稳定并受到持续的开发支持。

#### Python
[**Manim**:](https://github.com/3b1b/manim) 解释数学视频的动画引擎。可以用来创建精确的2D动画。

[**you-get**:](https://github.com/soimort/you-get) 这个爬虫神器能爬取视频网站和图片网站，你不用写任何代码就能很容易的把你喜欢的视频或者图片甚至音频文件给扒下来。而且支持腾讯、搜狐、新浪、B站、央视网、芒果TV，乐视网、优酷、熊猫斗鱼等等大多数的国内主流视频网站。

[**Scrapy**:](https://github.com/scrapy/scrapy) Scrapy是一个快速的高级web抓取和web抓取框架，用于抓取网站并从其页面中提取结构化数据。它可以用于广泛的用途，从数据挖掘到监视和自动化测试。

[**RapidJson**:](https://github.com/Tencent/rapidjson) 高效的 C++ JSON 解析／生成器，提供 SAX 及 DOM 风格 API。腾讯出品

## 论文书籍
[**awesome-Face_Recognition**:](https://github.com/ChanChiChoi/awesome-Face_Recognition) 论文集：人脸检测、人脸检测、人脸识别、人脸验证、人脸表示、人脸重构、人脸追踪、人脸去模糊、人脸合成、人脸欺骗、人脸检索等

## 公开课
