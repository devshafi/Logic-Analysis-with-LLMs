
# Exploring the Use of LLMs for Predicate Logic Understanding and Formalization​

This project explores the capabilities of Large Language Models (LLMs) in understanding, translating, and reasoning with predicate logic.

## Project Overview

The repository contains experiments analyzing how LLMs perform in translating natural language sentences into formal first-order logic (FOL) notation. The analysis includes both Chain of Thought (CoT) and In-Context Learning (ICL) approaches.

## Repository Structure

- **Notebooks**:
  - `LLM_Predicate_Logic_Project.ipynb`: Natural language to logic translation
  - `LLM_Predicate_Logic_CoT.ipynb`: Chain of Thought experiments
  - `LLM_Predicate_Logic_ICL.ipynb`: In-Context Learning experiments
  - `analysis_cot.ipynb`: Analysis of CoT results
  - `analysis_icl.ipynb`: Analysis of ICL results
  - `analysis.ipynb`: General analysis
  - `data_visualization.ipynb`: Visualizations of results

- **Data**:
  - `dataset/data.csv`: Source dataset
  - `results_cot.csv`: Results from Chain of Thought experiments
  - `results_icl.csv`: Results from In-Context Learning experiments
  - `results.csv`: Aggregated results
  - `llm_text2log_outputs.csv`: Model outputs translating text to logic

## Methodology

The project investigates the performance of LLMs in understanding and translating natural language sentences (like "Some men are wolves") into first-order logic expressions (such as "exists x1.(_man(x1) & exists x2.(_wolf(x2) & (x1 = x2)))").

Two main approaches are explored:
1. **Chain of Thought (CoT)**: Prompting the model to explain its reasoning process step by step
2. **In-Context Learning (ICL)**: Providing examples to guide the model's translations

## Results

The notebooks contain detailed analysis of model performance, including:
- Accuracy metrics for different types of logical statements
- Comparison between CoT and ICL appro

## Getting Started

1. Clone this repository
2. Install the required dependencies (see requirements in notebooks)
3. Run the notebooks in your preferred environment

## Requirements

- Python 3.x
- Pandas
- Jupyter
- LLM API access (specifics in notebooks)


## Contact

f.shafi@queensu.ca and ing.tao@queensu.ca