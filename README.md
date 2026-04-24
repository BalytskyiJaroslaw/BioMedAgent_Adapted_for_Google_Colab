# BioMedAgent Adapted for Google Colab

> **Unofficial Google Colab adaptation of BioMedAgent**  
> Open in Colab, enter your API key, upload the required input files, and follow the notebook prompts.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BalytskyiJaroslaw/BioMedAgent_Adapted_for_Google_Colab/blob/main/BioMedAgent_adapted_for_Google_Colab.ipynb)

In the current form, the notebook is doing 5 tasks: `statistics_t_test`, `machine_learning`, `statistics_qq_plot`, `visualization_survival_plot`, `visualization_violin_plot`. 

## Overview

This repository provides an **unofficial, Colab-oriented adaptation** of **BioMedAgent**, a multi-agent LLM framework for biomedical data analysis.

In the above notebook, click this cell to setup the environment in Colab: 

![Setting_up_the_environment](./Screenshot%202026-04-23%20122623.png)

Then, enter your API key, choose the task for BioMedAgent to perform, and upload the corresponding data to process: 

![Enter API key, choose task, and upload data](Screenshot%202026-04-23%20122640.png)

The original demo input data are available in the [`Demo_data`](https://github.com/BalytskyiJaroslaw/BioMedAgent_Adapted_for_Google_Colab/tree/main/Demo_data) folder.

The demo outputs for cross-checking are available in the [`Demo_outputs`](https://github.com/BalytskyiJaroslaw/BioMedAgent_Adapted_for_Google_Colab/tree/main/Demo_outputs) folder.

This cell initializes the BioMedAgent model: 

![Initialize the BioMedAgent model](Screenshot%202026-04-23%20122646.png)

This cell starts GPTServer and CodeExecutor, which are required to run BioMedAgent:

![Start GPTServer and CodeExecutor](Screenshot%202026-04-23%20122654.png)

This cell executes the task, shows intermediate outputs and processing steps, and saves the results:

![Execute the task and save results](Screenshot%202026-04-23%20122703.png)

> Note that unlike the official BioMedAgent implementation, where the `t_test` helper relies on the `bio_r` environment and explicitly calls `Rscript`, this Colab adaptation implements the `t_test` helper in Python, and thus, there is no R dependency in the t-test workflow.

This is an **accessible reproduction** arranged to run directly in **Google Colab**.

This repository is intended for users who want to:

- quickly try BioMedAgent in Colab,
- reproduce the public demo workflow with minimal setup,
- avoid local environment friction,
- use a notebook-based interface with prompts for required inputs.

## Intended use

This repository is mainly for:

- **reproduction**
- **demonstration**
- **educational/testing purposes**
- **easier first access to the BioMedAgent workflow**

It is **not** an official release from the original BioMedAgent Authors.

## Quick start

1. Click the [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BalytskyiJaroslaw/BioMedAgent_Adapted_for_Google_Colab/blob/main/BioMedAgent_adapted_for_Google_Colab.ipynb)
 badge.
2. Run the setup cells.
3. Enter your API key when prompted.
4. Upload the required input file(s) when prompted by the notebook.
5. Continue through the notebook cells to launch the adapted BioMedAgent workflow.

## Important disclaimer

- This repository is an **unofficial adaptation**.
- Credit for the original BioMedAgent framework belongs to the original Authors.

## Original BioMedAgent

You can download all their data using this notebook: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BalytskyiJaroslaw/BioMedAgent_Adapted_for_Google_Colab/blob/main/BioMedAgent_Download_Data.ipynb)

Original repository:  
`https://github.com/BOBQWERA/BioMedAgent`

BioMedAgent is presented by the original Authors as a multi-agent LLM framework for biomedical data analysis.

If you use BioMedAgent in academic work, please cite the **original BioMedAgent paper**.

## Citation

If this Colab adaptation helps you access or reproduce BioMedAgent, please cite the **original work**:

```bibtex
@article{bu2026empowering,
  title={Empowering AI data scientists using a multi-agent LLM framework with self-evolving capabilities for autonomous, tool-aware biomedical data analyses},
  author={Bu, Dechao and Sun, Jingbo and Li, Kun and He, Zihao and Huang, Wei and Hu, Jinlin and Zhang, Shanshan and Lei, Shuangshuang and Huo, Peipei and Wang, Zhihao and others},
  journal={Nature Biomedical Engineering},
  pages={1--16},
  year={2026},
  publisher={Nature Publishing Group UK London}
}
