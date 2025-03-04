# DeepkSeek R1 1.5B Finetuning

## Overview
This repository provides an **end-to-end solution** for fine-tuning the **DeepSeek R1 1.5B** model using **LoRA (Low-Rank Adaptation)**. The methodology follows best practices for **domain-specific text generation** while keeping computational efficiency in mind.

## Features
- ✅ Memory-efficient fine-tuning with **LoRA**
- ✅ Based on **Hugging Face Transformers**
- ✅ Works with **custom datasets**
- ✅ Includes a **fully executable Jupyter Notebook**

## Getting Started
### Prerequisites
Ensure you have the required dependencies installed:
```bash
pip install transformers peft torch datasets accelerate
```

### Clone the Repository
```bash
git clone https://github.com/itzdeenzxx/DeepkSeek_R1_1_5B_Finetuning.git
cd DeepkSeek_R1_1_5B_Finetuning
```

### Running the Notebook
Open the notebook in Jupyter or Google Colab:
```bash
jupyter notebook DeepkSeek_R1_1_5B_Finetuning_LoRA_sample.ipynb
```

Follow the step-by-step instructions to fine-tune the model on your dataset.

## Fine-Tuning Process
- 1️⃣ **Install dependencies**: Set up necessary libraries.
- 2️⃣ **Load DeepSeek R1 1.5B**: Utilize Hugging Face Transformers.
- 3️⃣ **Integrate LoRA**: Apply low-rank adaptation for efficient training.
- 4️⃣ **Prepare Dataset**: Load and preprocess domain-specific text.
- 5️⃣ **Fine-Tune**: Execute training with optimized parameters.
- 6️⃣ **Evaluate**: Validate model performance on test data.

## Resources
- 🔗 Colab Notebook: [Open in Google Colab](https://colab.research.google.com/drive/12nB0-QC5DU9hL79Q9eBtXEXLMEvAYMpk?usp=sharing)
- 🔗 Reference Guide: [Fine-Tuning DeepSeek R1 1.5B](https://www.linkedin.com/pulse/fine-tune-deepseek-r1-15b-free-gcp-colab-t4-hands-on-konathala-phd--4bluf/)

## Acknowledgements
- Thanks to **Hugging Face** for their robust **transformers** and **datasets** libraries.
- **LoRA implementation** is powered by **PEFT (Parameter-Efficient Fine-Tuning)**.


## Contact
For questions, issues, or contributions, feel free to open an **Issue** or **Pull Request** on GitHub.

📌 **Author:** [itzdeenzxx](https://github.com/itzdeenzxx)

