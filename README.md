# Single subject task fMRI
Please note this is a learning project, and does not report scientific findings.

Description: I conducted an end-to-end analysis of one participant (sub-1004) from the OpenNeuro dataset ds006039, Category-specific Associative Inference in Memory.

Dataset used: OpenNeuro ds006039, subject sub-1004 (one of 41). Dataset can be found at: https://github.com/OpenNeuroDatasets/ds006039. Used under this project for learning purposes.

Experimental design: 
Participants completed study-test phases of the Associative Inference in Memory task while undergoing fMRI scanning. During the study phase, they encoded overlapping AB and BC pairs. A and C items were always objects. The linking B item was either a face or a scene. At test, memory for the direct (AB, BC) and indirect associations (inferred AC) was tested. (taken from:  https://direct.mit.edu/jocn/article-abstract/38/1/100/131668/Scene-sensitive-Medial-Temporal-Lobe-Subregions?redirectedFrom=fulltext)

Subject-1004 data: 
8 blocks * 188 volumes 
Odd blocks are Scene and even blocks are Face
Each block has study (n=16) and test(n=24) trials, AC trials only included in the testing phase


Task flow:

dataset: HCP made available by Neuromatch
Functional Activation & Contrast Analysis (GLM): ROI identification, statistical contrast maps to understand functional specialization across hemispheres and hemispheres-by-condition interactions.
Static and Dynamic functional connectivity and Psychophysiological Interactions (PPI) assessing how the functional connectivity between a seed region and the rest of the brain is modulated by the experimental task conditions.
Representational Similarity Analysis (RSA) 4.Connectome-based Predictive Modeling - CPM
Represented the 360 parcels as nodes and their functional connectivity as edges.
