# Dengue Virus Genome Evolution Predictor

Predict the sequence of the evolving serotype through generative models and identify its closest match using a classification model.

## Introduction

The process of evolution in viral genomes poses challenges in diagnosis and vaccine effectiveness. This work focuses on the Dengue virus genome, which currently has four known serotypes. We aim to predict the sequence of the emerging serotype and determine its closest match among the existing serotypes.

### Models Details

- Generative Model: LSTM-based model that predicts the sequence for the emerging serotype based on evolutionary patterns.
- Classification Model: Classifies Dengue virus genomes into their respective serotypes.

## Features

- Labels: DENV Serotypes i.e., DNV1, DNV2, DNV3, and DNV4
- Features: Complete Genome Nucleotide sequences 

## Getting Started

### Prerequisites

Ensure you have all required libraries installed. Refer to the "All libraries" file for the complete list.

### Data Download

- Refer to the file `DNV-cont(original).fas` for the dataset.

### Implementation of models 

- Explore the `generative_model.ipynb` for the generative model implementation.
- Explore the `classification_model.ipynb` for the classification model implementation.

### Comparison of models 

- For comparing generative models, refer to the folder `Comparison-models`

### Similarity check

- To check similarity of generated sequences with other serotypes, refer to `similarity_check_generted_Sequence.ipynb`.



[![DOI](https://zenodo.org/badge/788123864.svg)](https://zenodo.org/doi/10.5281/zenodo.10988909)

