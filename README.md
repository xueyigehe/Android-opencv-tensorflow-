# Android-opencv-tensorflow-
Android+opencv+tensorflow，使用Android studio开发app，使用tensorflow训练的模型给手机使用，将tensorflow移植到手机上，利用Android端的opencv对摄像头实时获取的图片进行处理
实验效果：
<img src="https://github.com/xueyigehe/Android-opencv-tensorflow-/blob/master/result_img/Screenshot_20180608-172112.png" width="380"/>
<img src="https://github.com/xueyigehe/Android-opencv-tensorflow-/blob/master/result_img/Screenshot_20180608-174111.png" width="380"/>
<img src="https://github.com/xueyigehe/Android-opencv-tensorflow-/blob/master/result_img/Screenshot_20180609-223847.png" width="380"/>
<img src="https://github.com/xueyigehe/Android-opencv-tensorflow-/blob/master/result_img/Screenshot_20180609-224043.png" width="380"/>

master项目可在Android Studio中打开进行开发，使用的是opencv3.2。若直接使用，首先需要安装opencv manager（按照自己手机的架构选择安装包，我华为荣耀9选的是armeabi）：
https://github.com/xueyigehe/Android-opencv-tensorflow-/tree/master/apk
实时识别的安装包为apk文件下的tensorflowmnist.spk：
https://github.com/xueyigehe/Android-opencv-tensorflow-/tree/master/apk
使用时先打开opencv manager，退出后启动识别app即可使用。

由于是使用了opencv中的图像分割，将所有分割物体进行识别，结果都会为数字，即如果将摄像头对着文字，识别结果也会错误的显示为数字。所以此app只适用于手写数字识别。

实验结果的显示窗口只在中间小区域，找了很多资料，有人说这是opencv竖屏的结果，也改了一下，发现满屏后图像会失真，希望有懂的人可以交流一下。

欢迎关注公众号：机器学习与实践
