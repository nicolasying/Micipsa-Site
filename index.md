# Micipsa

Similarity and Association: 
Principles of Distributed Semantic Processing in the Human Brain, 

a research project conducted within the program of Cogmaster and SPEIT Master's, carried out in CAMS - CNRS/EHESS.


## What is Micipsa

How are word-meanings comprehended in natural languages, and how does our brain process lexical semantics? If word-meanings and concepts emerge based on perceptual/affective input, how are the abstract concepts processed? How does the usage of language refine word-meanings? We approach the neural processing of lexical semantics by dissociating the generalized, abstract and amodal *similarity* from sensorimotor/affective/syntagmatic semantic *association* information. These two hypothetical semantic principles are proposed to accommodate structural linguistic theories, pathological observations and neuroscience models. By hypothesizing that *similarity* is an hierarchical taxonomical organization of concepts based on Patterson et al's semantic-hub (and Paivio's dual-coding theory), we are able to build computational semantic representation models and that of *association* as an umbrella term, comprising perceptual-, affective- and episodic-dependent semantics as well as phrasal semantic control. fMRI recordings conducted in an ecological auditory narration comprehension setting serve as ground truth data. With an fMRI voxel-level neural activity encoding experiment with linear regression models and semantic representation models finely-tuned for each of the two semantic principles, the local preferences shown for the principles are contrasted by the regression model accuracy scores. Notably we tested the theorized anteroventrotemporal loci of semantic hub, and the results suggest the hub processes semantics of a mixed nature.

## Dive into the project

The project is mostly publicly available online disclosing anonymous and insensitive data and codes. As in the order of method presentation in the master's thesis, multiple repositories host relatively independent implementations of the methods.

1. The foundation of *similarity* space: [WordNet Embedding](https://github.com/nicolasying/WordNet-Embeddings)

2. The construction of *similarity* and *association* semantic spaces: [Semantic Decorrelation](https://github.com/nicolasying/Micipsa-Decorrelation)

3. With semantic spaces, build The Little Prince neural activation patterns: [Text Preprocessing](https://github.com/nicolasying/Micipsa-Text-Preprocessing)

4. Set up fMRI encoding environment and perform voxel-wise regressions: [Encoding](https://github.com/nicolasying/Micipsa)


## Article/Report

An [article](https://www.biorxiv.org/content/10.1101/2020.01.11.899831v1) has been submitted to bioRxiv preprint server. 
More results coming up.

Functional MRI Investigation on Paradigmatic and Syntagmatic Lexical Semantic Processing

Songsheng Ying, Sabine Ploux

bioRxiv 2020.01.11.899831; doi: https://doi.org/10.1101/2020.01.11.899831 

## Results

View the [brain](/pycortex.html) map generated with pycortex.

The pycortex visualization is generated with fsl auto-alignment. [Manual corrected alignment (unverified)](/pycortexdilated.html) are available too.