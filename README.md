# 🏗️ SaltSpot Dataset: Salt Damage Detection in Concrete Structures 🏛️  

## 📌 Overview  

The **SaltSpot dataset** is a collection of **3,799 images** 📸 of concrete surfaces, specifically designed for **deep learning applications in civil engineering**. This dataset enables **automated detection** of **salt damage** 🧂 on concrete structures using **computer vision techniques**.  

This dataset was used in the research:  
📄 *"SaltSpot: A Convolutional Neural Network Approach for Classifying Salt Contamination Damage on Civil Infrastructure"*.  
If you use this dataset in your research, please **cite our work** (see **Citation** section below).  

---

## 📂 Dataset Structure  

The dataset is divided into two **main classes**:  

- ✅ **Class 0 - •	Healthy structure:** Concrete surfaces without visible contamination or deterioration.  
- ❌ **Class 1 - •	Structure with salt damage:** Concrete surfaces with visible salt-related deterioration, including **spalling, scaling, discoloration, and crystal deposits**.  

### **📁 Folder Organization:**  
SaltSpot_Dataset/

│── train/ │ 

    ├── Class_0/ (Healthy Structures) │
  
    ├── Class_1/ (Salt Damaged Structures) │ 

│── valid/ │

    ├── Class_0/ (Healthy Structures) │
  
    ├── Class_1/ (Salt Damaged Structures) │

│── test/ │

    ├── Class_0/ (Healthy Structures) │ 
    
    ├── Class_1/ (Salt Damaged Structures) │

📌 **Images are in `.jpg` format** and have been preprocessed to **224x224 pixels** for deep learning applications.
---

## 🛠️ Usage

### **📥 Downloading the Dataset**
To download this dataset, clone this repository using:

    git clone https://github.com/yourusername/SaltSpot.git

Alternatively, you can download the dataset manually from the __Releases__ section.

## 📊 Applications

---
🔍 The SaltSpot dataset is intended for machine learning and deep learning applications, including:

- Binary Classification of salt-damaged vs. non-damaged structures 🏚️.
- Transfer Learning using pre-trained CNN models like ResNet50, VGG16, and MobileNet 🧠.
- Data Augmentation & Preprocessing techniques for improving model generalization.
- Structural Health Monitoring (SHM) applications in civil engineering 🏗️.

## 🏆 Citation

If you use this dataset in your research or project, please cite the following papers:

@article{guzman2025digital, <be>
  title={A digital twin approach based method in civil engineering for classification of salt damage in building evaluation}, <br>
  author={Guzm{\'a}n-Torres, JA and Dom{\'\i}nguez-Mota, FJ and Guzm{\'a}n, Elia M Alonso and Tinoco-Guerrero, G and Tinoco-Ru{\'\i}z, JG}, <br>
  journal   = {Mathematics and Computers in Simulation}, <br>
  year      = {2025}, <br>
  volume    = {233}, <br>
  pages     = {433-447}, <br>
  doi       = {https://doi.org/10.1016/j.matcom.2025.02.003} <br>
}

## ⚖️ License

This dataset is released under the MIT License. You are free to use, modify, and distribute it, but please credit the *authors* appropriately.
*MIT License © 2025 J. A. Guzmán-Torres et al.*

## 📩 Contact
For any questions or issues, please open an issue 🔗 in this repository or contact:

📢 J. A. Guzmán-Torres - Lead Researcher
✉️ Email: jose.alberto.guzman@umich.mx.com
🏛 Institution: Universidad Michoacana de San Nicolás de Hidalgo
