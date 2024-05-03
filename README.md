I am David Yu-Tung Hui / 許宇同, a 2023 MSc graduate from Mila, University of Montreal.

My research interest is to create algorithms that learn through interacting with the world.
I believe that algorithms that learn in this way will be more scalable than those that learn from static human-curated datasets.
Reinforcement learning (RL) poses the process of learning through interaction as an optimization problem and I'm excited by the potential of combining RL with deep learning algorithms that have been shown to be highly scalable numerical optimizers.

I'm especially interested in designing RL algorithms that stably optimize deep neural networks across a range of settings.
To alleviate instability in RL, I use linear algebra and probability theory to improve the mathematical soundness of loss functions optimized by RL algorithms.
I've written two works toward this goal:
1. [Stabilizing Q-Learning for Continuous Control, (MSc Thesis @University of Montreal)](https://papyrus.bib.umontreal.ca/xmlui/bitstream/handle/1866/32085/Hui_David_Yu-Tung_2022_memoire.pdf?sequence=2) showed that using LayerNorm in the critic network prevented divergence of optimizing for the mean-squared temporal-difference error with semi-gradients, solving high-dimensional continuous control such as dog-run in DeepMind Control.
2. [Double Gumbel Q-Learning, (Spotlight @NeurIPS 2023)](https://openreview.net/forum?id=UdaTyy0BNB) showed that Maximum-Entropy RL has two heteroscedastic Gumbel noise sources.  It introduced a new loss function accounting for these noise sources that improved the aggregate performance of SAC by 2x after 1M training timesteps.

I'm currently looking for opportunities where I can continue my research.

For more information about me, please see:

[Google Scholar](https://scholar.google.com/citations?user=pXHOdMwAAAAJ&hl=en)

[Short CV](https://dyth.github.io/CV_DavidYu_TungHui.pdf)
