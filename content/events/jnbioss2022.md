---
date: 2022-11-17
title: "Journée annuelle du GT Bioss (2022, 7e édition)"
summary: "Le **jeudi 17 novembre 2022** à **Nantes** sur le campus de l'école centrale de Nantes"
categories: "Manifestations"
aliases:
   - /events/2022_journée_nantes
---


## Informations générales

**Date** : le 17 novembre 2022 de 10h à 17h

**Lieu** : Amphi du batîment S (LS2N) de l'école centrale de Nantes - [Accès](https://www.ec-nantes.fr/version-francaise/plans-dacces)

**Organisateurs** : Morgan Magnin, Laurence Calzone, Cédric Lhoussaine, Loïc Paulevé et Élisabeth Remy


## Inscription

L'inscription est gratuite mais obligatoire:

https://framaforms.org/journee-nationale-bioss-2022-a-nantes-1662456643

## Programme

La journée se déroulera entre 10h et 17h dans l'amphi du batîment S (LS2N)  de l'école centrale de Nantes - [Accès](https://www.ec-nantes.fr/version-francaise/plans-dacces)



Orateurs invités:
* **[Anna Niarakis]([https://scholar.google.ch/citations?user=bpOOfdMAAAAJ&hl=en])**
* **[Sylvain Soliman]([https://scholar.google.ch/citations?hl=en&user=8WmCFEkAAAAJ])** 


### Déroulé provisoire de la journée

* Accueil café à 9h30
* 9h50: Introduction
* 10h00 - 11h00: Séminaire invité - Anna Niarakis "From mechanisms to systems to digital twins. Αddressing critical barriers in systems modelling."
* 11h00 - 11h20: Maxime Lecomte - "Reasoning approaches for the characterization of cooperation and competition in large-scale microbial communities"
* 11h20 - 11h40: Chabname Ghassemi - "Analyzing and modelling functions carried by key species in minimal microbial communities"
* 11h40 - 12h00: Kerian Thuillier - "MERRIN: MEtabolic Regulation Rule INference from time series data"
* 12h00 - 13h30: buffet / café
* 13h30 - 14h30: Séminaire invité - Sylvain Soliman - "Inferring Boolean models with CaSQ or why a problem "solved" almost 15 years ago, actually was not…"
* 14h30 - 15h00: Discussion Bioss
* 15h00 - 15h20: Café
* 15h20 - 15h40: Gautier Stoll - PopMaBoSS: a Boolean-based modeling tool suited for single-cell biological data
* 15h40 - 16h00: Gustavo Magaña López - "scBoolSeq: scRNA-Seq data binarization and synthetic generation from Boolean dynamics"
* 16h00 - 16h20: Sophie Le Bars - "Predicting weighted unobserved nodes in a regulatory network using Answer Set Programming"
* 16h20 - 16h40: Honglu Sun - "Limit cycle analysis of a hybrid modeling of dynamical biological systems"
* 16h40: Concluding remarks
---

### Résumés

**Anna Niarakis** - *From mechanisms to systems to digital twins. Αddressing critical barriers in systems modelling.*.\
Computational models have long been used to describe complex systems in biology. Their abstract nature and their ability to reproduce dynamic behaviours make them powerful tools for hypothesis testing and in silico predictions. Recently, computational modelling has been gaining ground in personalized medicine, drug development and treatment optimization. Digital twins, customized simulation models pioneered in the industry, are beginning to be deployed with some major successes in cardiovascular diagnostics and insulin-dependent diabetes monitoring and treatment. The development of advanced medical twins requires a collaborative effort between immunologists, modellers, clinicians, computational scientists, and software engineers. Therefore, a step towards lowering barriers to collaboration would be the development of a) infrastructures to encourage and support model construction, integration, and simulation and b) best practices to ensure the accuracy and credibility of these models. While modelling approaches may differ, when discussing best practices several critical points are shared related to model accessibility, reusability, interoperability, and reproducibility.  In my talk, I will discuss the importance of model annotations, the use and implementation of community standards, the transparency in model building and data sharing and the need for infrastructure that could accommodate models of higher complexity. I will present community-driven collaborative efforts to address these challenges and present high-level roadmaps that could facilitate the passage from mechanisms to systems to digital twins. 

**Sylvain Soliman** - *Inferring Boolean models with CaSQ or why a problem "solved" almost 15 years ago, actually was not…*\
In 2008, François Fages and I co-authored a paper showing that, under very general hypotheses, it is easy to obtain from a chemical reaction network, without any detail about the kinetics (hence a "map" as more and more are made available, e.g., www.diseasemaps.org) its symbolic Jacobian matrix, and hence a corresponding "influence model". However, in practice, going from these influences to a proper Logical model, i.e., obtaining logical formulae composing those influences, is not trivial. Moreover, even if that were possible, the obtained result would still be very different from what a modeller would have done. In this talk we will thus show why and how CaSQ not only uses the input map's topology, but also relies strongly on its nodes' annotations and on graph-rewriting rules in order to infer a Boolean model closer to what is wished for. We will use toy examples, classical models (MAPK cascade) and more recent maps (from the Covid-19 DiseaseMaps project) for illustration.

**Maxime Lecomte** - *Reasoning approaches for the characterization of cooperation and competition in large-scale microbial communities*\
The use of either genomics or metagenomics data combined with metabolic modelling provides putative mechanistic understanding on microbes’ interactions within large scale microbial communities. Genome-scale metabolic networks (GSMNs) can be inferred automatically from large collections of annotated reference genomes or metagenome assembled genomes using dedicated reconstruction tools and can be used to infer the behavior of the underlying microbial community. Such community-scale modelling can predict exchanges of metabolites between species as witnesses of the cooperative or competitive potential in the community. To do so, numerical approaches, mainly based on flux balance analysis, characterize bacterial community with a good accuracy by comparing individual and community growth rates. Other approaches determine competition and cooperation scores from the topological analysis of networks. A shared constraint between methods is the limitation to pairwise analysis that prevents complex interactions in the community. In this talk, I will introduce a reasoning-based approach for the characterization of cooperation and competition potentials in large-scale microbial communities that is not limited to pairwise analysis. This method relies on modelling the metabolic potential in each microbe using a Boolean abstraction of metabolic producibility previously used for single organisms and ecosystem characterization.  I will present a set of metrics that can be used to predict the potential for cooperative interactions and competition between species. We applied them to existing microbial communities and created benchmarks aiming at comparing our scores in several ecosystems. Results show variations in competition and cooperation potential in distinct ecosystems, and comparison to existing pairwise metrics evidence correlations between predictions. We believe such approach to be relevant in the journey towards the better understanding and control of complex microbial ecosystems. 

**Chabname Ghassemi** - *Analyzing and modelling functions carried by key species in minimal microbial communities*\
Microbial communities play an important role in various environments, and as a result also is the gut microbiota, where host-microbial and microbe-microbe interactions have been highlighted. Numerous studies throughout the last decade illustrated these symbioses and their impact on the health of the host. By using Genome-Scale Metabolic Networks (GSMNs), one can build models describing the ecosystem at the level of metabolism and make hypotheses on the organization of the associated microbial communities. With the improvement of GSMN reconstruction toolboxes, such models can be built for thousands of organisms, requiring scalable and robust metabolism abstractions.
Metage2Metabo (M2M) is a tool screening all metabolism of a group of bacteria to detect key species and select minimal communities able to produce target metabolisms. M2M uses a discrete model to simulate the concept of producibility in metabolic networks and solve combinatorial optimization problems with ASP. M2M was used on a set of more than 1,500 intestinal bacterial genomes. With this study it was possible to design hundreds of thousands equivalent minimal communities and select key species i.e. bacteria predicted on one or more of these communities. The connections between key species were represented in power graphs, helping us to visualize equivalence groups of species, often grouped by phylum. These models are a first step towards the understanding of interactions between organisms, through the composition of minimal communities, but the metabolic mechanisms explaining these associations of key species were lacking.
By using the same programming paradigm as M2M, we designed new models to highlight the metabolism in equivalence groups of bacteria. We studied these groups through the lens of the functions they carry, the compounds they produce and reactions they can activate. We made comparisons between groups and also with bacteria that are not key species and were thus left out of the minimal communities. We applied our models to minimal communities for 5 groups of target metabolites predicted with M2M. The results show the role of groups of GSMNs in unlocking functions for GSMNs of other groups, which groups are able to produce targets and the specificities around these productions. More generally our work proposes the possible interactions between members of minimal communities.
Our study succeeded at suggesting explainable models of previous combinatorial optimization problems results. With an expressive programming paradigm and a discrete model, we are able to propose metabolic mechanisms for a better understanding of microbial communities.

**Kerian Thuillier** - *MERRIN: MEtabolic Regulation Rule INference from time series data*\
Many techniques have been developed to infer Boolean regulations from a prior knowledge network and experimental data. Existing methods are able to reverse-engineer Boolean regulations for transcriptional and signaling networks, but they fail to infer regulations that control metabolic networks. We present a novel approach to infer Boolean rules for metabolic regulation from  time series data and a prior knowledge network.
Our method is based on a combination of answer set programming and linear programming. By solving both combinatorial and linear arithmetic constraints, we generate candidate Boolean regulations that can reproduce the given data when coupled to the metabolic network. We evaluate our approach on a core regulated metabolic network and show how the quality of the predictions depends on the available kinetic, fluxomics or transcriptomics time series data.

**Gautier Stoll** - *PopMaBoSS: a Boolean-based modeling tool suited for single-cell biological data*\
PopMaBoSS aims at confronting theoretical results with a large class of biological data, including single-cell data. PopMaBoSS model language is an extension of MaBoSS language, with completely new mathematical framework and algorithm. Because PopMaBoSS describes time dependent behavior of cell populations, its results can be confronted to single cell data (cytometry, single-cell RNA sequencing, etc.). In addition, PopMaBoSS is probabilistic upon cell populations, and therefore suited for modeling biological data variability (replicates for in vitro/ in vivo data, large cohort human samples, etc.).\
The first part of the presentation will be based on model examples, with confrontation to biological data. We will then present PopMaBoSS mathematical framework. 

**Gustavo Magaña López** - *scBoolSeq: scRNA-Seq data binarization and synthetic generation from Boolean dynamics*\
scBoolSeq is a Python package for linking scRNA-Seq data and Boolean gene activation states.
 From a reference dataset, scBoolSeq learns a set of statistical criteria which allow the classification of gene
expression distributions. Then, scBoolSeq offers two complementary features:
  * The binarization of scRNA-Seq datasets.
  * The sampling of RNA counts biased by a given Boolean activity state.
This enables the generation of synthetic scRNA-Seq datasets from the simulation of Boolean dynamical models,
which may then serve as a ground-truth baseline for validating inference methods, including trajectory reconstruction.

**Sophie Le Bars** - *Predicting weighted unobserved nodes in a regulatory network using Answer Set Programming*\
The impact of a perturbation, over-expression, or repression of a key node on an organism, can be modelled based on a regulatory and/or metabolic network. Integration of these two networks could improve our global understanding of biological mechanisms triggered by a perturbation.
This study focuses on improving the modelling of the regulatory network to facilitate a possible integration with the metabolic network.
Previously proposed methods that study this problem fail to deal with a real-size regulatory network, computing predictions sensitive to perturbation and quantifying the predicted species behaviour more finely. To address previously mentioned limitations, we develop a new method based on Answer Set Programming, MajS. It takes a regulatory network and a discrete partial set of observations as input. MajS tests the consistency between the input data, proposes minimal repairs on the network to establish consistency, and finally computes weighted and signed predictions over the network species. We tested MajS by comparing the HIF-1 signalling pathway with two gene-expression datasets. Our results show that MajS can predict 100\% of unobserved species. When comparing MajS with two similar (discrete and quantitative) tools, we observed that compared with the discrete tool, MajS proposes a better coverage of the unobserved species, is more sensitive to system perturbations, and proposes predictions closer to real data. Compared to the quantitative tool, MajS provides more refined discrete predictions that agree with the dynamic proposed by the quantitative tool.
MajS is a new method to test the consistency between a regulatory network and a dataset that provides computational predictions on unobserved network species. It provides fine-grained discrete predictions by outputting the weight of the predicted sign as a piece of additional information. MajS' output, thanks to its weight, could easily be integrated \emph{with} metabolic network modelling.

**Honglu Sun** - *Limit cycle analysis of a hybrid modeling of dynamical biological systems*\
In the literature, different formalisms have been used to model gene regulatory networks in order to determine the dynamical properties. Two widely used formalisms are discrete models (like Boolean networks) and continuous models (like differential equations). Discrete models have less parameters to identify compared to continuous model, so they can be easily implemented, and the dynamics of discrete models are easy to analyze. This means that such discrete approach can help to understand the global dynamical properties of complex biological systems, e.g., the existence of fixed points and cyclic attractors. The main drawback of discrete models relie in the difficulty to deduce continuous properties of the systems. For example, it is hard to identify damped oscillations using only discrete models. Continuous models are more precise, but their dynamics are sometimes hard to analyze particular in higher dimensions and the parameters are sometimes hard to identify due to the limits of biological knowledge or data. Beyond continuous and discrete models, there also exist some hybrid models which have been proposed as a way to build a bridge between approaches: they can be seen as a simplification of the continuous models or an extension of the discrete models. The reason why they are called hybrid is that they contain both continuous and discrete components. Our work is based on a class of hybrid models call hybrid gene regulatory network (HGRN) which is an extension of discrete models. In HGRN, the state space is separated into several discrete states like discrete models and in each discrete state the temporal derivative of system is a constant vector so it can also make a continuous evolution of the system over time like differential equations. The advantage of HGRN compared to discrete models is that continuous simulation can be made using HGRN, and the advantages of HGRN compared to continuous models are that some dynamical properties of HGRN are easier to analyze and it is sometimes possible to identify formally the constraints on parameters of HGRN based on biological knowledge. The objective of this work is to study formal methods to analyze the dynamical properties of HGRN, which are not yet widely explored in the literature. In this presentation, we will present our limit cycle analysis method: a formal method for the identification and the stability analysis of limit cycles of HGRN . Limit cycles describe periodic behaviors which are quite common in biological systems, for example circadian clock and cell cycle. Two main ideas of this work are: 1 An abstraction method is used to guide the search of periodic orbits; 2 Poincaré map is extended for HGRN in this work to analyze the stability of limit cycles. We will also introduce our on-going works about the application of this method to determine conditions for sustained oscillations in synthetic circuits.
