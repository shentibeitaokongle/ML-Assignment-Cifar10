# ML-Assignment-Cifar10    

2019 《“智能移动互联网+”创新创业实践》课人工智能模块在线学习仓库     

组长：鲍骞月    

## 大作业任务  

### [任务1.k-Nearest Neighbor classifier](knn-classification)

Jupyter Notebook **knn.ipynb**将引导你实现k-NN分类器。

数据集: CIFAR-10

- 实现k-NN算法。
- 通过使用部分向量化完成KNN算法。
- 通过使用全部矢量化来完成KNN算法。
- 通过交叉验证确定超参`k`的最佳值。    
- 特征提取     

*暂时不考虑图像数据的特征提取以及其他更好的分类算法。*

### [任务2.Two layers Neural Network(NN)](nn-classification)  

提高分类准确度   
This is your chance to show off! Try to get higher accuracy.

通过设计和实现新的特征并且选择算法来对CIFAR-10进行分类   
Design and implement a new type of feature and select an algorithm, and use them for image classification on CIFAR-10.   

* 实现前馈传播算法   
* 实现反向传播算法   
* 实现优化算法         
* 特征提取   
#### 参考    

* [理解softmax和softmax loss](https://blog.csdn.net/u014380165/article/details/77284921)    
* [理解反向传播](https://blog.csdn.net/u014380165/article/details/71181256)    

### 任务3.卷积神经网络实现  

* Tensorflow    
* 特征工程   
    * 提取图像频率域特征   
    * 小波变换   
    * 傅立叶变换     
    * ..      

## TODO List  

### 鲍骞月   
1. [x] kNN(矢量化距离计算)   
2. [x] NN(反向传播)   
3. [x] NN(调整超参数)            
4. [x] 图像特征提取     

### 张泽亿   
1. [x] kNN(半矢量化距离计算)    
2. [x] NN(训练函数)      
3. [x] NN(预测函数)   
4. [x] NN(调整超参数)      

### 景金龙    
1. [x] kNN(交叉验证)    
2. [x] NN(前向传播：计算损失)    
3. [x] NN(调整超参数)      

### 许瑞洋    
1. [x] kNN(非矢量距离计算，预测函数)    
2. [x] NN(前向传播：计算预测分数)     
3. [x] NN(调整超参数)       


## 小组成员

| Github                                             | 姓名   | 任务分工                      |
| -------------------------------------------------- | ------ | ----------------------------- |
| [BarackBao](https://github.com/shentibeitaokongle) | 鲍骞月 | 任务分配，kNN(矢量化距离计算)，NN(反向传播)， 图像特征提取      |
| [MIKIMIKA](<https://github.com/MIKIMIKA>)          | 张泽亿 | kNN(半矢量距离计算)，NN(随机梯度下降)          |
| [jjl1203](<https://github.com/jjl1203>)            | 景金龙 | kNN(交叉验证)，NN(前向传播：计算损失)                  |
| [MissXdd](<https://github.com/MissXdd>)            | 许瑞洋 | kNN(非矢量距离计算，预测函数)，NN(前向传播：计算预测分数)           |


