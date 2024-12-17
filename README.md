# Master's thesis: **Comparative evaluation of Retrieval-Augmented Generation (RAG) pipelines: analysis of traditional, GraphRAG and hybrid techniques**


## Overview
This repository contains all the resources, source code, and experiments for my Master's Thesis titled **"Comparative evaluation of Retrieval-Augmented Generation (RAG) pipelines: analysis of traditional, GraphRAG and hybrid techniques"**. The research focuses on the exploration and comparison of different RAG methodologies to overcome the limitations of traditional RAG systems and extend their applicability to complex tasks such as query-focused summarization.

The repository includes:
- Source code for experiments and simulations.
- Jupyter Notebooks with analyses and visualizations.
- Datasets used during the research.
- Documentation produced as part of the thesis.

---

## Table of Contents
1. [Introduction](#introduction)
2. [Repository Composition](#repository-composition)
3. [Technologies Used](#technologies-used)
4. [Results](#results)
5. [How to Perform Similar Tests](#how-to-perform-similar-tests)


---

## Introduction
The goal of this thesis is to explore and compare different Retrieval-Augmented Generation (RAG) pipelines, focusing on traditional, GraphRAG, and hybrid approaches. Traditional RAG systems, while effective for certain tasks, face limitations when applied to complex problems. This work aims to address these challenges by analyzing alternative techniques that can enhance the performance and adaptability of RAG systems.
In particular, the thesis evaluates the applicability of RAG methodologies to tasks such as **query-focused summarization**, where the ability to retrieve relevant context and generate accurate, tailored outputs is critical. By combining traditional RAG with advanced techniques like GraphRAG in hybrid models, this research demonstrates how the strengths of both approaches can be leveraged to extend RAG systems for solving more demanding and domain-specific problems.

**Main Components:**
- Development of a **traditional RAG pipeline**.
- Development of a **GraphRAG pipeline**.
- Implementation of a **hybrid pipeline** combining both traditional RAG and GraphRAG approaches.
- Implementation of experiments involving **question answering** and **query-focused summarization** tasks.
- Evaluation of performance through both **human expert evaluation** and an **LLM-as-a-judge approach**.
- Writing of the thesis document and preparation of the presentation.

---

## Repository Composition
The repository is structured as follows:
- **Doc**: Contains the thesis document and the presentation slides.
- **Narrative Test**: Includes notebooks and unofficial test codes performed on simple narrative datasets.
- **Official Thesis Experimentation**: Contains the official experimentation resources, including datasets, notebooks, and scripts used for the thesis experiments.

---

## Technologies Used
The project leverages the following technologies and tools:

- **Languages**: Python 3.11
- **Tools/Libraries**:
  - LangChain
  - GraphRAG

GraphRAG has been configured to use open-source private models following the tutorial available at [Autogen GraphRAG Ollama](https://github.com/karthik-codex/Autogen_GraphRAG_Ollama).

---

## Results
The primary results of this thesis include:
- The experimentation demonstrated that the **traditional RAG pipeline** performs better for tasks involving **question answering**.
- The **GraphRAG pipeline** achieves superior results when applied to more complex tasks such as **query-focused summarization**.
- The **hybrid pipeline**, which combines both traditional RAG and GraphRAG approaches, outperforms the individual pipelines by leveraging their strengths, achieving the best overall results.

Visualizations and insights are provided within the notebooks.

---

## How to Perform Similar Tests
To replicate or extend the experiments presented in this thesis:
1. Download **GraphRAG** and configure your private models, or insert your API keys if you wish to use public LLMs.
2. Modify the **parameters** to adapt them to your specific requirements.
3. Select datasets suitable for your experimentation.
4. Preprocess the data using **LlamaParse**, as done in the official experimentation.
5. Use the provided **Notebooks** as templates to conduct a similar test.
6. Evaluate the results using an **LLM-as-a-judge** approach.
7. Visualize and analyze the outcomes to draw insights.

---

## Author
**Tommaso Martinelli**  
