# 👋 Hi, I'm [Sechan Lee]  
I am currently in my fourth year of undergraduate studies in Computer Education at Sungkyunkwan University.  
I also participating in undergraduate research student in **swlab**(Prof.Min https://swlab.skku.edu/sw/index.do) for the past year.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)

---

## 🎓 Education
- **[BS]**, [Computer Education] (GPA: 4.43/4.5) **(Top 3%)**  
  Sungkyunkwan University, (2024.3 ~ 2026.2)
- **[AS]**, [Computer Information]  (GPA: 4.32/4.5) **(Magna Cum Laude)**  
  JEI University, (2019.3 ~ 2021.2)

---

## 🔬 Research Interest
- **Energy Efficient DeepLearning**
- **LLM Quantization, Distillation**
- Adversarial Attack
- **Anything about AI**

---
## 💻 Project  
### **[BAG: BERT-Attention GNN] (KCC 2025 under review)**  
I development a hybrid model, **BAG (BERT-Attention GNN)**, to effectively detect illegal gambling websites by combining the text and structural information of HTML tags. The proposed model analyzes the text of each HTML tag using BERT to generate an illegality score, which is then incorporated into the attention operations of a GAT to enhance the information from important nodes. Additionally, a Weighted Pooling technique is introduced to ensure that nodes containing illegal keywords contribute more significantly to the final prediction. Experimental results using HTML data from both illegal gambling and normal websites demonstrate excellent performance, achieving an accuracy of 0.89. Further ablation studies validate that the BERT-Attention mechanism significantly contributes to the model’s performance improvement.  

<div align="center">
  <img width="985" alt="Screenshot 2025-04-29 at 10 59 51 AM" src="https://github.com/user-attachments/assets/9975360b-ac96-40c2-9e85-4e9c0df8a377" />
  <img width="480" alt="Screenshot 2025-04-29 at 10 48 46 AM" src="https://github.com/user-attachments/assets/4e44aa1d-d0ee-4af0-bd24-9e61eb270a67" />
</div>  

**Github: https://github.com/chan1031/BAG**    
**Paper: [KCC.pdf](https://github.com/user-attachments/files/19951182/KCC.pdf)**  


### **[Stealth X-ADV]** (2024.10 ~ Present)  
Stealth X-ADV is an adversarial attack technique designed to target AI-based X-ray object detectors deployed in airports and seaports. In X-ray imaging, traditional adversarial attack methods based on texture or color manipulation are ineffective. Instead, adversarial objects must be crafted by manipulating tensors that represent the vertices of the object structure. Although a prior method, X-ADV (https://arxiv.org/abs/2302.09491), has been proposed, it faces the limitation that the generated adversarial objects are easily noticeable.
To address this, our project investigates whether it is possible to enhance the stealthiness of adversarial objects. Specifically, we aim to attack X-ray object detectors more covertly by using everyday items, such as keys, to create adversarial examples that blend naturally into their surroundings.  
<div align="center">
  <img width="480" alt="Screenshot 2025-04-29 at 10 48 46 AM" src="https://github.com/user-attachments/assets/a5dc27bc-968c-44d9-9395-7a157e69a6bd" />
</div>  

**Github: https://github.com/chan1031/X-adv2**

### **[SKKU LLM]** (2025.3 ~ Present)  
SKKU LLM is a large language model (LLM) specialized for Sungkyunkwan University (SKKU). As LLM technology continues to advance, domain-specific models such as sLLMs (specialized LLMs) are becoming increasingly important. In this project, we aim to fine-tune the **Llama-3-Open-Ko-8B** model to develop an SKKU-specific LLM.  

**Step 1: Crawling**  
We crawl all publicly available articles from www.skku.edu using a Depth-First Search (DFS) algorithm. After crawling, we preprocess the collected data to remove unnecessary information. Then, we use a GPT API to transform the data into a QA dataset format suitable for training. 
     
**Step 2: Fine-tuning**    
We fine-tune the base model to fit the specific needs of SKKU. To enable efficient training, we apply FP8 quantization and LoRA (Low-Rank Adaptation) techniques during fine-tuning.  
  
**Step 3: Inference Optimization**    
For real-world deployment, fast inference speed is essential. We study lightweight optimization techniques to accelerate inference while operating within limited computational resources.  
<div align="center">
  <img width="480" alt="Screenshot 2025-04-29 at 10 48 46 AM" src="https://github.com/user-attachments/assets/f869d618-a23d-43c1-a913-9ff67eb781f6" />
</div>  

**Github: https://github.com/chan1031/skku_sLLM**

---
