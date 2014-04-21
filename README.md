Installing--kinect-for-windows-sdk--using-Openni-and-NiTE 
===========================================================

 This tutorial will  introduce how to install kinect for windows sdk(v1.8) (Openni and Nite)
 
1.	Details：
The Kinect for Windows SDK includes the following:
•	Drivers for using Kinect for Windows sensors on a computer running Windows 7, Windows 8, Windows 8.1, and Windows Embedded Standard 7
•	Application programming interfaces (APIs) and device interfaces
•	Note: Samples, tools, and other valuable development resources are available in the Kinect for Windows Developer Toolkit.
•	However, if you want to know more about Kinect for Windows Sensor and SDK please click here.
•

2.	操作系统及软硬件要求
Kinect支持的操作系统：
Windows 7, Windows 8, Windows 8.1, Windows Embedded Standard 7
•	硬件要求：
•	要使用 Kinect for Windows 传感器，您需要一台安装了以下软件的PC：
•	32 位 (x86) 或 64 位 (x64) 处理器
•	专用的 USB 2.0 总线
•	2 GB RAM
•	一台Microsoft Kinect for Windows 传感器
•	配置Kinect for windows sensor你需要准备以下软件：
•	Note:按住ctrl并单击就可以访问软件下载点
•	KinectSDK-v1.8-Setup.exe
•	SimpleOpenNI-1.96.zip
•	NiTE2-Windows-x64(x86)-2.21.zip
•	OpenNI-Windows-x64(x86)-2.2.0.33.zip
•	Processing-2.1.2-windows-x64(x86).zip
3.	Install SDK Instructions:
a)	首先确保Kinect传感器没有插入任何电脑上的USB端口。
b)	double-click on KinectSDK-v1.8-Setup.exe，开始安装Kinect for Windows SDK
正在安装Kinect for windows SDK ：
　　　　　 
安装完成，点击关闭退出！
c)	成功安装KinectSDK-v1.8-Setup.exe之后，把kinect传感器的usb插口接上电脑的usb端口（确保kinect传感器已经通上电源插头），kinect传感器相关的驱动会自动安装。
 
驱动安装完成会自动退出安装界面，我们可以到设备管理器查看驱动是否安装好：
 
d)	成功安装好kinect SDK跟kinect driver后，接下来就是OpenNI2的安装，选定下载对应版本的安装包（安装方式：“下一步”策略，安装目录自定）
e)	成功安装OpenNI2后，我们就可以安装NITE2了，方法同上。
f)	解压Processing-2.1.2-Windows-x64(x86).zip，此过程只需将压缩包解压到指定的目录即可(不需要安装)，打开解压文件夹：双击processing.exe即可进入processing的编程界面。
Processing一个开源的程序语言及开发环境，提供给那些想要对影像、动画、声音进行程序编辑的工作者。如果有兴趣的话，不妨在editor里面输入ellipse(50,50,80,80);点击运行，在绘制窗口里面会出现一个椭圆，如下图：
processing相关的tutorials, click here.
   
g)	最后一步解压SimpleOpenNI-1.96.zip(对于windows用户来说解压目录一定要是C:\Users\Administrator\Documents\Processing\libraries，否则运行案例程序会报错no librares found)，SimpleOpenNI为一些在processing里面编写的OpenNI的例程，我们可以SimpleOpenNI\examples\OpenNI里面找到相关的程序。

4.	测试：
安装好以上的软件后，我们到了测试阶段，以检测我们的kinect是否可以正常使用了，不妨使用OpenNI自带的程序来作为测试工具。
1.先把kinect传感器电源线插上，usb线接在电脑usb端口上，我们会发现kinect传感器的指示灯为绿色，kinect传感器正常工作，
2.打开OpenNI2\Samples\Bin，双击其中一个.exe文件（如ClosestPointViewer.exe）会出现扫描窗口：
 
Done！

