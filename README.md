I am David Yu-Tung Hui / 許宇同, a 2023 MSc graduate from Mila, University of Montreal.

I'm interested in creating algorithms that learn through interactions with an environment.
I hope that these algorithms will eventually be used to discover new knowledge about our world.

To achieve this dream, I research reinforcement learning (RL) algorithms.
These algorithms frame the process of learning through interaction as an optimization problem.
My research focuses on using linear algebra and probability theory to design principled loss functions that enable stable optimization across a variety of settings. 

I've written two works toward this goal:
1. [Stabilizing Q-Learning for Continuous Control (MSc Thesis)](https://papyrus.bib.umontreal.ca/xmlui/bitstream/handle/1866/32085/Hui_David_Yu-Tung_2022_memoire.pdf)
showed that critic networks with LayerNorm had convergent semi-gradient updates of the mean-squared temporal-difference error.
This enabled learning high-dimensional continuous control tasks such as dog-run in DeepMind Control.

3. [Double Gumbel Q-Learning (Spotlight @NeurIPS 2023)](https://openreview.net/forum?id=UdaTyy0BNB)
showed that Maximum-Entropy RL has two heteroscedastic Gumbel noise sources.
Accounting for these noise sources improved the aggregate performance of SAC by 2x at 1M training timesteps.

I'm currently looking for opportunities where I can continue my research.

For more information about me, please see:

[Google Scholar](https://scholar.google.com/citations?user=pXHOdMwAAAAJ&hl=en)

[Short CV](https://dyth.github.io/CV_DavidYu_TungHui.pdf)
