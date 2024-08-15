I am David Yu-Tung Hui / 許宇同, and I am interested in model-free reinforcement learning.

My motivation is to create algorithms that learn about our world through interactions.
To achieve this goal, I develop Reinforcement Learning (RL) algorithms that frame the learning-through-interaction process as an optimization problem.
I'm curious about how to improve optimization in RL using insights from linear algebra and probability theory.

I've written two works on this theme:
1. [Stabilizing Q-Learning for Continuous Control (MSc Thesis, 2022)](https://papyrus.bib.umontreal.ca/xmlui/bitstream/handle/1866/32085/Hui_David_Yu-Tung_2022_memoire.pdf)
showed that adding LayerNorm to critic networks prevented semi-gradient updates of the mean-squared temporal-difference error from diverging.
Adding LayerNorm to DDPG solved high-dimensional continuous control tasks such as dog-run in DeepMind Control.

2. [Double Gumbel Q-Learning (Spotlight @NeurIPS 2023)](https://openreview.net/forum?id=UdaTyy0BNB)
showed that Maximum-Entropy RL algorithms have two heteroscedastic Gumbel noise sources.
Accounting for these noise sources improved the aggregate performance of SAC by 2x at 1M training timesteps.

In 2023, I graduated with an MSc from Mila, University of Montreal.
I'm looking for opportunities where I can continue my research.

For more information about me, see:

[Google Scholar](https://scholar.google.com/citations?user=pXHOdMwAAAAJ&hl=en)

[Short CV](https://dyth.github.io/CV_DavidYu_TungHui.pdf)
