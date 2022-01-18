# boolean2pew

__this README is not complete. I am updating it soon with further details [David]__

The core of this code is a modified version of the booleannet library, with the option of added probabikistic edge-weight (PEW) operators.
https://github.com/ialbert/booleannet

# Probabilistic Edge Weights fine-tune Boolean network dynamics

Biological systems are noisy by nature. This aspect is reflected both in our experimental measurements and should be reflected in the models we build to better understand these systems. The noise can be especially consequential when trying to interpret specific regulatory interactions, i.e. regulatory network edges. In this paper, we propose a method to explicitly encode edge-noise in Boolean dynamical systems by probabilistic edge-weight (PEW) operators. PEW operators have two important features: first, they introduce a form of edge-weight into Boolean models through the noise, second, the noise is dependent on the dynamical state of the system, which enables more biologically meaningful modeling choices. Moreover, we offer a simple-to-use implementation in the already well-established BooleanNet framework. In two application cases, we show how the introduction of just a few PEW operators in Boolean models can fine-tune the emergent dynamics and increase the accuracy of qualitative predictions. This includes fine-tuning interactions which cause non-biological behaviors when switching between asynchronous and synchronous update schemes in dynamical simulations. Moreover, PEW operators also open the way to encode more exotic cellular dynamics such as cellular learning and to implement edge-weights for regulatory networks inferred from omics data. 
