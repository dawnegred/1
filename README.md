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

      cmd: python 3t4mlp.py



