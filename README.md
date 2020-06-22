# Lecture notes for Machine Learning (机器学习讲义)

Python 3.5

### 主要内容

- <a href="Chapter1-CN.pdf">Chapter1 基础知识(79 Pages)</a>
   - 模型、策略和算法；
   - 实例：多项式曲线拟合；
      - 正则项的意义；
      - 测试数据集与验证数据集的引入；
   - 模型学习的概率解释；
      - 概率学派与贝叶斯学派；
      - 最大似然估计与最大后验估计的引入；
      - 高斯分布及其性质；
      - 基于高斯分布的似然函数及最大化；
      - 最大似然方法的局限性；
      - 多项式曲线拟合问题的概率解释；
      - 多项式曲线拟合问题的改进；
      - 贝叶斯曲线拟合；
   - 附录；
      - 概率论基础知识；
      - 矩阵与向量；
      - 特征值与奇异值分解；
      - 梯度下降法；
      - 牛顿法与拟牛顿法；
      - 拉格朗日乘数法；
   - 实验：最小二乘法之直线拟合与多项式拟合，<a href="Chapter1-SourceCode.zip">Source Code</a>；

- <a href="Chapter2-CN.pdf">Chapter2 判别函数的线性分类基础(47 Pages)</a>
   - 二分类与多分类基础；
   - 基本判别函数；
      - 最小平方分类方法；
      - Fisher二分类方法；
      - 最小平方分类方法与Fisher分类方法；
      - Fisher多分类方法；
      - 感知机；
   - 附录；
      - 标量函数对矩阵的求导；
   - 实验：感知机，<a href="Perceptron.ipynb">Source Code</a>，<a href="Fitting-Perceptron.mp4">Result(Video)</a>；

- <a href="Chapter3-CN.pdf">Chapter3 K近邻(20 Pages)</a>
   - kNN模型；
      - 距离度量；
      - k值；
      - 决策规则；
   - kd树；
      - kd树的生成；
      - kd树的搜索；
   - 实验：<a href="Chapter3-SourceCode.zip">Source Code</a>；

- <a href="Chapter4-CN.pdf">Chapter4 决策树(47 Pages)</a>
   - 分类决策树；
      - 信息论基础：自信息、信息熵、条件熵、联合熵、互信息、相对熵、交叉熵；
      - 特征选择；
      - 决策树的生成：ID3与C4.5算法；
      - 剪枝算法；
   - 分类回归树(CART算法)
      - 回归树的生成；
      - 分类树的生成；
      - 剪枝算法；
   -实验：<a href="Chapter4-SourceCode.zip">Source Code</a>

- <a href="Chapter5-CN.pdf">Chapter5 朴素贝叶斯(17 Pages)</a>
   - 分类模型；
   - 类别推理的依据——期望风险最小化；
   - 参数估计；
   - 学习算法；
   - 实验：<a href="Chapter5-SourceCode.zip">Source Code</a>；
