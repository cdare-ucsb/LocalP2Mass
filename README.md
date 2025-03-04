# DerivedCategoryMass

DerivedCategory mass is a project stemming from my Ph.D. work on the mass evolution of certain objects in the catagories relevant to the B-Model of string theory; however, this question also provides context about the relation between birational models of certain Calabi-Yau varieties obtained from considering the moduli-space of the skyscraper sheaf under wall-crossing.

For a general picture of applications where this is useful, in physics we typically contextualize the setting in which large-scale events occur as 4D-spacetime which is modeled using some Lorentzian manifold. Field theories (such as QFTs, CFTs) additionally describe the data of quantum (local) fields over the spacetime manifold as sections of tensor bundles (for example scalar fields = Higgs bundle, spinor fields = electrons, quarks), along with some symmetry data. Motivated by the Kaluza-Klein model — which predicts that at low energies a dimension unifying electromagnetism and gravity should be undetectable — we assume that the fundamental forces arise from dimensions too small to observe directly, and thus must be mathematially _compact_.  While supersymmetry (SUSY) is a significant assumption on such a field theory, mathematically it solves some notable issues stemming from the large quantum corrections of the Higgs boson at high energies. It turns out that the assumption that our theory survives at least __N__=1 supersymmetry in low energies requires that the compactified dimensions admit a covariantly constant spinor, and thus has a _SU(3)_ holonomy — in other words, our compactified dimensions are Calabi-Yau.

Backtracking somewhat to gauge theory, it turns out that not all gauge fields in our field configuration should be physically significant. In order to admit a vacuum state solution, there must exist a global minimum of the Yang-Mills action; for Gauge fields, the occurs if and only if the connection on the vector bundle is a Hermite-Einstein connection. By a theorem of Donaldson-Ulhenbeck-Yau, this is mathematically equivalent to the bundle being slope-stable with respect to some Kähler class.  In string theory, objects depending on some choice of Kähler class are often modified by world-sheet instanton corrections. In this context, the vacuaa are described as BPS vacua and correspond to Bridgeland-stable objects in the derived category of our compactified dimensions (i.e. the Calabi-Yau threefold). Unfortunately, only one example of a complex compact Kahler threefold that admits geometric Bridgeland stability conditions is known [Li (2019)](https://link.springer.com/article/10.1007/s00222-019-00888-z).



## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## Introduction

DeepGanModel is designed to simplify the process of creating and training GANs. It provides a set of tools and utilities to help you build, train, and evaluate GAN models.

## Installation

To install the required dependencies, run:

```sh
pip install -r requirements.txt
```

## Usage

To run the project, execute:

```python
python run.py
```

## Project Structure 

```
__pycache__/
.pytest_cache/
.vscode/
app/
    __init__.py
    models/
    routes.py
    static/
    templates/
config.py
data/
docs/
README.md
requirements.txt
run.py
src/
tests/
```

- `app`: Contains the application code for Flask to serve the correct files
- `config.py`: Configuration files for the project
- `data`: Directory for storing data files
- `docs`: Documentation files
- `src`: The main source code for the backend mass computations
- `tests`: Unit tests for the project

## License 

This project is licensed under the MIT License. See the LICENSE file for details.