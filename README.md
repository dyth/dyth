### David Yu-Tung Hui, 許宇同

I am an independent researcher interested in Deep Reinforcement Learning (RL).
My research goal is to make RL algorithms more scalable by improving their optimization stability using principled methods from probability theory and analysis.
I'm especially curious about how to design gradient-based optimization algorithms that enable neural networks to learn Q-functions.

I've written two works along this research direction:
1. [Stabilizing Q-Learning for Continuous Control](https://papyrus.bib.umontreal.ca/xmlui/bitstream/handle/1866/32085/Hui_David_Yu-Tung_2022_memoire.pdf) (MSc Thesis, University of Montreal, 2022)
showed that adding LayerNorm to critic networks prevented semi-gradient updates of the mean-squared temporal-difference error from diverging.
Adding LayerNorm to DDPG solved high-dimensional continuous control tasks such as dog-run in DeepMind Control.

2. [Double Gumbel Q-Learning](https://openreview.net/forum?id=UdaTyy0BNB) (David Yu-Tung Hui, Aaron Courville, Pierre-Luc Bacon, NeurIPS 2023 Spotlight)
showed that Maximum-Entropy RL algorithms have two heteroscedastic Gumbel noise sources.
Accounting for these noise sources improved the aggregate performance of SAC by 2x at 1M training timesteps.

In 2023, I graduated with an MSc from Mila, University of Montreal.
I'm looking for opportunities where I can continue my research.

For more information about me, see:

[Google Scholar](https://scholar.google.com/citations?user=pXHOdMwAAAAJ&hl=en)
