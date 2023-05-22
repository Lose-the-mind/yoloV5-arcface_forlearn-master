# yoloV5-arcface_forlearn-master
本次人脸识别实验参考的是这篇github博客（感谢作者大大）：
https://github.com/ooooxianyu/yoloV5-arcface_forlearn
一、模型介绍
    1、使用YOLOv5算法实现对人脸的检测，用的是celebA数据集（本次我没有进行训练直接使用的是yolov5已经训练好的模型）
    2、使用arcface算法实现人脸识别，CASIA-WebFace （我没有自己训练，直接用arcface源码提供的权重）
二、训练模型权重
    1、yoloV5的预训练权重包，训练好的侦测人脸的权重包best
    2、人脸识别的权重包resnet110
    下载地址：链接：https://pan.baidu.com/s/1YzgQcFVl4Rd6skN5q7mw-w 提取码：kusi
三、运行项目
    1、修改main.py文件中的相应位置代码，参考博客：https://blog.csdn.net/weixin_41809530/article/details/107313752
    2、将训练图片放在该项目相同的文件夹下，运行main.py即可
        
