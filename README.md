
# AI & ML Course
The course equips you to:

1. **Design and Implement AI & ML Infrastructure**  
   Develop end-to-end environments—data pipelines, model development frameworks, and cloud deployment platforms.

2. **Master AI & ML Algorithms and Techniques**  
   Apply supervised, unsupervised, reinforcement learning and deep learning methods to real-world problems.

3. **Develop Intelligent Troubleshooting Agents**  
   Create autonomous AI-powered agents capable of diagnosing and resolving issues without human intervention.

4. **Leverage Microsoft Azure for AI & ML Workflows**  
   Set up, manage, and optimize the entire AI & ML lifecycle using Azure services and best practices.

---

## 📂 Repository Structure

```
AI-ML-COURSE/
├── authentication-in-azureml/
│   ├── authentication-in-azureml.ipynb
│   ├── svc-pr-1.PNG
│   ├── svc-pr-2.PNG
│   ├── svc-pr-3.PNG
│   └── svc-pr-4.PNG
├── data/
│   ├── Credit Score Classification Dataset.csv
│   ├── quotes.json
│   └── student.csv
├── deploy-to-cloud/
│   ├── model-register-and-deploy.ipynb
│   ├── model-register-and-deploy.yml
│   ├── README.md
│   └── score.py
├── production-deploy-to-aks/
│   ├── production-deploy-to-aks.ipynb
│   ├── production-deploy-to-aks.yml
│   ├── production-deploy-to-aks-ssl.ipynb
│   ├── production-deploy-to-aks-ssl.yml
│   └── sklearn_regression_model.pkl
├── applying_transfer_learning.ipynb
├── course3mlai.ipynb
├── dev_gen_models.ipynb
├── finetunningC3M1P1.ipynb
├── lora.ipynb
├── qlora.ipynb
└── WomensECommerce.ipynb
```

---

## 📖 Module Summaries

### 1. authentication-in-azureml  
Demonstrates service principal authentication in Azure ML, plus sample “scoring” images (`svc-pr-*.PNG`).

### 2. data  
Contains datasets used across exercises:
- **Credit Score Classification Dataset.csv**  
- **student.csv**  
- **quotes.json**

### 3. deploy-to-cloud  
Covers model registration and deployment to Azure ML:
- `model-register-and-deploy.ipynb` — end-to-end demo  
- `model-register-and-deploy.yml` — Azure ML pipeline definition  
- `score.py` — scoring script

### 4. production-deploy-to-aks  
Hands-on with Kubernetes deployments:
- `production-deploy-to-aks.ipynb` / `.yml`  
- `production-deploy-to-aks-ssl.ipynb` / `.yml`  
- Pre-trained model: `sklearn_regression_model.pkl`

### 5. applying_transfer_learning.ipynb  
Fine-tuning and transfer-learning workflows on custom datasets.

### 6. course3mlai.ipynb  
Advanced Azure-hosted ML scenarios: MLOps patterns, automated retraining.

### 7. dev_gen_models.ipynb  
Explores generative model development and evaluation.

### 8. finetunningC3M1P1.ipynb  
Module 3, Lesson 1 project: fine-tuning deep learning models.

### 9. lora.ipynb & qlora.ipynb  
Implementations of LoRA (Low-Rank Adaptation) and QLoRA for parameter-efficient tuning.

### 10. WomensECommerce.ipynb  
Capstone: end-to-end ML pipeline for Women’s E-Commerce analytics and recommendation.

---

## ⚙️ Prerequisites

- Python 3.8+  
- `pip install azureml-sdk scikit-learn pandas numpy matplotlib tensorflow pytorch flask fastapi`  
- Azure subscription with permissions to create ML resources  
- Azure CLI & Azure ML CLI extensions installed  

---

## 📫 Contact & Next Steps

Feel free to **fork**, **star**, and **explore**!  
Questions or collaboration? Reach out:

- 🌐 Portfolio: [kevscastillo.github.io](https://kevswit.github.io)  
- 🐙 GitHub: [@KevsWit](https://github.com/KevsWit)  
- 🔗 LinkedIn: [kevicast](https://linkedin.com/in/kevicast)  

