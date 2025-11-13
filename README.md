### David Yu-Tung Hui 許宇同

I am currently unemployed.
I used to be an AI researcher in deep reinforcement learning.
I wrote two works improving the optimization stability of off-policy gradient-based Q-learning algorithms.

1. **Stabilizing Q-Learning for Continuous Control**  
David Yu-Tung Hui  
MSc Thesis, University of Montreal, 2022  
I described two principles for creating stable deep learning algorithms and applied the principles to create deep reinforcement learning algorithms.
I first showed that many deep learning loss functions satisfy the principle of maximum entropy and also showed that normalization layers and activation functions allowed convergence of deep learning algorithms via the neural tangent kernel.
I then used the principle of maximum entropy to justify the design of a Q-learning family of algorithms and showed that LayerNorm reduced divergence of these algorithms, especially when applied to high-dimensional continuous control.  
[[.pdf]](https://papyrus.bib.umontreal.ca/xmlui/bitstream/handle/1866/32085/Hui_David_Yu-Tung_2022_memoire.pdf)
[[Errata]](https://gist.github.com/dyth/0324b7a4c2ca4b0f3bab18583b5dc22b)

3. **Double Gumbel Q-Learning**  
David Yu-Tung Hui, Aaron Courville, Pierre-Luc Bacon  
Spotlight at NeurIPS 2023  
We showed that function approximation in Q-learning introduced two heteroscedastic Gumbel noise sources that are not modeled by previous algorithms.
An algorithm modeling these noise sources attained just under 2 times the performance of the popular SAC baseline aggregated over 33 continuous control tasks after 1M interactions.  
[[.pdf]](https://proceedings.neurips.cc/paper_files/paper/2023/file/07956d40074d6523bad11112b3225c6e-Paper-Conference.pdf)
[[Reviews]](https://openreview.net/forum?id=UdaTyy0BNB)
[[Poster (.png)]](https://nips.cc/media/PosterPDFs/NeurIPS%202023/71497.png)
[[5-min talk]](https://slideslive.com/39009623/double-gumbel-qlearning)
[[1-hour seminar]](https://www.youtube.com/watch?v=GMNtHLA3bAE)
[[Code (GitHub)]](https://github.com/dyth/doublegum)
[[Errata]](https://gist.github.com/dyth/0abd5c5b87184144854a431437de7d44)

The best way to contact me is email.
My email address is listed in one of my written works.
