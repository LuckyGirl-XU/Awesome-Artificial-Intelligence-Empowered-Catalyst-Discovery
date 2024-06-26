# Awesome-Artificial-Intelligence-Empowered-Catalyst-Discovery [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of papers and resources about our survey paper: 
<!-- **A Survey for AI-Empowered Catalyst Discovery: From Classical Machine Learning Approaches to Large Language Models** -->

## Contents

- [Datasets](#data)
- [Existing Surveys in Catalyst Discovery](#surveys)
- [Open Platforms](#platforms)
- [Four Main Categories](#Publications)
  - [Classical-based methods](#classical)
  - [Generative and Reinforcement Learning-based methods](#generative)
  - [Graph neural network-based methods](#Graph)
  - [Large language model-based methods](#LLM)
- [Other Related Works](#Others)

<a name="data" />

## Datasets
* Catalysis-Hub. org, an open electronic structure database for surface reactions (**Scientific data, 2019**) [[paper](https://www.nature.com/articles/s41597-019-0081-y)]
* The Open catalyst 2020 (OC20) dataset and community challenges (**Acs Catalysis, 2021**) [[paper](https://pubs.acs.org/doi/10.1021/acscatal.0c04525)]
* The Open Catalyst 2022 (OC22) dataset and challenges for oxide electrocatalysts (**ACS Catalysis, 2023**) [[paper](https://pubs.acs.org/doi/10.1021/acscatal.2c05426)]

<a name="surveys" />

## Existing Surveys in Catalyst Discovery
* Search for Catalysts by Inverse Design: Artificial Intelligence, Mountain Climbers, and Alchemists (**Chemical Reviews, 2019**) [[paper](https://pubs.acs.org/doi/abs/10.1021/acs.chemrev.8b00759)]
* High-throughput experimentation meets artificial intelligence - a new pathway to catalyst discovery (**Physical Chemistry Chemical Physics, 2020**) [[paper](https://pubs.rsc.org/en/content/articlelanding/2020/cp/d0cp00972e)]
* Automated in Silico Design of Homogeneous Catalysts (**ACS Catalysis, 2020**) [[paper](https://pubs.acs.org/doi/10.1021/acscatal.9b04952)]
* Data-Driven Design of Electrocatalysts - Principle, Progress, and Perspective (**Journal of Materials Chemistry A, 2023**) [[paper](https://pubs.rsc.org/en/content/articlelanding/2023/ta/d2ta09278f/unauth)]
* Bridging the complexity gap in computational heterogeneous catalysis with machine learning (**Nature Catalysis, 2023**) [[paper]([https://pubs.rsc.org/en/content/articlelanding/2023/ta/d2ta09278f/unauth](https://www.nature.com/articles/s41929-023-00911-w))]

### <img src="./fig/star.svg" width="15" height="15" /> A Brief Summary of Related Surveys
Table 1 in our survey paper.
<p align="center">
    <img src="./fig/Comparison.png" width="90%" style="align:center;"/>
</p>

<a name="platforms" />

## Open Platforms
* [Open Catalyst Project](https://opencatalystproject.org/): Provide datasets, baseline models, and a public leaderboard
* [ASE](https://gitlab.com/ase/ase): An open-source package for setting up, manipulating, running, visualizing, and analyzing atomistic simulations
* [LCMD](https://www.epfl.ch/labs/lcmd/): A platform that aggregates tools and databases for the digital optimization and discovery of catalysts
* [RDKit](https://github.com/rdkit/rdkit): Offer a comprehensive suite of tools for cheminformatics, supporting both 2D and 3D molecular operations

<a name="Publications" />
  
## Existing Works in both Homogeneous and Heterogeneous Catalyst Discovery (with either Direct or Inverse designs)

<a name="classical" />

### Classical Methods in Catalysts
* An adaptive machine learning strategy for accelerating discovery of perovskite electrocatalysts (**ACS Catalysis, 2020**) [[paper](https://pubs.acs.org/doi/pdf/10.1021/acscatal.9b05248)]
* Simple descriptor derived from symbolic regression accelerating the discovery of new perovskite catalysts (**Nature communications, 2020**) [[paper](https://www.nature.com/articles/s41467-020-17263-9)]
* Exploring chemical and conformational spaces by batch mode deep active learning (**Digital Discovery, 2022**) [[paper](https://pubs.rsc.org/en/content/articlelanding/2022/dd/d2dd00034b)]
* Accelerating atomic catalyst discovery by theoretical calculations-machine learning strategy (**Advanced Energy Materials, 2020**) [[paper](https://onlinelibrary.wiley.com/doi/abs/10.1002/aenm.201903949)]
* Artificial-intelligence-driven discovery of catalyst genes with application to CO2 activation on semiconductor oxides (**Nature Communications, 2022**) [[paper](https://www.nature.com/articles/s41467-022-28042-z)]
* Accelerated discovery of multi-elemental reverse water-gas shift catalysts using extrapolative machine learning approach (**Nature Communications, 2023**) [[paper](https://www.nature.com/articles/s41467-023-41341-3)]
* Automated and Intelligent Synthesis of Oxygen-Producing Catalysts from Martian Meteorites by Robotic AI-Chemist [[paper](https://www.researchsquare.com/article/rs-2681831/v1)]
* Data-driven discovery of electrocatalysts for CO2 reduction using active motifs-based machine learning (**Nature Communications, 2023**) [[paper](https://www.nature.com/articles/s41467-023-43118-0)]
* Machine-learning-accelerated design of high-performance platinum intermetallic nanoparticle fuel cell catalysts(**Nature Communications, 2024**) [[paper](https://www.nature.com/articles/s41467-023-44674-1)]

<a name="generative" />

### Generative and Reinforcement Learning in Catalysts
* Navigating through the maze of homogeneous catalyst design with machine learning (**Trends in Chemistry, 2021**) [[paper](https://www.cell.com/trends/chemistry/abstract/S2589-5974(20)30316-6)]
* Heterogeneous catalyst design by generative adversarial network and first-principles based microkinetics (**Scientific Reports, 2022**) [[paper](https://www.nature.com/articles/s41598-022-15586-9)]
* AdsorbRL: Deep Multi-Objective Reinforcement Learning for Inverse Catalysts Design. (**NeurIPS, 2023**) [[paper](https://arxiv.org/abs/2312.02308)]
* Designing catalysts with deep generative models and computational data. A case study for Suzuki cross coupling reactions (**Digital discovery, 2023**) [[paper](https://pubs.rsc.org/en/content/articlehtml/2023/dd/d2dd00125j)]

<a name="Graph" />

### Graph Neural Networks in Catalysts
* Gemnet: Universal directional graph neural networks for molecules (**NeurIPS, 2021**) [[paper](https://proceedings.neurips.cc/paper_files/paper/2021/hash/35cf8659cfcb13224cbd47863a34fc58-Abstract.html)]
* Towards Training Billion Parameter Graph Neural Networks for Atomic Simulations (**ICLR, 2022**) [[paper](https://arxiv.org/abs/2203.09697)]
* Catlas: an automated framework for catalyst discovery demonstrated for direct syngas conversion (**Catalysis Science & Technology, 2022**) [[paper](https://pubs.rsc.org/en/content/articlelanding/2022/cy/d2cy01267g/unauth)]
* Dr-label: Improving gnn models for catalysis systems by label deconstruction and reconstruction (**arXiv, 2023**) [[paper](https://arxiv.org/abs/2303.02875)]
* Revisiting Electrocatalyst Design by a Knowledge Graph of Cu-Based Catalysts for CO2 Reduction (**ACS Catalysis, 2023**) [[paper](https://pubs.acs.org/doi/abs/10.1021/acscatal.3c00759)]
* CURATOR: Autonomous Batch Active-Learning Workflow for Catalysts (**NeurIPS, 2023**) [[paper](https://openreview.net/forum?id=pKmcMaULn1)]
* Boosting heterogeneous catalyst discovery by structurally constrained deep learning models (**Materials Today Chemistry, 2023**) [[paper](https://www.sciencedirect.com/science/article/pii/S2468519423001684)]
* Interpretable design of Ir-free trimetallic electrocatalysts for ammonia oxidation with graph neural networks (**Nature communications, 2023**) [[paper](https://www.nature.com/articles/s41467-023-36322-5)]
* Artificial intelligence driven design of catalysts and materials for ring opening polymerization using a domain-specific language (**Nature Communications, 2023**) [[paper](https://www.nature.com/articles/s41467-023-39396-3)]
* Towards Combinatorial Generalization for Catalysts: A Kohn-Sham Charge-Density Approach (**NeurIPS, 2024**) [[paper](https://proceedings.neurips.cc/paper_files/paper/2023/hash/be82bb4bf8333107b0fe430e1017831a-Abstract-Conference.html)]
* PhAST: Physics-Aware, Scalable, and Task-Specific GNNs for Accelerated Catalyst Design (**JMLR, 2024**) [[paper](https://www.jmlr.org/papers/volume25/23-0680/23-0680.pdf)]

<a name="LLM" />

### Large Language Models in Catalysts
* Monte Carlo Thought Search: Large Language Model Querying for Complex Scientific Reasoning in Catalyst Design (**EMNLP, 2023**) [[paper](https://arxiv.org/abs/2310.14420)]
* Artificial Intelligence (AI) Workflow for Catalyst Design and Optimization (**Industrial & Engineering Chemistry Research, 2023**)[[paper](https://pubs.acs.org/doi/abs/10.1021/acs.iecr.3c02520)]
* Catalyst Energy Prediction with CatBERTa: Unveiling Feature Exploration Strategies through Large Language Models (**ACS Catalysis, 2023**) [[paper](https://pubs.acs.org/doi/full/10.1021/acscatal.3c04956)]
* Augmenting large language models with chemistry tools (**Nature Machine Intelligence, 2024**) [[paper](https://www.nature.com/articles/s42256-024-00832-8)]
* CO2 Reduction beyond Copper-Based Catalysts: A Natural Language Processing Review from the Scientific Literature (**ACS Sustainable Chemistry & Engineering, 2024**) [[paper](https://pubs.acs.org/doi/abs/10.1021/acssuschemeng.3c06920)]

<a name="Others" />

## Other Related Works
<!-- Molecular Generation -->
* Constrained Graph Variational Autoencoders for Molecule Design (**NeurIPS, 2018**) [[paper](https://arxiv.org/abs/1805.09076)]
* GraphAF: a Flow-based Autoregressive Model for Molecular Graph Generation (**SIGKDD, 2020**) [[paper](https://arxiv.org/abs/2001.09382)]
* MoFlow: An Invertible Flow Model for Generating Molecular Graphs (**ICLR, 2020**) [[paper](https://arxiv.org/abs/2006.10137)]
* Multi-objective molecule generation using interpretable substructures (**ICML, 2020**) [[paper](https://arxiv.org/abs/2002.03244)]
* E(n) Equivariant Normalizing Flows (**NeurIPS, 2021**) [[paper](https://arxiv.org/abs/2105.09016)]
* A 3D Generative Model for Structure-Based Drug Design (**NeurIPS, 2021**) [[paper](https://arxiv.org/abs/2203.10446)]
* Learning Neural Generative Dynamics for Molecular Conformation Generation (**ICLR, 2021**) [[paper](https://arxiv.org/abs/2102.10240)]
* Equivariant Diffusion for Molecule Generation in 3D (**ICML, 2022**) [[paper](https://arxiv.org/abs/2203.17003)]
* Generating 3D Molecules for Target Protein Binding (**ICML, 2022**) [[paper](https://arxiv.org/abs/2204.09410)]
* GeoLDM: Geometric Latent Diffusion Models for 3D Molecule Generation (**ICML, 2023**) [[paper](https://arxiv.org/abs/2305.01140)]
<!-- Catalytic Reaction -->
* Optimization of base-catalyzed ethanolysis of sunflower oil by regression and artificial neural network models (**Fuel processing technology, 2013**) [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0378382013001422)]
* Optimization of ultrasound-assisted base-catalyzed methanolysis of sunflower oil using response surface and artifical neural network methodologies (**Chemical Engineering Journal, 2013**) [[paper](https://www.sciencedirect.com/science/article/abs/pii/S1385894712014398)]
* Performance evaluation of artificial neural network coupled with generic algorithm and response surface methodology in modeling and optimization of biodiesel production process parameters from shea tree (Vitellaria paradoxa) nut butter (**Renewable Energy, 2015**) [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0960148114007794)]
* Artificial neural network method modeling of microwave-assisted esterification of PFAD over mesoporous TiO2‒ZnO catalyst (**Renewable Energy, 2022**) [[paper](https://www.sciencedirect.com/science/article/abs/pii/S0960148122001331)]

## Contribution

Contributions to this repository are welcome!

If you find any error or have relevant resources, feel free to open an issue or a pull request.

Paper format:
```
No. paper title (**publisher, published time**) `[[paper]([pdf link])]`
```

## Citations

Please cite the following paper if you find the resource helpful for your research.
```
updated later
```
