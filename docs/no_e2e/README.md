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


PART C model-base

We conducted experiments under
three different scenarios, straight lane, 90 turning, and
circular roundabout.


PART D Inverse Reinforcement Learning

1 Adversarial Inverse Reinforcement Learning with Self-attention Dynamics Model
Jiankai Sun,  Lantao Yu,  Pinqian Dong, Bo Lu, Bolei Zhou
The Chinese Univsersity of Hong Kong, Stanford Univsersity,
Huazhong University of Science and Technology

这篇文章是针对机器人算法做的优化，但很有借鉴意义。他本质是构建了一个对抗逆强化学习模型，能够更加有效的拟合专家行为。大家知道，逆强化学习是根据专家行为，来学习一个激励函数，
用来构建模型来拟合专家的行为，但这个过程的监督信号是比较弱的，通过对抗逆强化学习，来有效增强学习到的模型的精确性。

2、Incorporating Multi-Context Into the Traversability Map for Urban Autonomous Driving Using Deep Inverse Reinforcement Learning
David Hyunchul Shim
School of Electrical Engineering, Korea Advanced Institute of Science and Technology, Daejeon, South Korea
IEEE Robotics and Automation Letters ( Volume: 6, Issue: 2, April 2021) 

这篇文章是韩国小哥的文章。也很有意思。他是把整个环境（包括行人 车 道路）的上下文动态信息糅合进整个net，然后预测一个可驾驶图。从而提升驾驶行为的精度。实验表明整个驾驶轨迹跟人类驾驶轨迹很接近。这个方法已经在实际测试车上用了

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




