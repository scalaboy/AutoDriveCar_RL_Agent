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
