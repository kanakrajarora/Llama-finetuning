# 🚀 Fine-Tuning LLaMA with LoRA on a Custom Dataset  

This repository contains code to fine-tune **LLaMA (LLaMA-2/3)** on a custom dataset using **LoRA (Low-Rank Adaptation)**. LoRA enables efficient fine-tuning of large language models while reducing GPU memory usage.  

---

## Video demonstration
https://youtu.be/ZYRiFmkdD6k

## 📌 Features
- ✅ Fine-tunes **LLaMA-2 8B** or **LLaMA-3 7B** using Hugging Face’s Transformers and PEFT  
- ✅ Implements **LoRA (Low-Rank Adaptation)** for parameter-efficient fine-tuning  
- ✅ Runs on **Google Colab** with GPU support  
- ✅ Supports **custom dataset processing** (JSON/CSV format)  
- ✅ Saves the fine-tuned model and uploads it to **Hugging Face Model Hub**  

## ⚙️ Setup & Installation
### 🛠 1️⃣ Clone the Repository
```bash
git clone https://github.com/kanarajarora/Llama-finetuning.git
cd fine-tuning-llama-lora
```

### 📦 2️⃣ Install Dependencies  
```bash
pip install -r requirements.txt
```

### 🔑 3️⃣ Authenticate Hugging Face
```bash
from huggingface_hub import notebook_login
notebook_login()
```
 
