---
date: 2024-05-27
title: "Journées annuelles 2024 du GT Bioss"
summary: "Du **27 au 29 mai 2024** à **Paris**"
categories: "Manifestations"
---

Lieu : [Campus Pierre-et-Marie-Curie (Jussieu)](https://sciences.sorbonne-universite.fr/sorbonne-universite-campus-pierre-et-marie-curie), Paris 5e

Les journées annuelles sont un point de rassemblement important pour notre GT. Elles permettent un moment d'échange entre les chercheuses et chercheurs, débutant(e)s et confirmé(e)s, pour discuter sur nos avancées scientifiques récentes et les défis à aborder, à la frontière en informatique, mathématique, et biologie.
Cette année, nous avons décidé de regrouper les évènements du GT Bioss (typiquement une journée annuelle et 1 ou 2 journées thématiques) en une seule période. Ainsi, les journées annuelles seront suivies par deux ateliers thématiques, sur l'évaluation de méthodes d'inférence de modèles, et sur les outils développés autour des modèles logiques.

## Inscription

Les inscriptions sont closes.

## Programme préliminaire

Le programme général se déroulera entre le lundi 27 mai à 10h30 jusqu'au mardi 28 mai à 12h et offrira des exposés invités et contribués.
Deux ateliers d'une demi-journée suivront le mardi 28 après-midi et mercredi 29 mai matin.

Exposés invités confirmés
- [Jakob Ruess](https://www.inria.fr/fr/jakob-ruess) (Inria Saclay)
- [Wolfram Liebermeister](http://genome.jouy.inra.fr/~wliebermeis/index_en.html) (Inrae Jouy-en-Josas)

### Lundi 27 mai
*Salle de séminaire du LIP6 (salle 25-26/105), Campus UPMC Jussieu*

- 10h - 10h30 *Welcome*
- 10h30 - 11h: [Sabine Peres](https://lbbe.univ-lyon1.fr/fr/annuaires-des-membres/peres-sabine) (LBBE, Univ Claude Bernard Lyon 1), *"Constraint-based modeling of metabolic pathways using logic programming"*
- 11h - 11h30: [Maxime Folschette](http://maxime.folschette.name/) (CRIStAL, Centrale Lille), *"Modeling, Analysis and Parameter Inference of a Class of Hybrid Regulatory Networks"*
- 11h30 - 12h30: *contributed talks*:
    - 11h30: Sophia Orozco Ruiz (Institut Curie), *"Logical modeling of Mesenchymal to Epithelial Transition in Cancer Progression"*
    - 11h50: Gautier Stoll (Centre de Recherche des Cordeliers), *"Logical modeling of CART-cells treatment in multiple myeloma"*
    - 12h10: Nadine Ben Boina (I2M), *"Logical Modeling of Dysferlinopathies"*

Buffet 12h30 - 14h

- 14h - 15h: [Jakob Ruess](https://www.inria.fr/fr/jakob-ruess) (Inria Saclay), *"From single cells to microbial consortia and back: stochastic chemical kinetics coupled to population dynamics"*
- 15h - 16h50: *contributed talks*:
    - 15h00: Alexis Poindron (ENSTA Paris), *"The unate compatibility problem"*
    - 15h20: Stefan Haar (INRIA), *"Bridging the discrete-continuous gap: Continuous Petri nets"*
- 15h40 - 16h10: *Break*
    - 16h10: Van-Giang Trinh (LIS, Aix-Marseille University), *"Trap spaces of multi-valued networks: definition, computation, and applications"*
    - 16h30: Mathieu Hemery (Inria Saclay), *"Stabilizing CRN and Algebraic function - a surprising connexion"*

### Mardi 28 mai 9h30 - 12h
*Salle de séminaire du LIP6 (salle 25-26/105), Campus UPMC Jussieu*

- 9h30 - 10h30: [Wolfram Liebermeister](http://genome.jouy.inra.fr/~wliebermeis/index_en.html) (Inrae Jouy-en-Josas), *"Resource allocation in kinetic models of cell metabolism"*
- 10h30 - 11h: *Break*
- 11h - 11h40: *contributed talks*:
    - 11h00: François FAGES (Inria Saclay), *"Local vs global approaches to model learning: algorithms, failures and theorem"*
    - 11h20: Tony Ribeiro (LS2N), *"Learning Dynamics from Partial Observations - Symbolic Modeling of the Unknown"*
- 11h40 - 12h Discussion

### 🎯 Atelier "Évaluation de méthodes d'inférence de modèles" - mardi 28 mai 14h-17h
*Salle 306, IBENS, ENS Paris (46 rue d’Ulm, 75005 Paris)*

Objectifs:
- constituter un/des jeux de benchmarks pour évaluer les méthodes d'inférence de modèles (graphes causaux, modèles dynamiques) développées par des membres du GT
    - différents pré-requis/hypothèses des méthodes: observations à l'état stationnaire ou non, type de données quantitatives (scRNA-Seq-like, ..), séries temporelles
    - quels "ground truth"? (modèles de la littérature, modèles de synthèse, ..)
    - jeux de données avec mutants
- discuter de l'évaluation des modèles inférés vis-à-vis du ground truth:
    - vis-à-vis de la structure: équivalence/proximité avec le ground truth
    - vis-à-vis des prédictions (p. ex sur les mutants): permet de comparer des modèles de nature différente

[Programme dédié](https://codimd.math.cnrs.fr/s/pR4cVqX7d)

### 🛠️ Atelier "CoLoMoTo - Outils pour la modélisation logique" - mercredi 29 9h30-12h30
*Salle 306, IBENS, ENS Paris (46 rue d’Ulm, 75005 Paris)*

Objectifs:
- Faire le point sur les outils développés dans le GT et leur mise à disposition
- Défis méthodologiques pour la modélisation logique (combinaison de modèles, reproducibilité des simulations, ...)
- Faire le point sur l'état et le devenir de la distribution Docker CoLoMoTo

[Programme dédié](https://codimd.math.cnrs.fr/s/EVOoKlvx4)

## Résumés / Abstracts

### Jakob Ruess
*From single cells to microbial consortia and back: stochastic chemical kinetics coupled to population dynamics*

At the single-cell level, biochemical processes are inherently stochastic. Such processes are typically studied using models based on stochastic chemical kinetics, governed by a chemical master equation (CME). The CME describes the time evolution of the probability distribution over system states and has been a tremendously helpful tool in shedding light on the functioning of cellular processes. However, single cells are not living in isolation but are part of a growing population or community. In such contexts, stochasticity at the single-cell scale leads to population heterogeneity and cells may be subject to population processes, such as selection, that drive the population distribution away from the probability distribution of the single-cell process.
Here, I will introduce a multi-scale modeling framework that allows one to capture coupled stochastic single-cell and population processes. I will show that the expected population distribution of such multi-scale models can be calculated by solving a modified version of the CME that is of the same dimensionality as the standard CME. I will then show how such models can be used to explain experimental data on plasmid copy number fluctuations and population growth in media that selects against cells that have lost the plasmid. Finally, I will present an optogenetic recombination system that allows one to partition yeast populations into different cell types via external application of blue light to cells and show how our modeling framework can be used to predict and control emerging dynamics of the population composition in response to time-varying light stimuli.

### Wolfram Liebermeister
*Resource allocation in kinetic models of cell metabolism*

Metabolic fluxes in cells are often assumed to reflect an economical use of enzymes. To apply this principle of "minimal enzyme cost" to metabolic modelling and to study its biological consequences, I consider two types of computational models: models in which the metabolic fluxes are predefined and metabolite concentrations are optimised in order to minimise enzyme cost; and models in which the fluxes are also optimised. In the first case, optimal enzyme and metabolite levels can be computed by solving a convex optimization problem. The formalism highlights the close relationship between enzyme demand and reaction thermodynamics. In the second case, we obtain a nonlinear version of flux balance analysis, a method commonly used in flux prediction. The optimal fluxes can be determined by screening all elementary flux modes, a well-defined set of maximally sparse flux distributions. Altogether, we obtain a tractable method for predicting optimal fluxes, metabolite levels, and enzyme levels in models of central metabolism.


### Sophia Orozco Ruiz
*Logical modeling of Mesenchymal to Epithelial Transition in Cancer Progression*

The ability of carcinoma cells to move along the epithelial mesenchymal spectrum is crucial for metastasis. Even so, the reverse process of Epithelial to Mesenchymal Transition (EMT), Mesenchymal to Epithelial Transition (MET), has not been extensively explored, as the mechanisms capable of triggering it are not clearly defined. Here, we built a literature-based regulatory network that is translated into a logical model as a tool to reproduce and test aspects of EMT and MET. Through stochastic simulations, we provide insight into how external as well as autocrine signals can be interfered with to induce MET. Our model shows that the MET inducers capable of triggering the program are mostly dependent on the mesenchymal cellular context, as they do not act universally.

### Gautier Stoll
*Logical modeling of CART-cells treatment in multiple myeloma*

CAR T cells are T lymphocytes that have been engineered with a “Chimeric Antigen Receptor” for targeting specifically cancer cells. They are constructed from individual patient T lymphocytes and are re-injected as treatment. In multiple myeloma, they represent a new and promising therapy. An important clinical challenge is the understanding and the optimization of such a treatment. For that, a EU project have been created, CERTAINTY - “A cellular immunotherapy virtual twin for personalized cancer treatment”.
For that, we created a mathematical model of CAR T cell action on tumor cell. The model is based on signaling pathways inside T cell and tumor cells, with their interactions. The mathematical approach is logical. We use UPMaBoSS tool, which is suited for time-dependent interactions between heterogeneous cell types, including their respective signaling pathways.
In the context of this EU project, there is a need for integrating data from experiments, but above all from human cohort, which could be limited in size. We will show the different possible strategies. As preliminary results, we will show how we can integrate clinical data of clinical progression.

### Nadine Ben Boina
*Logical Modeling of Dysferlinopathies*

Dysferlinopathies are a group of rare muscle diseases caused by mutations in the dysferlin gene (DYSF). Patients suffer from severe weakness and skeletal muscle atrophy, resulting from impairments in muscle cell membrane repair, regeneration of muscle fibers and inflammatory response. We are currently building a logical model that encapsulates dysferlin-associated cellular processes, in order to get a better understanding of the genotype-phenotype relationship in dysferlinopathies. Ultimately, we aim to use this model to identify optimal therapeutic targets to help manage the symptoms of the diseases. 

In parallel, we have developed a method to identify relevant mutlivalued refinements of Boolean models. Boolean models offer a simplified approach to studying regulatory networks, but their high level of abstraction can miss specific cellular behaviors. Multivalued refinements address this limitation by allowing for more than just two states for some components. We introduce MRBM, a method that helps identify which components in a Boolean model should be represented with multiple states in oder to capture a specific cellular behavior (dynamical property). 

### Alexis Poindron
*The unate compatibility problem in regulatory Boolean networks*

A Boolean function is unate if it is monotone increasing or monotone decreasing, in each of its entries. The aim of this paper is to investigate the existence and construction of a unate function compatible with some imposed observations. The existence problem is found to be NP Complete.  A practical algorithm of inference is exposed and tested in terms of accuracy and computational complexity.

### Stefan Haar
Bridging the discrete-continuous gap: Continuous Petri nets

Discrete models for biological networks have produced a rich theory and efficient analysis algorithms this is true for  
Petri nets (PNs)  and Boolean Networks (BNs), which also allow mutual representations by equivalent translations. 
However, their semantics have been shown to miss state changes that are possible in a continuous representation of the same system;
 this has led to the introduction of  Most Permissive semantics for BNs. In this talk, I will advocate the use of a different  model
 from older literature, Continuous Petri nets (CPNs), that combines the modeling advantages of discrete PNs with a continuous relaxation
 of state evolution, for which reachability and other key properties can be efficiently decided. A survey of some recent results 
(ICATPN 2024) including attractor search with CPNs will be given, along with some first examples where the attractor landscape changes 
drastically under the passage to CPNs.

### Van-Giang Trinh
*Trap spaces of multi-valued networks: definition, computation, and applications*

Boolean Networks (BNs) are simple but efficient mathematical formalism for modelling complex biological systems. However, having only two levels of activation is sometimes not enough to fully capture the dynamics of real-world biological systems. Hence, the need for Multi-Valued Networks (MVNs), a generalization of BNs. Despite the importance of MVNs for modelling biological systems, only limited progress has been made on developing theories, analysis methods, and tools that can support them. In particular, the recent use of trap spaces in BNs made a great impact on the field of systems biology, but there has been no similar concept defined and studied for MVNs to date. In this work, we generalize the concept of trap spaces in BNs to that in MVNs. We then develop the theory and the analysis methods for trap spaces in MVNs. In particular, we implement all proposed methods in a Python package called trapmvn. Not only showing the applicability of our approach via a realistic case study, we also evaluate the time efficiency of the method on a large collection of real-world models. The experimental results confirm the time efficiency, which we believe enables more accurate analysis on larger and more complex multi-valued models.

Reference: Trinh, Van-Giang, Belaid Benhamou, Thomas Henzinger, and Samuel Pastva. "Trap spaces of multi-valued networks: definition, computation, and applications." Bioinformatics 39, no. Supplement_1 (2023): i513-i522. 

### Mathieu Hemery
*Stabilizing CRN and Algebraic function - a surprising connexion*

The Turing completeness of continuous Chemical Reaction Networks (CRNs) states
that any computable real function can be computed by a continuous CRN on a
finite set of molecular species, possibly restricted to elementary reactions,
i.e.~with at most two reactants and mass action law kinetics.  To investigate
pathways like MAPK, we have introduced a more stringent notion of robust online
analog computation called Absolute Functional Robustness (AFR), to refer to
CRNs that stabilize the concentration values of some output species to the
result of one function of the input species concentrations, while allowing
arbitrary perturbations for intermediate and output species throughout the
attraction basin. We prove that the set of real functions stabilized by a CRN
with mass action law kinetics is precisely the set of real algebraic functions.
Based on this result, we develop a compiler which takes as input any algebraic
function (defined by one polynomial and one point for selecting one branch of
the algebraic curve defined by the polynomial) and generates an abstract CRN to
stabilize it.

### François Fages
*Local vs global approaches to model learning: algorithms, failures and theorem*

Learning continuous time dynamical models of interacting agents from observed time series data is a challenge even in absence of latent variables.
In this talk, I compare global approaches such as Sparse Identification of Nonlinear Dynamical systems (SINDy) or neural networks,
to local approaches such as Reactmine which tries to infer some preponderant reactions in the different observed transitions, within a search tree.
We show that the former state-of-the-art methods fail on some very simple single trace synthetic data whereas Reactmine succeeds.
We analyze these failures in terms of the high correlation between the observables along a single trace,
and give sufficient conditions for Zhao’s irrepresentable condition, which ensures the correctness of Lasso regression.
We validate the theoretical analysis by showing that dealing with multiple traces with many zeros in the initial conditions
de-correlates the observables of the first transitions and helps SINDy to infer the correct reactions, outside our learning protocol.

Joint work with mainly Aymane El Gadhari, Julien Martinelli and Jeremy Grignard.

### Tony Ribeiro
*Learning Dynamics from Partial Observations - Symbolic Modeling of the Unknown*

In this presentation, we explore the challenge of learning dynamics from partial observations, where the system's state is only partially observable and some variables may be unknown. We introduce a novel approach that utilizes symbolic modeling to approximate the minimal rules governing the system's behavior, even in the presence of uncertainty. Our method ensures an overapproximation of the original state transitions and derived minimal rules, providing a robust framework for understanding complex systems under incomplete information.
