---
layout: page
title: Projects
permalink: /projects/
tags: projects
---

The projects are in reverse chronological order. Some of the lack references, project reports etc, which will be updated in time:
## Ongoing Projects
### Theoretical Computer Science
1. **Optimization using Dynamics** : Analysis of Hamiltonian dynamics for Convex and Non Convex optimization using Markov chains over constraint sets. We analyse the Cheeger constant (under mild assumptions about them) to bound the hitting time of the process with good probability. 

2. **Fast rates of convergence for Convex Optimization** : Investigation into faster rates of convergence for strongly convex or regularized objectives using Langevin Dynamics based algorithms by getting bounds on the restricted Cheeger constant for strongly convex or smooth functions. 

3. **Sparsification Techniques for Fast Flow algorithms** : There has been recent work that uses gives faster algorithms that run in $$ \tilde{\mathcal{O}}(n)$$ time to compute maximum flow in undirected graphs by graph sparsification techniques. The project is aimed at understanding and extending the work to acheive stronger bounds. 

4. **Algorithmic Randomness** : Analysing different notions of randomness for computable infinite binary sequences and differentiating between random sequences that can be generated from different complexity classes. More specifically the project is aimed at presenting a seperation between sequences that are random under polynomial time resource bounds and under polynomial space resource bounds. 

### Machine Learning
1. **Accented Speech Generation** : Using Generative Adversarial networks to generate accented speech which can interface with multi-modal input for use in a wide array of systems. The project is also aimed at generating disentangled representations for Multi modal data that can be further boot-strapped with other systems that learn higher order features.  One of the recent publications in this project is under review at ACL 2018.

### Systems : 
1. **Compiler** : Writing a C++ based compiler for Golang that compiles code for the x86 architecture. 

## Previous Projects :
### Theoretical Computer Science : 
1. **Optimizing MaxSAT** : The project developed parallel programming techniques that tried to convert an instance of the MaxSAT problem to an instance of the Set cover problem, the optimal values being $$ \epsilon $$ close. This algorithm would essentially prove that there exists a $$ NC$$ reduction that converts a problem in $$NP$$ to a problem that is $$NP-Complete$$ that therefore implies a circuit reducation. This circuit reduction is actually much stronger than the Polynomial time
   reduction. 

2. **Inferring Grammars** : A key observation exists that a $$LL(1)$$ grammar can be represented as statements of logic, and therefore any grammar can be inferred from a small number of rules by using first order logic solvers such as the Microsoft $$z3$$. This project aimed at usihng that for building a general system that inferred the grammar of a language from a given example by using first order logic. This therefore bypassed the need for writing grammars, and inferring them from
   examples (if possible). In general this problem lies in $$EXP$$, but we were able to show that this problem lies in $$coNP$$ and therefore used approximately correct solvers that gave us a good enough solution. This is only the case when a $$LL(1)$$ grammar is possible, because in general this is an undecidable problem. 

3. **Game Theory** : Tried out recursive and functional implementations of basic results in Game Theory that prove the existence of Nash Equilibrium, by showing small implementations of some $$PSL$$ hard problems. Functional implementations are much faster since Lambda calculus can give faster implementations of recursively defined computable functions in most cases.  
### Machine Learning:
1. **Post Disaster MicroBlog Retrieval** : Using natural language processing techniques for extracting information from Twitter data and using it for better managing a post disaster situation. The retrieved tweets could be used for manual dissemination of information among other uses. The design team also took up the initiative of creating prototypes for what would be the optimal use for such a tool, and was tested among multiple users who were at some points victims of
   the Chennai floods.
   The results were sumamrized in a paper published at [SIGIR](https://arxiv.org/abs/1707.06112)
2. **Unsupervised Text to Video Generation** : We used Generative Adversarial networks for Text to video generation. It involved developing robust techniques for generating disentangled representations for the style and content of video and learning from those rich distributions to reccurrently generate frames of the video. 
The results are under review at CVPR 2018.

3. **Zero Shot Learning** :  We did Zero shot learning by learning a distribution from the class specific variables to the parameters of the distribtuion that defined the class conditional distribution by using straightfoward linear regression. We tried it in multiple settings including the generalized zero shot setting, and good results. The key problem that hindered us from coming to a conclusion was the need for very high regularization that made the model not very good for
   scale. The code is available at [github](https://github.com/prannayk/zero-shot-learning). 

4. **Autonomous Underwater Vehicle (AUV)** : The project was aimed at developing Image Processing and control algorithms to successfully autonomously enable navigation of robot through a set of pre-defined oracles without much deviation. The key problem was the lack of power inside the bot requiring use of a very small number of resources in terms of compute power, while simultaneously optimizing on the accuracy of the robot motion. While I have left the project long ago it has been taken
   by others and recent acheivements can be seen [here](http://auviitk.com/index.html). 

### Systems:
1. **NachOS**  : Optimized and implemented various parts of the minimal NachOS while learning about the various operating system algorithms and data structures. The project was structured as part of a course project and was aimed at giving basic familiarity with most parts of the Operating System. We optimized memory used down to the minimal page length that could be used and was used in a very efficient manner to enable very fast access with very limited memory. The OS was simulated on a wide
   variety of everyday situations. The code can be seen on the [github page](https://github.com/pkhrag/OS-project)
