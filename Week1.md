# PyTorch框架班 

## 🎯Week 1

### 🛴【任务1】

**任务名称：**  
PyTorch简介及环境配置；PyTorch基础数据结构——张量

**任务简介：**  
安装PyTorch依赖环境学习PyTorch中的数据结构Tensor和Variable

**详细说明：**  
本节第一部分介绍pytorch及pytorch作为深度学习框架的优势，并且基于Windows系统进行安装Pycharm、Anaconda、Cuda、cudnn和pytorch，环境配置好后会进行demo演示，测试pytorch可以正常使用。
本节第二部分介绍pytorch中的数据结构——Tensor，Tensor是PyTorch中最基础的概念，其参与了整个运算过程，因此本节将介绍张量的概念和属性，如data, device, dtype等，并介绍tensor的基本创建方法，如直接创建、依数值创建和依概率分布创建等。

**作业名称（详解）：**  
1. 安装anaconda,pycharm, CUDA+CuDNN（可选），虚拟环境，pytorch，并实现hello pytorch查看pytorch的版本
2. 张量与矩阵、向量、标量的关系是怎么样的？
3. Variable“赋予”张量什么功能？
4. 采用torch.from_numpy创建张量，并打印查看ndarray和张量数据的地址；
5. 实现torch.normal()创建张量的四种模式。
- 本节代码下载：🔪[张量简介与创建](https://github.com/JansonYuan/Pytorch-Camp/blob/master/%E4%BB%A3%E7%A0%81%E5%90%88%E9%9B%86/01-02-%E4%BB%A3%E7%A0%81-%E5%BC%A0%E9%87%8F%E7%AE%80%E4%BB%8B%E4%B8%8E%E5%88%9B%E5%BB%BA/lesson-02.py)
- 本节课件下载: 📌[Pytorch简介与安装](https://github.com/JansonYuan/Pytorch-Camp/blob/master/%E8%AF%BE%E4%BB%B6%E5%90%88%E9%9B%86/01-01-pytorch%E7%AE%80%E4%BB%8B%E4%B8%8E%E5%AE%89%E8%A3%85.pdf)📌[Pytorch开发环境安装<补充>](https://github.com/JansonYuan/Pytorch-Camp/blob/master/%E8%AF%BE%E4%BB%B6%E5%90%88%E9%9B%86/01-01-%E8%A1%A5%E5%85%85-ppt-pytorch%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83%E5%AE%89%E8%A3%85.pdf)🔪[张量简介及创建](https://github.com/JansonYuan/Pytorch-Camp/blob/master/%E8%AF%BE%E4%BB%B6%E5%90%88%E9%9B%86/01-02-ppt-%E5%BC%A0%E9%87%8F%E7%AE%80%E4%BB%8B%E5%8F%8A%E5%88%9B%E5%BB%BA.pdf)

### 🛴【任务2】

**任务名称：**  
张量操作与线性回归；计算图与动态图机制

**任务简介：**  
学习张量的基本操作与线性回归模型的实现；学习计算图概念，理解动态图和静态图的差异

**详细说明：**  
本节将介绍张量的基本操作，如张量拼接切分、索引和变换，同时学习张量的数学运算，并基于所学习的知识，实现线性回归模型的训练，以加深知识点的认识。
本节第二部分介绍pytorch最大的特性——动态图机制，动态图机制是pytorch与tensorflow最大的区别，该部分首先介绍计算图的概念，并通过演示动态图与静态图的搭建过程来理解动态图与静态图的差异。

**作业名称（详解）：**  
1. 调整线性回归模型停止条件以及y = 2*x + (5 + torch.randn(20, 1))中的斜率，训练一个线性回归模型；
2. 计算图的两个主要概念是什么？
3. 动态图与静态图的区别是什么？
- 本节代码下载: 🥥[张量操作](https://github.com/JansonYuan/Pytorch-Camp/blob/master/%E4%BB%A3%E7%A0%81%E5%90%88%E9%9B%86/01-03-%E4%BB%A3%E7%A0%81-%E5%BC%A0%E9%87%8F%E6%93%8D%E4%BD%9C%E4%B8%8E%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92/lesson-03.py)与[线性回归](https://github.com/JansonYuan/Pytorch-Camp/blob/master/%E4%BB%A3%E7%A0%81%E5%90%88%E9%9B%86/01-03-%E4%BB%A3%E7%A0%81-%E5%BC%A0%E9%87%8F%E6%93%8D%E4%BD%9C%E4%B8%8E%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92/lesson-03-Linear-Regression.py)🥝[计算图与动态图机制](https://github.com/JansonYuan/Pytorch-Camp/blob/master/%E4%BB%A3%E7%A0%81%E5%90%88%E9%9B%86/01-04-%E4%BB%A3%E7%A0%81-%E8%AE%A1%E7%AE%97%E5%9B%BE%E4%B8%8E%E5%8A%A8%E6%80%81%E5%9B%BE%E6%9C%BA%E5%88%B6/lesson-04-Computational-Graph.py)
- 本节课件下载: 🥥[张量的操作及线性回归](https://github.com/JansonYuan/Pytorch-Camp/blob/master/%E8%AF%BE%E4%BB%B6%E5%90%88%E9%9B%86/01-03-ppt-%E5%BC%A0%E9%87%8F%E7%9A%84%E6%93%8D%E4%BD%9C%E5%8F%8A%E7%BA%BF%E6%80%A7%E5%9B%9E%E5%BD%92.pdf)🥝[计算图与动态图机制](https://github.com/JansonYuan/Pytorch-Camp/blob/master/%E8%AF%BE%E4%BB%B6%E5%90%88%E9%9B%86/01-04-ppt-%E8%AE%A1%E7%AE%97%E5%9B%BE%E4%B8%8E%E5%8A%A8%E6%80%81%E5%9B%BE%E6%9C%BA%E5%88%B6.pdf)

### 🛴【任务3】

**任务名称：**  
autograd与逻辑回归

**任务简介：**  
学习pytorch的自动求导系统——autograd；通过autograd训练逻辑回归模型

**详细说明：**  
本节对pytorch的自动求导系统中常用的两个方法torch.autograd.backward和torch.autograd.grad进行介绍，并演示一阶导数，二阶导数的求导过程；理解了自动求导系统，以及数据载体——张量，前向传播构建计算图，计算图求取梯度过程，这些知识之后，就可以开始正式训练机器学习模型。这里通过演示逻辑回归模型的训练，学习机器学习回归模型的五大模块：数据、模型、损失函数、优化器和迭代训练过程。这五大模块将是后面学习的主线。

**作业名称（详解）：**  
1. 逻辑回归模型为什么可以进行二分类？
2. 采用代码实现逻辑回归模型的训练，并尝试调整数据生成中的mean_value，将mean_value设置为更小的值，例如1，或者更大的值，例如5，会出现什么情况？  
再尝试仅调整bias，将bias调为更大或者负数，模型训练过程是怎么样的？
- 本节代码下载: ☕[autograd](https://github.com/JansonYuan/Pytorch-Camp/blob/master/%E4%BB%A3%E7%A0%81%E5%90%88%E9%9B%86/01-05-%E4%BB%A3%E7%A0%81-autograd%E4%B8%8E%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92/lesson-05-autograd.py)与[逻辑回归](https://github.com/JansonYuan/Pytorch-Camp/blob/master/%E4%BB%A3%E7%A0%81%E5%90%88%E9%9B%86/01-05-%E4%BB%A3%E7%A0%81-autograd%E4%B8%8E%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92/lesson-05-Logistic-Regression.py)
- 本节课件下载: ☕[autograd与逻辑回归](https://github.com/JansonYuan/Pytorch-Camp/blob/master/%E8%AF%BE%E4%BB%B6%E5%90%88%E9%9B%86/01-05-ppt-autograd%E4%B8%8E%E9%80%BB%E8%BE%91%E5%9B%9E%E5%BD%92.pdf)
