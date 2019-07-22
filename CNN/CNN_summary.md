# 【总结-渊源】卷积神经网络技术
@(算法模型)[CNN, Markdown]

[TOC]

## CNN研究意义
- 全连接网络对于图片识别应用，weights的个数非常巨大，需要巨大的内存与计算量；相比而言，CNN利用卷积核能够显著减小weights个数。
- CNN能够有效地extract图像的features，考虑了图像的空间变化。
- CNN在Computer Vision领域的应用非常有意义。
- Feature Engineering的好坏对机器学习效果的影响非常重要，对于不同人物，需要开展相应的有针对性的特征工程。CNN在学习过程中，不需要人为地进行feature engineering，不需要设定convolution kernel的固定数值，而是通过feature learning自动学习的。
> Convolutional nets do exactly this. Instead of having fixed numbers in our kernel, we assign parameters to these kernels which will be trained on the data. As we train our convolutional net, the kernel will get better and better at filtering a given image (or a given feature map) for relevant information. This process is automatic and is called feature learning. Feature learning automatically generalizes to each new task: We just need to simply train our network to find new filters which are relevant for the new task. This is what makes convolutional nets so powerful — no difficulties with feature engineering!


## References
- [Convolutional Neural Networks - deeplearning.ai](https://www.coursera.org/learn/convolutional-neural-networks/home/welcome)

