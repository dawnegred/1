# 转变温度预测

## 前言
搭建一维卷积神经网络和三层mlp网络，对转变温度进行预测。

## 运行
在一维卷积神经网络上进行第一批数据的训练和预测

      cmd: python vgg.py

在三层mlp网络上进行第一批数据的训练和预测

      cmd: python mlp.py

在一维卷积神经网络上将第一批数据学习到的知识迁移到第二批数据

      cmd: python 1t2cnn.py

在三层mlp网络上将第一批数据学习到的知识迁移到第二批数据

      cmd: python 1t2mlp.py

在一维卷积神经网络上将第二批数据学习到的知识迁移到第三批数据

      cmd: python 2t3cnn.py

在三层mlp网络上将第二批数据学习到的知识迁移到第三批数据

      cmd: python 2t3mlp.py

在一维卷积神经网络上将第三批数据学习到的知识迁移到第四批数据

      cmd: python 3t4cnn.py

在三层mlp网络上将第三批数据学习到的知识迁移到第四批数据

## 结果
第一批数据集的pred和真实值整理为7174morgan.csv，第一批迁移到第二批的pred和真实值整理为679morgan.csv，第二批迁移到第三批的pred和真实值整理为575morgan.csv，第三批迁移到第四批的pred和真实值整理为38morgan.csv

      cmd: python 3t4mlp.py



