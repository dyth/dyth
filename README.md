### David Yu-Tung Hui, 許宇同

I am an independent researcher interested in Deep Reinforcement Learning.
My research focuses on increasing the optimization stability of off-policy gradient-based $Q$-learning algorithms over a range of tasks and hyperparameters.
I'm especially interested in developing algorithms to solve continuous control tasks.

I've written two works along this research direction:

1. **Stabilizing Q-Learning for Continuous Control**  
David Yu-Tung Hui  
MSc Thesis, University of Montreal, 2022  
I showed that using LayerNorm in the critic of DDPG prevented divergence during training in MuJoCo and DeepMind Control continuous control environments, enabling non-trivial behaviors to be learned in the dog-run task of DeepMind Control.  
[[.pdf]](https://papyrus.bib.umontreal.ca/xmlui/bitstream/handle/1866/32085/Hui_David_Yu-Tung_2022_memoire.pdf)
[[Errata]](https://gist.github.com/dyth/0324b7a4c2ca4b0f3bab18583b5dc22b)

3. **Double Gumbel Q-Learning**  
David Yu-Tung Hui, Aaron Courville, Pierre-Luc Bacon  
Spotlight at NeurIPS 2023  
We modeled noise introduced by a function approximator in $Q$-learning as a heteroscedastic Gumbel distribution and derived a loss function from this noise model that was effective in off-policy continuous control -- our resultant algorithm achieved ~2x the aggregate performance of SAC after 1M training timesteps.  
[[.pdf]](https://proceedings.neurips.cc/paper_files/paper/2023/file/07956d40074d6523bad11112b3225c6e-Paper-Conference.pdf)
[[Reviews]](https://openreview.net/forum?id=UdaTyy0BNB)
[[Poster (.png)]](https://nips.cc/media/PosterPDFs/NeurIPS%202023/71497.png)
[[5-min talk]](https://slideslive.com/39009623/double-gumbel-qlearning)
[[1-hour seminar]](https://www.youtube.com/watch?v=GMNtHLA3bAE)
[[Code (GitHub)]](https://github.com/dyth/doublegum)
[[Errata]](https://gist.github.com/dyth/0abd5c5b87184144854a431437de7d44)

In 2023, I graduated with an MSc from Mila, University of Montreal.
I'm looking for opportunities where I can continue my research.

For more information about me, see my [Google Scholar](https://scholar.google.com/citations?user=pXHOdMwAAAAJ&hl=en).
