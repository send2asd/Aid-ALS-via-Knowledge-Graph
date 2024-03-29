# Aid Amyotrophic Lateral Sclerosis via Knowledge Graph

## Overview
This project, as detailed in `finale.ipynb`, focuses on two primary aspects: Entity Merging and Relationship Extraction, Knowledge graph validation and Refinement. These components are integral to processing and analyzing complex data structures in a specific domain.

### Entity Merging
This section of the project deals with the process of entity canonicalization, duplicate detection, and the merging of entities, as outlined in the report.

### Relationship Extraction
The project employs an ensemble method, incorporating elements of Stanford OpenIE, to extract relationships from the data.

### Validation of KG and Refinement
This project uses manual validation of knowledge graph and then refined that by passing addition argument like publication id.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries (ast, gensim, ipywidgets, itertools, json, nltk, numpyls, networkx, os, pandas, matplotlib, random, signal, scikit-learn, stanza, stanford_openie, subprocess, tensorflow)

### Installation
1. Clone the repository or download the `finale.ipynb` notebook.
2. Install Python 3.x and Jupyter Notebook if not already installed.
3. Install the required Python libraries by running the command: pip install library-name.
4. Download glove/GoogleNews-vectors-negative300.bin which is pre-trained Word2Vec model.
5. install stanza, stanford_openie and CoreNLPClient. Also insure to change local host port.



### Running the Notebook
1. Open Jupyter Notebook in your environment.
2. Navigate to the location of `finale.ipynb`.
3. Open the notebook and run the cells sequentially to see the results.

## Structure
The notebook is divided into two main sections:

1. **Entity Merging:** Here, the notebook goes through the process of entity canonicalization, followed by duplicate detection and entity merging.
2. **Relationship Extraction:** This section describes the ensemble method used for extracting relationships, utilizing Stanford OpenIE.
3. **Validation of KG and Refinement:** Validated th KG manually and then refined them. For refinement uses the publication id and make entoty unique by publication id and have pass those entoty with the abstract of that perticular publication id.


## License
No License

## Acknowledgements
Project has been devloped by 3 developers. 2 developers used mac and 1 used windows.  Section 9-14 may cause problem in mac. So install comaptible library.
