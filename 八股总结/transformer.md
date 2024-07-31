## Q：位置编码相关positonal encoding

## Q：自注意力机制数学表达式是什么
A：自注意力数学表达式为：
> ![image](https://github.com/user-attachments/assets/195ed14c-2fcb-4c3a-83aa-03e5dc360a6d)

其中`QKV`为查询、键、值矩阵，`dk`是键向量维度，这里通过将查询和键的点积除以根号dk进行缩放，然后用softmax获取权重，最后将权重用于值向量的加权求和。
## Q: 为什么计算时要除以根号dk
A: 

