---
layout: page
title: Research
order: 2
---

How do cognitive activities arise from interconnecting neurons? What constitute social structure in a group of animals? The emergence of “liveliness” in an interacting biological system is perhaps the most exciting question to a theoretical biophysicist. While the inanimate analogue of this question has been pursued enthusiastically in the field of statistical physics, to build a similar theory in biology has not been possible until the recent development of high-throughput experimental techniques, making now an exciting time to search for statistical physics-like principles in living systems.  

I am a theoretical physicist interested in a broad range of questions in collective behavior in living systems. Through close collaboration with experimentalists, I address these questions with mainly data-driven approaches, developing and applying methods in statistical inference to construct interacting models for living systems directly from empirical observations, while supplementing with more formal analyses. I work on problems in neuroscience and in collective animal behavior, as I believe that as these problems feed into one another, both in terms of the methods and the concepts. Below is a list of topics that I have worked on.

## Current projects:

### Develop new statistical inference method to learn collective dynamics

As a postdoctoral researcher at ENS working with Aleksandra Walczak and Thierry Mora, I have developed new methods to infer dynamical models from data, and am applying these methods to study the emergence of collective dynamics and information transfer in various biological systems.
By adding hidden variables and integrating their state out, we are able to write down a dynamical model, which uses the exact parameters learned from the synchronous activity, together with any arbitrary memory kernel which one can learn separately from the dynamics. This model is able to capture both the memory of each component for its past state, as well as causal relation with the others. The method is also very versatile in terms of it works for both continuous vs. discrete systems, and we expect it to solve the problem of learning models for out-of-equilibrium biological systems. As part of this ongoing project, I plan apply this method to various examples of datasets exhibiting collective dynamics, such as collective social dynamics among groups of mice and cortical neuron data.

### Infering social interaction in groups of mice 

As a case study, we are applying the above method to analyze the collective dynamics for social interaction in groups of mice. Collaborating with experimentalists in the group of Ewelina Knapska in Nencki Institute in Poland, we analyze co-localization patterns for groups of mice, placed in well-controlled and ecologically-relevant experimental environment.  Mice is known to be a good model for social interaction, and also can be tuned genetically. In the long run, we want to first develop methods for dissecting what comes from the interaction, and what comes from innate dynamics. Then we want to compare across different strains of the mice to understand more on the biology. Finally, we also want to understand the effect of information transfer on adaptation.

Currently we are in the first step, inferring model from data. The data shows features of collectiveness, but also a striking power-law like decay of correlation, which we are able to produce with our dynamical model. We show that both interaction with peers and the memory of individual animals are essential in reproducing the observed patterns. Our next step will be comparing the inferred parameters for mice before and after treatment with social-impairing drugs, and testing our model by analyzing data where the mice are perturbed by introduction of novel odors. We will also examine how information transfer among mice facilitates the collective adaptation to a new environment.


## Past projects:

### Collective dynamics and information transfer in groups of neurons in zebrafish 

In neuronal systems, the dynamics for a group of interconnected neurons arises from the combination of common stimuli, synaptic connections among neurons, and feedback from the environment. How to separate out each component and understand how information transfers through the neurons from stimulus to behavior? Collaborating with Claire Wyart’s group in Institut du Cerveau, we are analyzing neuronal activities in zebrafish embryo, where the zebrafish is stimulated by light patterns and invokes tail beating. We will use ideas such as Granger causality to understand the information flow. 

### Inferring maximum entropy models for interacting neurons in C. elegans

In my PhD work with experimental collaborators Francesco Randi, Andrew Leifer, and my PhD advisor William Bialek, we successfully extend these statistical inference methods to a very different nervous systems, the brain of the nematode, C. elegans. The compact nervous system of C. elegans comprises only 302 neurons, and instead of firing action potentials, these neurons generate graded electrical response. In this project, our experimental collaborators in the Leifer group recorded simultaneous activities in 50+ neurons in immobilized C. elegans, and I analyzed the data by building the maximum entropy model that matches the mean activity and pairwise correlations among these neurons. To capture the graded nature of the cells' responses, I used information theory-guided criteria to assign each cell multiple states. These models, which are equivalent to a family of Potts glasses, successfully predict higher statistical structure in the network. The adjacency matrix from these inferred models is found to be topologically similar to the known anatomical connection between neurons. 

Moreover, from these inferred statistical models, we found signatures of collective behavior in these inferred models, such as the state of single cells can be predicted from the state of the rest of the network; the distribution over network states has multiple local maxima, as in models of memory; and the parameters that describe the real network are close to a critical surface in this family of models. The model also predicts that the brain is robust when single neurons are damaged, but change of single neuron activity can quickly propagate to the entire network; this is among the first experimentally-testable hypotheses of the statistical inference models of neural networks.

### Information geometry analysis for control principles in the worm brain 

Statistical physics models constructed from data can guide our understanding of how the collective states are controlled. In a recent work led by Edward Lee and in collaboration with Bryan Daniels, we examined the information geometry of the above pairwise maximum entropy models, to investigate control principles in the worm brain. By asking how the collective neural statistics – a proxy of worm behavior – would change in response to local perturbations using the Fisher Information Matrix, we found that principal perturbative modes are dominated by a few pivotal neurons, suggesting a sparse control mechanism. We also propose that these pivotal neurons are the key neurons to perturb in optogenetic experiments, providing a guidance for future experiments.

### Theoretical exploration on emergent long time scales without fine-tuning

One example of collective behavior in living systems is individual components with short time scales (e.g. neurons with time scale on the order of milliseconds) interact to give long time scales (e.g. persistent neural activities lasting for seconds). What is the mechanism for the emergence of such long time scales? A well-accepted hypothesis is that these persistent neural activities arise from neurons interacting with each other. For example, if the dynamics of interconnected neurons give a line attractor, one can in principle achieve infinitely long time scales. ,However, this simple explanation requires fine-tuning of its parameters. Are there other more general methods to generate sufficiently long time scales? 

In a theoretical work with Willaim Bialek, we examined the tuning condition for the connection matrix among neurons such that the resulting dynamics exhibit long time scales. Starting from the simplest case of random symmetric connections, we combined maximum entropy and random matrix theory methods to explore the constraints required from long time scales to become generic. We argued that a single long time scale can emerge generically from realistic constraints on the overall neuronal activity, but a full spectrum of slow modes requires more fine-tuning. In addition, we also identified the Langevin dynamics that will generate patterns of synaptic connections drawn from these ensembles to be some familiar dynamics in neural systems, such as Hebbian learning and activity-dependent synaptic scaling.

