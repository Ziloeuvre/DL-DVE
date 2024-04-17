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


### Licence 

MIT License

Copyright (c) [2024] [Ziloeuvre]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

