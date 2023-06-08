import numpy as np

# 创建两个矩阵
A = np.array([[1, 2], [3, 4]])
B = np.array([[5, 6], [7, 8]])

# 矩阵加法
C = A + B

# 矩阵乘法
D = np.dot(A, B)

# 打印结果
print('A + B =', C)
print('A * B =', D)
