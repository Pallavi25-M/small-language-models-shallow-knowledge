# Small Language Models for Shallow Knowledge Extraction

## Project Overview

This project investigates the use of Small Language Models (SLMs) for shallow knowledge extraction. It explores whether smaller language models can perform selected knowledge extraction tasks effectively compared with larger language models.

The project is inspired by the research paper *No Need to Be a Know-It-All: Fact Checking with Shallow Knowledge (SHALLKNOW)*.

The main objective is to study the capabilities, limitations, and efficiency of small language models in knowledge extraction tasks.

## Project Objectives

- Investigate the performance of small language models in knowledge extraction.
- Explore different approaches to extracting factual information.
- Compare individual models and ensemble-based approaches.
- Analyse the impact of model size on extraction quality.
- Examine computational efficiency and execution time.

## Repository Structure

```text
small-language-models-shallow-knowledge/
│
├── data/
│   └── BPDP_Dataset/
│
├── notebooks/
│   └── 01_BPDP_EDA.ipynb
│
├── reports/
│   └── Call_it_Milestone_2_EDA_Report.pdf
│
├── results/
│   └── figures/
│       ├── graph_size_distribution.png
│       └── predicate_frequency.png
│
├── .gitignore
└── README.md
```

## Dataset

The project currently uses the BPDP dataset for exploratory analysis.

The dataset contains RDF files organised into training and testing subsets, with True and False categories.

The exploratory analysis examines:
- Dataset distribution and organisation.
- RDF graph sizes and triple counts.
- Predicate frequencies.
- Subject and object characteristics.
- Differences between selected True and False RDF graphs.
- Potential data-quality issues.

## Tools and Technologies

The project uses the following technologies:

- **Python** – Data analysis and experimentation.
- **Jupyter Notebook** – Exploratory analysis and experiments.
- **RDFLib** – RDF graph parsing and processing.
- **Pandas and NumPy** – Data organisation and statistical analysis.
- **Matplotlib** – Data visualisation.
- **Git and GitHub** – Version control and collaboration.

## Current Progress

### Milestone 2 – Exploratory Data Analysis

The initial exploratory analysis of the BPDP dataset has been completed.

The work includes:
- Dataset structure and class distribution analysis.
- RDF triple and graph-size analysis.
- Predicate frequency analysis.
- Subject and object statistics.
- Selected True and False graph comparisons.
- Preliminary investigation of date-format inconsistencies.

The detailed results are available in the `notebooks/` and `reports/` directories.

## Running the Analysis

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project directory:

```bash
cd small-language-models-shallow-knowledge
```

3. Create and activate a Python virtual environment.

4. Install the required libraries:

```bash
pip install rdflib pandas numpy matplotlib jupyter
```

5. Open the project in Visual Studio Code and run:

```text
notebooks/01_BPDP_EDA.ipynb
```

Ensure that the BPDP dataset is placed in the `data/BPDP_Dataset/` directory before running the notebook.

## Team Members

- Wojciech Dudziński
- Wiktoria Drabińska
- Michał Żurawski
- Pallavi Manepalli

## Institution

Poznań University of Technology
