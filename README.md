### David Yu-Tung Hui (許宇同)<sup>*</sup>

I am currently unemployed.
I used to research a subfield of AI called deep reinforcement learning.
I specifically researched methods to improve the optimization stability of off-policy deep Q-learning algorithms.
I wrote two works towards this goal:

1. **Stabilizing Q-Learning for Continuous Control**  
David Yu-Tung Hui  
MSc Thesis, University of Montreal, 2022  
I derived a deep reinforcement learning algorithm from first principles.
I first derived loss functions from the principle of maximum entropy.
I secondly argued that using LayerNorm in the critic improved convergence according to a mathematical analysis inspired by the neural tangent kernel.
Compared to baseline actor-critic algorithms, my algorithm did not diverge in high-dimensional continuous control.  
[[.pdf]](https://papyrus.bib.umontreal.ca/xmlui/bitstream/handle/1866/32085/Hui_David_Yu-Tung_2022_memoire.pdf)
[[Errata]](https://gist.github.com/dyth/0324b7a4c2ca4b0f3bab18583b5dc22b)

2. **Double Gumbel Q-Learning**  
David Yu-Tung Hui, Aaron Courville, Pierre-Luc Bacon  
Spotlight at NeurIPS 2023  
We showed that using function approximation in Q-learning introduces two heteroscedastic Gumbel noise sources.
Accounting for these noise sources almost doubled the performance of the popular SAC baseline.  
[[.pdf]](https://proceedings.neurips.cc/paper_files/paper/2023/file/07956d40074d6523bad11112b3225c6e-Paper-Conference.pdf)
[[Reviews]](https://openreview.net/forum?id=UdaTyy0BNB)
[[Poster (.png)]](https://nips.cc/media/PosterPDFs/NeurIPS%202023/71497.png)
[[5-min talk]](https://slideslive.com/39009623/double-gumbel-qlearning)
[[1-hour seminar]](https://www.youtube.com/watch?v=GMNtHLA3bAE)
[[Code (GitHub)]](https://github.com/dyth/doublegum)
[[Errata]](https://gist.github.com/dyth/0abd5c5b87184144854a431437de7d44)

[Google Scholar](https://scholar.google.com/citations?user=pXHOdMwAAAAJ&hl=en) lists my complete research works.

The best way to contact me is email.
You can find my email address in my works.

<sup>*</sup> There are multiple ways to write my name.
In Latin script, my surname is "Hui" and my firstname is "David Yu-Tung."
In Traditional Chinese characters, my family name is "許" and my given name is "宇同."
Most people call me "David."
Others call me "宇同" or "Yu-Tung."
