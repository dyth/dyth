I am David Yu-Tung Hui / 許宇同.  My family name is Hui / 許 and my personal name is David Yu-Tung / David / 宇同.
I graduated from Mila, University of Montreal in 2023 with an MSc in deep reinforcement learning.

My research interest is to create algorithms that learn through interacting with the world.
I believe that these algorithms will be more scalable than those that learn from fixed, human-curated datasets about our world.

I like how deep reinforcement learning (RL) abstracts the process of learning through interaction into an optimization problem.
What interests me most is how to design an RL algorithm that is stable to optimize across a range of hyperparameters and MDPs.

I believe that RL algorithms are unstable because they do not optimize a mathematically sound objective function.
To this end, my research has focused on using linear algebra and probability theory to analyze and derive loss functions for RL algorithms.
So far, I have:
1. Shown that using LayerNorm in the critic network prevents divergence when optimizing the mean-squared semi-gradient loss, enabling us to learn high-dimensional continuous control tasks such as dog-run in DeepMind Control ([Stabilizing Q-Learning for Continuous Control, MSc Thesis](https://papyrus.bib.umontreal.ca/xmlui/bitstream/handle/1866/32085/Hui_David_Yu-Tung_2022_memoire.pdf?sequence=2)).
2. Introduced a heteroscedastic semi-gradient loss with tunable pessimism as a more performant replacement for the mean-squared semi-gradient loss, yielding an algorithm that attains up to 2x performance of SAC after training for 1M timesteps ([Double Gumbel Q-Learning, NeurIPS 2023 Spotlight](https://openreview.net/forum?id=UdaTyy0BNB)).


[Google Scholar](https://scholar.google.com/citations?user=pXHOdMwAAAAJ&hl=en)

[Short CV](https://dyth.github.io/CV_DavidYu_TungHui.pdf)
