# Towards Analysable Chaos-based Cryptosystems: Constructing Difference Distribution Tables for Chaotic Maps

<!--[![DOI](https://zenodo.org/badge/DOI/10.XXXX/zenodo.XXXXXX.svg)](https://doi.org/10.XXXX/zenodo.XXXXXX) 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) -->

## Abstract

Chaos-based cryptography has yet to achieve practical, real-world applications despite extensive research. A major challenge is the difficulty in analysing the security of these cryptosystems, which often appear ad hoc in design. Unlike conventional cryptography, evaluating the security margins of chaos-based encryption against attacks such as differential cryptanalysis is complex. This paper introduces a straightforward approach of using chaotic maps in cryptographic algorithms in a way that facilitates cryptanalysis. We demonstrate how a chaos-based substitution function can be constructed using fixed-point representation, enabling the application of conventional cryptanalysis tools such as the difference distribution table. As a proof-of-concept, we apply our method to the logistic map, showing that differential properties vary based on the initial state and number of iterations. Our findings demonstrate the feasibility of designing analyzable chaos-based cryptographic components with well-understood security margins.

## Usage

The repository contains a Jupyter Notebook (`Chaos_Experiments.ipynb`) which includes all the code used for constructing the difference distribution tables for chaotic maps as discussed in the paper.

### Running the Notebook Locally

1. Clone the repository:
    ```bash
    git clone https://github.com/diffsearch/chaos_ddt.git
    cd chaos_ddt
    ```

2. Ensure you have Jupyter Notebook installed. If not, install it using pip:
    ```bash
    pip install notebook
    ```

3. Open the Jupyter Notebook:
    ```bash
    jupyter notebook Chaos_Experiments.ipynb
    ```

4. Execute the cells in the notebook to reproduce the results.

### Running the Notebook on Google Colab

1. Open Google Colab: [https://colab.research.google.com/](https://colab.research.google.com/)

2. In the top menu, click on `File` > `Open notebook`.

3. Select the `GitHub` tab and enter the repository URL: `https://github.com/diffsearch/chaos_ddt`.

4. Click the notebook file (`Chaos_Experiments.ipynb`) to open it.

5. Execute the cells in the notebook to reproduce the results.

