### David Yu-Tung Hui, 許宇同

I am an independent researcher interested in Deep Reinforcement Learning (RL).
My research goal is to make RL algorithms more scalable by improving their optimization stability using principled methods from probability theory and analysis.
I'm especially curious about how to design gradient-based optimization algorithms that enable neural networks to learn Q-functions.

I've written two works along this research direction:
1. **Stabilizing Q-Learning for Continuous Control (MSc Thesis, University of Montreal, 2022)** [[.pdf]](https://papyrus.bib.umontreal.ca/xmlui/bitstream/handle/1866/32085/Hui_David_Yu-Tung_2022_memoire.pdf)
presented empirical evidence that using LayerNorm in off-policy $Q$-Learning prevented divergence of the $Q$-function during training in MuJoCo and DeepMind Control environments.
Using LayerNorm in DDPG enabled learning in the dog-run task of DeepMind Control.

3. **Double Gumbel Q-Learning (David Yu-Tung Hui, Aaron Courville, Pierre-Luc Bacon, NeurIPS 2023 Spotlight)** [[.pdf]](https://proceedings.neurips.cc/paper_files/paper/2023/file/07956d40074d6523bad11112b3225c6e-Paper-Conference.pdf) [[reviews]](https://openreview.net/forum?id=UdaTyy0BNB) [[5 min talk]](https://slideslive.com/39009623/double-gumbel-qlearning) [[1-hour seminar]](https://www.youtube.com/watch?v=GMNtHLA3bAE)
showed that off-policy $Q$-learning algorithms have two heteroscedastic Gumbel noise sources.
Accounting for these noise sources improved the aggregate performance of SAC by 2x at 1M training timesteps.

In 2023, I graduated with an MSc from Mila, University of Montreal.
I'm looking for opportunities where I can continue my research.

For more information about me, see my [Google Scholar](https://scholar.google.com/citations?user=pXHOdMwAAAAJ&hl=en)
