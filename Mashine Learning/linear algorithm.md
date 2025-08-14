线性回归模型概述

线性回归是将一条直线拟合到数据上，是最常用的学习算法之一。
通过使用波特兰的房屋大小和价格数据集，可以预测房屋的售价。

监督学习通过提供带有正确答案的数据来训练模型，线性回归模型属于回归模型regression model，预测数值输出（如价格）。
与回归模型相对的是分类模型，后者预测离散类别（如猫或狗）。
数据集和标准符号

用于训练模型的数据集称为训练集，输入变量用小写字母x表示，输出变量用小写字母y表示。
每个训练示例用(x, y)表示，训练集中的每一行对应一个房屋的大小和价格。
x="input" variable feature
y="output" variable/ "target"variable
m= number of training examples
(x,y)=single training example
<img width="458" height="139" alt="image" src="https://github.com/user-attachments/assets/bee1f88e-537b-432e-8e72-272c34b56649" />
监督学习的基本概念

监督学习算法使用包含输入特征（如房屋大小）和输出目标（如房屋价格）的训练集进行训练。
训练后，算法生成一个函数f，该函数用于根据新的输入x预测输出y-hat（估计值）。
线性回归模型

线性回归模型的形式为f_w,b(x) = wx + b，其中w和b是决定预测y-hat的参数。
该模型通过绘制训练集数据，生成最佳拟合直线，帮助进行预测。
成本函数的重要性

成本函数是机器学习中的一个重要概念，用于评估模型的预测效果。
<img width="560" height="478" alt="image" src="https://github.com/user-attachments/assets/4980ef85-2691-4aa6-9977-cd988871f0d5" />
<img width="534" height="463" alt="image" src="https://github.com/user-attachments/assets/2b325a17-369d-44c9-97f3-d472d2e3a85b" />
