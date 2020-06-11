# Constrained-Policy-Optimization-Paper-Lists

This paper collection of contrained policy optimization classifies the papers according to the types of constraints they deal with. In the same class, papers are sorted by time. In the future, more reasonable classification standards will be adopted.

Constrained Policy Optimization is closely related to safe exploration, which means providing certain degree of safety guarantee during exploration procedure. More about exploration in reinforcement learning can be found in [RL-Exploration-Paper-Lists](https://github.com/apexrl/RL-Exploration-Paper-Lists/blob/master/README.md).

## Review / Survey

* <[Benchmarking Safe Exploration in Deep Reinforcement Learning](https://pdfs.semanticscholar.org/4d0f/6a6ffcd6ab04732ff76420fd9f8a7bb649c3.pdf)> by Alex Ray, Joshua Achiam and Dario Amodei, 2019.

* <[A Comprehensive Survey on Safe Reinforcement Learning](https://pdfs.semanticscholar.org/c0f2/c4104ef6e36bb67022001179887e6600d24d.pdf)> by Javier Garc´ıa and Fernando Fern´andez, 2015.

## Constraints on expectations

This type of constraints includes the total expected cost until the state reaches some set M, the expected discounted cost, expected average cost, etc.

* <[Safe Policy Learning for Continuous Control](https://openreview.net/pdf?id=HkxeThNFPH)> by Yinlam Chow, Ofir Nachum, Aleksandra Faust, Edgar Duenez-Guzman and Mohammad Ghavamzadeh, 2020.

* **[PCPO]** <[Projection-Based Constrained Policy Optimization](https://pdfs.semanticscholar.org/80ad/925b669e8d54dab4dd7c123e33a655612339.pdf)> by Tsung-Yen Yang, Justinian Rosca, Karthik Narasimhan and Peter J. Ramadge, 2020.

* **[RCPO]** <[Reward constrained policy optimization](https://arxiv.org/pdf/1805.11074)> by Chen Tessler, Daniel J. Mankowitz and Shie Mannor, 2019.

* <[Value constrained model-free continuous control](https://arxiv.org/pdf/1902.04623)> by Steven Bohez, Abbas Abdolmaleki, Michael Neunert, Jonas Buchli, Nicolas Heess and Raia Hadsell, 2019.

* <[Batch Policy Learning under Constraints](https://arxiv.org/pdf/1903.08738)> by Hoang M. Le, Cameron Voloshin and Yisong Yue, 2019.

* <[Constrained Cross-Entropy Method for Safe Reinforcement Learning]()> by Min Wen and Ufuk Topcu, 2018.

* <[A Lyapunov-based Approach to Safe Reinforcement Learning](http://papers.nips.cc/paper/8032-a-lyapunov-based-approach-to-safe-reinforcement-learning.pdf)> by Yinlam Chow, Ofir Nachum and Edgar Duenez-Guzman, 2018.

* **[CPO]** <[Constrained Policy Optimization](https://dl.acm.org/ft_gateway.cfm?id=3305384&type=pdf)> by Joshua Achiam, David Held, Aviv Tamar and Pieter Abbeel, 2017.

* **[CMDP]** <[Constrained Markov Decision Process](http://www-sop.inria.fr/members/Eitan.Altman/PAPERS/h.pdf)> by Eitan ALTMAN, 1999.
  
  This book establishes the framework of CMDPs and solve the optimization problem with known model by linear programming. But it does not give the solution for optimial control in high dimensional control.

## Separate constraints on each state/action

* <[Maximum Likelihood Constraint Inference for Inverse Reinforcement Learning](https://arxiv.org/pdf/1909.05477)> by Dexter R.R. Scobee and Shankar Sastry, 2019.

    This paper is in inverse RL setting.

* <[Safe Exploration in Continuous Action Spaces](https://arxiv.org/pdf/1801.08757)> by Gal Dalal, Krishnamurthy Dvijotham, Matej Vecerik, Todd Hester, Cosmin Paduraru and Yuval Tassa, 2018.

## Chance constraints

* <[Risk-Constrained Reinforcement Learning with Percentile Risk Criteria](http://www.jmlr.org/papers/volume18/15-636/15-636.pdf)> by Yinlam Chow, Mohammad Ghavamzadeh, Lucas Janson and Marco Pavone, 2015.
