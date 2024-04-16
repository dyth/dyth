I am David Yu-Tung Hui / 許宇同.
My family name is Hui / 許, and my personal name is David Yu-Tung / David / 宇同.
I graduated from Mila, University of Montreal in 2023 with an MSc in deep reinforcement learning.

My research focuses on creating algorithms that learn through interacting with the world.
I believe that these algorithms will be more scalable than other algorithms that learn from static human-curated datasets.

To create algorithms that learn through interaction, I use reinforcement learning -- an approach that presents this learning process as an optimization problem.
I am especially interested designing RL algorithms that optimize stably across a range of settings.
To this end, my research has focused on using linear algebra and probability theory to understand the mathematical soundness of loss functions optimized by RL algorithms.
I've written two works toward this goal:
1. [Stabilizing Q-Learning for Continuous Control, (MSc Thesis @University of Montreal)](https://papyrus.bib.umontreal.ca/xmlui/bitstream/handle/1866/32085/Hui_David_Yu-Tung_2022_memoire.pdf?sequence=2) showed that using LayerNorm in the critic network theoretically prevented divergence when minimizing the mean-squared semi-gradient loss, enabling the resultant algorithm to learn high-dimensional continuous control tasks such as dog-run in DeepMind Control.
2. [Double Gumbel Q-Learning, (Spotlight @NeurIPS 2023)](https://openreview.net/forum?id=UdaTyy0BNB) introduced a heteroscedastic semi-gradient loss with tunable pessimism as a more principled replacement for the mean-squared semi-gradient loss, yielding an algorithm named DoubleGum that attained up to 2x performance of SAC at 1M training timesteps.

I'm currently looking for opportunities where I can continue my research.
For more information about me, please see:

[Google Scholar](https://scholar.google.com/citations?user=pXHOdMwAAAAJ&hl=en)

[Short CV](https://dyth.github.io/CV_DavidYu_TungHui.pdf)
