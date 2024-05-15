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

- 10h - 10h30 *Welcome coffee*
- 10h30 - 11h: [Sabine Péres](https://lbbe.univ-lyon1.fr/fr/annuaires-des-membres/peres-sabine) (LBBE, Univ Lyon)
- 11h - 11h30: [Maxime Folschette](http://maxime.folschette.name/) (CRIStAL, Centrale Lille), *"Modeling, Analysis and Parameter Inference of a Class of Hybrid Regulatory Networks"*
- 11h30 - 12h30: *contributed talks*:
    - 11h30: Frida Sophia Orozco Ruiz (Institut Curie), *"Boolean model of epithelial mesenchymal plasticity"*
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

- 9h30 - 10h30: [Wolfram Liebermeister](http://genome.jouy.inra.fr/~wliebermeis/index_en.html) (Inrae Jouy-en-Josas)
- 10h30 - 11h: *Break*
- 11h - 11h30: *contributed talks*:
    - 11h00: François FAGES (Inria Saclay), *"Local vs global approaches to model learning: algorithms, failures and theorem"*
    - 11h20: Tony Ribeiro (LS2N), *"Learning Dynamics from Partial Observations - Symbolic Modeling of the Unknown"*
- 11h30 - 12h Discussion

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

### Nadine Ben Boina
*Logical Modeling of Dysferlinopathies*

Dysferlinopathies are a group of rare muscle diseases caused by mutations in the dysferlin gene (DYSF). Patients suffer from severe weakness and skeletal muscle atrophy, resulting from impairments in muscle cell membrane repair, regeneration of muscle fibers and inflammatory response. We are currently building a logical model that encapsulates dysferlin-associated cellular processes, in order to get a better understanding of the genotype-phenotype relationship in dysferlinopathies. Ultimately, we aim to use this model to identify optimal therapeutic targets to help manage the symptoms of the diseases. 

In parallel, we have developed a method to identify relevant mutlivalued refinements of Boolean models. Boolean models offer a simplified approach to studying regulatory networks, but their high level of abstraction can miss specific cellular behaviors. Multivalued refinements address this limitation by allowing for more than just two states for some components. We introduce MRBM, a method that helps identify which components in a Boolean model should be represented with multiple states in oder to capture a specific cellular behavior (dynamical property). 

### Alexis Poindron
*The unate compatibility problem in regulatory Boolean networks*

A Boolean function is unate if it is monotone increasing or monotone decreasing, in each of its entries. The aim of this paper is to investigate the existence and construction of a unate function compatible with some imposed observations. The existence problem is found to be NP Complete.  A practical algorithm of inference is exposed and tested in terms of accuracy and computational complexity.

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
