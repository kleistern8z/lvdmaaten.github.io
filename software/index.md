---
layout: page
title: Software
excerpt: "Software"
image:
  feature: sample-image-3.jpg
---

<section id="table-of-contents" class="toc">
  <header>
    <h3>Overview</h3>
  </header>
<div id="drawer" markdown="1">
*  Auto generated table of contents
{:toc}
</div>
</section><!-- /#table-of-contents -->

This page gives an overview of all the software I have released as open-source or have substantially contributed to over the years. Unless stated otherwise, the software on this webpage is free and open source software, distributed under the [FreeBSD License](http://en.wikipedia.org/wiki/BSD_licenses).

---

## t-SNE

My [t-SNE software](../tsne/) is available in a wide variety of programming languages [here](../tsne/). The code corresponds to the following papers:

* L.J.P. van der Maaten. **Accelerating t-SNE using Tree-Based Algorithms**. _Journal of Machine Learning Research_ 15(Oct):3221-3245, 2014. <i class="fa fa-file-pdf-o"></i> [PDF](../publications/papers/JMLR_2014.pdf) <small>[[Supplemental material](../publications/misc/Supplement_JMLR_2014.pdf)]</small>
* L.J.P. van der Maaten and G.E. Hinton. **Visualizing Non-Metric Similarities in Multiple Maps**. _Machine Learning_ 87(1):33-55, 2012. <i class="fa fa-file-pdf-o"></i> [PDF](../publications/papers/MachLearn_2012.pdf)
* L.J.P. van der Maaten. **Learning a Parametric Embedding by Preserving Local Structure**. In _Proceedings of the Twelfth International Conference on Artificial Intelligence & Statistics (AI-STATS), JMLR W&CP_ 5:384-391, 2009. <i class="fa fa-file-pdf-o"></i> [PDF](../publications/papers/AISTATS_2009.pdf)
* L.J.P. van der Maaten and G.E. Hinton. **Visualizing High-Dimensional Data Using t-SNE**. _Journal of Machine Learning Research_ 9(Nov):2579-2605, 2008. <i class="fa fa-file-pdf-o"></i> [PDF](../publications/papers/JMLR_2008.pdf) <small>[[Supplemental material](../publications/misc/Supplement_JMLR_2008.pdf)] [[Talk](https://www.youtube.com/watch?v=RJVL80Gg3lA&list=UUtXKDgv1AVoG88PLl8nGXmw)]</small>


---

## CrypTen

CrypTen is a research tool for secure machine learning in PyTorch. CrypTen is developed by Brian Knott, Awni Hannun, Shobha Venkataraman, Mark Ibrahim, Xing Zhou, Shubho Sengupta, and me. [CrypTen has its own website.](https://crypten.ai/)

---

## PHYRE

PHYRE is a benchmark for physical reasoning that contains a set of simple classical mechanics puzzles in a 2D environment. The benchmark is designed to encourage development of sample-efficient learning algorithms that generalize well across puzzles. PHYRE was developed by Anton Bakhtin, Justin Johnson, Laura Gustafson, Ross Girshick, and me. [PHYRE has its own website.](https://phyre.ai/)

---

## Classy Vision

Classy Vision is a framework for image and video classification in PyTorch with a modular API that makes computer-vision research easy, and with excellent support for large distributed training jobs. Classy Vision is developed by Aaron Adcock, Vinicius Reis, Mannat Singh, Zhicheng Yan, Kai Zhang, Simran Motwani, Jon Guerin, Naman Goyal, Ishan Misra, Laura Gustafson, Changhan Wang, Priya Goyal, and me. [Classy Vision has its own website.](https://classyvision.ai/)

---

## Visdom

Visdom is a visualization tool for (Py)Torch and Numpy that allows the user
to generate visualization from processes that run remotely on your workstation.
It was developed by [Allan Jabri](https://ajabri.github.io/), [Jack Urbanek](https://github.com/JackUrb), and me. The project is available [on Github](https://github.com/facebookresearch/visdom).

---

## Torchnet

[Torchnet](http://www.github.com/torchnet/torchnet) is a framework for [Torch 7](http://torch.ch) which provides a set of abstractions aiming at encouraging code re-use as well as encouraging modular programming. Torchnet was developed by Ronan Collobert, Laurens van der Maaten, and Armand Joulin. See [this paper](../publications/papers/Torchnet_2016.pdf) for more information.

---

## Dimensionality reduction

The [Matlab Toolbox for Dimensionality Reduction](../drtoolbox/) is available [here](../drtoolbox/). It contains Matlab implementations of a lot of techniques for dimensionality reduction, intrinsic dimensionality estimators, and additional techniques for data generation, out-of-sample extension, and prewhitening. The download is available [here](../drtoolbox/). The code corresponds to the following paper:

* L.J.P. van der Maaten, E.O. Postma, and H.J. van den Herik. **Dimensionality Reduction: A Comparative Review**. Tilburg University Technical Report, TiCC-TR 2009-005, 2009. <i class="fa fa-file-pdf-o"></i> [PDF](../publications/papers/TR_Dimensionality_Reduction_Review_2009.pdf)

Please note I am no longer maintaining this toolbox.

---

## Divvy

[Divvy](http://divvy.ucsd.edu) is a a tool for exploratory data analysis with unsupervised machine learning. [Divvy](http://divvy.ucsd.edu) was developed by [Joshua Lewis](http://www.cogsci.ucsd.edu/~josh/), me, and [Virginia de Sa](http://www.cogsci.ucsd.edu/~desa/), and is available [here](http://divvy.ucsd.edu). The code corresponds to the following paper:

* J.M. Lewis, V.R. de Sa, and L.J.P. van der Maaten. **Divvy: Fast and Intuitive Exploratory Data Analysis**. _Journal of Machine Learning Research_ 14(Oct):3159-5163, 2013. <i class="fa fa-file-pdf-o"></i> [PDF](../publications/papers/JMLR_2013.pdf)

---

## Metric learning

My [Torch package for metric learning](https://github.com/lvdmaaten/metriclearning) is [available on Github](https://github.com/lvdmaaten/metriclearning).

---

## Model-free tracking
Code for our structure-preserving object tracker is available [here](../software/code/SPOTv1.zip). This code corresponds to the papers:

* L. Zhang and L.J.P. van der Maaten. **Preserving Structure in Model-Free Tracking**. _IEEE Transactions on Pattern Analysis and Machine Intelligence_ 36(4):756-769, 2014. <i class="fa fa-file-pdf-o"></i> [PDF](../publications/papers/TPAMI_2014.pdf)
* L. Zhang, H. Dibeklioglu, and L.J.P. van der Maaten. **Speeding Up Tracking by Ignoring Features**. In _Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR)_, pages 1266-1273, 2014. <i class="fa fa-file-pdf-o"></i> [PDF](../publications/papers/CVPR_2014.pdf)

---

## Marginalized corrupted features
Code for training classifiers with [marginalized corrupted features](https://lvdmaaten.github.io/mcf/Marginalized_Corrupted_Features.html) is available from [a separate page](https://lvdmaaten.github.io/mcf/Marginalized_Corrupted_Features.html). This code corresponds to the following paper:

* L.J.P. van der Maaten, M. Chen, S. Tyree, and K.Q. Weinberger. **Learning with Marginalized Corrupted Features**. In _Proceedings of the International Conference on Machine Learning (ICML), JMLR W&CP_ 28:410-418, 2013. <i class="fa fa-file-pdf-o"></i> [PDF](../publications/papers/ICML_2013.pdf) <small>[[Talk](http://videolectures.net/roks2013_maaten_features/)]</small>

---

## Multiple maps t-SNE
If you want to visualize non-metric similarities such as semantic similarities, you can use [multiple maps t-SNE](https://lvdmaaten.github.io/multiplemaps/Multiple_maps_t-SNE/Multiple_maps_t-SNE.html). Matlab code for multiple maps t-SNE is available [here](https://lvdmaaten.github.io/multiplemaps/Multiple_maps_t-SNE/Multiple_maps_t-SNE.html). This code corresponds to the paper:

* L.J.P. van der Maaten and G.E. Hinton. **Visualizing Non-Metric Similarities in Multiple Maps**. _Machine Learning_ 87(1):33-55, 2012. <i class="fa fa-file-pdf-o"></i> [PDF](../publications/papers/MachLearn_2012.pdf)

An R port of this code (by [Benjamin Radford](https://benradford.github.io/)) is available [here](https://cran.r-project.org/web/packages/mmtsne/index.html).

---

## Structured prediction
My Matlab code for structured prediction using linear CRFs and [hidden-unit CRFs](http://cseweb.ucsd.edu/~lvdmaaten/hucrf/Hidden-Unit_Conditional_Random_Fields.html) is available [here](http://cseweb.ucsd.edu/~lvdmaaten/hucrf/Hidden-Unit_Conditional_Random_Fields.html). This code corresponds to the paper:

* L.J.P. van der Maaten, M. Welling, and L.K. Saul. **Hidden-Unit Conditional Random Fields**. In _Proceedings of the International Conference on Artificial Intelligence & Statistics (AI-STATS), JMLR W&CP_ 15:479-488, 2011. <i class="fa fa-file-pdf-o"></i> [PDF](../publications/papers/AISTATS_2011a.pdf)

---

## Fisher kernel learning
My implementation of Fisher kernels and [Fisher kernel learning](https://lvdmaaten.github.io/fisher/Fisher_Kernel_Learning.html) are available [here](https://lvdmaaten.github.io/fisher/Fisher_Kernel_Learning.html). Fisher kernel learning is described in detail in the following paper:

* L.J.P. van der Maaten. **Learning Discriminative Fisher Kernels**. In _Proceedings of the International Conference on Machine Learning (ICML)_, pages 217-224, 2011. <i class="fa fa-file-pdf-o"></i> [PDF](../publications/papers/ICML_2011.pdf)

---

## Matrix relational embedding
I wrote a simple Matlab implementation of Matrix Relational Embedding, that can be obtained from [here](http://www.cs.utoronto.ca/~ilya/code/2009/matlab_mre.zip). MRE is described in [this paper](http://www.cs.utoronto.ca/~ilya/pubs/2008/mre.pdf) by [Ilya Sutskever](http://www.cs.toronto.edu/~ilya/) and [Geoffrey Hinton](http://www.cs.toronto.edu/~hinton/).

---

## Fields of experts
I wrote a Matlab implementation to train Fields of Experts models, and to use them for image inpainting and denoising. The implementation uses a product of Student-t distribution as clique potentials, and performs the trainin using persistent contrastive divergence. The implementation can be obtained from [here](code/foe.tar.gz) (have a look at the <code>experiment.m</code> function). The model is described in [this paper](http://www.gris.tu-darmstadt.de/~sroth/pubs/foe-ijcv.pdf) by [Stefan Roth](http://www.gris.informatik.tu-darmstadt.de/~sroth/) and [Michael Black](http://ps.is.tuebingen.mpg.de/person/black).

---

## Writer identification
WRIDE is a simple Matlab implementation of a system for automatic WRIter IDEntification. It employs multi-scale edge-hinge features and multi-scale grapheme features. For more information on the system, we refer to this publication:

* L.J.P. van der Maaten and E.O. Postma. **Improving Automatic Writer Identification**. In _Proceedings of the BNAIC_, pages 260-266. Brussels, Belgium, 2005. <i class="fa fa-file-pdf-o"></i> [PDF](../publications/papers/BNAIC_2005.pdf)

The system is available for download [here](code/wride.tar.gz). Make sure to read the <code>Readme.txt</code> before using the system.

<br />
I also created a handwritten characters dataset with over 40,000 labeled character images, which is available [here](../publications/misc/characters.zip) (42 MB).

---

## Questions?

Found a bug or aren't quite sure how something works? Send me an email!

---

## License

Unless specified otherwise, all software on this webpage is free and open source software, distributed under the FreeBSD License.
