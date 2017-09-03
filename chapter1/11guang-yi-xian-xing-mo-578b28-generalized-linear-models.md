# 1.1.广义线性模型

 > 以下是一组用于回归的方法，其中目标值预期是输入变量的线性组合。在数学概念中，如果$$\hat{y}$$是预测值。》

>$$
 \hat{y}（w，x）= w_0 + w_1 x_1 + ... + w_p x_p
$$


> 在整个模块中，我们指定向量w =（w_1，...，w_p）作为coef_和w_0作为intercept_。
   要使用广义线性模型执行分类，请参阅 Logistic回归。 



[引用 文档](http://scikit-learn.org/stable/modules/linear_model.html "sklearn 文档")
```
  reg.coef_ //斜率
  reg.intercept_ //截距
  r-squared //r 的平方  最大为1 越接近一 性能越好 
```