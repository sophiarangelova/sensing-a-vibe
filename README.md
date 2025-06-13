# sensing-a-vibe

This repository accompanies the MA thesis
"Sensing a Vibe: Facilitating Serendipitous Discovery and Engagement for Casual Users via Digital Exploration through Internet Aesthetics. An Artpedia Case Study."
by Sofiya Rangelova, University of Amsterdam, 2025.

# Overview
This project examines how organizing digital cultural heritage collections by internet aesthetics, utilizing a searchless, visually organized interface, can enhance user engagement and facilitate serendipitous discovery for casual users. 

The repository contains:

The codebook used for manual annotation, compiled using the scraped Internet Aesthetics from the Aesthetics Fandom Wiki that can be accessed [here]/https://aesthetics.fandom.com/wiki/Category:Internet_Aesthetics 

The code (Jupyter notebook) used for data processing and automated classification experiments with large language models (LLMs).

The compiled dataset of internet aesthetics (IA) categories, scraped and curated from the Aesthetics Wiki, as used for classification and annotation tasks in the thesis.

The primary art dataset (Artpedia) used for annotation and experimentation is publicly available [here]\(https://aimagelab.ing.unimore.it/imagelab/page.asp?IdPage=35) and is not redistributed in this repository.

# Repository Contents

internet_aesthetics_codebook.pdf

Contains all internet aesthetics featured in internet_aesthetics_dataset.csv, with short descriptions and accompanying images.


internet_aesthetics_dataset.csv
The full list of internet aesthetics categories and metadata as used in the thesis.


sensing_a_vibe_notebook.ipynb
Jupyter notebook containing all code for:

Data preprocessing

LLM-based classification experiments (zero-shot and two-shot)

Data analysis and visualization

README.md
This file.

How to Use
Clone the repository

text
git clone https://github.com/yourusername/sensing-a-vibe.git

Install dependencies
The notebook uses Python 3.x and standard data science libraries (see the first cell of the notebook for details).
For LLM experiments, you will need an OpenAI API key.

Access the Artpedia dataset
Download the Artpedia dataset from its official repository and place it in your working directory if you wish to replicate the full experiments.

Run the notebook
Open sensing_a_vibe_notebook.ipynb in Jupyter or VS Code and follow the instructions in the notebook cells.

Citation
If you use this code or the IA dataset, please cite:

Rangelova, S. (2025). Sensing a Vibe: Exploring Serendipitous Discovery and Engagement for Casual Users via Digital Exploration of Internet Aesthetics for Digital Cultural Heritage Collections (Master’s thesis, University of Amsterdam).

License
This repository is licensed under the MIT License. See LICENSE.md for details.

Contact
For questions, please contact Sofiya Rangelova at [sofiya.rangelova@student.uva.nl].
