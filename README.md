## Jittor 第四届人工智能挑战赛 热身赛方案

战队名：ECNU_IDEALab

![主要结果](result.png)

## 简介
本项目可在单个RTX 3090上运行，主要使用Jittor框架实现。在MNIST数据集上进行训练，然后生成一串指定的手写数字的图像。

## 安装 

#### 运行环境
- ubuntu 20.04 LTS
- python >= 3.7
- jittor >= 1.3.0

#### 安装依赖
执行以下命令安装 python 依赖
```
pip install -r requirements.txt
```

## 训练与推理

在CGAN.py文件中，将需要生成的数字填写到number变量
执行以下命令进行训练与推理，模型训练完成之后会自动进行推理来实现指定数字的手写体图片生成。
```
python CGAN.py
```

## 致谢
本项目代码主要参考了[Jittor-GAN](https://github.com/Jittor/JGAN)