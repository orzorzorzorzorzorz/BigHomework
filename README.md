#《人工智能基础》大作业/实训

个人信息在提交的文档中



本项目直接包括了主实验exp1和补充实验exp2

##Exp1 (YOLOv5)

####1.环境配置

pip install -r .requirement.txt



####2.实验结果

* 准确率

    ==**93.6%       acc_top1**==

* 模型保存为exp1/best.pt



#### 3.运行

#####训练

* python exp1/train.py

#####验证

* python exp1/val.py

#####预测（单张图片)

* python exp1/predict.py



#### 4.代码结构

runs:存储运行记录

data:存储数据集

models:存储模型文件

val.py

predict.py

train.py



项目参考：https://github.com/ultralytics/yolov5



--------



## Exp2(ResNet50)

#### 1.环境配置

python == 3.6 
torch == 1.10.2 
torchvision == 0.11.3 
numpy == 1.19.5 



####2.实验结果

- 准确率

    ==**95.46%       acc_top1**==

* 模型保存为exp2/checkpoint/resnet50_cifar10.pt



#### 3.运行

#####训练

* python exp2/train.py

#####测试

* python exp2/test.py



#### 4.代码结构

utils:基本代码文件存放

dataset:存储数据集

checkpoint:存储模型文件

test.py

train.py



项目参考：https://github.com/ZOMIN28/ResNet18_Cifar10_95.46