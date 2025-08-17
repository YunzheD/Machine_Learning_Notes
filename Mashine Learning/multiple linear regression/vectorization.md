多元线性回归概述

使用向量表示参数，将多个参数 ( w_1 ) 到 ( w_n ) 收集为一个向量 ( w )。
模型表示为 ( f_{w,b}(x) = w \cdot x + b )，其中 ( b ) 仍为一个数。
梯度下降法

更新规则为 ( w_j = w_j - \alpha \cdot \frac{\partial J}{\partial w_j} )，其中 ( J ) 是成本函数。
对于多元线性回归，更新规则适用于所有参数 ( w_1 ) 到 ( w_n ) 和 ( b )。
正常方程法

另一种求解 ( w ) 和 ( b ) 的方法，称为正常方程法，不需要迭代。
该方法在特征数量较大时较慢，且不适用于其他学习算法。
<img width="738" height="364" alt="image" src="https://github.com/user-attachments/assets/886d150f-5831-408e-a6bc-412291ff7f90" />
<img width="732" height="362" alt="image" src="https://github.com/user-attachments/assets/ef98795e-12b4-41bb-a5cb-13ade947c623" />
