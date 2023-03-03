# boolean2pew


This repository includes the modified [__booleannet__](https://github.com/ialbert/booleannet) code with the Jupyter notebooks containing the code to reproduce the results of our paper titled: __Probabilistic Edge Weights Fine-Tune Boolean Network Dynamics__, published at PLoS Computational Biology at https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1010536.

The core of this code is a modified version of the _booleannet_ library, with the option of added probabilistic edge-weight (PEW) operators.
https://github.com/ialbert/booleannet

# Probabilistic Edge Weights fine-tune Boolean network dynamics

### Abstract

Biological systems are noisy by nature. This aspect is reflected in our experimental measurements and should be reflected in the models we build to better understand these systems. Noise can be especially consequential when trying to interpret specific regulatory interactions, i.e. regulatory network edges. In this paper, we propose a method to explicitly encode edge-noise in Boolean dynamical systems by probabilistic edge-weight (PEW) operators. PEW operators have two important features: first, they introduce a form of edge-weight into Boolean models through the noise, second, the noise is dependent on the dynamical state of the system, which enables more biologically meaningful modeling choices. Moreover, we offer a simple-to-use implementation in the already well-established BooleanNet framework. In two application cases, we show how the introduction of just a few PEW operators in Boolean models can fine-tune the emergent dynamics and increase the accuracy of qualitative predictions. This includes fine-tuning interactions which cause non-biological behaviors when switching between asynchronous and synchronous update schemes in dynamical simulations. Moreover, PEW operators also open the way to encode more exotic cellular dynamics, such as cellular learning, and to implementing edge-weights for regulatory networks inferred from omics data.

# Jupyter Notebooks:
* __Applications.ipynb__ -- contains the code to reproduce the simulations on empirical models, discussed in the Applications section of the paper
* __Murrugarra_et_al_2012_paper_results.ipynb__ and __Poret_et_al_paper_results-Boolean_init.ipynb__ --. code to reproduce some of the other noisy models within the PEW framework
* __Application Note__ Three more applications, where the PEW operators offer a relatively straightforward way to encode complex edge modulation, as well as examples for the usage of the general PEW operators, where the noise function is specified as well

# How to run?

Clone or download the repository on your machine and run notebooks in their local folder. The notebooks also serve as tutorials on how to apply the PEW freamwork for your own models. 


__If you have questions regarding the code please do not hesitate to contact me through the GitHub platform of at david.deritei@channing.harvard.edu [David]__
