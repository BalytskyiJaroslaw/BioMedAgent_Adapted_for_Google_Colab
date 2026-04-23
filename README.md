# BioMedAgent Adapted for Google Colab

> **Unofficial Google Colab adaptation of BioMedAgent**  
> Open in Colab, enter your API key, upload the required input files, and follow the notebook prompts.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://github.com/BalytskyiJaroslaw/BioMedAgent_Adapted_for_Google_Colab/blob/main/BioMedAgent_adapted_for_Google_Colab.ipynb)
## Overview

This repository provides an **unofficial, Colab-oriented adaptation** of **BioMedAgent**, a multi-agent LLM framework for biomedical data analysis.

The goal of this repository is **practical reproduction and accessibility**: instead of requiring a local Conda environment, Redis setup, and additional manual configuration, this version is arranged to run directly in **Google Colab** with a more guided workflow.

This repository is intended for users who want to:

- quickly try BioMedAgent in Colab,
- reproduce the public demo workflow with minimal setup,
- avoid local environment friction,
- use a notebook-based interface with prompts for required inputs.

## What this adaptation does

This Colab adaptation is designed to make the public BioMedAgent workflow easier to run by:

- organizing setup inside a notebook,
- prompting the user for their API key,
- prompting the user to upload the required files,
- reducing manual environment configuration,
- making the demo workflow easier to reproduce in Google Colab.

## Intended use

This repository is mainly for:

- **reproduction**
- **demonstration**
- **educational/testing purposes**
- **easier first access to the BioMedAgent workflow**

It is **not** presented as an official release from the original BioMedAgent authors.

## Quick start

1. Click the **Open in Colab** badge above.
2. Run the setup cells.
3. Enter your API key when prompted.
4. Upload the required input file(s) when prompted by the notebook.
5. Continue through the notebook cells to launch the adapted BioMedAgent workflow.

## Notes

- This repository is an **unofficial adaptation**.
- Credit for the original BioMedAgent framework belongs to the original authors.
- This repository focuses on making the public workflow easier to run in **Google Colab**.
- Some tasks in the original project may require additional tooling or environments beyond the simplest Colab demo flow.

## Original BioMedAgent

Original repository:  
`https://github.com/BOBQWERA/BioMedAgent`

BioMedAgent is presented by the original authors as a multi-agent LLM framework for biomedical data analysis.

## Important disclaimer

This repository is **not** the official BioMedAgent repository.

It is an **independent Colab adaptation** intended to help users reproduce and test the public BioMedAgent workflow in a notebook-based environment.

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
