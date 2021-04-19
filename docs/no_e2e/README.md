PART A 
模仿学习 Imitating learing 

1、Chauffeurnet: Learning to drive by imitating the best and synthesizing the worst
Bansal, Mayank, Alex Krizhevsky, and Abhijit Ogale. "Chauffeurnet: Learning to drive by imitating the best and synthesizing the worst." arXiv preprint arXiv:1812.03079 
(2018).

简介：这篇文章是强化学习做自动驾驶的经典之作。引用次数已经快300了。
核心思想是 在3000万（60天）驾驶记录数据中，通过数据增强的方式，构建一些碰撞、异常处理的数据，从而提升模仿学习样本的多样性。

其他方面：非end2end，输入的是一个原始图像数据处理过的中间结果，输出的也是一个中间结果，然后通过控制模块综合处理操作汽车。
在实际操作中有真实驾驶测试。

缺点：目前模仿学习做自动驾驶不是主流方式。不够鲁棒。但是历史思想来源之一。值得学习研究。懂历史才能知未来。


PART B model-free 

2、Driving in Dense Traffic with Model-Free Reinforcement Learning
Dhruv Mauria Saxena1, Sangjae Bae2, Alireza Nakhaei3, Kikuo Fujimura3, Maxim Likhachev1 ICRA2020

主要是解决可变车道短，拐角处怎么学策略的问题
![image](https://user-images.githubusercontent.com/10848033/115192590-98866480-a11d-11eb-9173-ad7d2afab194.png)



PART M  Multi-agent self-driving

1、P. Palanisamy, “Multi-agent connected autonomous driving using deep
reinforcement learning,” in 2020 International Joint Conference on
Neural Networks (IJCNN). IEEE, 2020

2、S. Bhalla, S. Ganapathi Subramanian, and M. Crowley, “Deep multi
agent reinforcement learning for autonomous driving,” in Advances in
Artificial Intelligence, C. Goutte and X. Zhu, Eds. Cham: Springer
International Publishing, 2020,

3、A. Wachi, “Failure-scenario maker for rule-based agent using multiagent
adversarial reinforcement learning and its application to autonomous
driving,” arXiv preprint arXiv:1903.10654, 2019.

4、C. Yu, X. Wang, X. Xu, M. Zhang, H. Ge, J. Ren, L. Sun, B. Chen, and
G. Tan, “Distributed multiagent coordinated learning for autonomous
driving in highways based on dynamic coordination graphs,” IEEE
Transactions on Intelligent Transportation Systems, vol. 21, no. 2, pp.
735–748, 2020.


