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

## Applications

---
The SaltSpot dataset is intended for machine learning and deep learning applications, including:

- Binary Classification of salt-damaged vs. non-damaged structures.
- Transfer Learning using pre-trained CNN models like ResNet50, VGG16, and MobileNet.
- Data Augmentation & Preprocessing techniques for improving model generalization.
- Structural Health Monitoring (SHM) applications in civil engineering.

## Citation

If you use this dataset in your research or project, please cite the following paper:

@article{guzmantorres2024saltspot,
  author    = {J. A. Guzmán-Torres, F. J. Domínguez-Mota, G. Tinoco-Guerrero, E. M. Alonso-Guzmán, 
               J. G. Tinoco-Guerrero, and M.Z. Naser},
  title     = {SaltSpot: A Convolutional Neural Network Approach for Classifying Salt Contamination Damage on Civil Infrastructure},
  journal   = {Journal Name},
  year      = {2024},
  volume    = {XX},
  pages     = {XX-XX},
  doi       = {XX.XXXXX/journal.xxx}
}

## License

This dataset is released under the MIT License. You are free to use, modify, and distribute it, but please credit the authors appropriately.

## Contact
For any questions or issues, please open an issue in this repository or contact:

J. A. Guzmán-Torres - Lead Researcher
Email: jose.alberto.guzman@umich.mx.com
Institution: Universidad Michoacana de San Nicolás de Hidalgo

MIT License © 2024 J. A. Guzmán-Torres et al.
