# 大创选题
## ABM
### 1、文献支撑
#### [理论2020 AER: Artificial Intelligence, Algorithmic Pricing, and Collusion （ABM+合谋）](./可行性讨论.md)
#### [实证Algorithmic Pricing and Competition: Empirical Evidence from the German Retail Gasoline Market，Journal of Political Economy](./Empirical.md)
### 2、可行性讨论
（1）[代码](./双寡头ABM_pricing.ipynb)
[代码的具体说明](./code.md)

跑一次大概几秒钟；Q-learning技术实现不难

（2）有没有“ABM+”的可能？

**idea1**  非对称需求会打破算法合谋吗？修改原来代码的demand函数 不用Logit需求。设定平台A有30%绝对不会走的用户，平台B只有10%

**idea2**  上游动态抽成策略会打破算法合谋吗？引入上游供应商，比如1个供应商+2个零售商。把供应商设定为rule-based（比如供应商按照下游零售价按比例抽成），让两个下游零售商用Q-learning博弈

**idea3** 复现文献，用社会网络分析方法 讨论 “监管”

### 3、我们的问题

（1）目前没想到ABM+ 的方向

（2）背景设定：数据市场/电力市场/....

（3）ABM的认可度？
