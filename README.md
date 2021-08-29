This repository is Forked from the original repository at https://github.com/hongliny/FedAc-NeurIPS20
from the paper "[Federated Accelerated Stochastic Gradient Descent](https://arxiv.org/abs/2006.08950)" authored by [Honglin Yuan](https://hongliny.github.io) (Stanford) and [Tengyu Ma](https://ai.stanford.edu/~tengyuma/) (Stanford), published in NeurIPS 2020 (**best paper** in [FL-ICML'20](http://federated-learning.org/fl-icml-2020/) workshop).

  [proceeding](https://papers.nips.cc/paper/2020/hash/39d0a8908fbe6c18039ea8227f827023-Abstract.html)
  | [video (3 min)](https://youtu.be/K28zpAgg3HM)
  | [poster (pdf)](https://hongliny.github.io/files/FedAc_NeurIPS20/FedAc_NeurIPS20_poster.pdf) 

---

Dependencies:

- python 3.7 with the following packages: numpy, matplotlib, scipy, pandas, sklearn
- Datasets `a9a` and `epsilon` can be downloaded from `https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/`. 
  - please place datasets to `libsvm_datasets` directory. Unzip `epsilon`.

Scripts:

- `logistic.py`: main functions
- `analysis_utils.py`: auxiliary functions for analysis

To produce the new results with communication strategy which includes "linearly growing communication intervals", among others, use the jupyter notebook "test.ipynb".

Here we used the same setting as Fig. 1 & 3 of the paper, using $l_2$ regularization factor of $Lambda = 1.0$.

Alternatively, you can plot the figures directly based on our results in Jupyter notebook `browse_figures.ipynb`.
In the legends, the purple line, with label "Linear", is what we added to the results.



