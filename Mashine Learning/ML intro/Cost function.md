成本函数的定义

成本函数用于评估模型的表现，帮助我们调整模型参数以提高预测准确性。
线性回归模型的参数包括权重（w）和偏置（b），它们决定了模型的预测函数。

参数parameters的影响(有时被称为系数coefficients/权重weights)

不同的w和b值会生成不同的预测线，影响模型的拟合效果。
通过图示化不同参数的影响，可以直观理解模型的行为。
成本函数的构建

成本函数通过计算预测值与真实值之间的误差来评估模型的表现。
采用平方误差的平均值作为成本函数，以便在训练集上衡量模型的整体表现。
<img width="654" height="323" alt="image" src="https://github.com/user-attachments/assets/e776853c-e830-4d20-9d6a-0f4a2d35efc9" />
成本函数的定义与作用

成本函数 J 用于衡量模型预测值与实际值之间的差异。
目标是找到参数 w 和 b，使得成本函数 J 的值尽可能小。
简化线性回归模型

在简化模型中，仅考虑参数 w，成本函数 J 变为仅依赖于 w 的函数。
通过选择不同的 w 值，可以观察到成本函数 J 的变化。
成本函数的可视化

通过图形展示，随着 w 的变化，模型 f(x) 的直线形状也会变化。
每个 w 值对应一个成本 J(w)，可以通过绘制这些点来描绘成本函数的形状。
<img width="921" height="475" alt="image" src="https://github.com/user-attachments/assets/d6ebe7b8-470b-47e4-8c12-0fc852ae96d5" />
<img width="828" height="490" alt="image" src="https://github.com/user-attachments/assets/d63215c2-920a-493b-870d-85780c984dc8" />
