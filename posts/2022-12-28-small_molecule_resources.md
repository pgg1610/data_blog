---
aliases:
- /chemical-science/machine-learning/resources/2022/12/28/Computational_drug_discovery
categories:
- chemical-science
- machine-learning
- resources
date: '2024-01-10'
description: Compendium of recent articles, resources, and blogs in the area of medicine discovery
layout: post
title: Medicine drug discovery resources
toc: true
---

Last update: July 2024

## Noteworthy blogs to follow:

**Cheminformatics** 

1. [Patrick Walters Blog on Cheminformatics](https://https://practicalcheminformatics.blogspot.com/)
    * [Cheminformatics Tutorials](https://github.com/PatWalters/practical_cheminformatics_tutorials)
    
2. [Is Life Worth Living](https://iwatobipen.wordpress.com/)

3. [Andrew White's Deep Learning for Molecule and Material](https://whitead.github.io/dmol-book/intro.html) 

4. [Cheminformia](http://www.cheminformania.com)

5. [Depth-First](https://depth-first.com)

**Fragment-based drug dicovery**

1. [Practical Fragments](http://practicalfragments.blogspot.com/) 

**Medicinal chemistry**

1. [Darryl B McConnell's Medchem blogpost](https://mcconnellsmedchem.com/)

2. [Chris Swaim's MedChem blogpost](https://www.cambridgemedchemconsulting.com/resources/)

**Computational chemistry**
1. [Gilles Ouvry](https://www.linkedin.com/in/gilles-ouvry-8b7b2b5/)

**General field**

1. [DrugDiscovery.NET - Andreas Bender](http://www.drugdiscovery.net/2019/07/25/new-post1/)

2. [DrugHunter](https://drughunter.com)

3. [Derek Lowe's In the Pipeline](https://www.science.org/blogs/pipeline)

## Online resources 

* [Andrea Volkmer, TeachOpenCADD: a teaching platform for computer-aided drug design (CADD)](https://github.com/volkamerlab/TeachOpenCADD) 

* [Patrick Walter's Cheminformatics Tutorials](https://github.com/PatWalters/practical_cheminformatics_tutorials)

* [Pat Walters' RSC CICAG Open Source Tools for Chemistry](https://www.macinchem.org/blog/files/fe66130c1da3375e46d0512e483eb901-2791.php?utm_source=pocket_mylist).[Video](https://www.youtube.com/watch?v=2ZjerAGS_IQ). [Github](https://github.com/PatWalters/chem_tutorial)

* [Pen's Python cookbook for Cheminformatics](https://github.com/iwatobipen/py4chemoinformatics)

* [Chem LibreText collection from ACS Division of Chemical Education](https://bit.ly/2SxItoc)

* [RDkit blogpost from Greg Landrum](https://greglandrum.github.io/rdkit-blog/)

* [Jeremy Monat's blogpost](https://bertiewooster.github.io/)

## Books

* [Bajorath, 2011. Chemoinformatics and Computational Chemical Biology. Methods in Molecular Biology.](https://link.springer.com/book/10.1007/978-1-60761-839-3) 

* [Heifetz, Alexander. (Ed.) (2022). "Artificial Intelligence in Drug Design."](https://link.springer.com/book/10.1007/978-1-0716-1787-8)

## Best practices 

* [Bender, Andreas, et al. "Evaluation guidelines for machine learning tools in the chemical sciences." Nature Reviews Chemistry (2022): 1-15.](https://www.nature.com/articles/s41570-022-00391-9). [Temporary SharedIt Link](https://www.nature.com/articles/s41570-022-00391-9.epdf?sharing_token=c7ajAY6RtejsBwo7JKb_EdRgN0jAjWel9jnR3ZoTv0PlqwefS9tuSzOUSTdLlQspcQfdrrg6BP1js7fwhK8sXckoDuc05MIHU8Tf2mCEeVGilKBg5tdIz-htajojgKeP-9SZLLqCDAphBNd8VUtODVWYw0CXTg8CY1uUfyiB8zk%3D)

Nice account outlining guidelines for evaluating different AI/ML methodologies in molecular science. They propose a checklist of tests and best practices to assess the practicality and importance of different methodologies thereby providing a framework on how to evaluate plethora of ML workflows being proposed in different areas of chemical science. The basis for not overlooking the older non-ML method when evaluating the 'new' learning-based method, emphasis on model interpretation to translate the corrleation to chemical causality and finally 

* [Artrith, Nongnuch, et al. "Best practices in machine learning for chemistry." Nature chemistry 13.6 (2021): 505-508.](https://www.nature.com/articles/s41557-021-00716-z)

Set of rules, considerations, and caveats to keep in mind when designing ML model for chemical science. The authors propose a checklist when evaluating ML models, while intuitive at first, when lot of the new ML papers are scanned through that lens, you can identify the shortcommings of the proposed model. This checklist is especially helpful for those entering just entering the field. 

## Pharma R&D Business 

* [Schuhmacher, Alexander, et al. "Analysis of pharma R&D productivity–a new perspective needed." Drug Discovery Today (2023): 103726.](https://www.sciencedirect.com/science/article/pii/S1359644623002428?via%3Dihub)

* [Paul, Steven M., et al. "How to improve R&D productivity: the pharmaceutical industry's grand challenge." Nature reviews Drug discovery 9.3 (2010): 203-214.](https://www.nature.com/articles/nrd3078)

## Overviews and Reviews

* [F. Strieth-Kalthoff, F. Sandfort, M. H. S. Segler, and F. Glorius, Machine learning the ropes: principles, applications and directions in synthetic chemistry, Chem. Soc. Rev](https://pubs.rsc.org/en/content/articlelanding/2020/CS/C9CS00786E#fn1)

Pedagogical account of various machine learning techniques, models, representation schemes from perspective of synthetic chemistry. Covers different applications of machine learning in synthesis planning, property prediction, molecular design, and reactivity prediction

* [Rodríguez-Pérez, Raquel, Filip Miljković, and Jürgen Bajorath. "Machine Learning in Chemoinformatics and Medicinal Chemistry." Annual review of biomedical data science 5 (2022)](https://www.annualreviews.org/doi/abs/10.1146/annurev-biodatasci-122120-124216)

* [Mariia Matveieva & Pavel Polishchuk. Benchmarks for interpretation of QSAR models](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-021-00519-x). [Github](https://github.com/ci-lab-cz/ibenchmark). [Patrick Walter's blog on the paper](https://patwalters.github.io/practicalcheminformatics/jupyter/ml/interpretability/2021/06/03/interpretable.html).

Paper outlining good practices for interpretating QSAR (Quantative Structure-Property Prediction) models. Good set of heuristics and comparison in the paper in terms of model interpretability. Create 6 synthetic datasets with varying complexity for QSAR tasks. The authors compare interpretability of graph-based methods to conventional QSAR methods. In regards to performance graph-based models show low interpretation compared to conventional QSAR method. 

* [W. Patrick Walters & Regina Barzilay. Applications of Deep Learning in Molecule Generation and Molecular Property Prediction](https://pubs.acs.org/doi/full/10.1021/acs.accounts.0c00699)

Recent review summarising the state of the molecular property prediction and structure generation research. In spite of exciting recent advances in the modeling efforts,  there is a need to generate better (realistic)  training data, assess model prediction confidence, and metrics to quantify molecular generation performance. 

* [Navigating through the Maze of Homogeneous Catalyst Design with Machine Learning](https://chemrxiv.org/articles/preprint/Navigating_through_the_Maze_of_Homogeneous_Catalyst_Design_with_Machine_Learning/12786722/1)

* [Coley, C. W. Defining and Exploring Chemical Spaces. Trends in Chemistry 2020](https://doi.org/10.1016/j.trechm.2020.11.004)

* [Machine learning directed drug formulation development](https://www.sciencedirect.com/science/article/pii/S0169409X21001800?via%3Dihub) 

Review from Aspuru-Guzik and Allen's group discussing how ML can be leveraged for various tasks in drug formulation tasks. 

## Commentary 

* [Weaver, Donald F. "Chemists Invent Drugs and Drugs Save Lives." ChemMedChem (2024): e202400074.](https://chemistry-europe.onlinelibrary.wiley.com/doi/10.1002/cmdc.202400074)

* [Will AI turbocharge the hunt for new drugs?](https://www.ft.com/content/3e57ad6c-493d-4874-a663-0cb200d3cdb5)

* [Comment about generative design from Patrick Walters](https://practicalcheminformatics.blogspot.com/2023/02/generative-molecular-design-we-need-to.html)

* [Walters, W. Patrick, and Mark Murcko. "Assessing the impact of generative AI on medicinal chemistry." Nature biotechnology 38.2 (2020): 143-145.](https://www.nature.com/articles/s41587-020-0418-2)

Correspondence on assessing the impact of AI on medicinal chemistry. It is a well written account on practical implication of generative design on pharmaceutical research.They outline two recent cases of 'success' of AI generative design in drug discovery and give more context and propose best practices for furthering the development of algorithms and drug discovery pipelines. 


* [We need better benchmarking for machine learning in drug discovery](https://practicalcheminformatics.blogspot.com/2023/08/we-need-better-benchmarks-for-machine.html)

Very good post outlining the focus on the good practices and lack thereof for consistent datasets for comparing different ML algorithms. 

## Industry-focused drug discovery reviews 

* [Hasselgren, Catrin, and Tudor I. Oprea. "Artificial Intelligence for Drug Discovery: Are We There Yet?." Annual Review of Pharmacology and Toxicology 64 (2024).](https://www.annualreviews.org/doi/10.1146/annurev-pharmtox-040323-040828?url_ver=Z39.88-2003&rfr_id=ori%3Arid%3Acrossref.org&rfr_dat=cr_pub++0pubmed) [ArXiv](https://arxiv.org/abs/2307.06521)

Latest review of the field and application of AI technologies to various functions of drug discovery. In addition to providing a quick review of the main technology the author list different case studies where AI has proposed clinical candidates across different therapeutic areas. Yet, the need for better data, novelty estimation, and validation in wet lab limit the full scale deployment and accuracy of AI pipelines in drug discovery. In closing they also hint at the limitation of ML model training a single property with single structure, QSAR, while in reality the molecule can exist in different conformers something multi-instance learning (MIL) can address. 'It is reasonable to assume that user expertise, bias, and time constraints play a significant role in early drug discovery, often more so than AI.'

* [Jayatunga, Madura KP, et al. "AI in small-molecule drug discovery: A coming wave." Nat. Rev. Drug Discov 21 (2022): 175-176.](https://www.nature.com/articles/d41573-022-00025-1)

* [Abramov, Yuriy A., Guangxu Sun, and Qun Zeng. "Emerging Landscape of Computational Modeling in Pharmaceutical Development." Journal of Chemical Information and Modeling (2022).](https://pubs.acs.org/doi/10.1021/acs.jcim.1c01580)

Overview of methods and scope of computational methods used in the drug development process. 

* [Dragovich, Peter S., et al. "Small-Molecule Lead-Finding Trends across the Roche and Genentech Research Organizations." Journal of Medicinal Chemistry (2022).](https://pubs.acs.org/doi/10.1021/acs.jmedchem.1c02106)

* [A. Bender and I. Cortés-Ciriano, “Artificial intelligence in drug discovery: what is realistic, what are illusions? Part 1: Ways to make an impact, and why we are not there yet,” Drug Discov. Today, vol. 26, no. 2, pp. 511–524, 2021](https://www.sciencedirect.com/science/article/pii/S1359644620305274)

## Special Journal Issues

1. [Data Science Meets Chemistry](https://pubs.acs.org/page/achre4/data-science-meets-chemistry)

This issue includes contributions that demonstrate the profound impact data science techniques have had in chemistry including chemical and materials synthesis, catalyst and materials design, and overhauling the models used in traditional theoretical or computational chemistry. 

2. [Journal of Medicinal Chemistry compendium of AI in Drug discovery issue](https://pubs.acs.org/doi/full/10.1021/acs.jmedchem.0c01077)

3. [Account of Chemical Research Special Issue on advances in data-driven chemistry research](https://pubs.acs.org/page/achre4/data-science-meets-chemistry)

4. [Special Issue on Reaction Informatics and Chemical Space, Journal of Chemical Information and Modeling (2022)](https://pubs.acs.org/toc/jcisd8/62/9)

## Meeting notes 

* [Warr, W. (2021). National Institutes of Health (NIH) Workshop on Reaction Informatics](https://chemrxiv.org/engage/chemrxiv/article-details/611cf1a6ac8b499b36458d19)

* [Warr, W. (2021). Report on an NIH Workshop on Ultralarge Chemistry Databases.](https://chemrxiv.org/engage/chemrxiv/article-details/60c75883bdbb89984ea3ada5)

## Chemical modalities 

* [Blanco, Maria-Jesus, and Kevin M. Gardinier. "New chemical modalities and strategic thinking in early drug discovery." ACS medicinal chemistry letters 11.3 (2020): 228-231.](https://pubs.acs.org/doi/pdf/10.1021/acsmedchemlett.9b00582)

Overview of different chemical modalities currently at work to address different disease targets. The article addresses the small molecule medicinal chemists and how they can expand their outlook of small molecules to include other molecular entities when considering the angle of attack for different target engagement strategies. The authors offer a nice set of tools and thought process when selecting possible drug modalities for different target classes and what questions should be asked when zeroing in a possible mode of action. 

* [Targeted Protein Degradation: Advances, Challenges, and Prospects for Computational Methods](https://pubs.acs.org/doi/10.1021/acs.jcim.3c00603)

## Meta themes on optimizing small molecules 

* [Walters, W. Patrick, and Mark A. Murcko. "Prediction of ‘drug-likeness’." Advanced drug delivery reviews 54.3 (2002): 255-271.](https://www.sciencedirect.com/science/article/abs/pii/S0169409X02000030?via%3Dihub) 

* [Veber, Daniel F., et al. "Molecular properties that influence the oral bioavailability of drug candidates." Journal of medicinal chemistry 45.12 (2002): 2615-2623.](https://pubs.acs.org/doi/10.1021/jm020017n)

Retrospective analysis on factors influencing the bioavailability of drug candidates. Authors find rotatable bonds and polar surface area or hydrogen bond count (sum of donor and accpetors) found to be important predictors of good oral bioavailability. Compounds having <10 rotatable bonds and <140 A (or < 12 hydrogen bonds) have good chances of being orally bioavailable. 

* [DeGoey, David A., et al. "Beyond the rule of 5: lessons learned from AbbVie’s drugs and compound collection: miniperspective." Journal of Medicinal Chemistry 61.7 (2017): 2636-2651.](https://pubs.acs.org/doi/10.1021/acs.jmedchem.7b00717)

AB-MPS calculated using cLogD, the number of aromatic rings (nAr), and the number of rotatable bonds (nRotB) according to the formula AB-MPS = Abs(cLogD −3) + nAr + nRotB. The lower the AB-MPS score, the more likely the compound is to be absorbed, and a value of ≤14 is reported to predict a higher probability of oral absorption.

* [Poongavanam, Vasanthanathan, Bradley C. Doak, and Jan Kihlberg. "Opportunities and guidelines for discovery of orally absorbed drugs in beyond rule of 5 space." Current Opinion in Chemical Biology 44 (2018): 23-29.](https://www.sciencedirect.com/science/article/pii/S1367593118300176#bib0030)

Hueristics for oral bioavailability of molecules that are violating the rule of 5. MW may reach up to approximately 1000 Da provided that TPSA increases proportionally up to 250 Å2. In contrast, cLogP and HBDs must be carefully controlled at high MW. Our lack of ability to predict compound conformations and flexibility is currently a hurdle that is critical to overcome to enable further prospective design in oral bRo5 space.

* [Taylor, R. D.; MacCoss, M.; Lawson, A. D. G. Rings in Drugs. J. Med. Chem. 2014, 57 (14), 5845–5859.](https://doi.org/10.1021/jm4017625)

* [Subbaiah, Murugaiah AM, and Nicholas A. Meanwell. "Bioisosteres of the phenyl ring: Recent strategic applications in lead optimization and drug design." Journal of Medicinal Chemistry 64.19 (2021): 14046-14128.](https://pubs.acs.org/doi/10.1021/acs.jmedchem.1c01215)

Looks at biosteric replacements for the phenyl rings in the lead optimization phase. Phenyl rings results in improve potency but have poor solubility and lipophilicitty. Find biosteres can be used to improve them.

* [Ertl, Peter. "Magic Rings: Navigation in the Ring Chemical Space Guided by the Bioactive Rings." Journal of Chemical Information and Modeling (2021).](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00761)

Analyze the nature of rings which appear in bioactive compounds. Ring systems are systematically extracted from one billion molecules and are analyzed to discover a structure or correlation in the bioactivity and type of rings.  No simple set of structural descriptors separating active and inactive rings could be identified, the separation is best described by a neural network model taking into account a complex combination of many substructure features.

* [Hartung, Ingo V., Bayard R. Huck, and Alejandro Crespo. "Rules were made to be broken." Nature Reviews Chemistry 7.1 (2023): 3-4.](https://www.nature.com/articles/s41570-022-00451-0)

Longitudinal analysis of physico-chemical properties for approved drugs in the clinic. They show that most of the drugs flout most of the Lipinski's rule of 5 except the HBD which is always consistently less 4. In addition, they show that in recent times, by categorizing the drugs in different time-bound classes, the mean MW and HBA has increased but mean HBD has constantly stayed less than 2. 

* [Young, Robert J., et al. "The time and place for nature in drug discovery." Jacs Au 2.11 (2022): 2400-2416.](https://pubs.acs.org/doi/10.1021/jacsau.2c00415)

Critique on the paper, [interesting take](https://fbdd-lit.blogspot.com/2024/05/a-time-and-place-for-nature-in-drug.html)

* [Property-Based Drug Design Merits a Nobel Prize](https://pubs.acs.org/doi/10.1021/acs.jmedchem.4c01345?ref=pdf)

Probably contentious topic but a good short review of the property-based optimization thought process for medicine discovery. 

* [Pennington, Lewis D., and Demetri T. Moustakas. "The necessary nitrogen atom: a versatile high-impact design element for multiparameter optimization." Journal of Medicinal Chemistry 60.9 (2017): 3552-3579.](https://pubs.acs.org/doi/10.1021/acs.jmedchem.6b01807)

Good perspective highlighting the impact of replacing CH group with N in aromatic and heteraromatic ring systems on molecular and physiochemical properties that translate to improved pharmacological properties. 


## Synthesis Chemistry 

Catalog of recent research articles that look at synthesis chemistry from a point of view of computational workflows, how traditional synthetic chemistry methods can be combined with informatics to augment drug discovery and synthesis processes. 

* [Ruck, Rebecca T., Neil A. Strotman, and Shane W. Krska. "The Catalysis Laboratory at Merck: 20 Years of Catalyzing Innovation." ACS Catalysis 13 (2022): 475-503.](https://pubs.acs.org/doi/10.1021/acscatal.2c05159#.Y6oIfVMoYEs)

* [Dreher, Spencer D., and Shane W. Krska. "Chemistry informer libraries: Conception, early experience, and role in the future of cheminformatics." Accounts of Chemical Research 54.7 (2021): 1586-1596.](https://pubs.acs.org/doi/10.1021/acs.accounts.0c00760)

Curated set of substrates to quickly assess the practicality of synthetic methods with the complete capture of success and failure, that can optimize reaction conditions with a broader scope with respect to relevant applications.

* [Campos, Kevin R., et al. "The importance of synthetic chemistry in the pharmaceutical industry." Science 363.6424 (2019): eaat0805.](https://www.science.org/doi/pdf/10.1126/science.aat0805)

* [Late-stage diversification of indole skeletons through nitrogen atom insertion](https://www.science.org/doi/10.1126/science.add1383)

## Large chemical libraries

Over the past few years several entites offering ultra-large ensembles of chemical libraries which can be made on-demand or purchased immediately have emerged. The existence of such services has reinvigorated the field of virtual screening and combinatorial library design. In addition, research groups have devised novel ways to navigate these libraries, more efficiently and also understand the differences in the chemical space these library cover. Following are some of the key papers in the field. 

* [Warr, W. (2021). Report on an NIH Workshop on Ultralarge Chemistry Databases.](https://chemrxiv.org/engage/chemrxiv/article-details/60c75883bdbb89984ea3ada5)

* [Warr, Wendy A., et al. "Exploration of ultralarge compound collections for drug discovery." Journal of Chemical Information and Modeling 62.9 (2022): 2021-2034.](https://pubs.acs.org/doi/10.1021/acs.jcim.2c00224)

* [The next level in chemical space navigation: going far beyond enumerable compound libraries](https://www.sciencedirect.com/science/article/pii/S1359644618304471)

* [Bellmann, Louis, et al. "Comparison of combinatorial fragment spaces and its application to ultralarge make-on-demand compound catalogs." Journal of Chemical Information and Modeling 62.3 (2022): 553-566.](https://pubs.acs.org/doi/full/10.1021/acs.jcim.1c01378?casa_token=Lo0YQQrtkcAAAAAA%3AhKiuAJ0GpAhXiNC-2cVO6Ixv0aCnf0J7mrr03mOxpCgH8OpVhaCnDxAkHPNvfm36VsDl8NxvtzusqQ)

SpaceCompare: calculation of the overlap of large, nonenumerable combinatorial fragment spaces, utilizes topological fingerprints and the combinatorial character of these chemical spaces. Enamine’s REAL Space, WuXi’s GalaXi Space, and Otava’s CHEMriya. The overlap of the commercial make-on-demand catalogs is only in the low single-digit percent range, despite their large overall size.

* [Konze, Kyle D., et al. "Reaction-based enumeration, active learning, and free energy calculations to rapidly explore synthetically tractable chemical space and optimize potency of cyclin-dependent kinase 2 inhibitors." Journal of chemical information and modeling 59.9 (2019): 3782-3793.](https://pubs.acs.org/doi/10.1021/acs.jcim.9b00367)

PathFinder uses retrosynthetic analysis followed by combinatorial synthesis to generate novel compounds in synthetically accessible chemical space.

* [Irwin, John J., et al. "ZINC20—a free ultralarge-scale chemical database for ligand discovery." Journal of chemical information and modeling 60.12 (2020): 6065-6073.](https://pubs.acs.org/doi/10.1021/acs.jcim.0c00675)

New version of ZINC with two major new features: billions of new molecules and new methods to search them. As a fully enumerated database, ZINC can be searched precisely using explicit atomic-level graph-based methods. Over 97% of the core Bemis–Murcko scaffolds in make-on-demand libraries are unavailable from “in-stock” collections. Correspondingly, the number of new Bemis–Murcko scaffolds is rising almost as a linear fraction of the elaborated molecules. Thus, an 88-fold increase in the number of molecules in the make-on-demand versus the in-stock sets is built upon a 16-fold increase in the number of Bemis–Murcko scaffolds. The make-on-demand library is also more structurally diverse than physical libraries

* [Neumann, Alexander, Lester Marrison, and Raphael Klein. "Relevance of the Trillion-Sized Chemical Space “eXplore” as a Source for Drug Discovery." ACS Medicinal Chemistry Letters (2023).](https://pubs.acs.org/doi/10.1021/acsmedchemlett.3c00021)

The authors examine the composition of the recently published and, so far, biggest chemical space, “eXplore”, which comprises approximately 2.8 trillion virtual product molecules. The utility of eXplore to retrieve interesting chemistry around approved drugs and common Bemis Murcko scaffolds has been assessed with several methods (FTrees, SpaceLight, SpaceMACS). Further, the overlap between several vendor chemical spaces and a physicochemical property distribution analysis has been performed. Despite the straightforward chemical reactions underlying its setup, eXplore is demonstrated to provide relevant and, most importantly, easily accessible molecules for drug discovery campaigns.

* [Medina, Jorge, and Andrew D. White. "Bloom filters for molecules." arXiv preprint arXiv:2304.05386 (2023).](https://arxiv.org/pdf/2304.05386.pdf)

This paper proposes and studies Bloom filters for testing if a molecule is present in a set using either string or fingerprint representations. Bloom filters are small enough to hold billions of molecules in just a few GB of memory and check membership in sub-milliseconds. The authors found string representations can have a false positive rate below 1% and require significantly less storage than using fingerprints. Canonical SMILES with Bloom filters with the simple FNV hashing function provide fast and accurate membership tests with small memory requirements. They provide a general implementation and specific filters for detecting if a molecule is purchasable, patented, or a natural product according to existing databases at https://github.com/whitead/molbloom.

## Virtual screeening

* [Dodds, Michael, et al. "Sample efficient reinforcement learning with active learning for molecular design." Chemical Science 15.11 (2024): 4146.](https://pubs.rsc.org/en/content/articlelanding/2024/sc/d3sc04653b)

An active learning system linked with an RL model (RL–AL) for molecular design, which aims to improve the sample-efficiency of the optimization process.

AZ group looking at generative design + RL + Virtual screening campaign 

* [Vakili, Mohammad Ghazi, et al. "Quantum Computing-Enhanced Algorithm Unveils Novel Inhibitors for KRAS." arXiv preprint arXiv:2402.08210 (2024).](https://arxiv.org/pdf/2402.08210.pdf)

First paper to showcase deployment of quantum-based generative models with virtual screening workflow on a target-based compound discovery. Chemistry42 is used for reward function implementation. The authors show that molecule generated from this combined effort are 'better' quality-wise than traditional workflow (LSTM and Genetic algorithm) and the modeling success downstream is roughly correlated with number of qubits employed. This is exciting more from technical standpoint of combining quantum + traditional workflows. 

* [Sadybekov, Anastasiia V., and Vsevolod Katritch. "Computational approaches streamlining drug discovery." Nature 616.7958 (2023): 673-685.](https://www.nature.com/articles/s41586-023-05905-z)

Nice review on virtual screening workflow for streamlining drug discovery 

* [Gorgulla, Christoph, et al. "An open-source drug discovery platform enables ultra-large virtual screens." Nature 580.7805 (2020): 663-668.](https://www.nature.com/articles/s41586-020-2117-z)

VirtualFlow as a tool for conducting virtual screening. The authors use VirtualFlow, to prepare one of the largest and freely available ready-to-dock ligand libraries, with more than 1.4 billion commercially available molecules. They screening ~1 billion compounds and identified a set of structurally diverse molecules that bind to KEAP1 with submicromolar affinity.

* [Deep Learning Strategies for Enhanced Molecular Docking and Virtual Screening](https://chemrxiv.org/engage/chemrxiv/article-details/654a339b48dad2312043870c)

* [A practical guide to machine-learning scoring for structure-based virtual screening](https://www.nature.com/articles/s41596-023-00885-w)

* [Keeping pace with the explosive growth of chemical libraries with structure-based virtual screening](https://wires.onlinelibrary.wiley.com/doi/10.1002/wcms.1678)

* [Lyu, Jiankun, et al. "Ultra-large library docking for discovering new chemotypes." Nature 566.7743 (2019): 224-229.](https://www.nature.com/articles/s41586-019-0917-9)

Researchers at UCSF looking at large scale docking for making ultra-large libraries accessible. They dock 170 million make-on-demand compounds from 130 well characterized reactions. Found new chemotypes that have interaction with 2 targets. 

## Fragment-based drug discovery 

**What is a fragment?**

In fragment-based drug discovery (FBDD), a fragment is a small, low-molecular-weight chemical entity typically ranging from 120-250 Daltons, with properties such as cLogP < 2.5, hydrogen atom count (HAC) of 9-18, hydrogen bond acceptors (HBA) < 7, and hydrogen bond donors (HBD) < 4, as specified by Asinex. These fragments serve as starting points for drug development. They bind to target proteins with low affinity but high efficiency, enabling the identification of key interactions. By optimizing and linking fragments, researchers can develop potent lead compounds, enhancing the efficiency of the drug discovery process and improving hit finding.

**Known collection**

* [Cambridge Chem Consulting](https://www.cambridgemedchemconsulting.com/resources/hit_identification/fragment_collections.html)
* [Evotec](https://www.evotec.com/en/investor-relations/news/p/evotec-enhances-its-fragment-based-drug-discovery-business-by-the-addition-of-nmr-screening-assets-from-combinature-4496)
* [Diamond light source](https://www.diamond.ac.uk/Instruments/Mx/Fragment-Screening/Fragment-Libraries.html)

**Blogs**

* [Practical Fragment blog](https://practicalfragments.blogspot.com/2024/03/fragments-2024.html)

**Book Chapters**

* [Rees, D. C.; Congreve, M.; Murray, C. W.; Carr, R. Fragment-Based Lead Discovery. Nat Rev Drug Discov 2004, 3 (8), 660–672](https://doi.org/10.1038/nrd1467)

The paper by Rees, D. C.; Congreve, M.; Murray, C. W.; Carr, R. discusses the concept of fragment-based lead discovery in drug development. The authors highlight the challenges in the drug discovery pipeline, particularly the 'target-rich, lead-poor' issue and the high attrition rate of chemical compounds in preclinical development. They discuss the use of fragment-based approaches as a solution, which involves the selection, screening, and optimization of fragments (also referred to as needles, shapes, binding elements, or seed templates) for lead identification. This approach requires significantly fewer compounds to be screened and synthesized, and has a high success rate in generating chemical series with lead-like properties. The authors also discuss different strategies for developing fragments into high-affinity leads, such as fragment evolution and fragment linking. The paper includes examples from 25 different protein targets to illustrate these strategies.

**Articles**

* [Fragmenstein: predicting protein-ligand structures of compounds derived from known crystallographic fragment hits using a strict conserved-binding–based methodology](https://chemrxiv.org/engage/chemrxiv/article-details/65d751ab9138d23161b7ea38)

* [Zhang, Yueqing, et al. "FragGrow: A Web Server for Structure-Based Drug Design by Fragment Growing within Constraints." Journal of Chemical Information and Modeling (2024).](https://pubs.acs.org/doi/10.1021/acs.jcim.4c00154)

* [Cree, Ben, et al. "Active learning driven prioritisation of compounds from on-demand libraries targeting the SARS-CoV-2 main protease." (2024).](https://chemrxiv.org/engage/chemrxiv/article-details/667699175101a2ffa837f110)[FEGrow Github](https://github.com/cole-group/FEgrow/)

* [Igashov, Ilia, et al. "Equivariant 3D-conditional diffusion model for molecular linker design." Nature Machine Intelligence (2024): 1-11.](https://www.nature.com/articles/s42256-024-00815-9) [Pen's blog](https://iwatobipen.wordpress.com/2024/04/24/generate-new-molecules-from-fragments-with-diffusion-model-cheminformatics-rdkit-difflinker-memo/)

* [Penner, Patrick, et al. "FastGrow: on-the-fly growing and its application to DYRK1A." Journal of Computer-Aided Molecular Design 36.9 (2022): 639-651.](https://pubmed.ncbi.nlm.nih.gov/35989379/) [Pen's blog](https://practicalfragments.blogspot.com/2022/09/growing-fragments-in-silico-with.html)

* [Boby, M. L. Open Science Discovery of Potent Noncovalent SARS-CoV-2 Main Protease Inhibitors. Science 2023, 382 (6671)](https://doi.org/10.1126/science.abo7201)

* [Müller, Janis, et al. "Magnet for the needle in haystack:“crystal structure first” fragment hits unlock active chemical matter using targeted exploration of vast chemical spaces." Journal of Medicinal Chemistry 65.23 (2022): 15663-15678.](https://pubs.acs.org/doi/10.1021/acs.jmedchem.2c00813). [Blog](https://www.science.org/content/blog-post/crystal-fragments?utm_source=pocket_mylist)

The authors use a fragment screening approach to look at hits for protein kinase target and instead of using biophysical assay in fragment screening use crystallographic data directly to learn the conformation of the fragments. They find 4 ‘seed’ substructures which fit nicely in the protein(not affinity) and use those to inform the latter expansion which is done through the Enamine REAL dataset and known reaction classes. What I liked the most and found interesting is the high throughput binding pose and docking workflow of 200k compounds, the large scale crystallographic fragment hit analysis, and the focused curated library generation using Enamine REAL dataset. I was curious to know what seasoned experts had to say about this.

* [BROOD](https://www.eyesopen.com/brood)

Commercial software solution from OpenEye for fragment exchange 

## Protein engineering 

* [PeSTo: parameter-free geometric deep learning for accurate prediction of protein binding interfaces](https://www.nature.com/articles/s41467-023-37701-8)


## Protein-ligand interactions 

* [Yim, Jason, et al. "Diffusion models in protein structure and docking." Wiley Interdisciplinary Reviews: Computational Molecular Science 14.2 (2024): e1711.](https://wires.onlinelibrary.wiley.com/doi/10.1002/wcms.1711)

Nice review of the field that looks at computational model to predict protein-ligand interaction and molecular docking. In recent times, diffusion-based model have shown promising performance. This review documents the current state of the field and next steps. This survey covers DMs primarily from the point of view of backbone generation, both unconditional and conditional generation. It is interesting to see how modeling the backbone, sequence, and side chains would bring further benefit beyond the current strategy of modeling them one after the other. 

* [DiffDock](https://arxiv.org/abs/2210.01776)

* [NeuralPlexer](https://www.nature.com/articles/s42256-024-00792-z)

Iambic Therapeutics’ AI model that predicts the combined shape of proteins and small molecules outperforms Google DeepMind’s AlphaFold. Lambic’s newest model, called NeuralPLexer2, had a 75% success rate in predicting these protein-ligand structures. AlphaFold’s latest version, as described last October in a blog post, was 74% successful. But Iambic’s model jumps to a 93% success rate when the model receives additional info on amino acids near the small molecule.

* [RFdiffusion All-Atom](https://www.science.org/doi/10.1126/science.adl2528) [Github](https://github.com/baker-laboratory/rf_diffusion_all_atom)

RoseTTAFold All-Atom (RFAA) was trained to represent amino acids and DNA bases at the residue level and all other chemical groups at the atomic level, allowing it to accurately model proteins and the other chemicals they so often interact with.

RFdiffusion All-Atom: build bespoke protein structures around small molecules. The team designed and experimentally validated, through crystallography and binding measurements, proteins that bind the cardiac disease therapeutic digoxigenin, the enzymatic cofactor heme, and the light-harvesting molecule bilin.
Although there is still room for improvement in prediction accuracy, we anticipate that RFAA should be broadly useful for modeling full biological assemblies and RFdiffusionAA for designing small molecule–binding proteins and sensors.

* [DynamicBind](https://www.nature.com/articles/s41467-024-45461-2)

DynamicBind, a deep learning method that employs equivariant geometric diffusion networks to construct a smooth energy landscape, promoting efficient transitions between different equilibrium states. DynamicBind accurately recovers ligand-specific conformations from unbound protein structures without the need for holo-structures or extensive sampling.

* [Yu, Jie, et al. "Computing the relative binding affinity of ligands based on a pairwise binding comparison network." Nature Computational Science 3.10 (2023): 860-872.](https://www.nature.com/articles/s43588-023-00529-9?#Sec13)

### Conformer generators

* [McNutt, Andrew T., et al. "Conformer Generation for Structure-Based Drug Design: How Many and How Good?." Journal of Chemical Information and Modeling (2023).](https://pubs.acs.org/doi/10.1021/acs.jcim.3c01245)

* [Wang, Zhe, et al. "Small-Molecule Conformer Generators: Evaluation of Traditional Methods and AI Models on High-Quality Data Sets." Journal of Chemical Information and Modeling (2023).](https://pubs.acs.org/doi/10.1021/acs.jcim.3c01519)

* [Zhu, Yanqiao, et al. "Learning Over Molecular Conformer Ensembles: Datasets and Benchmarks." arXiv preprint arXiv:2310.00115 (2023).](https://arxiv.org/pdf/2310.00115.pdf)

**Structure Quality Assessment**

* [Buttenschoen, Martin, Garrett M. Morris, and Charlotte M. Deane. "PoseBusters: AI-based docking methods fail to generate physically valid poses or generalise to novel sequences." arXiv preprint arXiv:2308.05777 (2023).](https://arxiv.org/abs/2308.05777)

Python package for evaluating the quality of docked poses. PoseBusters performs a series of geometry checks on docked poses and also evaluates intra and inter-molecular interactions.  The authors used the Astex Diverse Set and a newly developed PoseBusters benchmark set to evaluate five popular deep learning docking programs and two conventional docking approaches.  The conventional docking programs dramatically outperformed the deep learning methods on both datasets.  In most cases, more than half of the solutions generated by the DL docking programs failed the PoseBusters validity tests.  In contrast, with the conventional docking programs, only 2-3% of the docked poses failed to validate. 

* [Morehead, Alex, et al. "Deep Learning for Protein-Ligand Docking: Are We There Yet?." arXiv preprint arXiv:2405.14108 (2024)](https://arxiv.org/abs/2405.14108)[Github](https://github.com/BioinfoMachineLearning/PoseBench)

Suite of tools and workflow to benchmark Deep learning method's ability to predict protein-ligand interaction modeling - from apo to halo configuration for P/L pairs. The authors find that all but one DL method fail to generalize to multi-ligand protein targets. 


[Benchmarking Generated Poses: How Rational is Structure-based Drug Design with Generative Models](https://arxiv.org/abs/2308.07413)

PoseCheck evaluates steric clashes, ligand strain energy, and intramolecular interactions to identify problematic structures.  In addition, structures are redocked with AutoDock Vina to confirm the validity of the proposed binding mode.  In evaluating several recently published generative models, the authors identify failure modes that will hopefully influence future work on structure-based generative design. 

### Binding energetic prediction 

* [Warren, M., Deane, C., Magarkar, A., Morris, G., & Biggin, P. (2024). How to make machine learning scoring functions competitive with FEP.](https://chemrxiv.org/engage/chemrxiv/article-details/6675a38d5101a2ffa8274f62)

Current SOTA model fail in out of distribution datasets implying overfitting or memorization of ligand-specific features. This paper introduces AEV-PLIG, atomic environment vector with protein-ligand interaction  graphs. They propose new benchmark metrics and data augmentation strategies.A multi-head attention graph NN is trained with the node features of the P-L interaction. They report comparable performance to FEP+ on standard benchmarks.  

* [Koh, Huan Yee, et al. "Physicochemical graph neural network for learning protein–ligand interaction fingerprints from sequence data." Nature Machine Intelligence (2024): 1-15.](https://www.nature.com/articles/s42256-024-00847-1). [Github](https://github.com/huankoh/PSICHIC)

PSICHIC (PhySIcoCHemICal graph neural network), a framework incorporating physicochemical constraints to decode interaction fingerprints directly from sequence data alone.

* [Janela, Tiago, and Jürgen Bajorath. "Rationalizing general limitations in assessing and comparing methods for compound potency prediction." Scientific Reports 13.1 (2023): 17816.](https://www.nature.com/articles/s41598-023-45086-3)

* [Efficient prediction of relative ligand binding affinity in drug discovery. Nat Comput Sci 3, 829–830 (2023). https://doi.org/10.1038/s43588-023-00531-1](https://www.nature.com/articles/s43588-023-00531-1)

* [Xu, Huafeng. "The slow but steady rise of binding free energy calculations in drug discovery." Journal of Computer-Aided Molecular Design (2022): 1-8.](https://link.springer.com/article/10.1007/s10822-022-00494-x)

* [Thompson, James, et al. "Optimizing active learning for free energy calculations." Artificial Intelligence in the Life Sciences 2 (2022): 100050.](https://www.sciencedirect.com/science/article/pii/S2667318522000204)

## Molecular-dynamics 

* [MDANCE](https://mdance.readthedocs.io/en/latest/about.html)

Molecular Dynamics Analysis with N-ary Clustering Ensembles (MDANCE) is a flexible n-ary clustering package that provides a set of tools for clustering Molecular Dynamics trajectories. 


## Cheminformatics-focus

Catalog of recent reviews and manuscripts I have found useful when learning more about the state-of-the-art in Cheminformatics. I've tried to categorize them roughly based on their area of application: 

### Representation

Small molecules to be understood by computers and used for model training have to represented in a form amenable for optimization. In addition, this form of abstraction much capture appropriate level of chemical properties so as to imbue the data-driven models with necessary chemistry and physics for modeling. A lot of times different properties of the molecules are 'lost in translation' or obfuscated when converting them into machine-ready forms. Formerly the process of converting molecules from one form to another is called featurization. There are different forms, methods, theories to encode the molecules. Broadly there are as follows: 
* Fingerprints
* Descriptors
* Pharmacophores 
* Graph-based 
* Natural language-based 
* Shape-based 

**Reviews**

* [From intuition to AI: evolution of small molecule representations in drug discovery](https://academic.oup.com/bib/article/25/1/bbad422/7455245)

* [Representation of Molecules in NN: Molecular representation in AI-driven drug discovery: review and guide](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00460-5)


**Articles** 

* [Boulougouri, Maria, Pierre Vandergheynst, and Daniel Probst. "Molecular set representation learning." (2023).](https://chemrxiv.org/engage/chemrxiv/article-details/6525acea45aaa5fdbbb87ac2?utm_source=pocket_saves)

The authors propose a new way to represent molecules, not as chemical bonds, but rather set representations. They show the set representation scheme can be alternative to SOTA graph-models and performs at par to the predictive tasks such as reaction yields and protein-ligand affinities.  

* [M. Krenn, F. Hase, A. Nigam, P. Friederich, and A. Aspuru-Guzik, “Self-Referencing Embedded Strings (SELFIES): A 100% robust molecular string representation,” Mach. Learn. Sci. Technol., pp. 1–9, 2020](https://arxiv.org/abs/1905.13741)

* [Could graph neural networks learn better molecular representation for drug discovery? A comparison study of descriptor-based and graph-based models](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00479-8)

Comparative study of descriptor-based and graph-based models using public data set. Used descriptor-based models (XGBoost, RF, SVM, using ECFP) and compared them to graph-based models (GCN, GAT, AttentiveFP, MPNN). They show descriptor-based models outperform the graph-based models in terms of prediction accuracy and computational efficiency with SVM having best predictions. Graph-based methods are good for multi-task learning. 

* [He, Jiazhen, et al. "Molecular optimization by capturing chemist’s intuition using deep neural networks." Journal of cheminformatics 13.1 (2021): 1-17.](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-021-00497-0)

**Descriptor generation**

* [Morfeus](https://github.com/digital-chemistry-laboratory/morfeus)
Machine learning focused descriptors for small molecules with emphasis on 3D information. 

* [Mordred](https://github.com/mordred-descriptor/mordred)

* [MolFeat](https://molfeat.datamol.io/featurizers)

* [DeepChem](https://deepchem.readthedocs.io/en/latest/api_reference/featurizers.html)

* [PMapper](https://github.com/DrrDom/pmapper)

Pmapper is a Python module to generate 3D pharmacophore signatures and fingerprints. Signatures uniquely encode 3D pharmacophores with hashes suitable for fast identification of identical pharmacophores.

* [SteriMol](https://pubs.acs.org/doi/10.1021/acscatal.8b04043)

Generate conformationally sampled descriptors for a molecule. This workflow provides Boltzmann-averaged Sterimol parameters. These descriptors might be useful for problems where spatial orientation inform the selectivity or properties being trained for. [Github](https://github.com/bobbypaton/wSterimol)

### Predictive modeling 

**Reviews**

* [Chemical complexity challenge: Is multi-instance machine learning a solution](https://wires.onlinelibrary.wiley.com/doi/10.1002/wcms.1698)

Traditional ML uses the relationship between a single instance (a chemical structure) and a single label (a property). It doesn’t provide a facility for mapping multiple instances (an ensemble of conformers) to a label. There has recently been renewed interest in multiple instance learning (MIL), a technique developed over 30 years ago. MIL provides a framework that enables the mapping of conformational ensembles to properties. A recent review by Zankov from Hokkaido University and coworkers at other institutions provides an excellent overview of the challenges and opportunities associated with MIL in QSAR, genomics, and several other areas. The paper also provides links to several software packages for building MIL models.

* [Current Methods for Drug Property Prediction in the Real World](https://arxiv.org/abs/2309.17161)

Overview of the field and some factors that complicate current benchmarking efforts.  The authors compared several molecular representations and ML algorithms in evaluating model accuracy and uncertainty.  These evaluations highlighted the strengths of different QSAR modeling and ADME prediction methods.  Consistent with other papers published in 2023, 2D descriptors performed best for ADME prediction, while Gaussian Process Regression with fingerprints was the method of choice when predicting biological activity. 

* [Rationalizing general limitations in assessing and comparing methods for compound potency prediction](https://www.nature.com/articles/s41598-023-45086-3)

A paper by Janela and Bajorath outlines several limitations in current benchmarking strategies.  The authors used sound statistical methodologies to examine the impact of compound potency value distributions on performance metrics associated with regression models.  They found that across several different ML algorithms, there was a consistent relationship between model performance and the activity range of the dataset.  These findings enabled the authors to define bounds for prediction accuracy. The method used in this paper should be informative to those designing future benchmarks. 

* [Yang, K., Swanson, K., Jin, W., Coley, C., Eiden, P., Gao, H., Guzman-Perez, A., Hopper, T., Kelley, B., Mathea, M. and Palmer, A., 2019. Analyzing learned molecular representations for property prediction. Journal of chemical information and modeling, 59(8), pp.3370-3388](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.9b00237)

Benchmark property prediction models on 19 public and 16 proprietary industrial data sets spanning a wide variety of chemical end points. Introduce a modeling framework (__Chemprop__) that consistently matches or outperforms models using fixed molecular descriptors as well as previous graph neural architectures on both public and proprietary data sets.

* [Stuyver, T. and Coley, C.W., 2021. Quantum chemistry-augmented neural networks for reactivity prediction: Performance, generalizability and interpretability. arXiv preprint arXiv:2107.10402](https://arxiv.org/abs/2107.10402)

Combine structure (Graph-networks) and descriptor based features (QM-derived) to predict activation energies (E<sub>2</sub>/SN<sub>2</sub> barrier height prediction) and regioselectivity. Incorporating QM and structure leads to better overall accuracy and generalizability even in low data regions. Atom and bond level features derived using QM and used in the model generation with a smaller dataset.

**pKa prediction**

* [Abarbanel, Omri, and Geoffrey Hutchison. "QupKake: Integrating Machine Learning and Quantum Chemistry for micro-pKa Predictions." (2023).](https://pubs.acs.org/doi/10.1021/acs.jctc.4c00328). [Github](https://github.com/hutchisonlab/QupKake)

QupKake combines GFN2-xTB calculations with graph-neural-networks to accurately predict micro-pKa values of organic molecules. 

**Hydrogen bond energy**

* [Jazzy: Fast calculation of hydrogen-bond strengths and free energy of hydration of small molecules](https://www.nature.com/articles/s41598-023-30089-x)


## Pharmacophore / shape searching 

* [Rianjongdee, Francesco, et al. "bbSelect–An Open-Source Tool for Performing a 3D Pharmacophore-Driven Diverse Selection of R-Groups." Journal of Chemical Information and Modeling (2024).](https://pubs.acs.org/doi/10.1021/acs.jcim.4c00453). [Pen's blog](https://iwatobipen.wordpress.com/2024/06/25/new-approach-for-selecting-builidng-blocks-from-reagent-set-rdkit-memo-cheminformatics/)

* [PheSA: An Open-Source Tool for Pharmacophore-Enhanced Shape Alignment](https://pubs.acs.org/doi/10.1021/acs.jcim.4c00516)

PheSA is a CPU bound algorithmic improvement over ROCS shape/color alignment that gives you an option to incorporate binding site knowledge.

* [ShaEP](https://users.abo.fi/mivainio/shaep/download.php)

* [Roshambo](https://github.com/molecularinformatics/roshambo)

ROSHAMBO is a GPU accelerated implementation of ROCS


### QSAR benchmarks 

* [Llompart, P., et al. "Will we ever be able to accurately predict solubility?" Scientific Data 11.1 (2024): 303.](https://www.nature.com/articles/s41597-024-03105-6)

The paper discusses challenges in predicting thermodynamic solubility with machine learning. It reviews historical data, analyzes solubility datasets, and assesses model reliability. The authors propose a workflow for data curation and present new models and quality-assessed datasets for public use.

* [Multi-task ADME/PK Prediction at Industrial Scale: Leveraging Large and Diverse Experimental Datasets](https://chemrxiv.org/engage/chemrxiv/article-details/659d3878e9ebbb4db9c3088f)

* [Deng, Jianyuan, et al. "A systematic study of key elements underlying molecular property prediction." Nature Communications 14.1 (2023): 6395.](https://www.nature.com/articles/s41467-023-41948-6)

Deng and coworkers from Stony Brook University compared many popular ML algorithms and representations, curated new datasets, and performed statistical analysis on the results. This paper provides one of the best comparisons of ML methods published to date. The authors compare fixed representations, such as molecular fingerprints, with representations learned from SMILES strings and molecular graphs and conclude that, in most cases, the fixed representations provide the best performance.  Another interesting aspect of this paper was an attempt to establish a relationship between dataset size and the performance of different molecular representations.  While fixed representations performed well on smaller datasets, learned representations didn’t become competitive until between 6K and 100K datapoints were available. 

* [Fang, Cheng, et al. "Prospective Validation of Machine Learning Algorithms for Absorption, Distribution, Metabolism, and Excretion Prediction: An Industrial Perspective." Journal of Chemical Information and Modeling (2023).](https://pubs.acs.org/doi/10.1021/acs.jcim.3c00160)

A paper from Fang and coworkers at Biogen introduced several new ADME datasets. Unlike most literature benchmarks, which contain data collected from dozens of papers, these experiments were consistently performed by the same people in the same lab.  The authors provided prospective comparisons of several widely used ML methods, including random forest, SVM, XGBoost, LightGBM, and message-passing neural networks (MPNNs) on several relevant endpoints, including aqueous solubility, metabolic stability, membrane permeability, and plasma protein binding. 

* [Beckers, Maximilian, et al. "Prediction of Small-Molecule Developability Using Large-Scale In Silico ADMET Models." Journal of Medicinal Chemistry (2023).](https://pubs.acs.org/doi/10.1021/acs.jmedchem.3c01083)

The paper presents a novel deep learning approach to predict the developability of small molecules based on their predicted ADMET properties. The authors use a large-scale data set of compounds from the Novartis pipeline and train a neural network to rank compounds according to their potential to progress beyond in vivo PK studies. The resulting score, called bPK, outperforms other compound scoring methods and shows strong generalization ability on public data. The authors demonstrate the usefulness of bPK for series prioritization and optimization in drug discovery projects.

* [D van Tilborg, Derek, Alisa Alenicheva, and Francesca Grisoni. "Exposing the limitations of molecular machine learning with activity cliffs." Journal of Chemical Information and Modeling 62.23 (2022): 5938-5951.](https://pubs.acs.org/doi/10.1021/acs.jcim.2c01073)

Account on how to treat and analyze activity cliffs in context of developing a predictive model. The authors outline best practices to probe activity cliffs. They show, using 24 DL and ML models and 30 targets, ML approaches based on molecular descriptors outperformed more complex deep learning methods. Activity cliff pairs were defined on similarity of the molecule SMILES and the bioactivity difference.  Compared to most traditional machine learning approaches, deep neural networks seem to fall short at picking up subtle structural differences (and the corresponding property change) that give rise to activity cliffs.

* [Large-scale comparison of  machine learning methods for drug target prediction on ChEMBL - Chemical Science (RSC Publishing)](https://pubs.rsc.org/en/content/articlelanding/2018/sc/c8sc00148k)

* [Beyond the hype: deep neural networks outperform established methods using a ChEMBL bioactivity benchmark set, Journal of Cheminformatics](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-017-0232-0)

* [Systematic Evaluation of Local and Global Machine Learning Models for the Prediction of ADME Properties](https://pubs.acs.org/doi/10.1021/acs.molpharmaceut.2c00962)

Authors provide an evaluation of global and local models for ADME endpoint prediction. They compare the performance of global models and domain-specific local models. 10 different asays and 112 drug discovery projects were analyzed. The results showed consistent superior performance of global ADME models for property prediction. Performance improvement of global models over project-wise local models ranged from 3% to 25% in MAE. Local model improvements higher than 20% were achieved for only 7% of the assay-project pairs. 

* [Swanson, Kyle, et al. "ADMET-AI: A machine learning ADMET platform for evaluation of large-scale chemical libraries." BioRxiv (2023): 2023-12.](https://www.biorxiv.org/content/10.1101/2023.12.28.573531v1.abstract) [Web interface](https://admet.ai.greenstonebio.com/) [Code](https://github.com/swansonk14/admet_ai)

Online web interface to quickly predict ADMET properties using specific AI models trained on Therapeutic Data Commmons dataset. 

**Datasets**

* [QMugs](https://www.nature.com/articles/s41597-022-01390-7)

QMugs (Quantum mechanical properties of drug-like molecules) collection comprises quantum mechanical properties of more than 665 k biologically and pharmacologically relevant molecules extracted from the ChEMBL database, totaling 2M conformers.

* [MoleculeNet: a benchmark for molecular machine learning (rsc.org)](https://pubs.rsc.org/en/content/articlelanding/2018/sc/c7sc02664a)

* [TDC: Therapeutic Data Commons](https://tdcommons.ai/)

### Matched molecular-pair

* [Raymond, John W., and Peter Willett. "Maximum common subgraph isomorphism algorithms for the matching of chemical structures." Journal of computer-aided molecular design 16.7 (2002): 521-533.](https://link.springer.com/article/10.1023/A:1021271615909)

* [Dalke, Andrew, Jerome Hert, and Christian Kramer. "mmpdb: An open-source matched molecular pair platform for large multiproperty data sets." Journal of chemical information and modeling 58.5 (2018): 902-910.](https://pubs.acs.org/doi/10.1021/acs.jcim.8b00173)

### Enumeration of chemical space

* [Bellmann, Louis, et al. "Comparison of Combinatorial Fragment Spaces and Its Application to Ultralarge Make-on-Demand Compound Catalogs." Journal of Chemical Information and Modeling (2022).](https://pubs.acs.org/doi/10.1021/acs.jcim.1c01378)

Authors propose an algorithmic approach called as SpaceCompare to calculate overlap and diversity of the ultra-large combinatorial chemical libraries. The tool uses topological fragment spaces to capture the subtlties of the reaction having same product but different reactant substructures.

* [Nicolaou, Christos A., et al. "The proximal lilly collection: Mapping, exploring and exploiting feasible chemical space." Journal of chemical information and modeling 56.7 (2016): 1253-1266.](https://pubs.acs.org/doi/full/10.1021/acs.jcim.6b00173)

* [Zabolotna, Y., et al. (2021). "SynthI: A New Open-Source Tool for Synthon-Based Library Design." Journal of Chemical Information and Modeling.](https://pubs.acs.org/doi/full/10.1021/acs.jcim.1c00754)

Interesting work on de-novo design of molecules wherein, the molecules being created are made up from the fragments that is known to exist and are available to the user. New molecules are generated based on the fragmented (synthons) made available in the dataset. 

* [Fully Automated Creation of Virtual Chemical Fragment Spaces Using the Open-Source Library OpenChemLib](https://pubs.acs.org/doi/10.1021/acs.jcim.1c01041)

Open-source tool to generate synthetically accessible chemical spaces using reaction definitions and building blocks. Virtual fragments are generated using one-step reaction and real-world building blocks - the workflow also support 2-3 steps creation. 

* [Zabolotna, Yuliana, et al. "NP navigator: a new look at the natural product chemical space." Molecular informatics 40.9 (2021): 2100068.](https://onlinelibrary.wiley.com/doi/10.1002/minf.202100068).

Organizing the chemical space of ChEMBL, and ZINC to compare its overlap with natural products through COCONUT. Generative Topological Mapping is used for the clustering and analysis. Helpful overview of the method with its application to drug discovery can be found [here](https://www.sciencedirect.com/science/article/pii/S1740674920300044)

## Explainable/Interpretable Machine Learning 

**Reviews/Perspectives**

* [Wellawatte, Geemi P., et al. "A Perspective on Explanations of Molecular Prediction Models." (2022).](https://pubs.acs.org/doi/10.1021/acs.jctc.2c01235)

* [Rodríguez-Pérez, Raquel, and Jürgen Bajorath. "Explainable Machine Learning for Property Predictions in Compound Optimization." Journal of medicinal chemistry 64.24 (2021): 17744-17752](https://pubs.acs.org/doi/10.1021/acs.jmedchem.1c01789)

**Articles**

* [Wellawatte, Geemi P., Aditi Seshadri, and Andrew D. White. "Model agnostic generation of counterfactual explanations for molecules." (2021).](https://chemrxiv.org/engage/chemrxiv/article-details/613268f0d5f0803706ba0c79)

* [Matveieva, Mariia, and Pavel Polishchuk. "Benchmarks for interpretation of QSAR models." Journal of cheminformatics 13.1 (2021): 1-20](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-021-00519-x). [Patrick Walter's blog](https://patwalters.github.io/practicalcheminformatics/jupyter/ml/interpretability/2021/06/03/interpretable.html)


## Uncertainty quantification

* [Mervin, L. H., Johansson, S., Semenova, E., Giblin, K. A., & Engkvist, O. (2021). Uncertainty quantification in drug design. Drug discovery today, 26(2), 474-489.](https://www.sciencedirect.com/science/article/pii/S1359644620305110?via%3Dihub)

* [Alan Aspuru-Guzik perspective on uncertainty and confidence](https://arxiv.org/pdf/2102.11439.pdf)

* [Uncertainty Quantification Using Neural Networks for Molecular Property Prediction. J. Chem. Inf. Model. (2020) Hirschfeld, L., Swanson, K., Yang, K., Barzilay, R. & Coley, C. W.](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.0c00502)

Benchmark different models and uncertainty metrics for molecular property prediction. 

* [Evidential Deep learning for guided molecular property prediction and disocovery Ava Soleimany, Conor Coley, et. al.](https://arxiv.org/abs/1910.02600). [Slides](https://slideslive.com/38942396/evidential-deep-learning-for-guided-molecular-property-prediction-and-discovery)

Train network to output the parameters of an evidential distribution. One forward-pass to find the uncertainty as opposed to dropout or ensemble - principled incorporation of uncertainties

* [Differentiable sampling of molecular geometries with uncertainty-based adversarial attacks](https://arxiv.org/pdf/2101.11588.pdf)

* [J. P. Janet, S. Ramesh, C. Duan, H. J. Kulik, ACS Cent. Sci. 2020](https://pubs.acs.org/doi/10.1021/acscentsci.0c00026)

Conduct a global multi-objective optimization with expected improvement criterion. Find transition metal complex redox couples for Redox flow batteries that address stability, solubility, and redox potential metric. Use distance of a point from a training data in latent space as a metric to quantify uncertainty. 

## Active Learning 

Active learning provides strategies for efficient screening of subsets of the library. In many cases, we can identify a large portion of the most promising molecules with a fraction of the compute cost.

**Comparisons**

[Traversing Chemical Space with Active Deep Learning](https://chemrxiv.org/engage/chemrxiv/article-details/655f22eecf8b3c3cd7ef43d7)

The authors compared six active learning approaches on three benchmark datasets and concluded that the acquisition function is critical to AL performance. When comparing molecular representations, they found that fingerprints generalized better than graph neural networks.  Consistent with previous studies, they found that the choice of an initial training set had little impact on the outcome of an AL model. 

**Articles**

* [Correy, Galen J., Moira M. Rachman, Takaya Togo, Stefan Gahbauer, Yagmur U. Doruk, Maisie GV Stevens, Priyadarshini Jaishankar et al. "Extensive exploration of structure activity relationships for the SARS-CoV-2 macrodomain from shape-based fragment merging and active learning." bioRxiv (2024): 2024-08.](https://www.biorxiv.org/content/10.1101/2024.08.25.609621v1)

Very nice work from Shoichet (Zinc, UCSF) + Relay folks (Pat Walter et al) expanding on their active learning method to SAR CoV2. Use FrankenROCS and Thompson sampling to screen millions of compounds, identifying hits with IC50 values as low as 130 μM + ~100 X-ray crystal structures with binding data. Have been a big fan of active learning esp. multi-armed bandits. 

* [Gusev, Filipp, et al. "Active learning guided drug design lead optimization based on relative binding free energy modeling." Journal of Chemical Information and Modeling 63.2 (2023): 583-594.](https://pubs.acs.org/doi/10.1021/acs.jcim.2c01052)

Active learning on BDE. 

* [Klarich, Kathryn, et al. "Thompson Sampling─ An Efficient Method for Searching Ultralarge Synthesis on Demand Databases." Journal of Chemical Information and Modeling (2024).](https://pubs.acs.org/doi/10.1021/acs.jcim.3c01790). Update on it from AZ folks [Link](https://www.biorxiv.org/content/10.1101/2024.05.16.594622v1.full.pdf)

* [Fromer, Jenna C., David E. Graff, and Connor W. Coley. "Pareto optimization to accelerate multi-objective virtual screening." Digital Discovery (2024).](https://pubs.rsc.org/en/content/articlelanding/2024/dd/d3dd00227f)

* [Graff, David E., Eugene I. Shakhnovich, and Connor W. Coley. "Accelerating high-throughput virtual screening through molecular pool-based active learning." Chemical science 12.22 (2021): 7866-7881.](https://pubs.rsc.org/en/content/articlehtml/2021/sc/d0sc06805e). [GitHub](https://github.com/coleygroup/molpal)

Article talks about MolPAL as an active learning methodology. The team explores the application of these techniques to computational docking datasets and assess the impact of surrogate model architecture, acquisition function, and acquisition batch size on optimization performance. We observe significant reductions in computational costs; for example, using a directedmessage passing neural network we can identify 94.8% or 89.3% of the top-50 000 ligands in a 100M member library after testing only 2.4% of candidate ligands using an upper confidence bound or greedy acquisition strategy, respectively.

* [Thompson, James, et al. "Optimizing active learning for free energy calculations." Artificial Intelligence in the Life Sciences 2 (2022): 100050.](https://www.sciencedirect.com/science/article/pii/S2667318522000204)

Article exploring different active learning strategies for looking at sampling the congeneric RBFE calculations. The paper explores the impact of several AL design choices. They show that in their case, the overall AL performance is largely insensitive to the specific ML method and acquisition functions used. The significant factor affecting the performance was the number of molecules sampled at each iteration. 

* [Reker, D. Practical Considerations for Active Machine Learning in Drug Discovery. Drug Discov. Today Technol. 2020](https://doi.org/10.1016/j.ddtec.2020.06.001)

* [Janet, J. P., Ramesh, S., Duan, C., & Kulik, H. J. (2020). Accurate multiobjective design in a space of millions of transition metal complexes with neural-network-driven efficient global optimization. ACS central science, 6(4), 513-524.](https://pubs.acs.org/doi/abs/10.1021/acscentsci.0c00026)

* [A. P. Soleimany, A. Amini, S. Goldman, D. Rus, S. N. Bhatia, and C. W. Coley, “Evidential Deep Learning for Guided Molecular Property Prediction and Discovery,” ACS Cent. Sci., Jul. 2021.](https://pubs.acs.org/doi/10.1021/acscentsci.1c00546). [Slideshare](https://slideslive.com/38942396/evidential-deep-learning-for-guided-molecular-property-prediction-and-discovery)

Train property prediction model to output a distribution statistics in single pass that describes the uncertainty. This is in contrast to using ensemble models like MC dropout. Interesting way to estimate the epistemic (due to / from model) uncertainty in the prediction. Use this approach on antibiotic search problem of Stokes et. al. Compare Chemprop and SchNet models on different tasks. 

### Multi-parameter optimization 

* [Computer-aided multi-objective optimization in small molecule discovery](https://www.cell.com/patterns/fulltext/S2666-3899(23)00001-6)

* [Pareto Optimization to Accelerate Multi-Objective Virtual Screening](https://arxiv.org/abs/2310.10598)

## Transfer Learning  

**Reviews** 

* [Cai, Chenjing, et al. "Transfer learning for drug discovery." Journal of Medicinal Chemistry 63.16 (2020): 8683-8694.](https://pubs.acs.org/doi/pdf/10.1021/acs.jmedchem.9b02147)

**Articles** 

* [Approaching coupled cluster accuracy with a general-purpose neural network potential through transfer learning](https://www.nature.com/articles/s41467-019-10827-4)

Transfer learning by training a network to DFT data and then retrain on a dataset of gold standard QM calculations (CCSD(T)/CBS) that optimally spans chemical space. The resulting potential is broadly applicable to materials science, biology, and chemistry, and billions of times faster than CCSD(T)/CBS calculations.

* [Improving the generative performance of chemical autoencoders through transfer learning](https://iopscience.iop.org/article/10.1088/2632-2153/abae75/meta)

## Meta Learning 

* [Altae-Tran, H., Ramsundar, B., Pappu, A. S., & Pande, V. (2017). Low data drug discovery with one-shot learning. ACS central science, 3(4), 283-293.](https://pubs.acs.org/doi/abs/10.1021/acscentsci.6b00367)

Authors demonstrate how one-shot learning can be used to signifinicantly lower the amount of data required to make predictions in drug discovery tasks. LSTM combined with GCNNs is shown to improve learning capabilities of the model. In the simplest one-shot learning formalism these continuous vectors are then fed into a simple nearest-neighbor classifier that labels new examples by distance-weighted combination of support set labels

* [Nguyen, C. Q., Kreatsoulas, C., & Branson, K. M. (2020). Meta-learning GNN initializations for low-resource molecular property prediction. arXiv preprint arXiv:2003.05996.](https://arxiv.org/pdf/2003.05996.pdf)

Use CheMBL dataset to train a gated graph neural network (GGNN) for prediction and classification tasks using meta learning protocols. Show appreciable model performance even with just approx. 256 datapoints.

## Federated Learning 

* [Simm, Jaak, et al. "Splitting chemical structure data sets for federated privacy-preserving machine learning." Journal of Cheminformatics 13.1 (2021): 1-14.](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-021-00576-2)

* [Melloddy consortium](https://www.melloddy.eu/objectives)

Consortia comprising of leading resarch labs and companies working on decentralized datasets and predictive modeling of biochemical and cellular activity. 

## Generative design

**Reviews** 

* [Du, Y., Jamasb, A. R., Guo, J., Fu, T., Harris, C., Wang, Y., ... & Blundell, T. L. (2024). Machine learning-aided generative molecular design. _Nature Machine Intelligence_, 1-16.](https://www.nature.com/articles/s42256-024-00843-5)

* [Tang, Yidan, Rocco Moretti, and Jens Meiler. "Recent Advances in Automated Structure-Based De Novo Drug Design." Journal of Chemical Information and Modeling (2024).](https://pubs.acs.org/doi/full/10.1021/acs.jcim.4c00247?ref=recommended)

* [Anstine, Dylan M., and Olexandr Isayev. "Generative Models as an Emerging Paradigm in the Chemical Sciences." Journal of the American Chemical Society 145.16 (2023): 8736-8750.](https://pubs.acs.org/doi/full/10.1021/jacs.2c13467)

* [Mouchlis VD, Afantitis A, Serra A, et al. Advances in de Novo Drug Design: From Conventional to Machine Learning Methods. Int J Mol Sci. 2021;22(4):1676. Published 2021 Feb 7. doi:10.3390/ijms22041676](https://pubmed.ncbi.nlm.nih.gov/33562347/)

* [B. Sanchez-Lengeling and A. Aspuru-Guzik, “Inverse molecular design using machine learning: Generative models for matter engineering,” Science (80)., vol. 361, no. 6400, pp. 360–365, Jul. 2018](https://science.sciencemag.org/content/361/6400/360)

**Benchmarks**

* [Thomas, Morgan, et al. "MolScore: a scoring, evaluation and benchmarking framework for generative models in de novo drug design." Journal of Cheminformatics 16.1 (2024): 1-20.](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-024-00861-w). [Github](https://github.com/MorganCThomas/MolScore)

MolScore contains code to score and benchmark de novo compounds in the context of generative de novo design by generative models via the subpackage `molscore`, as well as, facilitate downstream evaluation via the subpackage `moleval`. An objective is defined via a JSON file which can be shared to propose new benchmark objectives, or to conduct multi-parameter objectives for drug design. 

* [Flam-Shepherd, Daniel, Kevin Zhu, and Alán Aspuru-Guzik. "Keeping it Simple: Language Models can learn Complex Molecular Distributions." arXiv preprint arXiv:2112.03041 (2021).](https://arxiv.org/abs/2112.03041). [Nature Comms Link](https://www.nature.com/articles/s41467-022-30839-x)

Test SOTA language models and representation performance against graph-based methods (CGVAE, JTVAE) for 'challenging' generative modeling tasks - generate a molecule - property distribution as a function of synthetic feasiblity. Graph models faced chanllenge in generating large molcules (> 100 HAs). Selfies provided advantage here. All of the models seem to generate novel molecules - how practical each of these novel molecules are is yet an open question. 

* [MOSES - Benchmarking platform for generative models](https://arxiv.org/abs/1811.12823).

Propose a platform to deploy and compare state-of-the-art generative models for exploring molecular space on same dataset. In addition the authors also propose list of metrics  to evaluate the quality and diversity of the generated structures.  

* [GuacaMol: Benchmarking models for De Novo Molecular Design](https://www.benevolent.com/guacamol). [Blogpost](https://www.benevolent.com/research/guacamol-benchmarking-models-for-de-novo-molecular-design)

Evaluation framework from BenevolentAI to compare different de-novo design models. 

* [J. Zhang, R. Mercado, O. Engkvist, and H. Chen, “Comparative Study of Deep Generative Models on Chemical Space Coverage,” J. Chem. Inf. Model., vol. 61, no. 6, pp. 2572–2581, Jun. 2021.](https://pubs.acs.org/doi/10.1021/acs.jcim.0c01328)

Interesting analysis from team at AstraZeneca R&D. They look at the chemical space coverage accounted by the SOTA generative models. Proposes a metric for evaluating space coverage, and thereby comparing different SOTA models, using a reference data (GDB-13 in this case). The new metric computes how much of the GDB-13 dataset can be recovered by a model that is trained on small GDB subset.  Generative models were trained on same 1M data points and 1B molecules were then sampled from each model. It was seen that at most 39% of the molecules in the parent dataset were sampled / generated by the model. Most models sampled the same compounds atleast twice. It was observed that graph-based model sampled much diverse molecules than string-based methods. Besides, the coverage of GAN-based models was worse compared to Language and Graph models. 

* [Gao, W.; Coley, C. W. The Synthesizability of Molecules Proposed by Generative Models. J. Chem. Inf. Model. 2020](https://doi.org/10.1021/acs.jcim.0c00174)

This paper looks at different ways of integrating synthesizability criteria into generative models. 

* [REINVENT4: Modern AI–Driven Generative Molecule Design](https://github.com/MolecularAI/REINVENT4) [Supported with PyTorch 2.0]

REINVENT is a molecular design tool for de novo design, scaffold hopping, R-group replacement, linker design, molecule optimization, and other small molecule design tasks. At its heart, REINVENT uses a Reinforcement Learning (RL) algorithm to generate optimized molecules compliant with a user defined property profile defined as a multi-component score. Transfer Learning (TL) can be used to create or pre-train a model that generates molecules closer to a set of input molecules.

**Language models:**


* [PromptSMILES: Prompting for scaffold decoration and fragment linking in chemical language models](https://chemrxiv.org/engage/chemrxiv/article-details/65e718eee9ebbb4db9f21886)

* [Xia, Yingce, et al. "Target-aware Molecule Generation for Drug Design Using a Chemical Language Model." bioRxiv (2024): 2024-01.](https://www.biorxiv.org/content/10.1101/2024.01.08.574635v3.abstract)

Collaboration with Microsoft AI and Global Health Drug Discovery Institute. TamGen, a method that employs a GPT-like chemical language model and enables target-aware molecule generation and compound refinement.The authors identified 7 compounds showing compelling inhibitory activity against the Tuberculosis ClpP protease. 

* [Maziarz, Krzysztof, et al. "Learning to extend molecular scaffolds with structural motifs." arXiv preprint arXiv:2103.03864 (2021).](https://arxiv.org/pdf/2103.03864.pdf). [Github](https://github.com/microsoft/molecule-generation)

Team at Novartis and Microsoft propose MoLeR, graph based model to generate molecule using scaffold as a seed. Scaffold based SAR speed up shown. 

* [Ross, Jerret, et al. "Large-scale chemical language representations capture molecular structure and properties." Nature Machine Intelligence 4.12 (2022): 1256-1264.](https://www.nature.com/articles/s42256-022-00580-7.epdf?sharing_token=p5m9Z0797IQeBDOiMGn71dRgN0jAjWel9jnR3ZoTv0MeIJPs9pbG9QLaEN_McFTR3KHv1tHh1FDNJB4ZuILdAmRtINVn6KqXrLkPhEiAZW5mM0dWWKSmPk82eibEUBx01sLTSHx6w903cDaUoXg9lAGzcHY_ifmakrBcIzUUDwI%3D). [Github]https://github.com/IBM/molformer?tab=readme-ov-file)

* [SELFIES and generative models using STONED](https://chemrxiv.org/articles/preprint/Beyond_Generative_Models_Superfast_Traversal_Optimization_Novelty_Exploration_and_Discovery_STONED_Algorithm_for_Molecules_using_SELFIES/13383266) 

[Reproducibility study of the STONED work from Jablonka et. al.](https://arxiv.org/pdf/2102.00700.pdf)

Representation using SELFIES proposed to make it much more powerful

* [Iovanac, Nicolae C., Robert MacKnight, and Brett Savoie. "Actively Searching: Inverse Design of Novel Molecules with Simultaneously Optimized Properties." ChemRxiv (2021)](https://chemrxiv.org/engage/chemrxiv/article-details/60c7591a9abda2847ff8ea1f)

Using quantum chemistry attributes calculated on-the-fly as scoring functions for sampling the generative model chemical space. Active learning strategy is deployed to explore the area of space where the properties of the molecules are unknown. 

* [R. Gómez-Bombarelli et al., “Automatic Chemical Design Using a Data-Driven Continuous Representation of Molecules,” ACS Cent. Sci., vol. 4, no. 2, pp. 268–276, 2018](https://pubs.acs.org/doi/10.1021/acscentsci.7b00572)

One of the first implementation of a variational auto-encoder for molecule generation. 

**Graph-based**

* [Flam-Shepherd, Daniel, Alexander Zhigalin, and Alán Aspuru-Guzik. "Scalable Fragment-Based 3D Molecular Design with Reinforcement Learning." arXiv preprint arXiv:2202.00658 (2022)](https://arxiv.org/abs/2202.00658?)

Reinforcement learning-based generative model whici is an update on point cloud approach by the same group to now incorporate 'grammar' for building molecules in form of functional groups in 3D space. 

* [W. Jin, R. Barzilay, and T. Jaakkola, “Junction tree variational autoencoder for molecular graph generation,” 35th Int. Conf. Mach. Learn. ICML 2018, vol. 5, pp. 3632–3648, 2018](https://arxiv.org/abs/1802.04364)

Junction tree based decoding. Define a grammar for the small molecule and find sub-units based on that grammar to construct a molecule. The molecule is generated in two-steps: first being generating the scaffold or backbone of the molelcule, then the nodes  are added with molecular substructure as identified from the 'molecular grammar'. 

**GANs**

* [MolGAN: An implicit generative model for small molecular graphs, N. De Cao and T. Kipf, 2018](https://arxiv.org/abs/1805.11973)

Generative adversarial network for finding small molecules using graph networks, quite interesting. Avoids issues arising from node ordering that are associated with likelihood based methods by using an adversarial loss instead (GAN)

**Scaffold-retained** 

* [Kaitoh, Kazuma, and Yoshihiro Yamanishi. "Scaffold-Retained Structure Generator to Exhaustively Create Molecules in an Arbitrary Chemical Space." Journal of Chemical Information and Modeling (2022).](https://pubs.acs.org/doi/10.1021/acs.jcim.1c01130)

* [Maziarz, Krzysztof, et al. "Learning to extend molecular scaffolds with structural motifs." arXiv preprint arXiv:2103.03864 (2021).](https://arxiv.org/pdf/2103.03864.pdf). [Github](https://github.com/microsoft/molecule-generation)

Team at Novartis and Microsoft propose MoLeR, graph based model to generate molecule using scaffold as a seed. Scaffold based SAR speed up shown. 

**Reaction tranformation-based** 

Here the idea is to constraint the molecules generated by the transformations amenable to a particular platform, like automated synthesis workflow. 

* [Luo, S., Gao, W., Wu, Z., Peng, J., Coley, C. W., & Ma, J. (2024). Projecting Molecules into Synthesizable Chemical Spaces. _arXiv preprint arXiv:2406.04628_.](https://arxiv.org/abs/2406.04628)

* [Expanding the chemical space using a chemical reaction knowledge graph](https://pubs.rsc.org/en/content/articlelanding/2024/dd/d3dd00230f)

* [Swanson, K., Liu, G., Catacutan, D.B. et al. Generative AI for designing and validating easily synthesizable and structurally novel antibiotics. Nat Mach Intell 6, 338–353 (2024).](https://www.nature.com/articles/s42256-024-00809-7)

* [Seo, Seonghwan, Jaechang Lim, and Woo Youn Kim. "Molecular Generative Model via Retrosynthetically Prepared Chemical Building Block Assembly." Advanced Science (2023): 2206674.](https://onlinelibrary.wiley.com/doi/10.1002/advs.202206674?utm_source=pocket_saves)

* [Bradshaw, John, et al. "Barking up the right tree: an approach to search over molecule synthesis dags." Advances in neural information processing systems 33 (2020): 6852-6866.](https://arxiv.org/pdf/2012.11522.pdf)

* [Fialková, Vendy, et al. "LibINVENT: reaction-based generative scaffold decoration for in silico library design." Journal of Chemical Information and Modeling 62.9 (2021): 2046-2063.](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00469)

* [Nguyen, Dai Hai, and Koji Tsuda. "A generative model for molecule generation based on chemical reaction trees." arXiv preprint arXiv:2106.03394 (2021).](https://arxiv.org/pdf/2106.03394.pdf)

Authors propose a generative model to generate molecules via multi-step chemical reaction trees, each campaign first generates a reaction-tree with template transformations as breaking points.

* [Bradshaw, John, et al. "A model to search for synthesizable molecules." Advances in Neural Information Processing Systems 32 (2019).](https://arxiv.org/abs/1906.05221)

**Diffusion models**

* [Mixed Continuous and Categorical Flow Matching for 3D De Novo Molecule Generation](https://arxiv.org/abs/2404.19739v1)

This model extends beyond traditional diffusion models by learning to map samples directly from arbitrary distributions, allowing for greater flexibility and application-specific model design. It is achieving remarkable efficiency (>10-fold reduction in inference time) and accuracy in molecule generation.

* [Igashov, Ilia, et al. "Equivariant 3D-conditional diffusion model for molecular linker design." Nature Machine Intelligence (2024): 1-11.](https://www.nature.com/articles/s42256-024-00815-9). [Blog from Pen](https://iwatobipen.wordpress.com/2024/04/24/generate-new-molecules-from-fragments-with-diffusion-model-cheminformatics-rdkit-difflinker-memo/)

* [Schneuing, Arne, et al. "Structure-based drug design with equivariant diffusion models." arXiv preprint arXiv:2210.13695 (2022)](https://arxiv.org/abs/2210.13695). Blog from Pen. [Link](https://iwatobipen.wordpress.com/2024/03/05/pocket-awaer-structure-generation-diffdec-cheminformatics/)


**3D conformations-aware** 

* [Integrating structure-based approaches in generative molecular design](https://www.sciencedirect.com/science/article/pii/S0959440X23000337)

* [Bolcato, Giovanni, Esther Heid, and Jonas Boström. "On the Value of Using 3D Shape and Electrostatic Similarities in Deep Generative Methods." Journal of chemical information and modeling 62.6 (2022): 1388-1398.](https://pubs.acs.org/doi/full/10.1021/acs.jcim.1c01535)

Extension to the fragment-based generative design model (DeepFMPO) using reinforcement learning now incorporating 3D electrostatic similarity in the analysis. Ability to replace fragment with similar 3D shape and electrostatics. ESP_sim [tutorial](https://www.youtube.com/watch?v=Ka08REoGYvI) for comparison of electrostatic potential and molecule shape is used for this purpose. The authors find scaffold-hopping bioisoteres for CDK2. 

**Protein-ligand interactions aware** 

* [Zhang, Jie, and Hongming Chen. "De novo molecule design using molecular generative models constrained by ligand–protein interactions." Journal of Chemical Information and Modeling 62.14 (2022): 3291-3306.](https://pubs.acs.org/doi/full/10.1021/acs.jcim.2c00177)

**Linker design**

* [Igashov, Ilia, et al. "Equivariant 3d-conditional diffusion models for molecular linker design." arXiv preprint arXiv:2210.05274 (2022).](https://arxiv.org/abs/2210.05274)

* [Guo, Jeff, et al. "Link-INVENT: Generative Linker Design with Reinforcement Learning." (2022).](https://chemrxiv.org/engage/chemrxiv/article-details/62628b2debac3a61c7debf31). [BlogPost](https://iwatobipen.wordpress.com/2022/06/04/generate-molecules-with-link-invent-rdkit-rinvent-chemoinformatics/)

* [Imrie, Fergus, et al. "Deep generative models for 3D linker design." Journal of chemical information and modeling 60.4 (2020): 1983-1995.](https://pubs.acs.org/doi/10.1021/acs.jcim.9b01120). [Blogpost](https://iwatobipen.wordpress.com/2020/05/09/replace-core-with-delinker-rdkit-chemoinformatics-deeplearning/)

Interesting work on designing linkers using conformation aware generative design algorithm. Think of it like fragment-growing. 

* [Nori, Divya, Connor W. Coley, and Rocío Mercado. "De novo PROTAC design using graph-based deep generative models." arXiv preprint arXiv:2211.02660 (2022).](https://arxiv.org/abs/2211.02660)

**Synthetic-cost aware**

* [Fromer, Jenna C., and Connor W. Coley. "An algorithmic framework for synthetic cost-aware decision making in molecular design. Sparrow" _Nature Computational Science_ (2024): 1-11.](https://www.nature.com/articles/s43588-024-00639-y). [Preprint](https://arxiv.org/abs/2311.02187). [Medium blogpost](https://medium.com/@kapeluha.ann00/cost-aware-prioritization-of-molecules-for-synthesis-with-sparrow-68c453b66f03)

SPARROW prioritizes molecules that both have high rewards and can be synthesized in a few steps from cheap starting materials. It is also shown to combine the library-focused and generative design based compounds in one setting depending on the harmony of the proposed synthetic routes and costs. 

## Computer Aided Synthesis Planning (CASP) 

**Reviews:** 

* [Torren-Peraire, Paula, et al. "Models Matter: the impact of single-step retrosynthesis on synthesis planning." Digital Discovery 3.3 (2024): 558-572.](https://pubs.rsc.org/en/content/articlelanding/2024/dd/d3dd00252g)

* [Thakkar, Amol, et al. "Artificial intelligence and automation in computer aided synthesis planning." Reaction chemistry & engineering 6.1 (2021): 27-51.](https://pubs.rsc.org/en/content/articlehtml/2021/xx/d0re00340a?casa_token=XlT3Q35wF_QAAAAA:Rcge3W9WUQher8k9zVMPBUQJsCeOskpUZOvQShiCcVZw127BHRFMRrZL0X6Upa9eHD-KMYPBNTaPww)

Perspective on the current SOTA of synthesis planning, automation, and reaction optimization in drug discovery and development phases using AI and ML. 

* [Madzhidov, T. I., et al. (2021). "Machine learning modelling of chemical reaction characteristics: yesterday, today, tomorrow." Mendeleev Communications 31(6): 769-780.](https://www.sciencedirect.com/science/article/abs/pii/S0959943621002959?dgcid=author)

* [Jorner, K., et al. (2021). "Organic reactivity from mechanism to machine learning." Nature Reviews Chemistry 5(4): 240-255.](https://www.nature.com/articles/s41570-021-00260-x)

* [Struble, T. J., et al. (2020). "Current and Future Roles of Artificial Intelligence in Medicinal Chemistry Synthesis." J Med Chem 63(16): 8667-8682](https://pubs.acs.org/doi/pdf/10.1021/acs.jmedchem.9b02120)

* [The Exploration of Chemical Reaction Networks](https://arxiv.org/pdf/1906.10223.pdf)

Perspective article summarising their position on the current state of research and future considerations on developing better reaction network models. Break down the analysis of reaction networks as into 3 classes (1) Front Open End: exploration of products from reactants (2) Backward Open Start: Know the product and explore potential reactants (3) Start to End: Product and reactant known, explore the likely intermediates. 

Nice summary of potential challenges in the field:

- Validating exploration algorithms on a consistent set of reaction system. 
- Need to generate a comparative metric to benchmark different algorithms.  
- Considering effect of solvents and/or protein embeddings in the analysis

**Best practices** 

* [Gimadiev, T. R., Lin, A., Afonina, V. A., Batyrshin, D., Nugmanov, R. I., Akhmetshin, T., ... & Varnek, A. (2021). Reaction Data Curation I: Chemical Structures and Transformations Standardization. Molecular Informatics, 2100119.](https://onlinelibrary.wiley.com/doi/abs/10.1002/minf.202100119?casa_token=SczoexCIDDUAAAAA:3M-uhrRFMaNRnydOQb-NBhJ1VvocjwZ1_ll--OGP1QwJ-X5Amwt24M586NXxbbgazYn0t-NBAmxS1oFk)

Article from Varnek group on best practices on processing data for reaction informatics. 

**Benchmarking**

* [Hastedt, Friedrich, et al. "Investigating the reliability and interpretability of machine learning frameworks for chemical retrosynthesis." _Digital Discovery_ 3.6 (2024): 1194-1212.](https://pubs.rsc.org/en/content/articlelanding/2024/dd/d4dd00007b)

* [Genheden S, Bjerrum E. PaRoutes: a framework for benchmarking retrosynthesis route predictions. ChemRxiv. Cambridge: Cambridge Open Engage; 2022](https://chemrxiv.org/engage/chemrxiv/article-details/621c86f3c3e9da4f737b0047). [Github](https://github.com/MolecularAI/PaRoutes)

Benchmarking framework for comparing different multi-step retrosynthesis methods from researchers at AstraZeneca R&D. Provides 10k synthetic routes which can be used as a validation set for different methodologies, providing a platform for systematic comparison of different methods being proposed in the community. 

**Classifying chemical reactions:**

* [Schwaller, Philippe, et al. "Mapping the space of chemical reactions using attention-based neural networks." Nature Machine Intelligence 3.2 (2021): 144-152.](https://www.nature.com/articles/s42256-020-00284-w). [rxnfp - Github](https://github.com/rxn4chemistry/rxnfp). [Preprint](https://arxiv.org/abs/2012.06051). [News Article](https://cen.acs.org/physical-chemistry/computational-chemistry/Mapping-reaction-space-machine-learning/99/i5?utm_source=LatestNews&utm_medium=LatestNews&utm_campaign=CENRSS). 

Transformer-based model for reaction classification. Compared it with BERT. Besides classification, the work also formalizes the reaction fingerprint generation using the learned representations. The reaction fingerprints are visualized using TMAPS.  

* [Heid, E; Green, W; Machine learning of reaction properties via learned representations of the condensed graph of reaction. ChemRxiv (2021)](https://chemrxiv.org/engage/chemrxiv/article-details/6112ac487117507542e68bef)

Reaction classifiction prediction using atom-mapped reaction that are used to generate condensed reaction graphs and passed through a GCN-variant as implemented in chemprop. 

**Reaction-specific features**

* [Heid, E., & Green, W. H. (2021). Machine learning of reaction properties via learned representations of the condensed graph of reaction. Journal of Chemical Information and Modeling, 62(9), 2101-2110.](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00975)

* [Probst, Daniel, Philippe Schwaller, and Jean-Louis Reymond. "Reaction Classification and Yield Prediction Using the Differential Reaction Fingerprint DRFP." ChemRxiv (2021)](https://chemrxiv.org/engage/chemrxiv/article-details/60e358fb379e8d3ba9f92d15)

* [Schneider, N., et al. (2015). "Development of a Novel Fingerprint for Chemical Reactions and Its Application to Large-Scale Reaction Classification and Similarity." Journal of Chemical Information and Modeling 55(1): 39-53.](https://pubs.acs.org/doi/10.1021/ci5006614)

Using scrapped US Patent data to classify chemical reactions and deploy various fingerprints and ML models for classification. 


**Atom mapping:** 

* [Chen, Shuan, et al. "Precise atom-to-atom mapping for organic reactions via human-in-the-loop machine learning." Nature Communications 15.1 (2024): 2250.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10937625/pdf/41467_2024_Article_46364.pdf)


* [Lin, A., et al. (2021). "Atom-to-atom Mapping: A Benchmarking Study of Popular Mapping Algorithms and Consensus Strategies."](https://onlinelibrary.wiley.com/doi/10.1002/minf.202100138?af=R)

Comparative analysis of different atom-mapping schemes for generating atom-mapped reaction features. Comments on the state of the art methods and their performance on a curated reaction database. 

* [Extraction of organic chemistry grammar from unsupervised learning of chemical reactions](https://advances.sciencemag.org/content/7/15/eabe4166). [RXMapper](https://github.com/rxn4chemistry/rxnmapper)

Data-driven atom mapping schemes which uses transformers for learning the context of the chemical reaction. Researchers at IBM trained a flavor of language model based on Transformer architecture and used it to find reaction centers and maps atoms. Shown to be robust compared to other SOTA methods. 

* [Automatic mapping of atoms across both simple and complex chemical reactions](https://www.nature.com/articles/s41467-019-09440-2)

**Predicting reaction outcomes:** 

* [Data-Efficient, Chemistry-Aware Machine Learning Predictions of Diels–Alder Reaction Outcomes](https://pubs.acs.org/doi/10.1021/jacs.4c03131)

Researchers use NERF that model electron flow in the reaction alongside bond-enviorment to propose diels-alder chemistry products. 

* [C. W. Coley et al., “A graph-convolutional neural network model for the prediction of chemical reactivity,” Chem. Sci., vol. 10, no. 2, pp. 370–377, 2019.](https://pubs.rsc.org/en/content/articlepdf/2019/sc/c8sc04228d)

Template-free prediction of organic reaction outcomes using graph convolutional neural networks

* [Prediction of Organic Reaction Outcomes Using Machine Learning, ACS Cent. Sci. 2017](https://pubs.acs.org/doi/10.1021/acscentsci.7b00064?ref=acsciiVIdeepchemistry)

* [Guan, Y., et al. (2021). "Regio-selectivity prediction with a machine-learned reaction representation and on-the-fly quantum mechanical descriptors." Chemical Science 12(6): 2198-2208](https://pubs.rsc.org/en/content/articlehtml/2021/sc/d0sc04823b)

* [Multi-Instance Learning Approach to the Modeling of Enantioselectivity of Conformationally Flexible Organic Catalysts](https://pubs.acs.org/doi/full/10.1021/acs.jcim.3c00393)

Conformational sampling and designing of chiral organic catalysts. 

**Yield prediction**

* [Raghavan, Priyanka, et al. "Incorporating Synthetic Accessibility in Drug Design: Predicting Reaction Yields of Suzuki Cross-Couplings by Leveraging AbbVie’s 15-Year Parallel Library Data Set." Journal of the American Chemical Society (2024).](https://pubs.acs.org/doi/full/10.1021/jacs.4c00098)

Evaluation of AbbVie’s medicinal chemistry library data set to build machine learning models for the prediction of Suzuki coupling reaction yields.


* [Ma, Yihong, et al. "Are we making much progress? Revisiting chemical reaction yield prediction from an imbalanced regression perspective." Companion Proceedings of the ACM on Web Conference 2024. 2024.](https://dl.acm.org/doi/pdf/10.1145/3589335.3651470)

Through experiments on real-world datasets, they demonstrate that treating reaction yield prediction as an imbalanced regression problem and incorporating cost-sensitive reweighting methods can significantly improve predictions for underrepresented high-yield reactions. 

* [Voinarovska, Varvara, et al. "When yield prediction does not yield prediction: an overview of the current challenges." (2023](https://chemrxiv.org/engage/chemrxiv/article-details/6509a987ed7d0eccc3d2b2c7)

* [Saebi, Mandana, et al. "On the use of real-world datasets for reaction yield prediction." Chemical science 14.19 (2023): 4997-5005.](https://pubs.rsc.org/en/content/articlehtml/2023/sc/d2sc06041h)

* [Predicting reaction performance in C–N cross-coupling using machine learning](https://www.science.org/doi/10.1126/science.aar5169?url_ver=Z39.88-2003&rfr_id=ori:rid:crossref.org&rfr_dat=cr_pub%20%200pubmed)

* [Multilabel Classification Models for the Prediction of Cross-Coupling Reaction Conditions](https://pubs.acs.org/doi/10.1021/acs.jcim.0c01234)

* [Schwaller, P., et al. (2021). "Prediction of chemical reaction yields using deep learning." Machine Learning: Science and Technology 2(1)](https://iopscience.iop.org/article/10.1088/2632-2153/abc81d). [Tutorial and blogpost](https://rxn4chemistry.github.io/rxn_yields/)

* [Schwaller, P., et al. (2019). "Molecular Transformer: A Model for Uncertainty-Calibrated Chemical Reaction Prediction." ACS Central Science 5(9): 1572-1583.](https://pubs.acs.org/doi/10.1021/acscentsci.9b00576) 

* [Ahneman, D. T., Estrada, J. G., Lin, S., Dreher, S. D., & Doyle, A. G. (2018). Predicting reaction performance in C–N cross-coupling using machine learning. Science, 360(6385), 186-190.](https://www.science.org/doi/full/10.1126/science.aar5169)

Classic paper, one of the firsts to show modeling reaction yields using ML. A random forest algorithm, was used to predict synthetic reaction performance in multidimensional chemical space with high-throughput experimentation data. Descriptors for components in a palladium-catalyzed Buchwald-Hartwig cross-coupling were computed and used as inputs. The random forest model outperformed linear regression in predictive accuracy, even with sparse training sets and out-of-sample predictions, highlighting its potential for synthetic methodology adoption.

**Retrosynthetic routes:** 

* [Do Chemformers Dream of Organic Matter? Evaluating a Transformer Model for Multistep Retrosynthesis](https://pubs.acs.org/doi/10.1021/acs.jcim.3c01685)

Transformer model evaluation for retrosynthesis from AZ folks. Template-free method. 

* [Westerlund, Annie, et al. "Data-driven approaches for identifying hyperparameters in multi-step retrosynthesis." (2023).](https://onlinelibrary.wiley.com/doi/10.1002/minf.202300128)

Meta analysis on the best set of hyperparameters for retrosynthesis routines. Here the authors explore different parameters of the retrosynthesis workflow and their impact on the performance of the route scoping. They propose new set of parameters, other than the default, to assist in improving the odds of the software finding a route for diverse of set of molecules. First of its kind look into an approach to identify such a set. 

* [Schwaller, P., et al. (2020). "Predicting retrosynthetic pathways using transformer-based models and a hyper-graph exploration strategy." Chemical Science 11(12): 3316-3325.](https://pubs.rsc.org/en/content/articlelanding/2020/sc/c9sc05704h)

* [Computational planning of the synthesis of complex natural products](https://www.nature.com/articles/s41586-020-2855-y)

* [Watson, I. A., et al. (2019). "A retrosynthetic analysis algorithm implementation." J Cheminform 11(1)](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-018-0323-6)

* [Segler, Marwin HS, and Mark P. Waller. "Neural‐symbolic machine learning for retrosynthesis and reaction prediction." Chemistry–A European Journal 23.25 (2017): 5966-5971.](https://chemistry-europe.onlinelibrary.wiley.com/doi/10.1002/chem.201605499)

Hybrid neural-symbolic approach for both retrosynthesis and reaction prediction that can be trained with large reaction sets from databases. Template extraction from known reaction datasets to classify new reaction to known reaction classes. 

* [Seidl, Philipp, et al. "Improving Few-and Zero-Shot Reaction Template Prediction Using Modern Hopfield Networks." Journal of chemical information and modeling 62.9 (2022): 2111-2120.](https://pubs.acs.org/doi/10.1021/acs.jcim.1c01065)

Introduce a template-based single-step retrosynthesis model based on Modern Hopfield
Networks, which learn an encoding of both molecules and reaction templates in order to
predict the relevance of templates for a given molecule. The model does not consider templates as distinct categories, but can leverage structural information about the template. The retrieval approach enables generalization across templates, which makes zero-shot learning possible and improves few-shot learning. On the single-step retrosynthesis benchmark USPTO-50k, the MHN model reaction reaches the state-of-the-art at top-k accuracy for k ≥ 3. 

* [Tu, Zhengkai, and Connor W. Coley. "Permutation invariant graph-to-sequence model for template-free retrosynthesis and reaction prediction." Journal of Chemical Information and Modeling (2021).](https://pubs.acs.org/doi/full/10.1021/acs.jcim.2c00321)

Graph2SMILES, a template-free retrosynthesis model to predict reaction outcomes and retrosynthesis routes. This model eliminates the need for any input-side SMILES augmentation, while achieving noticeable improvements over Transformer baselines (especially for top-1 accuracy). 

**Generate reaction networks:**

* [Fooshee, David, et al. "Deep learning for chemical reaction prediction." Molecular Systems Design & Engineering 3.3 (2018): 442-452.](https://pubs.rsc.org/en/content/articlehtml/2018/me/c7me00107j)

* [M. Liu et al., “Reaction Mechanism Generator v3.0: Advances in Automatic Mechanism Generation,” J. Chem. Inf. Model., May 2021](https://pubs.acs.org/doi/10.1021/acs.jcim.0c01480)

Newest version of RMG (v3) is updated to Python v3. It has ability to generate heterogeneous catalyst models, uncertainty analysis to conduct first order sensitivity analysis. RMG dataset for the thermochemical and kinetic parameters have been expanded. 

* [More and Faster: Simultaneously Improving Reaction Coverage and Computational Cost in Automated Reaction Prediction Tasks](https://s3-eu-west-1.amazonaws.com/itempdf74155353254prod/13076087/More_and_Faster__Simultaneously_Improving_Reaction_Coverage_and_Computational_Cost_in_Automated_Reaction_Prediction_Task_v1.pdf)

Presents an algorithmic improvement to the reaction network prediction task through their YARP (Yet Another Reaction Program) methodology. Shown to reduce computational cost of optimization while improving the diversity of identified products and reaction pathways. 

* [Molecular Transformer: A Model for Uncertainty-Calibrated Chemical Reaction Prediction](https://pubs.acs.org/doi/abs/10.1021/acscentsci.9b00576)
    * Follow-up: [Quantitative interpretation explains machine learning models for chemical reaction prediction and uncovers bias](https://www.nature.com/articles/s41467-021-21895-w)

* [Automatic discovery of chemical reactions using imposed activation](https://chemrxiv.org/articles/preprint/Automatic_discovery_of_chemical_reactions_using_imposed_activation/13008500/1)

* [Machine learning in chemical reaction space](https://www.nature.com/articles/s41467-020-19267-x)

Look at exploration of reaction space rather than compound space. SOAP kernel for representing the moelcules. Estimate atomization energy for the molecules using ML. Calculate the d(AE) for different ML-estimated AEs. Reaction energies (RE) are estimated and uncertainty propogation is used to estimate the errors. Uncorrelated constant error propogation. 30,000 bond breaking reaction steps Rad-6-RE network used. RE prediction is not as good as AE.

**Estimate molecular synthesizability**

The idea of estimating whether a molecule is 'synthesizable' can be thought of from two areas:
1. Complexity based - compare the fragments in the molecule to the known fragments in the chemical space  
2. Full retrosynthesis based - entire route is considered for molecule generation. Reactant complexity drives route complexity. 

* [Li, Junren, Lei Fang, and Jian-Guang Lou. "Retro-BLEU: quantifying chemical plausibility of retrosynthesis routes through reaction template sequence analysis." Digital Discovery (2024).](https://pubs.rsc.org/en/content/articlehtml/2024/dd/d3dd00219e)

Retro-BLEU, a statistical metric adapted from the well-established BLEU score in machine translation, to evaluate the plausibility of retrosynthesis routes based on reaction template sequences analysis. The authors use PaRoute to validate this approach. 

* [Ertl, Peter, and Ansgar Schuffenhauer. "Estimation of synthetic accessibility score of drug-like molecules based on molecular complexity and fragment contributions." Journal of cheminformatics 1.1 (2009): 1-11.](https://jcheminf.biomedcentral.com/articles/10.1186/1758-2946-1-8). [RDkit implementation](https://github.com/rdkit/rdkit/tree/master/Contrib/SA_Score)

Synthetic Accessbility  score (SA_Score) is a popular heuristic score for quantifying synthesizability. It computes a score using a fragment-contribution approach, where rarer fragments (as judged by their abundance in the PubChem database of 1mil representative cmpds) are taken as an indication of lower synthesizability. 

* [Coley, Connor W., et al. "SCScore: synthetic complexity learned from a reaction corpus." Journal of chemical information and modeling 58.2 (2018): 252-261.](https://pubs.acs.org/doi/full/10.1021/acs.jcim.7b00622). [DeepChem implementation](https://github.com/deepchem/deepchem/blob/master/examples/tutorials/Synthetic_Feasibility_Scoring.ipynb)

SCScore is a learned synthetic complexity score computed as a neural network model trained on reaction data from the Reaxys database. It was designed with synthesis planning in mind to operate on molecules resembling not just drug-like products but intermediates and simpler building blocks as well.

* [Liu, Cheng-Hao, et al. "RetroGNN: Fast Estimation of Synthesizability for Virtual Screening and De Novo Design by Learning from Slow Retrosynthesis Software." Journal of Chemical Information and Modeling 62.10 (2022): 2293-2300.](https://pubs.acs.org/doi/10.1021/acs.jcim.1c01476)

RetroGNN is a graph neural network based model to predict outcome of a synthesis planner given the target molecule. Shown to better perform than SAScore. Code is yet to be released. 

* [Chen, Shuan, and Yousung Jung. "Estimating the synthetic accessibility of molecules with building block and reaction-aware SAScore." Journal of Cheminformatics 16 (2024).](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-024-00879-0)

Authors introduce BR-SAScore, an enhanced version of SAScore that integrates the available building block information (B) and reaction knowledge (R) from synthesis planning programs into the scoring process. The score can also identify fragment contributing to the synthetic infeasibility. 

* [Parrot, Maud, et al. "Integrating synthetic accessibility with AI-based generative drug design." Journal of Cheminformatics 15.1 (2023): 83.](https://link.springer.com/article/10.1186/s13321-023-00742-8)

From team at Iktos for triaging molecule designs. The group introduces (retro-score) RScore and RSPred (derived score from RScore using NN). RScore is computed through a full retrosynthesis analysis. The R2 value for RSPred is 0.75. 

### Data-driven chemistry modeling and reaction optimization

**Review / Perspectives**

* [Raghavan, Priyanka, et al. "Dataset design for building models of chemical reactivity." ACS Central Science 9.12 (2023): 2196-2204.](https://pubs.acs.org/doi/full/10.1021/acscentsci.3c01163#)

Authors discuss the design of reaction datasets in ways that are conducive to data-driven modeling, emphasizing the idea that training set diversity and model generalizability rely on the choice of molecular or reaction representation. They lay down the experimental constraints associated with generating common types of chemistry datasets and how these considerations should influence dataset design and model building.

* [Maloney, Michael P., et al. "Negative Data in Data Sets for Machine Learning Training." Organic Letters (2023).](https://pubs.acs.org/doi/10.1021/acs.joc.3c00844)

Thoughts from industry practioners on how to label low/no yield reactions in electronic lab notebooks (eLNs). This is important when building ML model for reaction outcomes. 

* [Williams, Wendy L., et al. "The evolution of data-driven modeling in organic chemistry." ACS central science 7.10 (2021): 1622-1637.](https://pubs.acs.org/doi/full/10.1021/acscentsci.1c00535)

* [Machine Learning Strategies for Reaction Development: Toward the Low-Data Limit](https://pubs.acs.org/doi/full/10.1021/acs.jcim.3c00577)

**Industrial reactions commentary**

* [Expanding the medicinal chemistry synthetic toolbox](https://www.nature.com/articles/nrd.2018.116)

* [The Medicinal Chemist’s Toolbox: An Analysis of Reactions Used in the Pursuit of Drug Candidates](https://doi.org/10.1021/jm200187y)

* [Late-Stage Saturation of Drug Molecules](https://pubs.acs.org/doi/10.1021/jacs.4c00807?ref=recommended)


**Substrate Scoping**

Area to understand the coverage of chemical space by a specific reaction transformation. Knowing which substrates can be used for a specific type of reactions can accelerate the generation of HTE datasets, and also reduce wastage and failures in searching for right substrates. Every new reaction protocol which is proposed would have a corresponding set of amenable 'action-space' for the ligands. 

* [Rana, D., Pflüger, P. M., Hölter, N. P., Tan, G., & Glorius, F. (2024). Standardizing Substrate Selection: A Strategy toward Unbiased Evaluation of Reaction Generality. ACS Central Science, 10(4), 899-906.](https://pubs.acs.org/doi/10.1021/acscentsci.3c01638)

The authors report a standardized substrate selection strategy which mitigates biases found in traditional substrate scoping tables. This way the chemists can showcase unbiased applicability of novel methodologies facilitating their practical applications. 

* [Gao, W., Raghavan, P., Shprints, R., & Coley, C. W. (2024). Substrate Scope Contrastive Learning: Repurposing Human Bias to Learn Atomic Representations. arXiv preprint arXiv:2402.16882.](https://arxiv.org/pdf/2402.16882)

* [Kariofillis, Stavros K., et al. "Using data science to guide aryl bromide substrate scope analysis in a Ni/photoredox-catalyzed cross-coupling with acetals as alcohol-derived radical sources." Journal of the American Chemical Society 144.2 (2022): 1045-1055.](https://pubs.acs.org/doi/10.1021/jacs.1c12203)

Integration of data science techniques, including DFT featurization, dimensionality reduction, and hierarchical clustering, to delineate a diverse and succinct collection of aryl bromides that is representative of the chemical space of the substrate class

* [On the Topic of Substrate Scope](https://pubs.acs.org/doi/10.1021/acs.orglett.2c03246)

**Articles**

* [Pomberger, Alexander, et al. "The effect of chemical representation on active machine learning towards closed-loop optimization." Reaction Chemistry & Engineering 7.6 (2022): 1368-1379.](https://pubs.rsc.org/en/content/articlelanding/2022/re/d2re00008c)

Lapkin and co look at the effect of chemical representation on reaction performance and condition prediction tasks. They look at the high throughput experientation generated datasets and the impact of calculated chemical descriptors on the prediction of reaction yields. They show tailored descriptions did not outperform the traditional ones but larger initial data accelerated reaction performance. 

* [Haas, Brittany, et al. "Rapid Prediction of Conformationally-Dependent DFT-Level Descriptors using Graph Neural Networks for Carboxylic Acids and Alkyl Amines." (2024).](https://chemrxiv.org/engage/chemrxiv/article-details/65d79de59138d23161bec6e6)

2D and 3D-aware GNNs to predict DFT descriptors for conformationally flexible molecules, focusing on carboxylic acid and amines in particular. 

* [Wang, J.Y., Stevens, J.M., Kariofillis, S.K. et al. Identifying general reaction conditions by bandit optimization. Nature 626, 1025–1033 (2024).](https://www.nature.com/articles/s41586-024-07021-y#citeas)

Latest from Abigail Doyle's group where they use bandit optimization routine, related to Thompson sampling, to find reaction condition. 

* [Götz, Julian, et al. "High-throughput synthesis provides data for predicting molecular properties and reaction success." Science advances 9.43 (2023)](https://www.science.org/doi/full/10.1126/sciadv.adj2314). [Github](https://github.com/jugoetz/slap-platform-predict)

The authors propose a platform that is built for looking at photocatalytic N-heterocycle synthesis connected with HTE, automated purification, and physicochemical assays. Implement train-test split in 3 different strategies to minimize ligand overlap. 

* [Machine learning from quantum chemistry to predict experimental solvent effects on reaction rates](https://pubs.rsc.org/en/Content/ArticleLanding/2024/SC/D3SC05353A)

* [Casetti, Nicholas, et al. "Combining Molecular Quantum Mechanical Modeling and Machine Learning for Accelerated Reaction Screening and Discovery." Chemistry–A European Journal 29.60 (2023): e202301957.](https://chemistry-europe.onlinelibrary.wiley.com/doi/full/10.1002/chem.202301957)

* [B. J. Shields et al., “Bayesian reaction optimization as a tool for chemical synthesis,” Nature, vol. 590, no. June 2020, p. 89, 2021](https://www.nature.com/articles/s41586-021-03213-y). [Github](https://github.com/b-shields/edbo)

Experimental design using Bayesian Optimization. Look at 3 rxn class with multiple reaction parameters - temp solvent ligand. Algorithm identifies the optimal conditions. Variables looked into: ligands, bases, solvents, temperatures, concentrations. Algorithm arrived at 99% yields consistently - which was possible by using unusual ligand not known to work well (cognitive bias).

* [Torres, Jose Garrido, et al. "A Multi-Objective Active Learning Platform and Web App for Reaction Optimization." (2022).](https://chemrxiv.org/engage/chemrxiv/article-details/62f6966269f3a5df46b5584b). [Follow-up Version 2.0](https://pubs.acs.org/doi/full/10.1021/jacs.2c08592?ref=recommended)

* [Hickman, Riley J., et al. "Bayesian optimization with known experimental and design constraints for chemistry applications." arXiv preprint arXiv:2203.17241 (2022).](https://arxiv.org/abs/2203.17241)

* [Gensch, Tobias, et al. "A comprehensive discovery platform for organophosphorus ligands for catalysis." Journal of the American Chemical Society 144.3 (2022): 1205-1217.](https://pubs.acs.org/doi/full/10.1021/jacs.1c09718?casa_token=SsZZYyjrgFUAAAAA%3AGnpCghTv-1TwIGt3sANEQ_abtAe_sh-wHoltFPY41NP0vgKose0mzPvCpQMVziiZe6I2yBEihBCrSMI6)

Also called Kraken - a discovery platform covering monodentate organophosphorus(III) ligands providing comprehensive physicochemical descriptors based on representative conformer ensembles. Using quantum-mechanical methods, the authors calculated descriptors for 1558 ligands, including commercially available examples, and trained machine learning models to predict properties of over 300000 new ligands. 

* [Häse, Florian, et al. "Gryffin: An algorithm for Bayesian optimization of categorical variables informed by expert knowledge." Applied Physics Reviews 8.3 (2021): 031406.](https://aip.scitation.org/doi/abs/10.1063/5.0048164)

* [Dotson, Jordan, et al. "Data-driven multi-objective optimization tactics for catalytic asymmetric reactions." (2022).](https://chemrxiv.org/engage/chemrxiv/article-details/62b2dc4b7da6ce2ddb1b3264)

Multi-objective optimization of catalytic reactions that employ chiral bisphosphine ligands. Optimization of 2 sequential reactions in asymmetric synthesis of API. Classification method identify active catalysts -- 5% yield (user provided) cutoff for binary classification. Linear regression to model reaction selectivity. DFT-derived descriptor dataset of >550 bisphosphine ligands. Develop an interpretable chemical space mapping tool using PCA. Look at the domain of applicability with the euclidean distance in chemical space. 


**Generate catalysts**

* [Schilter, Oliver, et al. "Designing catalysts with deep generative models and computational data. A case study for Suzuki cross coupling reactions." Digital Discovery (2023).](https://pubs.rsc.org/en/content/articlelanding/2023/DD/D2DD00125J)

Use VAE and RNN to propose new catalyst for Suzuki cross-coupling reaction. The trained models are used to find catalyst's binding energy and find high percentage of novel and valid designs. 

**Databases**

* [Avila, Claudio, et al. "Chemistry in a graph: modern insights into commercial organic synthesis planning." Digital Discovery (2024).](https://pubs.rsc.org/en/content/articlelanding/2024/dd/d4dd00120f)

Team from Pfizer use Graph Datasets and Network visualization to show how process chemistry data (GLP1 inhibitor Lotiglipron in this case) can be stored, queried, and used for illustration purposes. They demonstrate the utility of knowledge graph for optimizing the route selection process. Neo4J is used for querying the dataset. 

* [Kearnes, S. M., et al. (2021). "The Open Reaction Database." Journal of the American Chemical Society.](https://pubs.acs.org/doi/full/10.1021/jacs.1c09820?utm_source=pocket_mylist)

* [Data Sharing in Chemistry: Lessons Learned and a Case for Mandating Structured Reaction Data](https://pubs.acs.org/doi/full/10.1021/acs.jcim.3c00607)

* [Rohrbach, Simon, et al. "Digitization and validation of a chemical synthesis literature database in the ChemPU." Science 377.6602 (2022): 172-180.](https://www.science.org/doi/10.1126/science.abo0058)

* [CGRdb2.0: A Python Database Management System for Molecules, Reactions, and Chemical Data](https://pubs.acs.org/doi/full/10.1021/acs.jcim.1c01105)

**Reaction sanitization** 

* [ORDerly: Datasets and benchmarks for chemical reaction data](https://chemrxiv.org/engage/api-gateway/chemrxiv/assets/orp/resource/item/64ca5d3e4a3f7d0c0d78ca42/original/or-derly-datasets-and-benchmarks-for-chemical-reaction-data.pdf)

* [Reaction Data Curation I: Chemical Structures and Transformations Standardization](https://onlinelibrary.wiley.com/doi/full/10.1002/minf.202100119)

**Reaction data extraction** 

* [Dong, Qingyang, and Jacqueline M. Cole. "Snowball 2.0: Generic Material Data Parser for ChemDataExtractor." Journal of Chemical Information and Modeling (2023).](https://pubs.acs.org/doi/full/10.1021/acs.jcim.3c01281)

* [ReactionDataExtractor 2.0: A Deep Learning Approach for Data Extraction from Chemical Reaction Schemes](https://pubs.acs.org/doi/10.1021/acs.jcim.3c00422)

### Automated chemistry workflows 

**Reviews**

* [Self-Driving Laboratories for Chemistry and Materials Science](https://chemrxiv.org/engage/chemrxiv/article-details/65a887f29138d231612bf6df)

This review article provides an in-depth analysis of the state-of-the-art in SDL technology, its applications across various scientific disciplines, and the potential implications for research, and industry. This review additionally provides an overview of the enabling technologies for SDLs, including their hardware, software, and integration with laboratory infrastructure. Most importantly, this review explores the diverse range of scientific domains where SDLs have made significant contributions, from drug discovery and materials science to genomics and chemistry.

* [Seifrid, Martin, et al. "Autonomous Chemical Experiments: Challenges and Perspectives on Establishing a Self-Driving Lab." Accounts of Chemical Research (2022): e0229862-131.](https://pubs.acs.org/doi/abs/10.1021/acs.accounts.2c00220)

* [Godfrey, Alexander G., Thierry Masquelin, and Horst Hemmerle. "A remote-controlled adaptive medchem lab: an innovative approach to enable drug discovery in the 21st Century." Drug Discovery Today 18.17-18 (2013): 795-802.](https://www.sciencedirect.com/science/article/pii/S135964461300069X)

Account of Eli Lilly and Company's ASL (Automated Synthesis Lab)

**Articles**

* [Autonomous, multiproperty-driven molecular discovery: From predictions to measurements and back](https://www.science.org/doi/10.1126/science.adi1407)

* [Nambiar, Anirudh MK, et al. "Bayesian Optimization of Computer-Proposed Multistep Synthetic Routes on an Automated Robotic Flow Platform." ACS Central Science (2022).](https://pubs.acs.org/doi/10.1021/acscentsci.2c00207)

* [Wilbraham, Liam, S. Hessam M. Mehr, and Leroy Cronin. "Digitizing chemistry using the chemical processing unit: from synthesis to discovery." Accounts of Chemical Research 54.2 (2020): 253-262.](https://pubs.acs.org/doi/full/10.1021/acs.accounts.0c00674)


### DNA-encoded Libraries 

* [Matthew Clark, et. al. DNA-encoded small-molecule libraries (DEL)](https://www.nature.com/articles/nchembio.211). [C&EN article on the topic](https://cen.acs.org/articles/95/i25/DNA-encoded-libraries-revolutionizing-drug.html)

New form of storing huge amounts of molecule related data using DNA. Made partially possible by low cost of DNA sequencing. Each molecule in the storage is attached with a DNA strand which encode information about its recipe. 

- [Follow up to the work with Machine Learning for hit finding.](https://pubs.acs.org/doi/abs/10.1021/acs.jmedchem.0c00452)
 
DNA encodings for discovery of novel small-molecule protein inhibitors. Outline a process for building a ML model using DEL. Compare graph convolutions to random forest for classification tasks with application to protein target binding. Graph models seemed to achieve high hit rate comapred to random forest. Apply diversity, logistical, structural filtering to search for novel candidates. First work to use GCN for hit searching.

* [Martín, A., et al. (2020). "Navigating the DNA encoded libraries chemical space." Communications Chemistry 3(1).](https://www.nature.com/articles/s42004-020-00374-1?error=cookies_not_supported&code=2d1394f8-2e1b-46ef-b926-9441292aea56)

* [Zabolotna, Y., Pikalyova, R., Volochnyuk, D., Horvath, D., Marcou, G., & Varnek, A. (2021). Exploration of the chemical space of DNA-encoded libraries.](https://chemrxiv.org/engage/chemrxiv/article-details/60fac8718804431689e3155b)

* [Shmilovich, Kirill, et al. "DEL-Dock: Molecular Docking-Enabled Modeling of DNA-Encoded Libraries." arXiv preprint arXiv:2212.00136 (2022).](https://pubs.acs.org/doi/10.1021/acs.jcim.2c01608)

Propose a way to incoporate 3D-spatial information in the DEL read outs to denoise the data. 

* [Zhang, Chris, et al. "Building Block-Based Binding Predictions for DNA-Encoded Libraries." (2023).](https://pubs.acs.org/doi/10.1021/acs.jcim.3c00588) [Github](https://github.com/MobleyLab/DEL_analysis)

Set of informatic tools to look at BBs producitivity in DEL screens and guide designs for new DELs. Authors calculate joint probabilities of the BBs for its activity and find increasing binding metric for individual BBs also increases the overall binding energy. The authors then cluster these BBs using 2D and 3D tanimoto FPs (3D Tanimoto Combo) and HDBSCAN clustering. Good workflow for implementing 3D-based ROCs filtering. 

## Large Language Models (LLMs)

It’s a stretch to say that GPT-4 or any other LLM understands Chemistry.  

At this point, LLMs seem to have two general use cases.  First, summarization and information retrieval.  LLMs can parse vast collections of text, which can be queried using natural language.  These information retrieval capabilities have many applications, from writing computer code and collating clinical trial results to summarizing papers on a specific topic.  

While there are still issues with LLMs hallucinating and providing incorrect information, tools and strategies are being developed to ensure the validity of LLM responses.  

The other area where LLMs appear to be making inroads is workflow management or tools orchestration.  Many activities in drug discovery, whether computational or experimental, require long sequences of steps, which can be tedious to orchestrate. These include asking questions about data, analyze results, do routine post processing for comparing with known state of the project. 

While it is often possible to script the execution of these steps, scripting requires a detailed knowledge of each step.  LLMs have the potential to simplify this process and carry out multi-step procedures given only a set of initial conditions and a final objective.  While the amount of progress the field has made in a short time is impressive, I don’t see LLMs replacing scientists any time soon. 

Previously the field has propose assistants for this job [here](https://www.science.org/content/blog-post/lilly-s-virtual-med-chem-assistant) which comprised of pre-scripted set of rules and processes. While tedious, they seem to add lot of value to project teams for quickly analyzing the SAR. The hope is LLMs might make the dream of all encompasing assistant a reality. 

* [Total survey of the LLM landscape](https://arxiv.org/abs/2402.06196)

* [General LLM-based multi-agent survey](https://arxiv.org/pdf/2402.01680)

* [Scientific Large Language Models: A Survey on Biological & Chemical Domains](https://arxiv.org/pdf/2401.14656)

**Reviews**

* [Ramos, Mayk Caldas, Christopher J. Collison, and Andrew D. White. "A Review of Large Language Models and Autonomous Agents in Chemistry." _arXiv preprint arXiv:2407.01603_ (2024).](https://arxiv.org/abs/2407.01603)

* [Blogpost on different LLMs in chemistry](https://chemicbook.com/2023/04/11/LLMs-in-Chemistry.html#ref2)

* [Bran, Andres M., and Philippe Schwaller. "Transformers and Large Language Models for Chemistry and Drug Discovery." arXiv preprint arXiv:2310.06083 (2023).](https://arxiv.org/abs/2310.06083)

**Agents**

* [PaperQA: Retrieval-Augmented Generative Agent for Scientific Research](https://arxiv.org/abs/2312.07559)

PaperQA, a Retrieval-Augmented Generation (RAG) agent for the scientific literature.  PaperQA begins by constructing LLM search queries from a set of keywords.  The results of these searches are aggregated into a vector database and combined with a pre-trained LLM to create a summary of the search results. In benchmark comparisons, the differences between answers provided by PaperQA and human evaluators were similar to differences between individual human evaluators.  Encouragingly, unlike many other LLMs, PaperQA didn’t hallucinate citations. 

* [Bran, Andres M., et al. "ChemCrow: Augmenting large-language models with chemistry tools." arXiv preprint arXiv:2304.05376 (2023).](https://arxiv.org/abs/2304.05376)

ChemCrow provides software tools for performing domain-specific tasks, including web searches, file format conversions, and similarity searches.  Compared with GPT-4, ChemCrow provided superior performance on tasks like synthetic route planning.  The authors also point to potential misuse of LLMs and suggest mitigation strategies. 

* [Boiko, Daniil A., Robert MacKnight, and Gabe Gomes. "Emergent autonomous scientific research capabilities of large language models." arXiv preprint arXiv:2304.05332 (2023).](https://arxiv.org/abs/2304.05332). [Peer-review](https://www.nature.com/articles/s41586-023-06792-0)

Coscientist, a set of LLMs for designing and executing organic syntheses.  Coscientist consists of four components designed to search the web, write Python code, extract information from documentation, and program laboratory robotics.  The authors test Coscientist using several open and closed-source LLMs and present examples of the system's ability to plan and execute simple organic syntheses. 

* [ProtAgents](https://github.com/lamm-mit/ProtAgents)

* [AI Scientist from SakanaAI](https://github.com/SakanaAI/AI-Scientist?tab=readme-ov-file)

**Generative Design**

* [Wang, Haorui, et al. "Efficient Evolutionary Search Over Chemical Space with Large Language Models." _arXiv preprint arXiv:2406.16976_ (2024).](https://molleo.github.io/)

Introduce LLMs for conducting evolutionary algorithm searches. 

**Predictive modeling**

* [The Goldilocks paradigm: comparing classical machine learning, large language models, and few-shot learning for drug discovery applications](https://www.nature.com/articles/s42004-024-01220-4) 

* [Jablonka, Kevin Maik, et al. "Leveraging Large Language Models for Predictive Chemistry." (2023).](https://chemrxiv.org/engage/chemrxiv/article-details/652e50b98bab5d2055852dde). [Peer-review](https://www.nature.com/articles/s42256-023-00788-1)

Authors show GPT3 based predictive models perform on-par with SOTA with lower data points. Caution is the models are purely text-based and extreme black box and sometimes, while trite, correlation doesnt mean causation might become important here. Finally the fine tuning doesnt do regression on the data in same sense as a linear regression or random forest would do.

* [BindGPT](https://arxiv.org/abs/2406.03686)

* [Nach0](https://arxiv.org/abs/2311.12410)

* [Tx-LLM](https://arxiv.org/html/2406.06316v1)

The team is looking at creating an LLM-based predictive model (regression and classification). They show that one large model can be used to predict multiple end points (think of one model used for all ADME endpoints), and it indicates that training on a variety of tasks can improve overall performance (positive transfer learning). 

I am glad to see this work as it shows how much information and feature-richness can be encoded within the transformer model, especially in the low-data regime; that said,  one caution with this approach is that the models are purely text-based and extremely black box and correlation doesn’t mean causation, more so here since we don’t have good control over features being used to train the model.

**Small molecule related tasks**

* [Le, Khiem, et al. "MolX: Enhancing Large Language Models for Molecular Learning with A Multi-Modal Extension." arXiv preprint arXiv:2406.06777 (2024).](https://arxiv.org/pdf/2406.06777)

* [Liu, Shengchao, et al. "Multi-modal molecule structure–text model for text-based retrieval and editing." Nature Machine Intelligence 5.12 (2023): 1447-1457.](https://www.nature.com/articles/s42256-023-00759-6)

* [Yu, Botao, et al. "LlaSMol: Advancing Large Language Models for Chemistry with a Large-Scale, Comprehensive, High-Quality Instruction Tuning Dataset." arXiv preprint arXiv:2402.09391 (2024).](https://osu-nlp-group.github.io/LLM4Chem/)

* [Pei, Qizhi, et al. "BioT5+: Towards Generalized Biological Understanding with IUPAC Integration and Multi-task Tuning." arXiv preprint arXiv:2402.17810 (2024).](https://arxiv.org/pdf/2402.17810.pdf)

BioT5+ incorporates several novel features: integration of IUPAC names for molecular understanding, inclusion of extensive bio-text and molecule data from sources like bioRxiv and PubChem, the multi-task in struction tuning for generality across tasks, and a novel numerical tokenization technique for improved processing of numerical data. 

* [Irwin, R., Dimitriadis, S., He, J., Bjerrum, E.J., 2021. Chemformer: A Pre-Trained Transformer for Computational Chemistry. Mach. Learn. Sci. Technol.](https://github.com/MolecularAI/Chemformer). Previously called [MolBART](https://github.com/MolecularAI/MolBART)

* [LLM-based generation and benchmarking](https://www.deepmirror.ai/post/one-molecular-generator-to-rule-them-all)

* [Language + Molecule Benchmarks](https://github.com/language-plus-molecules/LPM-24-Tutorial)

**Protein design and mechanics**

* [Ruffolo, Jeffrey A., and Ali Madani. "Designing proteins with language models." Nature Biotechnology 42.2 (2024): 200-202.](https://www.nature.com/articles/s41587-024-02123-4)

* [Buehler, Eric L., and Markus J. Buehler. "X-LoRA: Mixture of Low-Rank Adapter Experts, a Flexible Framework for Large Language Models with Applications in Protein Mechanics and Design." arXiv preprint arXiv:2402.07148 (2024).](https://arxiv.org/abs/2402.07148)

Mixture of LoRA Experts: Leverage the power of fine-tuned LoRA experts by employing a mixture of experts, or MoE technique.

* [Ghafarollahi, Alireza, and Markus J. Buehler. "ProtAgents: Protein discovery via large language model multi-agent collaborations combining physics and machine learning." arXiv preprint arXiv:2402.04268 (2024).](https://arxiv.org/abs/2402.04268)

**Clinical text**

* [Van Veen, D., Van Uden, C., Blankemeier, L. et al. Adapted large language models can outperform medical experts in clinical text summarization. Nat Med (2024).](https://www.nature.com/articles/s41591-024-02855-5). [Github](https://github.com/StanfordMIMI/clin-summ)

Authors look at clinical summarization and implement quantitative assesments with synctactic, semantic, and conceptual NLP metrics. A clinical reader study with 10 physicians evaluated summary completeness, correctness and conciseness; in most cases, summaries from our best-adapted LLMs were deemed either equivalent (45%) or superior (36%) compared with summaries from medical experts. The research provides evidence of LLMs outperforming medical experts in clinical text summarization across multiple tasks. This suggests that integrating LLMs into clinical workflows could alleviate documentation burden, allowing clinicians to focus more on patient care.

* [Saab, K.; et. al. Capabilities of Gemini Models in Medicine. arXiv May 1, 2024.](https://doi.org/10.48550/arXiv.2404.18416)

Google's team shows Med-Gemini's real-world utility by surpassing human experts on tasks such as medical text summarization, alongside demonstrations of promising potential for multimodal medical dialogue, medical research and education.

**Data curation**

* [Extracting Structured Data from Free-form Organic Synthesis Text](https://github.com/qai222/LLM_organic_synthesis)

Hackathon to quickly fine-tune GPT to parse synthesis data and extract relevant chemistry-related information. 

**Material science**

* [Gruver, Nate, et al. "Fine-Tuned Language Models Generate Stable Inorganic Materials as Text." arXiv preprint arXiv:2402.04379 (2024).](https://arxiv.org/abs/2402.04379)

##  Data extraction 

**Rule-based tool**

* [LeadMine - NextMove](https://www.nextmovesoftware.com/leadmine.html)

**AI-based tool**

Despite so much progress around computer vision and optical character recognition (OCR) the state of the art for molecule image conversion to structure still remains to be manual curation. There have been some interesting tools proposed for automating this using different flavor of computer-vision algorithms. 

* [MolGrapher](https://github.com/DS4SD/MolGrapher)

* [Img2Mol](https://github.com/bayer-science-for-a-better-life/Img2Mol)

One of the core reasons this area has been under explored seems to be molecule patents are MADE to be tough to decipher. The format is non standard and markush enumerations, alongside, their actual chemical space coverage is ill-defined. 

* [DECIMER](https://github.com/Kohulan/DECIMER-Image_Transformer)

DECIMER Image Transformer: Deep Learning for Chemical Image Recognition using Efficient-Net V2 + Transformer. [V1](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-021-00538-8). Extraction of chemical structure through OSCR (Optical chemical structure recognition) from Steinbeck's group. 

* [Fan, Vincent, et al. "OpenChemIE: An information extraction toolkit for chemistry literature." _Journal of Chemical Information and Modeling_ (2024).](https://pubs.acs.org/doi/10.1021/acs.jcim.4c00572)

Focused on the extraction of reaction data from journals. OpenChemIE is most suited for information extraction on organic chemistry literature, where molecules are generally depicted as planar graphs or written in text and can be consolidated into a SMILES format.

* [Ai, Q., Meng, F., Shi, J., Pelkie, B. G., & Coley, C. W. (2024). Extracting structured data from organic synthesis procedures using a fine-tuned large language model. Digital Discovery.](https://pubs.rsc.org/en/content/articlelanding/2024/dd/d4dd00091a)

Using Llama-2 7b to extract entities from synthesis recipes from reactions. 

## Code / Packages:

* [Molecular AI department at AstraZeneca R&D](https://github.com/MolecularAI)

* [Jazzy: Fast calculation of hydrogen-bond strengths and free energy of hydration of small molecules](https://www.nature.com/articles/s41598-023-30089-x)

* [GHOST: Generalized threshold shifting procedure](https://github.com/rinikerlab/GHOST). [Paper](https://pubs.acs.org/doi/10.1021/acs.jcim.1c00160). [Blogpost](https://greglandrum.github.io/rdkit-blog/exploratory/machinelearning/2021/12/23/ternary-ghost.html#Synthetic-datasets)

Automates the selection of decision threshold for imbalanced classification task. The assumption for this method to work is the similar characteristics (like imbalance ratio) of training and test data. 

* [MOSES - Benchmarking platform for generative models (PyTorch Implementation)](https://arxiv.org/abs/1811.12823). [Github](https://github.com/molecularsets/moses)

Benchmarking platform to implement molecular generative models. It also provides a set of metrics to evaluate the quality and diversity of the generated molecules. A benchmark dataset (subset of ZINC) is provided for training the models. 

* [Reinvent 4.0 - an AI tool forr de novo drug design](https://chemrxiv.org/articles/preprint/REINVENT_2_0_an_AI_Tool_for_De_Novo_Drug_Design/12058026/1). [Github](https://github.com/MolecularAI/Reinvent)

Production-ready tool for de novo design from Astra Zeneca. It can be effectively applied on drug discovery projects that are striving to resolve either exploration or exploitation problems while navigating the chemical space. Language model with SMILE  output and trained by “randomizing” the SMILES representation of the input data. Implement reinforcement-leraning for directing the model towards relevant area of interest. Now uses PyTorch 2.0! 

* [OpenChem](https://chemrxiv.org/articles/OpenChem_A_Deep_Learning_Toolkit_for_Computational_Chemistry_and_Drug_Design/12691943/1). [Github](https://github.com/Mariewelt/OpenChem)

* [DeepChem (Tensorflow)](https://github.com/deepchem/deepchem). [Website](https://deepchem.io) 

DeepChem aims to provide a high quality open-source toolchain that democratizes the use of deep-learning in drug discovery, materials science, quantum chemistry, and biology - from Github

* [ChemProp (Pytorch)](https://github.com/chemprop/chemprop)

Github repository for implmenting message passing neural networks for molecular property prediction as described in the paper [Analyzing Learned Molecular Representations for Property Prediction](https://pubs.acs.org/doi/abs/10.1021/acs.jcim.9b00237) by Yang et. al. 

* [FastJTNN - python 3 version of the JT-NN](https://github.com/Bibyutatsu/FastJTNNpy3)

* [DimeNet++  - extension of Directional message pasing working (DimeNet)](https://arxiv.org/abs/2003.03123). [Github](https://github.com/klicperajo/dimenet)

* [BondNet - Graph neural network model for predicting bond dissociation energies, considers both homolytic and heterolytic bond breaking](https://github.com/mjwen/bondnet). [Github](https://github.com/mjwen/bondnet)

* [AutodE](https://duartegroup.github.io/autodE/)

* [DScribe](https://singroup.github.io/dscribe/latest/)

* [RMG - Reaction Mechanism Generator](https://github.com/ReactionMechanismGenerator/RMG-Py)

Tool to generate chemical reaction networks. Includes Arkane, package for calculating thermodynamics from quantum mechanical calculations. 

* [PyePAL](https://pyepal.readthedocs.io/en/latest/?badge=latest)

Active learning approach to efficiently and confidently identify the Pareto front with any regression model that can output a mean and a standard deviation.

* [rxnfp](https://github.com/rxn4chemistry/rxnfp)

Github repository to generate chemical reaction fingerprints from reaction SMILES. 

* [mols2grid](https://github.com/cbouy/mols2grid)

Interactive chemical viewer for small molecules (RDKit wrapper)

* [molplotly](https://github.com/wjm41/molplotly)

Spotfire like capabilities to jupyter notebook. Medium article on explaining the MolPlotly. [Link](https://medium.com/@qcojuandavidmarin/molplotly-a-wonderful-tool-for-the-scientist-5ddb9a42c037?utm_source=pocket_saves)

* [ESPsim](https://github.com/hesther/espsim)

Calculate similarities of shapes and electrostatic potentials between molecules. Pen has a nice blogpost on using to estimate electronic similarities of common bioisosteres. [blog](https://iwatobipen.wordpress.com/2022/12/31/calculate-similarity-of-popular-bioisosters-rdkit-espsim-memo/)

* [HotSpots: Curran, Peter R., et al. "Hotspots api: a python package for the detection of small molecule binding hotspots and application to structure-based drug design." Journal of chemical information and modeling 60.4 (2020): 1911-1916.](https://github.com/prcurran/hotspots/tree/master?tab=readme-ov-file#scoring)

Survey protein surfaces for binding hotspots can help to evaluate target tractability and guide exploration of potential ligand binding regions. 

* [MolPal](https://github.com/coleygroup/molpal)

Active learning methodology for sampling the chemical space 

* [Generative Toolkit 4 Scientific Discovery](https://github.com/GT4SD/gt4sd-core)

* [Jazzy + Chemprop](https://github.com/ghiander/chemprop-jazzy)

Chemprop version that combines Jazzy (AZ's workflow for predicting H-bond strength)

## Datasets & Chemical libraries 

**Molecule datasets**

* PubChem: public sourced molecules 
* ChEMBL: bioactive molecules (most synthetic)
* SUREChEMBL: small molecules appearing in Patents 
* ZINC: collection of synthetic molecules (not all are bioactive) 
* QM 7/8/9: small molecules having not more than 7/8/9 heavy atoms 
* GDB-17
* [Papyrus](https://chemrxiv.org/engage/chemrxiv/article-details/617aa2467a002162403d71f0)
* [COCONUT](https://jcheminf.biomedcentral.com/articles/10.1186/s13321-020-00478-9): NP 400k there are some which are not NP 
* [Mcule](https://mcule.com/database/): Used in DEL enumerations 
* [DrugBank](https://go.drugbank.com/)

**Reaction Datasets**

* USPTO 
* Pistachio
* Reaxys
* Open Reaction Database 

**Commercial (building block) vendors**

* eMolecules 
* Enamine  
* WuXi 
* Chembridge
* Asinex
* Molport
* Pharmablock
* Otava's CHEMriya 

## Helpful utilities:

* [RD-Kit](https://github.com/rdkit/rdkit)
    * [Get Atom Indices in the SMILE:](https://colab.research.google.com/drive/16T6ko0YE5WqIRzL4pwW_nufTDn7F3adw)

    * [Datamol for manipulating RDKit molecules](https://github.com/datamol-org/datamol)
 
* [MOSES: Molecular generation models benchmark](https://github.com/molecularsets/moses)

* [Therapeutics Data Commons](https://tdcommons.ai)

Therapeutics Data Commons is an open-science platform with AI/ML-ready datasets and learning tasks for therapeutics, spanning the discovery and development of safe and effective medicines. TDC also provides an ecosystem of tools, libraries, leaderboards, and community resources, including data functions, strategies for systematic model evaluation, meaning

