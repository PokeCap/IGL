# Finding the Math Department's Deep Structure

## Introduction

The "barycenter" folder is part of the research project titled "Finding the Math Department's Deep Structure," conducted by the Illinois Geometry Laboratory (IGL). This sub-project focuses on finding Barycenters in the space of Phylogenetic Trees, aiming to map and analyze the convergence of research interests among mathematics professors. By constructing these Phylogenetic Trees, the project seeks to represent and visualize distinct areas within the field of mathematics.

---

## Features

- Generate distance matrices using an existing dataset, based on similarities in references, journals, MSC codes, keywords, and extended co-author networks.
- Construct phylogenetic trees from these distance matrices.
- Evaluate the resulting trees and clusterings for alignment with the department's existing research structure.
- Aggregate the generated trees to identify plausible barycenters.
- Use these barycenters to detect and define research clusters within the department.

## Installation

### Prerequisites

Make sure you have Python installed on your system. This project requires Python 3.8 or higher.

### Required Packages

The following packages are required to run this project:

- `numpy`
- `scipy`
- `scikit-learn`
- `matplotlib`
- `pandas`
- `networkx`
- `ujson`
- `os` (built-in, no need to install)
- `io` (built-in, no need to install)
- `collections` (built-in, no need to install)
- `ete3`
