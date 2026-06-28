# 🚀 Fine-Tuning LLMs with LoRA & QLoRA

![Python](https://img.shields.io/badge/Python-3.10-blue)
![PyTorch](https://img.shields.io/badge/PyTorch-2.x-red)
![Transformers](https://img.shields.io/badge/HuggingFace-Transformers-yellow)
![PEFT](https://img.shields.io/badge/PEFT-LoRA-green)
![License](https://img.shields.io/badge/License-MIT-blue)

A complete end-to-end notebook demonstrating efficient fine-tuning of Large Language Models (LLMs) using modern Parameter-Efficient Fine-Tuning (PEFT) techniques such as LoRA and QLoRA.

---

##  Overview

Training billion-parameter language models is expensive.

This project demonstrates how to fine-tune an LLM using only a small number of trainable parameters while maintaining high performance.

The notebook covers:

- Loading a pre-trained LLM
- Dataset preparation
- 4-bit Quantization using BitsAndBytes
- LoRA Configuration
- PEFT Integration
- Supervised Fine-Tuning (SFT)
- Model Inference
- Saving the Fine-Tuned Model

---

##  Features

-  LoRA Fine-Tuning
-  QLoRA (4-bit Quantization)
-  PEFT
-  Hugging Face Transformers
-  TRL SFTTrainer
-  Accelerate
-  Memory Efficient Training
-  Google Colab Compatible

---

## 🛠 Tech Stack

| Library | Purpose |
|----------|----------|
| Transformers | Load LLM |
| PEFT | LoRA Fine-Tuning |
| TRL | SFT Trainer |
| Datasets | Dataset Loading |
| BitsAndBytes | Quantization |
| Accelerate | Faster Training |
| PyTorch | Deep Learning |

---

## 📂 Repository Structure

```
Fine-Tuning-LLMs-with-LoRA-and-QLoRA
│
├── Fine_Tuning_LLM_with_LoRA_QLoRA.ipynb
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## ⚙ Installation

Clone the repository

```bash
git clone https://github.com/santanu211/Fine-Tuning-LLMs-with-LoRA-and-QLoRA.git
```

Move into the folder

```bash
cd Fine-Tuning-LLMs-with-LoRA-and-QLoRA
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

##  Workflow

```
Dataset
   │
   ▼
Tokenizer
   │
   ▼
Load Pretrained Model
   │
   ▼
4-bit Quantization
   │
   ▼
Apply LoRA
   │
   ▼
SFT Trainer
   │
   ▼
Fine-Tuning
   │
   ▼
Inference
```

---

##  Concepts Covered

- Large Language Models
- Transformers
- Tokenization
- Quantization
- LoRA
- QLoRA
- PEFT
- Hugging Face
- TRL
- Fine-Tuning
- Inference

---

## Results

- Successfully fine-tuned an LLM
- Reduced GPU memory using QLoRA
- Efficient parameter-efficient training
- Ready for inference

---

##  Future Improvements

- Add Evaluation Metrics
- Push Model to Hugging Face Hub
- Add Weights & Biases Logging
- Multi-GPU Training
- Streamlit Demo
- Gradio Interface

---

## 🤝 Contributing

Pull requests are welcome.

Feel free to fork this repository and improve it.

---

## ⭐ Show your support

If this project helped you,

⭐ Star this repository.

---

## 👨‍💻 Author

**Santanu Pal**

GitHub:
https://github.com/santanu211

---

## 📄 License

This project is licensed under the MIT License.