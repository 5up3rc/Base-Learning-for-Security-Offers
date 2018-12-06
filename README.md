# Base-Learning-for-Security-Offers
## 404notfound的知识库
- [基础语言类]
  - [Java](#Java基础知识)
  - [Python](#Python基础知识)
- [四大科班基础课程类]
  - [数据结构]
  - [计算机网络]
  - [操作系统]
  - [计算机组成原理]
- [机器学习基础类]
  - [理论基础](#理论基础)
  - [算法原理](#算法原理)
  - [算法特性、优缺点]
  - [算法比较](#算法比较)
- [网络空间安全基础类]
  - [网络安全]
  - [应用安全]
  - [系统安全]
- [安全算法类]

# 基础语言类 #
## Java基础知识 ##
- [(Java中)堆和栈的区别](https://www.cnblogs.com/zyj-bozhou/p/6723863.html)
联系数据结构中、操作系统中、C++中、Java中堆和栈的区别

## Python基础知识 ##
* [Python装饰器、迭代器、生成器原理及应用场景](https://www.jianshu.com/p/efaa19594cf4)<br>
* [Python进程、线程和协程的区别及应用场景](https://zhuanlan.zhihu.com/p/30980478)<br>
* [Python扫描速度的优化到GIL锁的原理和优化](http://cenalulu.github.io/python/gil-in-python/)
* [masscan扫描和nmap扫描等端口探测的原理和方式](http://www.freebuf.com/articles/network/146087.html)<br>

# 机器学习基础类 #
## 理论基础 ##
- 怎么防止过拟合？
答：a. 增加样本（data bias or small data的缘故），移除噪声。
b. 减少特征，保留重要的特征（可以用PCA等对特征进行降维）。
c. 对样本进行采样（类似bagging）。就是建树的时候，不是把所有的样本都作为输入，而是选择一个子集。
d. 对特征进行采样。类似样本采样一样, 每次建树的时候，只对部分的特征进行切分。
- 机器学习里面的偏差和方差有什么区别
- [L1和L2有什么区别？](https://www.zhihu.com/question/26485586)
从最优化问题解的平滑性来看，L1范数的最优解相对于L2范数要少，但其往往是最优解，而L2的解很多，但更多的倾向于某种局部解。
- [为什么L1能得到稀疏解？](https://www.zhihu.com/question/37096933)
答：L1、L2两种正则能不能把最优的x变成0，取决于原先的函数在0点处的导数。如果本来导数不为0，那么施加L2正则后导数依然不为0，最优的x也不会变成0；而施加L1正则时，只要正则项的系数C，大于原先函数在0点处的导数的绝对值，x=0就会变成一个极小值点。上面只分析了一个参数x，事实上L1正则会使许多参数的最优值变成0，这样模型就稀疏了。

## 算法原理 ##
- xgb的原理

## 算法比较 ##
- [RF、GBDT和XGB比较](https://zhuanlan.zhihu.com/p/34679467)
- lgb和xgb有什么区别

