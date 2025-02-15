# **Tender Touch: AI-Based Meat Freshness and Texture Simulation Model**

## **Project Overview**  
**Tender Touch** is an AI-driven system designed to assess meat freshness using **Convolutional Neural Networks (CNNs)**. By leveraging image processing and deep learning techniques, the model classifies meat into categories like **Fresh, Half-Fresh, and Spoiled**, improving accuracy and efficiency in food safety evaluation.

## **Key Features**  
- 🚀 AI-based **freshness detection** using CNN simulations.  
- 🔍 **Automated image classification** to overcome traditional manual inspections.  
- 🎨 **Preprocessing techniques** to capture color variations and texture changes.  
- 📊 **High accuracy model**, validated on diverse datasets.  

## **Dataset**  
- **Source:** Kaggle dataset with various meat types, cuts, and conditions.  
- **Split:**  
  - 🏋️ **Training:** 80%  
  - 🛠 **Validation:** 20%  
  - 🔬 **Testing:** 10%  

## **Files in This Repository**  
📂 `train/` & `valid/` – Image datasets for training and validation.  
📜 `Meat_Freshnessss.ipynb` – Jupyter Notebook implementing CNN model.  
🧠 `Meat_FreshnessTrainedModel.keras` – Pretrained Keras model. 

## **Installation & Usage**  
### **1. Clone the repository and install dependencies**  

[🔗 GitHub Repository: Tender Touch](https://github.com/momina-nz/Tendor-Touch)  

```bash
git clone https://github.com/momina-nz/Tendor-Touch
cd Tendor-Touch
pip install -r requirements.txt
```
### **2. Run the Jupyter Notebook for model training & evaluation**  
```bash
jupyter notebook Meat_Freshnessss.ipynb
```
### **3. Load the pretrained model and classify images**  
```bash
from tensorflow.keras.models import load_model  
model = load_model('Meat_FreshnessTrainedModel.keras')  
```
## **Results & Accuracy**  

✅ **High classification accuracy** achieved through **iterative parameter tuning**.  
📌 **Reliable predictions** on unseen meat images, making it suitable for real-world applications.  
📊 **Evaluation metrics** demonstrate robustness in freshness classification.  

## **References**  

📚 Smith, J., & Jones, M. (2022). _Application of Convolutional Neural Networks in Meat Quality Assessment_.  
📚 Simonyan, K., & Zisserman, A. (2014). _Very Deep Convolutional Networks for Large-Scale Image Recognition_.  
