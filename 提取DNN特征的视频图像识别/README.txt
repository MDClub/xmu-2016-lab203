队伍名称：lab203
项目名称：视频图像识别
团队队长：杨恒宝
团队成员：唐志敏、李少辉、曹磊、李虎
项目简介：视频图像识别，找出视频中有模板图像中的人，并红色框标记。
1、平台：Microsoft Visual Studio 2015 和OpenCV3.10
2、Harr进行人脸检测
3、提取人脸的cnn特征进行人脸匹配
4、程序运行：
   main.cpp中
   string VideoPath="girl.flv";//视频的地址
   string TemplateFacePath="girl.png";//模板图像的地址
5、因为实验室电脑配置很低，内存不够于这个代码的运行。我们是提
取一张张图像提取cnn特征，再计算同一个人和不同人之间cnn特征距离。
2015年12月caffe才加进OpenCV3.10中。对于caffe，我们有一定的研究。