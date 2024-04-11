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

Inscription gratuite mais obligatoire : https://framaforms.org/journees-du-gt-bioss-2024-ateliers-1710882707 avant le **30 avril**.

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
- 11h - 11h30: [Maxime Folschette](http://maxime.folschette.name/) (CRIStAL, IUT Lille)
- 11h30 - 12h30: *contributed talks* (TBA)

Buffet 12h30 - 14h

- 14h - 15h: [Jakob Ruess](https://www.inria.fr/fr/jakob-ruess) (Inria Saclay), *"From single cells to microbial consortia and back: stochastic chemical kinetics coupled to population dynamics"*
- 15h - 15h30: *contributed talks* (TBA)
- 15h30 - 16h00: *Break*
- 16h - 17: *contributed talks* (TBA)

### Mardi 28 mai 9h30 - 12h
*Salle de séminaire du LIP6 (salle 25-26/105), Campus UPMC Jussieu*

- 9h30 - 10h30: [Wolfram Liebermeister](http://genome.jouy.inra.fr/~wliebermeis/index_en.html) (Inrae Jouy-en-Josas)
- 10h30 - 11h: *Break*
- 11h - 11h30: *contributed talk* (TBA)
- 11h30 - 12h Discussion

### Atelier "Évaluation de méthodes d'inférence de modèles" - mardi 28 mai 14h-17h
*Salle 306, IBENS, ENS Paris (46 rue d’Ulm, 75005 Paris)*

Objectifs:
- constituter un/des jeux de benchmarks pour évaluer les méthodes d'inférence de modèles (graphes causaux, modèles dynamiques) développées par des membres du GT
    - différents pré-requis/hypothèses des méthodes: observations à l'état stationnaire ou non, type de données quantitatives (scRNA-Seq-like, ..), séries temporelles
    - quels "ground truth"? (modèles de la littérature, modèles de synthèse, ..)
    - jeux de données avec mutants
- discuter de l'évaluation des modèles inférés vis-à-vis du ground truth:
    - vis-à-vis de la structure: équivalence/proximité avec le ground truth
    - vis-à-vis des prédictions (p. ex sur les mutants): permet de comparer des modèles de nature différente

### Atelier "CoLoMoTo - Outils pour la modélisation logique" - mercredi 29 9h30-12h30
*Salle 306, IBENS, ENS Paris (46 rue d’Ulm, 75005 Paris)*

Objectifs:
- Faire le point sur les outils développés dans le GT et leur mise à disposition
- Défis méthodologiques pour la modélisation logique (combinaison de modèles, reproducibilité des simulations, ...)
- Faire le point sur l'état et le devenir de la distribution Docker CoLoMoTo

Programme préliminaire : https://codimd.math.cnrs.fr/s/EVOoKlvx4

## Résumés / Abstracts

### Jakob Ruess
*From single cells to microbial consortia and back: stochastic chemical kinetics coupled to population dynamics*

At the single-cell level, biochemical processes are inherently stochastic. Such processes are typically studied using models based on stochastic chemical kinetics, governed by a chemical master equation (CME). The CME describes the time evolution of the probability distribution over system states and has been a tremendously helpful tool in shedding light on the functioning of cellular processes. However, single cells are not living in isolation but are part of a growing population or community. In such contexts, stochasticity at the single-cell scale leads to population heterogeneity and cells may be subject to population processes, such as selection, that drive the population distribution away from the probability distribution of the single-cell process.
Here, I will introduce a multi-scale modeling framework that allows one to capture coupled stochastic single-cell and population processes. I will show that the expected population distribution of such multi-scale models can be calculated by solving a modified version of the CME that is of the same dimensionality as the standard CME. I will then show how such models can be used to explain experimental data on plasmid copy number fluctuations and population growth in media that selects against cells that have lost the plasmid. Finally, I will present an optogenetic recombination system that allows one to partition yeast populations into different cell types via external application of blue light to cells and show how our modeling framework can be used to predict and control emerging dynamics of the population composition in response to time-varying light stimuli.
