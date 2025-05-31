### David Yu-Tung Hui, 許宇同

I am interested in Deep Reinforcement Learning and its application in continuous-control tasks.
My research focused on improving the optimization stability of off-policy gradient-based $Q$-learning algorithms over a range of tasks and hyperparameters.

I've written two works along this research direction:

1. **Stabilizing Q-Learning for Continuous Control**  
David Yu-Tung Hui  
MSc Thesis, University of Montreal, 2022  
There are two topics in this thesis.
First, I investigated the duality between maximizing entropy and maximizing likelihood in RL.
Then, I showed that LayerNorm reduced divergence in $Q$-learning for high-dimensional continuous control.  
[[.pdf]](https://papyrus.bib.umontreal.ca/xmlui/bitstream/handle/1866/32085/Hui_David_Yu-Tung_2022_memoire.pdf)
[[Errata]](https://gist.github.com/dyth/0324b7a4c2ca4b0f3bab18583b5dc22b)

3. **Double Gumbel Q-Learning**  
David Yu-Tung Hui, Aaron Courville, Pierre-Luc Bacon  
Spotlight at NeurIPS 2023  
We showed that using function approximation in $Q$-learning introduced two heteroscedastic Gumbel noise sources.
Modeling these noise sources improved by up to $2\times$ the aggregate performance of a $Q$-learning algorithm at 1M timesteps over 33 continuous control tasks.  
[[.pdf]](https://proceedings.neurips.cc/paper_files/paper/2023/file/07956d40074d6523bad11112b3225c6e-Paper-Conference.pdf)
[[Reviews]](https://openreview.net/forum?id=UdaTyy0BNB)
[[Poster (.png)]](https://nips.cc/media/PosterPDFs/NeurIPS%202023/71497.png)
[[5-min talk]](https://slideslive.com/39009623/double-gumbel-qlearning)
[[1-hour seminar]](https://www.youtube.com/watch?v=GMNtHLA3bAE)
[[Code (GitHub)]](https://github.com/dyth/doublegum)
[[Errata]](https://gist.github.com/dyth/0abd5c5b87184144854a431437de7d44)


See my [Google Scholar](https://scholar.google.com/citations?user=pXHOdMwAAAAJ&hl=en) for more of my research.
