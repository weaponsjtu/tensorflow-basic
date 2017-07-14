# 准备事项
1. 自带电脑
2. 安装培训所需软件
  - Python >= 2.6
  - TensorFlow >= 1.0

# 课程简介
近几年深度学习技术在学术界和工业界都得到了广泛的应用和传播。深度学习的传播不仅是由于算法的进步，更是因为深度学习技术在各行各业都取得了非常好的应用效果。

深度学习作为一门理论和实践相结合的学科，在新的算法理论不断涌现的同时，各种深度学习框架也不断出现在人们视野。比如Torch，MxNet，theano，Caffe等等。Google在2015年11月9日宣布开源自己的第二代机器学习系统Tensorflow。深度学习是未来新产品和新技术的一个关键部分。在这个领域的研究是全球性的，并且发展很快，却缺少一个标准化的工具。Google希望把Tensorflow做成深度学习行业的标准。

Tensorflow支持python和c++语言，支持CNN、RNN和LSTM等算法，可以被用于语音识别或图像处理等多项深度学习领域。它可以在一个或多个CPU或GPU中运行。它可以运行在嵌入式系统(如手机，平板电脑)中，PC中以及分布式系统中。它是目前全世界最火爆的深度学习平台(没有之一)。

课程内容基本上是以代码编程为主，也会有少量的深度学习理论内容。课程会从Tensorflow最基础的图(graphs),会话(session),张量(tensor),变量(Variable)等一些最基础的知识开始讲起，逐步讲到Tensorflow的基础使用，以及在Tensorflow中CNN的使用、训练可视化。在课程的后面会带着大家一起做实际的项目，比如训练自己的模型去进行手写数字识别。课程中还会为大家带来AlphaGo的核心算法，介绍如何打造自己的AlphaGo。


# TensorFlow培训大纲
1. TensorFlow新手入门
  - 简介
  - [下载与安装](http://www.tensorfly.cn/tfdoc/get_started/os_setup.html)
2. [TensorFlow的基础使用](http://www.tensorfly.cn/tfdoc/get_started/basic_usage.html)
  - 数据流图介绍
  - Graph，session，tensor，variable等基本概念介绍
3. [基于TensorFlow实现MNIST多分类](http://www.tensorfly.cn/tfdoc/tutorials/mnist_beginners.html)
  - Softmax简介
  - 实现一个简单的多分类程序
4. 使用TensorBoard可视化学习
  - [训练过程可视化](http://www.tensorfly.cn/tfdoc/how_tos/summaries_and_tensorboard.html)
  - [网络结构可视化](http://www.tensorfly.cn/tfdoc/how_tos/graph_viz.html)
5. [卷积神经网络](http://www.tensorfly.cn/tfdoc/tutorials/deep_cnn.html)
  - 卷积神经网络介绍
  - CIFAR-10图像多分类问题
  - 多GPU训练模型
  - 分布式训练
6. AlphaGo的policy和value网络
  - AlphaGo核心算法简介
  - Policy Network模型结构与训练
  - Value Network模型结构与训练
7. 其它
  - 如何加速训练
  - [数据序列化](http://www.tensorfly.cn/tfdoc/how_tos/reading_data.html)
