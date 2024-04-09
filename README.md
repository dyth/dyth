I am David Yu-Tung Hui / 許宇同.  In my name, my family name is Hui / 許 and my personal name is David Yu-Tung / David / 宇同.
I graduated from Mila, University of Montreal in 2023 with an MSc in deep reinforcement learning.

My research interest is to create algorithms that learn through interacting with the world.
I believe that these algorithms will be more scalable than those that learn from static datasets about our world curated by humans.

I like how deep reinforcement learning poses the learning through interaction as optimization.
What interests me most is how to design an RL algorithm that optimizes stably across a range of hyperparameters and MDPs.

I believe that RL algorithms are unstable because they do not optimize a mathematically sound objective function.
To this end, my research has focused on using linear algebra and probability theory to analyze and derive loss functions for RL algorithms.
I've written two works toward this goal:
1. [Stabilizing Q-Learning for Continuous Control, (MSc Thesis @University of Montreal)](https://papyrus.bib.umontreal.ca/xmlui/bitstream/handle/1866/32085/Hui_David_Yu-Tung_2022_memoire.pdf?sequence=2) showed that using LayerNorm in the critic network prevented divergence when minimizing the mean-squared semi-gradient loss, enabling the resultant algorithm to learn high-dimensional continuous control tasks such as dog-run in DeepMind Control.
2. [Double Gumbel Q-Learning, (Spotlight @NeurIPS 2023)](https://openreview.net/forum?id=UdaTyy0BNB) introduced a heteroscedastic semi-gradient loss with tunable pessimism as a more performant replacement for the mean-squared semi-gradient loss, yielding an algorithm that attains up to 2x performance of SAC after training for 1M timesteps.


[Google Scholar](https://scholar.google.com/citations?user=pXHOdMwAAAAJ&hl=en)

[Short CV](https://dyth.github.io/CV_DavidYu_TungHui.pdf)
