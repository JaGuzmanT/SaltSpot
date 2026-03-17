# 🏗️ SaltSpot Dataset: Salt Damage Detection in Concrete Structures 🏛️  
![](Salt_damage.jpg)![](Salt_damage_2.jpg)![](Salt_damage_3.jpg)

## 📋 Table of Contents
- [Overview](#-overview)
- [Key Features](#-key-features)
- [Dataset Structure](#-dataset-structure)
- [Usage](#-usage)
- [Applications](#-applications)
- [Supported Frameworks](#-supported-frameworks)
- [Research Team](#-research-team)
- [Citation](#-citation)
- [License](#-license)
- [Contact](#-contact)

## 📌 Overview  

The **SaltSpot dataset** is a collection of **1,542 images** 📸 of concrete surfaces, specifically designed for **deep learning applications in civil engineering**. This dataset enables **automated detection** of **salt damage** 🧂 on concrete structures using **computer vision techniques**.  

This dataset was used in the research:  
📄 *"SaltSpot: A Convolutional Neural Network Approach for Classifying Salt Contamination Damage on Civil Infrastructure"*.  
If you use this dataset in your research, please **cite our work** (see **Citation** section below).  

---

## ✨ Key Features

- **📸 High-Quality Imagery**: 1,542 high-resolution images preprocessed to 224x224 pixels.
- **🏷️ Expertly Labeled**: Binary classification (Healthy vs. Salt Damaged) verified by civil engineering experts.
- **🏗️ Real-World Scenarios**: Captures diverse concrete textures, lighting conditions, and degradation levels.
- **🧠 Ready for AI**: Formatted and organized specifically for CNN training (ResNet, VGG, MobileNet).

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

## 🛠️ Supported Frameworks

<div align="center">

| :package: Framework | :rocket: Usage |
|:---:|:---:|
| [![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)](https://pytorch.org/) | **Deep Learning Model Training** |
| [![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)](https://www.tensorflow.org/) | **Model Deployment & TFLite** |
| [![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)](https://keras.io/) | **Rapid Prototyping** |
| [![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)](https://opencv.org/) | **Image Preprocessing** |

</div>

## 🧑‍🔬 Research Team

<div align="center">

### 🌟 Meet the Team
*Researchers advancing civil engineering and computational methods*

</div>

### 👥 Main Researchers

<table align="center">
  <thead>
    <tr>
      <th align="center" width="120">Photo</th>
      <th align="left">Researcher</th>
      <th align="left">Affiliation</th>
      <th align="left">Contact</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center" width="120">
        <img src="Public/docs/Images/JAGT1.jpg" alt="Dr. José Alberto Guzmán Torres" width="96" height="96">
      </td>
      <td>
        <b>Dr. José Alberto Guzmán Torres</b> :mexico:<br/>
        <sub>Engineering Applications &amp; Artificial Intelligence</sub>
      </td>
      <td>
        <a href="http://www.siiia.com.mx"><img alt="Company: SIIIA MATH" src="https://img.shields.io/badge/%F0%9F%8F%A2%20Company-SIIIA%20MATH-0B1B3A"></a><br/>
        <a href="http://www.umich.mx"><img alt="University: UMSNH" src="https://img.shields.io/badge/%F0%9F%8E%93%20University-UMSNH-1A3A6B"></a>
      </td>
      <td>
        <a href="mailto:jose.alberto.guzman@umich.mx"><img alt="Contact" src="https://img.shields.io/badge/%F0%9F%93%A7-Contact-blue"></a><br/>
        <a href="https://orcid.org/0000-0002-9309-9390"><img alt="ORCID 0000-0002-9309-9390" src="https://img.shields.io/badge/ORCID-0000--0002--9309--9390-green"></a><br/>
        <a href="https://www.researchgate.net/profile/Jose-Guzman-Torres"><img alt="ResearchGate Profile" src="https://img.shields.io/badge/ResearchGate-Profile-teal"></a>
      </td>
    </tr>
    <tr>
      <td align="center" width="120">
        <img src="Public/docs/Images/FJDM1.jpg" alt="Dr. Francisco Javier Domínguez Mota" width="96" height="96">
      </td>
      <td>
        <b>Dr. Francisco Javier Domínguez Mota</b> :mexico:<br/>
        <sub>Applied Mathematics &amp; Finite Difference Methods</sub>
      </td>
      <td>
        <a href="http://www.siiia.com.mx"><img alt="Company: SIIIA MATH" src="https://img.shields.io/badge/%F0%9F%8F%A2%20Company-SIIIA%20MATH-0B1B3A"></a><br/>
        <a href="http://www.umich.mx"><img alt="University: UMSNH" src="https://img.shields.io/badge/%F0%9F%8E%93%20University-UMSNH-1A3A6B"></a>
      </td>
      <td>
        <a href="mailto:francisco.mota@umich.mx"><img alt="Contact" src="https://img.shields.io/badge/%F0%9F%93%A7-Contact-blue"></a><br/>
        <a href="https://orcid.org/0000-0001-6837-172X"><img alt="ORCID 0000-0001-6837-172X" src="https://img.shields.io/badge/ORCID-0000--0001--6837--172X-green"></a><br/>
        <a href="https://www.researchgate.net/profile/Francisco-Dominguez-Mota"><img alt="ResearchGate Profile" src="https://img.shields.io/badge/ResearchGate-Profile-teal"></a>
      </td>
    </tr>
    <tr>
      <td align="center" width="120">
        <img src="Public/docs/Images/EMAG.jpg" alt="Dra. Elia M. Alonso Guzmán" width="96" height="96">
      </td>
      <td>
        <b>Dra. Elia M. Alonso Guzmán</b> :mexico:<br/>
        <sub>Civil Engineering &amp; Materials Science</sub>
      </td>
      <td>
        <a href="http://www.umich.mx"><img alt="University: UMSNH" src="https://img.shields.io/badge/%F0%9F%8E%93%20University-UMSNH-1A3A6B"></a>
      </td>
      <td>
        <a href="mailto:elia.alonso@umich.mx"><img alt="Contact" src="https://img.shields.io/badge/%F0%9F%93%A7-Contact-blue"></a><br/>
        <a href="https://orcid.org/0000-0002-8502-4313"><img alt="ORCID 0000-0002-8502-4313" src="https://img.shields.io/badge/ORCID-0000--0002--8502--4313-green"></a><br/>
        <a href="#"><img alt="ResearchGate Profile" src="https://img.shields.io/badge/ResearchGate-Profile-teal"></a>
      </td>
    </tr>
    <tr>
      <td align="center" width="120">
        <img src="Public/docs/Images/GTG.jpg" alt="Dr. Gerardo Tinoco Guerrero" width="96" height="96">
      </td>
      <td>
        <b>Dr. Gerardo Tinoco Guerrero</b> :mexico:<br/>
        <sub>Numerical Methods &amp; Computational Mathematics</sub>
      </td>
      <td>
        <a href="http://www.siiia.com.mx"><img alt="Company: SIIIA MATH" src="https://img.shields.io/badge/%F0%9F%8F%A2%20Company-SIIIA%20MATH-0B1B3A"></a><br/>
        <a href="http://www.umich.mx"><img alt="University: UMSNH" src="https://img.shields.io/badge/%F0%9F%8E%93%20University-UMSNH-1A3A6B"></a>
      </td>
      <td>
        <a href="mailto:gerardo.tinoco@umich.mx"><img alt="Contact" src="https://img.shields.io/badge/%F0%9F%93%A7-Contact-blue"></a><br/>
        <a href="https://orcid.org/0000-0003-3119-770X"><img alt="ORCID 0000-0003-3119-770X" src="https://img.shields.io/badge/ORCID-0000--0003--3119--770X-green"></a><br/>
        <a href="https://www.researchgate.net/profile/Gerardo-Tinoco-Guerrero"><img alt="ResearchGate Profile" src="https://img.shields.io/badge/ResearchGate-Profile-teal"></a>
      </td>
    </tr>
    <tr>
      <td align="center" width="120">
        <img src="Public/docs/Images/JGTR1.jpg" alt="Dr. José Gerardo Tinoco Ruíz" width="96" height="96">
      </td>
      <td>
        <b>Dr. José Gerardo Tinoco Ruíz</b> :mexico:<br/>
        <sub>Applied Mathematics &amp; Computational Modeling</sub>
      </td>
      <td>
        <a href="http://www.umich.mx"><img alt="University: UMSNH" src="https://img.shields.io/badge/%F0%9F%8E%93%20University-UMSNH-1A3A6B"></a>
      </td>
      <td>
        <a href="mailto:jose.gerardo.tinoco@umich.mx"><img alt="Contact" src="https://img.shields.io/badge/%F0%9F%93%A7-Contact-blue"></a><br/>
        <a href="https://orcid.org/0000-0002-0866-4798"><img alt="ORCID 0000-0002-0866-4798" src="https://img.shields.io/badge/ORCID-0000--0002--0866--4798-green"></a><br/>
        <a href="#"><img alt="ResearchGate Profile" src="https://img.shields.io/badge/ResearchGate-Profile-teal"></a>
      </td>
    </tr>
    <tr>
      <td align="center" width="120">
        <img src="Public/docs/Images/Harias.webp" alt="Dr. Heriberto Árias Rojas" width="96" height="96">
      </td>
      <td>
        <b>Dr. Heriberto Árias Rojas</b> :mexico:<br/>
        <sub>Engineering Applications</sub>
      </td>
      <td>
        <a href="http://www.siiia.com.mx"><img alt="Company: SIIIA MATH" src="https://img.shields.io/badge/%F0%9F%8F%A2%20Company-SIIIA%20MATH-0B1B3A"></a><br/>
        <a href="http://www.umich.mx"><img alt="University: UMSNH" src="https://img.shields.io/badge/%F0%9F%8E%93%20University-UMSNH-1A3A6B"></a>
      </td>
      <td>
        <a href="mailto:heriberto.arias@umich.mx"><img alt="Contact" src="https://img.shields.io/badge/%F0%9F%93%A7-Contact-blue"></a><br/>
        <a href="https://orcid.org/0000-0002-7641-8310"><img alt="ORCID 0000-0002-7641-8310" src="https://img.shields.io/badge/ORCID-0000--0002--7641--8310-green"></a><br/>
        <a href="https://www.researchgate.net/profile/Heriberto-Arias-Rojas"><img alt="ResearchGate Profile" src="https://img.shields.io/badge/ResearchGate-Profile-teal"></a>
      </td>
    </tr>
  </tbody>
</table>

## 🏆 Citation

If you use this dataset in your research or project, please cite the following papers:

@article{guzman2025digital, <be>
  title={A digital twin approach based method in civil engineering for classification of salt damage in building evaluation}, <br>
  author={Guzmán-Torres, JA and Domínguez-Mota, FJ and Guzmán, Elia M Alonso and Tinoco-Guerrero, G and Tinoco-Ruíz, JG}, <br>
  journal   = {Mathematics and Computers in Simulation}, <br>
  year      = {2025}, <br>
  volume    = {233}, <br>
  pages     = {433-447}, <br>
  doi       = {https://doi.org/10.1016/j.matcom.2025.02.003 } <br>
}

## ⚖️ License

This dataset is released under the MIT License. You are free to use, modify, and distribute it, but please credit the *authors* appropriately. <br>
*MIT License © 2025 J. A. Guzmán-Torres et al.*

## 📩 Contact
For any questions or issues, please open an issue 🔗 in this repository or contact:

📢 J. A. Guzmán-Torres - Lead Researcher <br>
✉️ Email: jose.alberto.guzman@umich.mx.com <br>
🏛 Institution: Universidad Michoacana de San Nicolás de Hidalgo
