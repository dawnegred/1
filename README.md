# 舰船分类
使用预训练的 ResNet18 模型进行舰船图像分类。

## 要求
- Python 3.x
- PyTorch
- Torchvision
- PIL（Pillow）
- Matplotlib
- Numpy

## 训练
```bash
python train.py
```
注意修改数据集路径
```bash
data_directory = "path/to/your/data"
```

## 训练
```bash
python infer.py
```
注意修改测试图片路径
```bash
test_image_path = "path/to/your/image"
```
