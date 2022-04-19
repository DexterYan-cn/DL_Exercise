# DL_Exercise
日常的深度学习练习（采用pytorch）

## 文件目录

```
data.py
Start.py
LeNet.py
touch_exercise.py
```

## 文件说明

### data.py

包含了数据处理模块，目前载入的数据为Cifar-10，需自行下载数据集，同时修改路径

### Start.py

包含了训练模块和测试模块，支持命令行方式运行

```python
命令行运行参数介绍：
# 批处理大小，默认32
--batch-size
# 训练轮次，默认20
--epochs
# 学习率，默认0.01
--lr
# 采用的模型，目前支持LeNet
--model
# 模型存放的路径，默认同文件夹下'./model.ckpt'
--model-save-path
# 是否采用cuda运行，默认否，当且仅当改参数为True，且机器支持GPU时可运行cuda
--cuda
```



### LeNet.py

基础的LeNet模型



### touch_Exercise(感知机)
使用的数据集是kaggle上面的house-prices-advanced-regression-techniques数据集，该文件用来熟悉touch的一些基础操作

