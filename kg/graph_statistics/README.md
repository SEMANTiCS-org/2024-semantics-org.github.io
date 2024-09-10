# Statistics about the Semantics 2024 KG

The script `generate_stats.py` generates statistics on the Semantics 2024 KG. It will also serialize the KG in TTL.

## Requirements
* rdflib
* matplotlib

## Running scripe
From the current folder: `python generate_stats.py`

## Statistics results:
- Number of accepted papers (Research, Industry, Posters and Demos):  73
- Number of papers with resources: 45
- Papers with datasets, with code or ontologies:
    - Software Source Code: 43
    - Ontology: 8
    - Demo: 14
    - Dataset: 17
- Resources with license:  39
- Papers with resources with license:  25
- Papers with no license in some resource:  28
- Resources with DOIs:  7
- Papers with resources with DOIs:  5
- Papers storing data in GitHub:  2

<p align="center">
 <img src="./plots/research.png" alt="research papers" width="40%"/>
 <img src="./plots/posters.png" alt="research papers" width="40%"/>
</p>
