RNA binding project
=====

# Biological question

Proteins and RNA do not act as independent biomolecules, but also orchestrate
cell biology through protein-RNA interactions. Cross-linking experiments
followed by RNA-seq are a useful way of detecting these interactions. Could
training a ML model on this data be able to predict if a given protein binds
to a given RNA molecule?

# Questions to test



Protein of interest [ELAVL1](https://www.encodeproject.org/genes/1994/)

ENCODE API: https://www.encodeproject.org/help/rest-api/

Processed DataSet (HF): https://huggingface.co/datasets/morrislab/eclip

DKC1
DKC1 encodes dyskerin, a core RNA-binding and catalytic protein in H/ACA small nucleolar ribonucleoprotein (snoRNP) complexes. It functions in telomere maintenance. Dyskerin binds to the telomerase RNA component (TERC/hTR) to stabilize and support telomerase activity, which protects chromosome ends


Main objectives
---------------
1. first: download the sequences
2. second
3. third

## Jupyter Notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/dgruano/elixir_AI4LS_rna_binding/blob/main/rna_binding_eclip.ipynb)

Open and run the notebook directly in Google Colab: [`rna_binding_eclip.ipynb`](./rna_binding_eclip.ipynb)
