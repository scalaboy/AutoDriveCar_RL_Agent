# AutoDriveCar_RL_Agent
![image](https://user-images.githubusercontent.com/10848033/115166619-a1a80f00-a0e6-11eb-8565-0ac3ff262990.png)

总起

这个repo会把近几年用强化学习来做自动驾驶决策器的文献和代码做一个整理。方便大家全面了解这个领域。自动驾驶一辆汽车是一个复杂决策问题。强化学习作为一个策略学习器，来做这个事情是比较合适的。有着广阔的前景。尽管目前没有全面接管，还在实验研究阶段，但终究会成为主流决策器。小RL Agent 从一开始模仿学习人类的驾驶决策行为，到可以学会自己跑直线，再到逆强化学习（IRL）来学习人类驾驶行为背后的激励函数，再到最近可以在CALAR模仿器中end2end的驾驶一辆汽车跑复杂城市道路。一切都在慢慢长大。

关于分类

如果按强化学习的方法来分，则会分的很细，有 on-Policy off-Policy,有Imitation learning ，Inverse Reinforcement Learning,按是否对环境建模有Model-base和model-free，甚至有多个agent模拟的  Multi-agent reinforcement learning，但如果从解决实际问题的角度出发，则可以分的比较清楚。就是end2end的驾驶决策器和no_e2e的驾驶决策器。这样就不会陷入细枝末节的方法分类里。也许最终的自动驾驶决策器的产品形态不会让Agent完全接管，例如用规则作为Agent的补充，来防止Agent的bad case的驾驶事故，但端到端学习驾驶决策是RL-Agent长大成人的主要标志。在自动驾驶业务角度看具有划时代意义。

