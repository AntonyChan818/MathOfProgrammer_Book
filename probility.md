- Joint probability
![](https://github.com/AntonyChan818/MathOfProgrammer_Book/blob/master/Res/pro_1.png)  
- 概率图模型  
- chain rule   

从数据中推断模型参数  
在贝叶斯机器学习中，我们同样采用贝叶斯公式从data（D）中推导模型参数（θ）。  
P(θ|D) = P(D|θ) * P(θ) / P(data)  
值得说明的是，P（data）在通常情况下无法被计算，但这并不会带来什么问题。因为我们在推导及求解的过程中，最重要的还是那些含有θ的表达式，而P（data）到底是多少，其实并不需要真的求出来。  
P(θ) 为先验概率，也就是我们对样本空间中各类样本所占比例的可能性推测。通常我们认为，当训练集包含重组的独立同分步样本时，P(θ) 可通过各类样本出现的频率进行判断。关于先验的其它知识，可以参考Where priors come from的介绍。  
P(D|θ) 是样本D相对于类标记θ的类条件概率，也就是我们理解的「似然」。人们经常会使用可能性来评估模型，如果对实际数据能做出更高可能性的预测，那么这个模型自然更为有效。
那么，等式左边的P(θ|D) 就是我们最终想得到的东西，也就是基于先验概率与数据所获得的模型参数所呈现的概率分布。
如果能通过数据采样来估计概率分布参数，最经典的方法就是最大似然估计（maximum-likelihood estimation，MLE），也就是我们所说的极大似然法。而如果将先验考虑在内，那么就是最大后验概率（MAP）。如果在先验均匀分布的情况下，这两者应该相同。

- tree diagram


---
- learning map  
![](https://github.com/AntonyChan818/MathOfProgrammer_Book/blob/master/Res/DL_1.png)
- Supervised learning  
dataset:  
![](https://github.com/AntonyChan818/MathOfProgrammer_Book/blob/master/Res/DL_2.png)  

- Linear Regression 拟合问题  
![](https://github.com/AntonyChan818/MathOfProgrammer_Book/blob/master/Res/DL_3.png)
![](https://github.com/AntonyChan818/MathOfProgrammer_Book/blob/master/Res/DL_4.png)  

- closed form solution  
- regularized least square regression  
- gradient descent  
![](https://github.com/AntonyChan818/MathOfProgrammer_Book/blob/master/Res/DL_5.png)
---


Linear Classification and Support Vector Machine and Stochastic Gradient Descent 
- Linear Classification  
- support Vector machine  
使用支持向量机模型来寻找最好的分类器  
<matrix cookbook>  

- Stochastic Gradient Descent  
- Mini-Batch Stochastic Gradient Descent  
- Dual Problem
---
Adam Gradient 
![](https://github.com/AntonyChan818/MathOfProgrammer_Book/blob/master/Res/DL_6.png)
![](https://github.com/AntonyChan818/MathOfProgrammer_Book/blob/master/Res/DL_7.png)
---
docker  

