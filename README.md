# cs182-final-project

🔍 Understanding Fine-Tuned GPT-2 on Algorithmic Tasks

This repository contains the code and data for our project exploring the mechanistic interpretability of GPT-2-small fine-tuned on two algorithmic tasks: array sorting and modular subtraction. We investigate how structured representations emerge across transformer layers and whether task-specific reasoning circuits can be identified.

📌 Key Features

Fine-tuning GPT-2-small on symbolic reasoning datasets

Linear probing to quantify layer-wise task encoding

Logit lens and Tuned Lens analysis to visualize prediction evolution

Attention head ablation to assess causal roles

Fourier analysis to detect potential periodic computation circuits

🧪 Tasks Studied

Array Sorting: Predicting sorted output from unsorted integer arrays (length ≤ 5)

Modular Subtraction: Computing (a - b) mod 97 with integer inputs

📁 Contents

array_sorting/: finetuned model, intermediate data and notebook for array sorting

mod_subtraction/: finetuned model, intermediate data and notebook for modular subtraction

📜 Paper

This project was the final project for CS 182, Spring 2025.
