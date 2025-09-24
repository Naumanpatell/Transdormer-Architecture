
# 🧠 Transformer Architecture Notes  

This repository contains my detailed study notes on the **Transformer Architecture** – the backbone of modern NLP and Large Language Models (LLMs) like BERT, GPT, and T5.  
The goal of this repo is to **document my learning journey** and provide a structured reference for revision and sharing.  

---

## 📑 Contents  

- 🔹 **Introduction to Transformers**  
  - Why Transformers replaced RNNs & LSTMs  
  - Advantages over sequential models  

- 🔹 **Self-Attention Mechanism**  
  - Queries, Keys, Values (Q, K, V)  
  - Scaled Dot-Product Attention  

- 🔹 **Multi-Head Attention**  
  - Parallel attention heads  
  - Learning multiple representation subspaces  

- 🔹 **Positional Encoding**  
  - Injecting order into input sequences  
  - Sine and cosine functions  

- 🔹 **Encoder-Decoder Architecture**  
  - Layer breakdown  
  - Role of encoders vs. decoders  

- 🔹 **Applications**  
  - Machine Translation  
  - Text Summarisation  
  - BERT, GPT, and other LLMs
 


- 🔹 **Refrences**
  - Vaswani et al. – "Attention Is All You Need" (2017)
  
      

```math
Attention(Q, K, V) = softmax\left(\frac{QK^T}{\sqrt{d_k}}\right)V
