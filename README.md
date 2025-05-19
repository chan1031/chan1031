# 👋 Hi, I'm [Sechan Lee] [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/se-chan-lee-6b168b224/)  

I am currently in my fourth year of undergraduate studies in Computer Education at Sungkyunkwan University.  
I also participating in undergraduate research student in **swlab**(Prof.Min https://swlab.skku.edu/sw/index.do) for the past year.  
### **[Paper implementation & review ](https://github.com/chan1031/paper-review)**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)

---

## 🎓 Education
- **[BS]**, [Computer Education] (GPA: 4.43/4.5) **(Top 3%)**  
  Sungkyunkwan University, (2024.3 ~ 2026.2)
- **[AS]**, [Computer Information]  (GPA: 4.30/4.5) **(Magna Cum Laude)**  
  JEI University, (2019.3 ~ 2021.2)

---
## 💼 Experience
- **SWlab** (prof. Moohong Min) (https://swlab.skku.edu/sw/index.do) [2024.7 ~ Present]   
  **Undergraduate Students**  
  Research Area: AI Development, Adversarial Attack  
- **TA**, Basic and Applications of AI  [2024.9 ~ Present]
  In the "Basic and Applications of AI" course, I covered an introduction to the Transformer architecture and its implementation in code.  

## 🔬 Research Interest  
I can enjoy anything about AI, CS  
- Saftey AI
- Adversarial Attack
- Safety Benchmark
- AI Kill-Switch

---

## 🎓 Publication
- BAG: A hybrid “BERT-Attention GNN“ model for Illegal Site Detection from HTML / KCC 2025
(Under Review) / First author  
Paper: [KCC.pdf](https://github.com/user-attachments/files/20015436/KCC.pdf)  
- TriModal: A Multimodal Framework for Detecting Redirection to Illegal OnlineGamblingSites / DFRWS APAC 2025 (Under Review) / Second author  
Paper:[DFRWS2025.pdf](https://github.com/user-attachments/files/20284293/DFRWS2025.pdf)  
- Analysis of Deepfake Detection Models Against Deepfake Crimes / Mobisec 2024 / First author  
Paper: [Mobisec_Analysis of Deepfake Detection Models Against Deepfake Crimes.pdf](https://github.com/user-attachments/files/20284494/Mobisec_Analysis.of.Deepfake.Detection.Models.Against.Deepfake.Crimes.pdf)  
- Malware Attacks Targeting Industrial Facilities and Response Strategies / ACK 2024 / First author  
Paper: [Malware Attacks Targeting Industrial Facilities and Response Strategies.pdf](https://github.com/user-attachments/files/20284697/Malware.Attacks.Targeting.Industrial.Facilities.and.Response.Strategies.pdf)

---
## 💻 Project  
### 1.BAG: BERT-Attention GNN (KCC 2025 under review)  
**Github: https://github.com/chan1031/BAG**    
**Paper: [KCC.pdf](https://github.com/user-attachments/files/20015436/KCC.pdf)**  
I development a hybrid model, **BAG (BERT-Attention GNN)**, to effectively detect illegal gambling websites by combining the text and structural information of HTML tags. The proposed model analyzes the text of each HTML tag using BERT to generate an illegality score, which is then incorporated into the attention operations of a GAT to enhance the information from important nodes. Additionally, a Weighted Pooling technique is introduced to ensure that nodes containing illegal keywords contribute more significantly to the final prediction. Experimental results using HTML data from both illegal gambling and normal websites demonstrate excellent performance, achieving an accuracy of 0.89. Further ablation studies validate that the BERT-Attention mechanism significantly contributes to the model’s performance improvement.  

<div align="center">
  <img width="985" alt="Screenshot 2025-04-29 at 10 59 51 AM" src="https://github.com/user-attachments/assets/9975360b-ac96-40c2-9e85-4e9c0df8a377" />
  <img width="480" alt="Screenshot 2025-04-29 at 10 48 46 AM" src="https://github.com/user-attachments/assets/4e44aa1d-d0ee-4af0-bd24-9e61eb270a67" />
</div>  


### 2.Stealth X-ADV 
**Github: https://github.com/chan1031/Stealth_X-adv**  
Stealth X-ADV is an adversarial attack technique designed to target AI-based X-ray object detectors deployed in airports and seaports. In X-ray imaging, traditional adversarial attack methods based on texture or color manipulation are ineffective. Instead, adversarial objects must be crafted by manipulating tensors that represent the vertices of the object structure. Although a prior method, X-ADV (https://arxiv.org/abs/2302.09491), has been proposed, it faces the limitation that the generated adversarial objects are easily noticeable.
To address this, our project investigates whether it is possible to enhance the stealthiness of adversarial objects. Specifically, we aim to attack X-ray object detectors more covertly by using everyday items, such as keys, to create adversarial examples that blend naturally into their surroundings.  
<div align="center">
  <img width="480" alt="Screenshot 2025-04-29 at 10 48 46 AM" src="https://github.com/user-attachments/assets/a5dc27bc-968c-44d9-9395-7a157e69a6bd" />
</div>  

### 3.SKKU-LLM  
**Github: https://github.com/chan1031/skku_sLLM**  
SKKU LLM is a large language model (LLM) specialized for Sungkyunkwan University (SKKU). As LLM technology continues to advance, domain-specific models such as sLLMs (specialized LLMs) are becoming increasingly important. In this project, we aim to fine-tune the **Llama-3-Open-Ko-8B** model to develop an SKKU-specific LLM.  

**Step 1: Crawling**  
We crawl all publicly available articles from www.skku.edu using a Depth-First Search (DFS) algorithm. After crawling, we preprocess the collected data to remove unnecessary information. Then, we use a GPT API to transform the data into a QA dataset format suitable for training. 
     
**Step 2: Fine-tuning**    
We fine-tune the base model to fit the specific needs of SKKU. To enable efficient training, we apply FP4 quantization and LoRA (Low-Rank Adaptation) techniques during fine-tuning.  
  
**Step 3: Inference Optimization**    
For real-world deployment, fast inference speed is essential. We study lightweight optimization techniques to accelerate inference while operating within limited computational resources.  
<div align="center">
  <img width="480" alt="Screenshot 2025-04-29 at 10 48 46 AM" src="https://github.com/user-attachments/assets/f869d618-a23d-43c1-a913-9ff67eb781f6" />
</div>  


### 4.Tracking Illegal Gambling Website  [Selected 2025-1 SKKU CO-Deeplearning]  
**Github: https://github.com/skku-swlab/illegal_gambling-detector**  
The operation of illegal gambling websites poses a serious threat to our society.  
However, manually identifying and blocking these sites is highly impractical.  
To address this challenge, our SWLab has developed an AI-powered tracking system for detecting illegal gambling websites.  

🕸️ Web Crawling Modules  
1. OCR-Based Banner Image Analysis  
Illegal gambling websites often use promotional banners for advertising. We apply OCR (Optical Character Recognition) technology to detect such banners and extract associated URLs for further crawling.  

2. Redirection Analysis  
Operators of illegal gambling sites often hack legitimate websites and set up redirections that reroute visitors to illegal destinations. Our system identifies and analyzes such hidden redirections.  

3. SMS Spam Dataset Analysis  
We utilize the spam SMS dataset provided by KISA to periodically extract and update known illegal gambling URLs.  

4. Social Media Crawling  
We crawl promotional posts from platforms such as Instagram, X (formerly Twitter), and Facebook to identify and collect illegal gambling URLs.  

5. Telegram sLLM Chatbot  
To ensure more precise enforcement, blocking must go beyond URLs to include associated bank account numbers. We are developing a specialized GPT Telegram chatbot capable of extracting bank account information from chat messages.  
Model: https://chatgpt.com/g/g-6829c37cdb648191b8b594db10a3a945-co-deep-mdoel/c/682b0e45-9c2c-800b-b8ec-3f09ce888770

<div align='center'>
<img width="790" alt="image" src="https://github.com/user-attachments/assets/8db21a56-6e9e-468d-9397-1cf5662ff86e" />
</div>

🤖 AI-Based Classification Modules  
1. Image Classification  
Illegal gambling websites tend to share visually similar design elements. We classify these images using CNN-based architectures such as EfficientNet and ResNet.  

2. HTML Structure Analysis  
We apply our newly developed BAG (BERT-Attention GNN) architecture to effectively analyze and classify the HTML structure of websites for illegal gambling indicators.  

<div align="center">
  <img width="480" alt="Screenshot 2025-04-29 at 10 48 46 AM" src="https://github.com/user-attachments/assets/e258c7f3-6868-4539-a3f1-440ee5aca357" />
</div>  

