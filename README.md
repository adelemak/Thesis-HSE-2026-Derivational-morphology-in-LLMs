# Evaluation of Derivational Morphology in LLMs: Evidence from Russian
#### HSE 2026 Thesis
#### Adelina Makarova
#### Supervisor: Daria Ryzhova, Docent

This repository contains materials, data, and code for my thesis on **Derivational morphology in Large Language Models**, with a focus on **Russian agent noun formation**.

## Project overview

The study investigates how different large language models handle derivation from both existing and nonce Russian verbs and how their outputs compare to native-speaker responses.

The repository contains the following directories:

- **experiment 1** — model outputs and their comparison with human responses
- **experiment 2** — vector representations and clustering analysis

---

## Repository structure

### `experiment 1/`

This folder contains the materials and outputs for the first experiment, which compares model-generated derivatives with forms produced by native speakers.

Files include:

- `analysis_code.ipynb` — notebook used for processing and analysing the results of Experiment 1
- `model_outputs.csv` — collected outputs of the tested language models
- `human_reference.csv` — table witj native-speaker responses
- `model_vs_human_evaluation.csv` — comparison of model outputs with human-derived data
- `human_suffix_counts.csv` — counts of suffixes attested in native-speaker responses
- `suffix_distribution_counts.csv` — suffix frequency counts across humans and models
- `suffix_distribution_long.csv` — long-format table for suffix distribution analysis across all models and human speakers
- `suffix_distribution_table.csv` — summary table of suffix distributions
- `qwen.csv` — outputs and analysis related to Qwen
- `mistral.csv` — outputs and analysis related to Mistral

### `experiment 2/`

This folder contains the materials for the second, exploratory experiment based on vector representations and clustering.

Files and folders include:

- `verbs.csv` — list of stimulus verbs and their meanings
- `getting_vectos_Qwen.ipynb` — notebook for extracting vector representations from Qwen
- `getting_vectors_Mistral.ipynb` — notebook for extracting vector representations from Mistral
- `CLUSTERS.ipynb` — notebook for semantic similarity, clustering, and visualization analysis
- `embeddings_Qwen/` — saved embeddings extracted from Qwen (.npy files)
- `embeddings_mistral/` — saved embeddings extracted from Mistral (.npy files)
---
[Table](https://docs.google.com/spreadsheets/d/1AwOek70bDcFayr3xdRnRjhNuNkyr6Vp5hR9BV8_neFw/edit?usp=sharing) for experiment 3 with the results of annotation by native-speakers

## Models

The repository contains data related to the following models:

- [Qwen2.5-7B-Instruct](https://huggingface.co/Qwen/Qwen2.5-7B-Instruct)
- [Mistral-Nemo-Instruct-2407](https://huggingface.co/mistralai/Mistral-Nemo-Instruct-2407)
- [Claude](https://claude.ai/)
- [Yandex GPT 5.1 Pro](https://ya.ru/ai/gpt) (Accessed through AI Studio: https://aistudio.yandex.ru/ru)
- [Alice AI](https://ya.ru/ai/aliceai#section-llm) (Accessed through AI Studio: https://aistudio.yandex.ru/ru)
