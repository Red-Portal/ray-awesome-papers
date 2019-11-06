# Ray Kim's Awesome Papers
The papers that made me stay awake all night long.
Let me know if you have anything interesting to share!

## Interests
* High-Performance Computing
* Probabilistic Machine Learning
* Bayesian Statistics
* Numerical Analysis
* Computational Linear Algebra
* Heterogeneous, Specialized Hardware
* Programming Language Theory
* Computer Vision
* Image Processing

## Awesome Papers
* Blei, David M., Andrew Y. Ng, and Michael I. Jordan. [**"Latent dirichlet allocation."**](http://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf) Journal of machine Learning research 3.Jan (2003): 993-1022.
    * *A beautifully simple and powerful example of applying probabilistic graphical modeling and variational inference. One of my favorite. This paper completely sold me on probabilistic machine learning.*
    
* Neal, Radford M. [**"Bayesian learning for neural networks."**](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.446.9306&rep=rep1&type=pdf) Vol. 118. Springer Science & Business Media, 2012.
    * *Haven't read it all yet, but already one of my favorite. Neal reviews and constructs a Bayesian perspective of neural networks and performs Bayesian inference.*

* Chaney, Allison, et al. [**"Detecting and characterizing events."**](http://dirichlet.net/pdf/chaney16detecting.pdf) Proceedings of the 2016 Conference on Empirical Methods in Natural Language Processing. 2016.
    * *An application of topic modelling and probabilistic graphical models for historians. We can see that probabilistic graphical models can be effectively used in a wide range of domains.*

* Regier, Jeffrey, et al. [**"Approximate Inference for Constructing Astronomical Catalogs from Images."**](https://arxiv.org/abs/1803.00113) arXiv preprint arXiv:1803.00113 (2018).
    * [Juliacon 2017 Talk](https://juliacomputing.com/case-studies/celeste.html)
    * *An example of applying probabilistic graphical modelling for extremely complex inference problems with variables interacting with each other in complicated ways. Also, the model is unsupervised.*
    
* Shanbhag, Naresh R., et al. [**"Shannon-inspired statistical computing for the nanoscale era."**](https://ieeexplore.ieee.org/document/8482253) Proceedings of the IEEE 107.1 (2019): 90-107.
    * [Stanford Seminar](https://www.youtube.com/watch?v=zwzYNura0Ps)
    * *Shannon communication theory can sometimes be applied in very unexpected places. This paper discusses applying communication theory to circuits with indeterministic, probabilistic transmissions.*
    
* Ungar, David, and Sam S. Adams. [**"Harnessing emergence for manycore programming: early experience integrating ensembles, adverbs, and object-based inheritance."**](https://dl.acm.org/citation.cfm?id=1869546) Proceedings of the ACM international conference companion on Object oriented programming systems languages and applications companion. ACM, 2010.
    * [STI Conference Presentation](https://youtu.be/GBtqQwcJoN0)
    
* Thompson, Neil, and Svenja Spanuth. [**"The Decline of Computers As a General Purpose Technology: Why Deep Learning and the End of Moore’s Law are Fragmenting Computing."**](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3287769) Available at SSRN 3287769 (2018).
    * *A summary of the specialized, heterogeneous computing paradigm.*
    
* Hammernik, Kerstin, et al. [**"Learning a variational network for reconstruction of accelerated MRI data."**](https://arxiv.org/abs/1704.00447) Magnetic resonance in medicine 79.6 (2018): 3055-3071.
    * Previous works
        * Chen, Yunjin, Wei Yu, and Thomas Pock. [**"On learning optimized reaction-diffusion processes for effective image restoration."**](https://arxiv.org/abs/1503.05768) Proceedings of the IEEE conference on computer vision and pattern recognition. 2015.
    * *An example where neural networks can integrate tightly with domain-specific theory. In this paper the authors combine compressed sensing, a popular method used in MRI image reconstruction, with a neural network-ish method called reaction-diffusion.*
    
* Fuchs, Adi, and David Wentzlaff. [**"The Accelerator Wall: Limits of Chip Specialization."**](http://parallel.princeton.edu/papers/wall-hpca19.pdf) 2019 IEEE International Symposium on High-Performance Computer Architecture (HPCA). IEEE, 2019.

* Ulyanov, Dmitry, Andrea Vedaldi, and Victor Lempitsky. [**"Deep image prior."**](https://arxiv.org/abs/1711.10925) Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2018. 
    * *Deep image prior (DIP) is one of the recently discovered mysteries in convolutional neural networks (CNN). The paper shows that CNNs inherently have a structural bias towards 'natural images'. However, it only briefly discusses the discovery and provides limited theoretical insight (which makes the DIP an open problem).*
    * Follow-up works
        * Zezhou Cheng, Matheus Gadelha, Subhransu Maji, Daniel Sheldon. [**"A Bayesian Perspective on the Deep Image Prior"**](https://arxiv.org/abs/1904.07457). Proceedings of the 2019 Conference on Computer Vision and Pattern Recognition (CVPR'19).
        
* Licht, Johannes de Fine, Simon Meierhans, and Torsten Hoefler. [**"Transformations of High-Level Synthesis Codes for High-Performance Computing."**](https://arxiv.org/abs/1805.08288) arXiv preprint arXiv:1805.08288 (2018).

* Kendall, Alex, and Yarin Gal. [**"What uncertainties do we need in bayesian deep learning for computer vision?."**](https://arxiv.org/abs/1703.04977) Advances in neural information processing systems. 2017.

* Boyd, Stephen, et al. [**"Distributed optimization and statistical learning via the alternating direction method of multipliers."**](http://web.stanford.edu/~boyd/papers/admm_distr_stats.html) Foundations and Trends® in Machine learning 3.1 (2011): 1-122.
    * [Microsoft Research Talk](https://www.youtube.com/watch?v=Xg0ozgCXXB8)
    
* Qiang Liu and Dilin Wang. 2016. [**"Stein variational Gradient descent: a general purpose Bayesian inference algorithm."**](https://dl.acm.org/citation.cfm?id=3157362) In Proceedings of the 30th International Conference on Neural Information Processing Systems (NIPS'16)
    * *A recently developed Variational Inference (VI) method. It combines the flavor of particle filter sequential monte carlo methods with VI.*
    * [Interactive demo](https://chi-feng.github.io/mcmc-demo/app.html). Select *SVGD* for the algorithm.
    * Follow-up works
        * Han, J. & Liu, Q.. (2018). [**"Stein Variational Gradient Descent Without Gradient."**](http://proceedings.mlr.press/v80/han18b.html) Proceedings of the 35th International Conference on Machine Learning, in PMLR 80:1900-1908

    
* Jordan, Michael I. [**"Dynamical, Symplectic and Stochastic Perspectives on Gradient-Based Optimization."**](https://eta.impa.br/dl/PL012.pdf) University of California, Berkeley (2018).
    * [ICM 2018 Talk](https://www.youtube.com/watch?v=wXNWVhE2Dl4)
    * *A review of recent advances in optimization. Recently an unusual differential equation representation of the nesterov acceleration scheme has been found. This paper also discusses this subject.*
    
* Kruskal, Clyde P., and Alan Weiss. [**"Allocating independent subtasks on parallel processors."**](https://ieeexplore.ieee.org/abstract/document/1701915) IEEE Transactions on Software engineering 10 (1985): 1001-1016.
    * Follow-up works
        * Bast, Hannah. [Ph.D. Thesis](http://ad.informatik.uni-freiburg.de/files/phd-thesis-hannah-bast.pdf/view?set_language=en), 2000
        
* Solnik, Benjamin, et al. [**"Bayesian Optimization for a Better Dessert."**](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/46507.pdf) (2017).
    * *Bayesian optimization (BO) can be applied to objective functions that were previously unimagineable to optimize. This is a very interesting example where BO optimizes the 'utility function' of cookie eaters. Human utility is obviously not differentiable and notoriously noisy. Despite these difficulties, BO was able to find an optimal (tasty) cookie recipe*
    
* Dai, Z., Yu, H., Low, B.K.H. & Jaillet, P.. (2019). [**"Bayesian Optimization Meets Bayesian Optimal Stopping"**](http://proceedings.mlr.press/v97/dai19a.html). Proceedings of the 36th International Conference on Machine Learning, in PMLR 97:1496-1506
    * *Bayesian optimal stopping is applied to Bayesian Optimization for Deep Learning hyperparameters tuning. A very simple but powerful solution that has strong theoretical foundations.*

