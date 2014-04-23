Installing - kinect-for-windows-sdk - using-Openni-and-NiTE
This tutorial will introduce how to install kinect for windows sdk (v1.8) (Openni and Nite)

Details: The Kinect for Windows SDK includes the following: 
• Drivers for using Kinect for Windows sensors on a computer running Windows 7, Windows 8, Windows 8.1, and Windows Embedded Standard 7 
• Application programming interfaces (APIs) and device interfaces 
• Note: Samples, tools, and other valuable development resources are available in the Kinect for Windows Developer Toolkit. • However, if you want to know more about Kinect for Windows Sensor and SDK google •

Kinect operating systems and hardware and software requirements Supported operating systems: 
Windows 7, Windows 8, Windows 8.1, Windows Embedded Standard 7 • 

Hardware requirements: 
• To use the Kinect for Windows sensor, you need a computer with the following software PC: 
• 32 bit (x86) or 64-bit (x64) processor 
• Dedicated USB 2.0 bus 
• 2 GB RAM 
• A Microsoft Kinect for Windows sensor 

• Kinect for windows sensor configuration you need the following software: 

Download 
• KinectSDK-v1.8-Setup.exe 
• SimpleOpenNI-1.96.zip 
• NiTE2-Windows-x64 (x86)-2.21.zip 
• OpenNI-Windows-x64 (x86) -2.2.0.33.zip 
• Processing-2.1.2-windows-x64 (x86).zip

Install SDK Instructions: 
a) First make sure Kinect sensor is not plugged into any USB port on your computer. 
b) double-click on KinectSDK-v1.8-Setup.exe, begin installing Kinect for Windows SDK is being installed Kinect for windows SDK: the installation is complete, click Close to exit! 
c) After successful installation KinectSDK-v1.8-Setup.exe, the usb kinect sensor socket connected to the computer's usb port (ensure kinect sensor has pass on the power plug), kinect sensor associated driver is installed automatically.
Driver installation will automatically exit the installation interface, we can go to the Device Manager to see if the driver is installed.
d) After successfully installing the kinect SDK with kinect driver, the next step is to install OpenNI2 selected download the corresponding version of the installation package (Installation: After the "Next" strategy, custom installation directory) 
e) successfully installed OpenNI2, we you can install NITE2 the methods above. 
f) extracting Processing-2.1.2-Windows-x64 (x86) zip, this process simply unpack the archive to the specified directory can (no installation), open the unpacked folder: Double-click to enter processing.exe processing the programming interface. Processing an open source programming language and development environment available to those workers want to images, animations, sounds for program editing. If you are interested, may wish to enter the editor inside the ellipse (50,50,80,80); click Run, which will appear in the window to draw an ellipse, as shown below: processing-related tutorials, click here.
g) The final step to extract SimpleOpenNI-1.96.zip (For windows users, it must be unpacked directory C: \ Users \ Administrator \ Documents \ Processing \ libraries, otherwise the program will run error case no librares found), SimpleOpenNI there is some processing OpenNI written routines, we can SimpleOpenNI \ examples \ OpenNI inside to find the relevant procedures.

Testing: After installing more software, we went to the testing phase, to detect whether our kinect normal use, may wish to use OpenNI program comes as a testing tool. 1 first kinect sensor power cord plug, usb cable connected to the computer usb port, we will find that the indicator is green kinect sensor, kinect sensor is working properly, 2 open OpenNI2 \ Samples \ Bin, double-click one. Exe files (such as ClosestPointViewer.exe) scan window will appear.

Done!
