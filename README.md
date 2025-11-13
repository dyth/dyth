### David Yu-Tung Hui 許宇同

I am currently unemployed.
I used to be an AI researcher in deep reinforcement learning.
I wrote two works improving the optimization stability of off-policy gradient-based Q-learning algorithms.

1. **Stabilizing Q-Learning for Continuous Control**  
David Yu-Tung Hui  
MSc Thesis, University of Montreal, 2022  
I described two principles for creating stable deep learning algorithms and applied the principles to deep reinforcement learning.
The principles were 1) maximum entropy, from which many deep learning loss functions are derived and 2) the neural tangent kernel, which provides a convergence analysis justifying the use of normalization layers and the ReLU activation function.
In RL, I used maximum entropy to justify the design of a Q-learning family of algorithms and showed that LayerNorm reduced divergence of these algorithms, especially in high-dimensional continuous control problems.  
[[.pdf]](https://papyrus.bib.umontreal.ca/xmlui/bitstream/handle/1866/32085/Hui_David_Yu-Tung_2022_memoire.pdf)
[[Errata]](https://gist.github.com/dyth/0324b7a4c2ca4b0f3bab18583b5dc22b)

3. **Double Gumbel Q-Learning**  
David Yu-Tung Hui, Aaron Courville, Pierre-Luc Bacon  
Spotlight at NeurIPS 2023  
We showed that using deep neural networks in Q-learning introduces two heteroscedastic Gumbel noise sources.
An algorithm modeling these noise sources attained just under 2 times the aggregate asymptotic performance of the popular SAC baseline.  
[[.pdf]](https://proceedings.neurips.cc/paper_files/paper/2023/file/07956d40074d6523bad11112b3225c6e-Paper-Conference.pdf)
[[Reviews]](https://openreview.net/forum?id=UdaTyy0BNB)
[[Poster (.png)]](https://nips.cc/media/PosterPDFs/NeurIPS%202023/71497.png)
[[5-min talk]](https://slideslive.com/39009623/double-gumbel-qlearning)
[[1-hour seminar]](https://www.youtube.com/watch?v=GMNtHLA3bAE)
[[Code (GitHub)]](https://github.com/dyth/doublegum)
[[Errata]](https://gist.github.com/dyth/0abd5c5b87184144854a431437de7d44)

The best way to contact me is email.
My email address is listed in one of my written works.
