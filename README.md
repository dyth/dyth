I graduated from Mila, University of Montreal in 2023 with an MSc in deep reinforcement learning.

[Google Scholar](https://scholar.google.com/citations?user=pXHOdMwAAAAJ&hl=en)

[Short CV](https://dyth.github.io/CV_DavidYu_TungHui.pdf)


I want to create algorithms that learn through interacting with the world.
I believe that these algorithms will be more scalable than those that learn from fixed, human-curated datasets about our world.

I like how deep reinforcement learning (RL) frames the problem of learning through interaction.
However, I think that current RL algorithms are too unstable to train and too sensitive to hyperparameters to be of any practical use.
I believe that deriving a theoretically sound loss function for RL can mitigate these issues.

To achieve this, I have
1. Analyzed the unstable training dynamics induced by optimizing the mean-squared semi-gradient loss and proposed using LayerNorm in the network architecture as a fix ([my MSc thesis](https://papyrus.bib.umontreal.ca/xmlui/bitstream/handle/1866/32085/Hui_David_Yu-Tung_2022_memoire.pdf?sequence=2)).
2. Proposed a heteroscedastic semi-gradient loss with tunable pessimism as a more performant replacement for the mean-squared semi-gradient loss ([Double Gumbel Q-Learning, NeurIPS 2023 Spotlight](https://openreview.net/forum?id=UdaTyy0BNB)).
