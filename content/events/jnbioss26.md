---
date: 2026-04-09
title: "Journées annuelles 2026 du GT Bioss"
summary: "Les **1 et 2 juin 2025** à **Paris**"
categories: "Manifestations"
---

Lieu : Centre Inria de Paris 
(Amphi Jacques-Louis Lions les 1 et 2 juin)

Les journées annuelles sont un point de rassemblement important pour notre GT. Elles permettent un moment d'échange entre les chercheuses et chercheurs, débutant(e)s et confirmé(e)s, pour discuter sur nos avancées scientifiques récentes et les défis à aborder, à la frontière en informatique, mathématique et biologie.
Cette année encore, nous avons décidé de regrouper les évènements du GT Bioss (une journée et demi annuelle et une demi-journée thématique) en une seule période. Ainsi, les journées annuelles seront suivies par un atelier thématique, sur la modélisation multiéchelle. 

## Inscription

Merci d'utiliser ce [formulaire d'inscription](https://framaforms.org/journees-du-gt-bioss-2026-atelier-1771594486). L'inscription est gratuite, mais obligatoire. Le repas du lundi midi est pris en charge, sous réserve d'inscription. Les autres repas (lundi soir et mardi) sont à votre charge. <p>

La date limite pour les inscriptions est le 3 avril. <p>

## Programme préliminaire

Le programme général se déroulera entre le lundi 1 juin et le mardi 2 juin (horaires à définir). Il offrira des exposés invités et contribués, ainsi qu'une demi-journée ateliers d'une demi-journée.

Exposés invités confirmés
- **[Sylvain Soliman](https://lifeware.inria.fr/~soliman/)** (INRIA, Paris-Saclay) 
- **[Laurence Calzone](https://curie.fr/personne/laurence-calzone)** (Institut Curie)

### Journées annuelles 

- Lundi 1 juin : de 10:00 à 17:30
  
  *Amphithéâtre Jacques-Louis Lions, Centre Inria de Paris, 48 rue Barrault, Paris* - [Carte](https://www.openstreetmap.org/node/12127574547)

  - Programme à venir
  

- Mardi 2 juin matin : de 9:30 à 12:30

  *Amphithéâtre Jacques-Louis Lions, Centre Inria de Paris, 48 rue Barrault, Paris* - [Carte](https://www.openstreetmap.org/node/12127574547)

  - Programme à venir

### Atelier thématique (Modélisation multi-échelle) 

- Mardi 2 juin après-midi : de 14:00 à 17:00

  *Amphithéâtre Jacques-Louis Lions, Centre Inria de Paris, 48 rue Barrault, Paris* - [Carte](https://www.openstreetmap.org/node/12127574547)

   - Exposé invité : **Matthieu Bouguéon** (UCL Cancer Institute)
  
   - Table ronde 

## Résumés des exposés invités (journées annuelles) / Invited talk abstracts (annual days)

### [Laurence Calzone](https://curie.fr/personne/laurence-calzone) (Institut Curie)

TBA

### [Sylvain Soliman](https://lifeware.inria.fr/~soliman/) (INRIA, Paris Saclay)

Common work with Ángela Garcinuño Feliciano

*Sensitivity analysis for Boolean networks*

Boolean networks are a simple yet powerful formalism that has been widely used
for modelling qualitative interactions in complex dynamical systems, especially
in computational biology. The study of their continuous counterpart, such as
models defined by ordinary differential equations, often includes the response
to perturbations and in particular, "sensitivity analysis", a quantitative
measure of the effect of changes in each input (parameter) on the output of the
system.  If numerous propositions for a global robustness evaluation exist for
Boolean networks, to our knowledge, there is no sensitivity index that would
both scale and consider each node of the network as input and its asymptotic
behavior as output. In this preliminary work we explore propositions for such a
sensitivity analysis for Boolean networks and evaluate them on both toy and
published models.

## Résumés des exposés sur proposition (journées annuelles) / Contributed talk abstracts (annual days)

### Salvish Goomanee (Université Côte d'Azur)

*Topology guided geometric diffusion from cellular graph sequences: Enhancing energy constrained models*

Graph neural networks (GNNs) have emerged as a powerful framework for learning on structured data, yet their theoretical properties and long-term stability under iterative graph evolution remain incompletely understood. In this work, we introduce a geometric, equivariant graph learning framework designed to emulate complex dynamical processes on evolving 3D geometric graphs. Our representation encodes interacting entities as nodes and their pairwise interactions as weighted edges, allowing continuous geometric information to be coupled with discrete topology. The model integrates geometric message passing with diffusion-based updates, enabling stable propagation of information while respecting symmetry constraints. This construction is motivated by recent theoretical results on information loss in GNNs, including analyses based on functional inequalities (Cheeger, Log-Sobolev & Poincaré) that quantify mixing, contraction, and oversmoothing phenomena in deep message passing networks. By incorporating geometric diffusion mechanisms and topology-aware attention, in the spirit of topology-constrained graph transformers, our framework mitigates representation collapse and maintains discriminative features across successive topological updates. More broadly, this work contributes to the mathematical understanding of information propagation, symmetry preservation, and stability in geometric graph learning, with potential implications for a wide range of applications involving dynamical systems on evolving networks.

### Rebecca Ghidini (ENS Paris)

*Static analysis of Kappa models at edit time*

Kappa offers a modeling environment to describe, simulate, and reason about rule-based models. It has been used to model protein-protein interaction networks, especially models of signaling pathways.
To assist the modelers, it provides a static analyzer, KaSa, to assess the consistency of the models. While efficient, KaSa is sometimes too slow to reason while modifying large models, or when editing models within the user interface. Here we propose an incremental version that update the result of the current analysis at each model modifications.

Our approach relies on the use of a relational analysis which approximate relationships between the rules of the model and the properties that they induce. Partial evaluation is used when some rules are removed from a model (since the corresponding rule is no longer present). Adding rules is done is classically by resuming the iterations of the analysis algorithm.
This incremental analysis is available both in command line or in an electron app, and it evaluated on examples of the literature.

### Patricia Roxo (ENS Paris)

*On the properties of 2-distance immediate neighbors of monotonic non-degenerate Boolean functions*   

### Leopold Carron, Romain Grall, Rayane Ayoub Ait Allaoua (L'Oréal)
    
*A computational knowledge graph pipeline for NAM-based risk assessment*

The transition toward New Approach Methodologies (NAMs) for chemical risk assessment, particularly in Developmental and Reproductive Toxicology (DART), demands frameworks capable of integrating heterogeneous biological knowledge. Two major initiatives structure this space: the Adverse Outcome Pathway (AOP) framework — maintained as a community-driven resource via the AOPWiki (OECD) — scaffolding causal chains from Molecular Initiating Events through Key Events (KEs) to Adverse Outcomes; and the ONTOX consortium (EU, Horizon 2020) physiological maps, enriching KEs with molecular interaction context to enable mechanistic hypothesis generation.  
Knowledge Graphs (KGs) represent a promising paradigm for structuring and querying such heterogeneous knowledge. We present a Toxicology Knowledge Graph (TKG) implemented as a Labeled Property Graph (LPG) in Neo4j [1], integrating the AOPWiki XML dump, ONTOX physiological maps, and biological entities retrieved via the Ontology Lookup Service (OLS4) across 10 ontologies and controlled vocabularies (GO, UBERON, NCIT, MeSH, et al.). The objective of TKG development is to enable outcome-agnostic biomarker identification, testing strategy construction, and chemical biological behavior prediction, with a primary focus on DART.  
However, the heterogeneous curation depth of these resources — including incomplete FAIR-compatible annotations — results in sparse gene-to-KE associations. While AOPWikiRDF [2] provides PRO-based gene-KE mappings, many KEs remain unannotated, constraining graph traversal and biomarker extraction.  
Building upon the PRO-based approach of AOPWikiRDF, an improved rule-based lexical entity recognition step was applied to KE titles — involving text normalization, punctuation handling, and lexicon-based gene entity matching — exploiting the concise structure of KE titles to yield high-confidence associations and reduce false positives observed with description-level annotation.  
Validation across a reproductive toxicity use case demonstrated robust AOP retrieval: a ground truth of 47 relevant AOPs was constructed through combined expert curation and systematic literature mining over the human/unspecified AOP space (n=388). Non-specialist seed-term querying achieved 52% precision, 83% recall and 88.7% accuracy. Title-level lexical enrichment independently annotated 73 previously unannotated KEs while confirming 42% of existing expert KE-gene associations, outperforming description-level annotation in precision.  
These results establish the TKG as a scalable, semantically interoperable platform for hypothesis-driven DART risk assessment. Future work will focus on integrating developmental stage ontologies to enable stage-spanning predictions and finer-grained testing strategy construction across embryonic and postnatal exposure windows.

[1] InSilicoVida Research Lab. AOPWiki Explorer. github.com/InSilicoVida-Research-Lab/AOPWiki_Explorer  
[2] Martens M, Evelo CT, Willighagen EL. Appl In Vitro Toxicol. 2022;8(1):2–13. DOI: 10.1089/aivt.2021.0010 

### Victoria Bruning (Institut Curie)
  
*Inference of cell-cell communication Boolean networks*

The presentation will introduce a Boolean network inference framework for reconstructing executable multicellular dynamical models of cell-cell communication from temporal ligand-receptor observations. Cell types are represented through receptor and ligand nodes linked by a bipartite structure, with pseudo-steady-state constraints encoding the timescale separation between fast receptor activation and slow ligand secretion. BoNesis exhaustively infers all Boolean networks consistent with the observed dynamical sequence, producing an ensemble that distinguishes constrained interactions from biologically redundant ones. The framework is validated on a two-cell toy model and scaled to a 50-node CLL tumor microenvironment model, recovering expected dynamics and generating coherent perturbation predictions.

### Juliette Audemard (Université de Nantes, École Centrale Nantes)
  
*Exploring strategies for prior knowledge integration into an inductive logic program framework*

The increasing availability of high-throughput biological data, together with the
development of curated knowledge bases such as KEGG [7], MetaCyc [2], and BioModels
[8], has led to the emergence of large collections of structured biological knowledge.
Formalized as networks of interactions and relationships, prior knowledge networks (PKN),
serves multiples purposes in systems biology: they provide a means to store biological
interactions [3], input to build mechanistic models of biological processes [10], or to support
inference of new-data based knowledge [9].
Among the way to identify relationships between biological components from dynamical
data, inductive logic programming (ILP) such as Learning From Interpretation Transition
(LFIT) [6, 11], learns the dynamics of a system from observation of state transitions. In this
talk, we propose to implement and investigate the implications of using prior knowledge into
LFIT framework.
The integration of prior knowledge when working with biological observations is
particularly valuable, as such observations are prone to incompleteness and noise.
However, while the benefits of PKN integration may seem straightforward, it becomes
challenging when the PKN itself is inconsistent with observations [4]. Manual curation of
knowledge and models, although arguably the most reliable solution [1], is time-consuming
and requires expert intervention that may not always be available to modelers. We then
distinguish two broad strategies for PKN integration into an ILP framework: a naive one,
where the PKN solely restricts the hypothesis search space by limiting the computational
process to variables unexplained by background knowledge, without guaranteeing
consistency with observed data [9]; and a more principled one, where conflicts between
prior knowledge and data-driven rules are explicitly identified and handled. Indeed, in
biological settings, PKN may be too specific, too general, or simply inconsistent with
observations due to context-dependency or experimental noise, making naive integration
insufficient [4, 5]. In line with biological contexts, and building on logical model revision and
inconsistency handling [12, 5], our work aims to characterize the nature of such conflicts in
the LFIT framework and to explore strategies for their resolution.

References  
[1] Amel Bekkar, Anne Estreicher, Anne Niknejad, Cristina Casals-Casas, Alan Bridge, Ioannis
Xenarios, Julien Dorier, and Isaac Crespo. Expert curation for building network-based dynamical
models: A case study on atherosclerotic plaque formation. Database: The Journal of Biological
Databases and Curation, 2018:bay031, January 2018.  
[2] Ron Caspi, Richard Billington, Ingrid M Keseler, Anamika Kothari, Markus Krummenacker,
Peter E Midford, Wai Kit Ong, Suzanne Paley, Pallavi Subhraveti, and Peter D Karp. The
MetaCyc database of metabolic pathways and enzymes—a 2019 update. Nucleic Acids
Research, 48(D1):D445–D453, 2019.  
[3] Claudine Chaouiya, Sarah M. Keating, Duncan Berenguier, Aurélien Naldi, Denis Thieffry,
Martijn P. van Iersel, Nicolas Le Novère, and Tomáš Helikar. SBML Level 3 package: Qualitative
Models, Version 1, Release 1. Journal of Integrative Bioinformatics, 12(2):691–730, June 2015.  
[4] Fulvia Ferrazzi, Paolo Magni, Lucia Sacchi, Angelo Nuzzo, Uroš Petroviˇc, and Riccardo Bellazzi.
Inferring gene regulatory networks by integrating static and dynamic data. International Journal
of Medical Informatics, 76:S462–S475, December 2007.  
[5] Martin Gebser, Carito Guziolowski, Mihail Ivanchev, Torsten Schaub, Anne Siegel, Sven Thiele,
and Philippe Veber. Repair and prediction (Under Inconsistency) in large biological networks
with answer set programming. In Proceedings of the Twelfth International Conference on
Principles of Knowledge Representation and Reasoning, KR’10, pages 497–507, Toronto,
Ontario, Canada, May 2010. AAAI Press.  
[6] Katsumi Inoue, Tony Ribeiro, and Chiaki Sakama. Learning from interpretation transition.
Machine Learning, 94(1):51–79, January 2014.  
[7] M. Kanehisa and S. Goto. KEGG: Kyoto encyclopedia of genes and genomes. Nucleic Acids
Research, 28(1):27–30, January 2000.  
[8] Rahuman S Malik-Sheriff, Mihai Glont, Tung V N Nguyen, Krishna Tiwari, Matthew G Roberts,
Ashley Xavier, Manh T Vu, Jinghao Men, Matthieu Maire, Sarubini Kananathan, Emma L
Fairbanks, Johannes P Meyer, Chinmay Arankalle, Thawfeek M Varusai, Vincent Knight-
Schrijver, Lu Li, Corina Dueñas-Roca, Gaurhari Dass, Sarah M Keating, Young M Park, Nicola
Buso, Nicolas Rodriguez, Michael Hucka, and Henning Hermjakob. BioModels — 15 years of
sharing computational models in life science. Nucleic Acids Research, 48(D1):D407–D415, 1
2020. gkz1055.  
[9] Stephen Muggleton and Luc De Raedt. Inductive Logic Programming: Theory and methods.
The Journal of Logic Programming, 19–20:629–679, May 1994.  
[10] Anna Niarakis, Martin Kuiper, Marek Ostaszewski, Rahuman S Malik Sheriff, Cristina Casals-
Casas, Denis Thieffry, Tom C Freeman, Paul Thomas, Vasundra Touré, Vincent Noël, Gautier
Stoll, Julio Saez-Rodriguez, Aurélien Naldi, Eugenia Oshurko, Ioannis Xenarios, Sylvain
Soliman, Claudine Chaouiya, Tomáš Helikar, and Laurence Calzone. Setting the basis of best
practices and standards for curation and annotation of logical models in biology—highlights of
the [BC]2 2019 CoLoMoTo/SysMod Workshop. Briefings in Bioinformatics, 22(2):1848–1859,
April 2020.  
[11] Tony Ribeiro, Maxime Folschette, Morgan Magnin, and Katsumi Inoue. Learning any memory-
less discrete semantics for dynamical systems represented by logic programs. Machine
Learning, November 2021.  
[12] Chiaki Sakama and Katsumi Inoue. Updating Extended Logic Programs through Abduction.
In Michael Gelfond, Nicola Leone, and Gerald Pfeifer, editors, Logic Programming and
Nonmonotonic Reasoning, pages 147–161, Berlin, Heidelberg, 1999. Springer.

### Tony Ribeiro (École Centrale de Nantes)

*Static and Dynamic Counterfactual Explanations for Learning From Interpretation Transition*

Counterfactual explanations are becoming vital tools for interpreting the "black box" of artificial intelligence, offering human-readable insights by illustrating how specific input changes alter predictions. In the context of bioinformatics, where understanding the causal drivers of disease phenotypes or metabolic shifts is critical, these explanations provide a bridge between complex modeling and actionable biological discovery.  
In this work, we extend the Learning From Interpretation Transitions (LFIT) framework by formalizing counterfactual explanations within multi-valued logic programs. We address two primary challenges:  
Static Systems (e.g., Diagnostics & Classification): We introduce CELOS, an efficient algorithm that leverages logic-rule properties to compute all minimal counterfactual explanations. This allows researchers to identify the smallest set of features (such as gene expression levels or proteomic markers) required to flip a classification from "diseased" to "healthy" for example. We provide theoretical proofs of correctness and evaluate the algorithm using both synthetic data and biological benchmarks from literature.  
Dynamic Systems (e.g., Gene Regulatory Networks): We formalize counterfactual reasoning as a dynamic navigation problem. For deterministic dynamics, finding a minimal explanation is equivalent to discovering the shortest path within a state-transition graph. For non-deterministic dynamics, we focus on guaranteeing the reachability of a desired goal state by pruning transitions based on system rules and user controls.  
By providing a rigorous foundation for answering "what-if" queries, this work offers a path toward identifying optimal intervention strategies in complex, discrete systems.

### José-Américo NLF de Freitas (Institut Mondor)

*Dynamic modeling of the transcriptional regulatory network controlling cellular senescence*

Cellular senescence (CS) is a complex cellular stress response associated with various age-related diseases, such as diabetes, cancer, and Alzheimer's disease. The phenotypic shift of cells undergoing senescence results from profound and dynamic changes in the epigenetic and transcriptomic landscape, coordinated by a hierarchical network of transcription factors. In order to decipher the gene regulatory network that implements changes in the cell's state and identity during CS, we leverage the comprehensive scRNA-seq atlas Tabula Sapiens and RNA velocity inference tools to build a mathematical model with non-linear differential equations that mimic the transcriptome evolution of senescent cells. We simulate in silico temporal gene expression profiles from initial conditions corresponding to senescent and non-senescent lung fibroblasts. The senescence status of a cell is defined according to gene expression levels of CS markers, defined in gene lists such as SenMayo or the SASP Atlas. We employ model interpretability tools, such as Local Interpretable Model-Agnostic Explanations (LIME), to inform us about the regulators with highest weights for a given target, at a specific point in their transcriptomic trajectory. By characterizing non-linear interactions, our model accounts for regulatory interactions dependent on cell identity. Furthermore, we have identified cells expressing CS-associated markers in the Tabula Sapiens dataset, which underscores the physiological relevance of CS and shows that our model can accurately portray the transcriptional dynamics of senescent cells. Ultimately, we will be able to quantify cellular senescence dynamics, identifying actionable targets with therapeutic applications and alleviating the detrimental impact of senescent cells on aging and age-related diseases to prolong healthspan.

### Charles Cazenave (LaBRI)

(Joint work with Xichen Zhang, Charles Cazenave, Loïc Paulevé, and Tristan Cazenave)

*Efficient Search for Combinations of Mutations on Boolean Network Ensembles*

We study mutation-set search in asynchronous Boolean Network (BN)
ensembles to control reachable attractors from initial conditions. The
robust evaluation of mutations requires averaging over many plausible
models. In this setting, each rollout is expensive, while attractor
estimates remain noisy under limited simulation budgets. We first derive
a variance decomposition that separates across-model diversity from
within-model simulation noise, yielding a simple rule for allocating the
ensemble size and the number of trajectories. We then compare  Lazy
Nested Monte Carlo Search (NMCS) and Nested Rollout Policy Adaptation
(NRPA) algorithms, and introduce Bi-Level Lazy NMCS (BILNMCS): a
two-level scheme that screens candidate moves on a small, cheap ensemble
and confirms best candidates on a large, accurate one. We benchmark the
algorithms on different ensemble of Boolean networks coming from
biological applications, showing BILNMCS efficiency on realistic case
studies.

### Theo Roncalli (LaBRI)

*scBridge: pipeline for Boolean network Reconstruction and Inference from multiple experimental Data in Gene Expression*

Predictive logical models have redefined the study of biomedical challenges, by facilitating
the identification of regulatory mechanisms driving biological processes. Yet, their construction remains non-trivial, as it typically relies on extensive prior biological knowledge at the genome scale. The emergence of single-cell transcriptomic assays has enabled new alternatives for model reconstruction by supporting data-driven approaches, thereby reducing reliance on prior knowledge. However, state-of-the-art methods remain limited, as they struggle to address poorly characterized biological contexts, rely on insufficiently automated workflows, and fail to exploit datasets from heterogeneous biological experiments. To overcome these challenges, we introduce scBridge, a novel semi-automated workflow for the data-driven reconstruction of logical models that enables multi-condition data integration.

### Louison Crepin (IBISC/Université Évry Paris Saclay)
    
*Qualification Games: A Game-Theoretic Framework for Overcoming Drug Resistance*

Drug resistance is a pervasive challenge across a vast spectrum of diseases, systematically undermining therapy efficacy and complicating clinical outcomes. Current approaches, largely reliant on empirical trial-and-error, fail to capture the inherently dynamic and adversarial interplay between treatment strategies and evolving resistance mechanisms. To address this issue, we introduce Qualification Games, a novel two-player game-theoretic framework where qualification predicates—formally defined as Boolean conditions— uniquely identify winning states for the physician (e.g., inducing apoptosis) or the disease (e.g., evading therapy).  
This framework provides a rigorous formalism to model resistance by encoding its adversarial dynamics: the physician deploys interventions to enforce therapeutic success, while the disease adapts through mutations or phenotypic shifts. By leveraging reachability-based qualifications, our model systematically explores optimal strategies to overcome resistance in complex diseases.  
Our framework integrates Boolean Control Networks (BCNs) to represent the biological system. In a qualification game, transitions are driven by therapeutic controls or disease adaptations. We formalize resistance as the discovery of a reachability winning region on this logical arena, allowing for the computation of optimal treatment sequences that maximize efficacy while preempting adaptive responses of the disease.  
As a proof of concept, we apply Qualification Games to breast cancer, modeling the interplay between targeted therapies (e.g., pik3/akt inhibitors) and resistance emergence. Using biomarker-driven BCNs, we identify critical control nodes—such as ESR1 amplification or MAPK1 rewiring—that underpin resistance. Our results demonstrate the ability to predict minimal intervention sets (e.g., drug combinations) to enforce apoptosis while mitigating resistance risks.  
Beyond oncology, this framework can be generalized to any system where resistance arises from dynamic interactions (e.g., antimicrobial resistance, chronic diseases). By unifying game theory, BCNs, and dynamical systems, Qualification Games offers a scalable framework for designing adaptive, precision treatment strategies.

### Hélène Siboulet (INRIA Saclay)
   
*On the equality between differential and mean stochastic dynamics of chemical reaction networks with low numbers of molecules*

Complex systems can be advantageously modelled by formal reaction systems
(RS), a.k.a. chemical reaction networks (CRN) in chemistry. A same reaction-based model with kinetics can
indeed be interpreted in a hierarchy of semantics, most notably by Ordinary Differential Equations (ODEs), 
Continuous Time Markov Chains (CTMCs), discrete Petri nets and asynchronous Boolean transition systems,
with various relevance depending on the question at hand. The last three semantics can be easily related by formal abstractions in the framework of abstract interpretation. 
The first two are classically related by Kurtz’s limit theorem which states that if reactions are density-dependent families, then,
as the volume goes to infinity, the mean reactant concentrations of the CTMC tends towards the solution of the ODE. 
In the more realistic context of bounded volumes, it is easy to show, by moment closure, that the restriction to reactions
with at most one reactant, ensures similarly that the mean of the CTMC trajectories is equal to the solution of the ODE at all time points. 

In this talk, we show that under some graphical conditions on the infuence graph structure of a CRN, the equality also holds in presence of some polyreactant reactions, 
at all time points, with no condition on the number of molecules.
Evaluation on the repository of models BioModels shows that our conditions are satisfied for all variables in unimolecular reaction models only,
but are satisfied for a non§trivial subset of variables in presence of polymolecular reactions.
Interestingly, we also show, using different methods, that the equality with the ODE solution also holds for a stochastic oscillator CRN implementing the sine and cosine functions of time,
in presence of an absorbing state and of diverging trajectories which somehow compensate at all time points.

### Mathieu Hemery (INRIA Saclay)

*Reading a real number with Chemical Reaction Network (CRN)*


The computation framework proposed by Fages et al. encodes the mathematical
variables of a program in the concentration of chemical species. This allows for
an elegant implementation of analog computing which have been proven by Bournez
et al. to be Turing complete. It also means that if we want to "read" the result
of our program, we have to measure accurately the concentration of a species,
the value of which can be any real number.

We propose here a CRN that takes a real number and a precision and produces a
behavior allowing an observer to build a rational number approaching the input
with the desired precision.

In particular, we investigate how the precision depends on the different rates
of the model and provide theoretical arguments to explain the fractal behavior
of the measured error revealed by the numerical integration of the model.