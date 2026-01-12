# Exploring Art through Internet Aesthetics

This repository accompanies the demo paper “Exploring Art through Internet Aesthetics: A Serendipitous Interface for Artpedia” by Sophia Rangelova, Jaap and the master’s thesis “Sensing a Vibe: Integrating Internet Aesthetics into an Exploratory Interface for the Serendipitous Navigation of the Artpedia Dataset” (University of Amsterdam, 2025) by Sophia Rangelova.


# Overview
This project examines how organizing digital cultural heritage collections by internet aesthetics, utilizing a searchless, visually organized interface, can enhance user engagement and facilitate serendipitous discovery for casual users. 

The repository contains:

The codebook used for manual annotation, compiled using the scraped Internet Aesthetics from the Aesthetics Fandom Wiki that can be accessed [here]/https://aesthetics.fandom.com/wiki/Category:Internet_Aesthetics 


The manual annotation results for all coders


The results for zero-shot and two-shot prompting LLM classification results


The code (Jupyter notebook) used for data processing and automated classification experiments with large language models (LLMs).


The compiled dataset of internet aesthetics (IA) categories, scraped and curated from the Aesthetics Wiki, as used for classification and annotation tasks in the thesis.


The primary art dataset (Artpedia) used for annotation and experimentation is publicly available [here]\(https://aimagelab.ing.unimore.it/imagelab/page.asp?IdPage=35) and is not redistributed in this repository.


# Repository Contents

internet_aesthetics_codebook.pdf

Contains all internet aesthetics featured in internet_aesthetics_dataset.csv, with short descriptions and accompanying images.


manual_annotation_results_all_coders.csv

Contains all annotations done by 3 coders, title of the image 


zero-shot_&_two_shot_LLM_classification_results.csv

Contains results from automated classification with LLMs for zero-shot and two-shot prompting


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

If you use this repository, code, or internet aesthetics dataset in academic work, please cite:

Demo paper
Rangelova, S. (2026). Exploring Art through Internet Aesthetics: A Serendipitous Interface for Artpedia (demo paper).

Thesis
Rangelova, S. (2025). Sensing a Vibe: Integrating Internet Aesthetics into an Exploratory Interface for the Serendipitous Navigation of the Artpedia Dataset (Master’s thesis, University of Amsterdam).


License

This repository is licensed under the MIT License. See LICENSE.md for details.


Contact

For questions, please contact Sophia Rangelova at [sophiarangelova7@gmail.com].
