# DORIS
DORIS: Dataset for herding and predator detection with the use of robots

## 🐑 Dataset for Precision Livestock Farming and Predator Detection  

Precision livestock farming leverages new technologies to enhance farm efficiency, particularly in operations with low profit margins. Unlike agriculture, extensive livestock farming requires continuous supervision, making technological advancements slower in this field. Additionally, modern sustainability efforts emphasize biodiversity conservation and reducing the carbon footprint, promoting sustainable animal husbandry practices.  

Small livestock farms, often located in remote areas with challenging generational replacement, can greatly benefit from robotics and intelligent systems. These technologies can assist farmers in daily tasks, such as monitoring flocks of sheep and detecting potential predators like wolves. By identifying threats in real time, farmers can take proactive measures, such as relocating the herd to safer pastures.  

This repository provides a **dataset** containing images and videos to facilitate the detection, classification, and analysis of sheep flocks and their natural predator, the wolf. The dataset includes:  

- **Videos of sheep flocks** captured in various locations, under different lighting conditions, and featuring different sheep breeds.  
- **Images of wolves** in natural environments, which are typically underrepresented in standard computer vision datasets.  
- **Data captured with quadruped robot cameras**, enabling research on animal behavior in the presence of robotic systems.  

### 📥 Dataset Access  

Due to its size, the dataset is available across three Zenodo repositories:  

📌 **Sheep images**: [Zenodo - 11313800](https://zenodo.org/records/11313800)  
📌 **Images of wolves, humans, and depth maps for simulation**: [Zenodo - 11313966](https://zenodo.org/records/11313966)  
📌 **YOLO annotations**: [Zenodo - 11313165](https://zenodo.org/records/11313165)  

### 📖 Citation  

If you use this dataset, please cite the following article:  

```bibtex
@article{YANG2024110691,
  title = {Dataset for herding and predator detection with the use of robots},
  journal = {Data in Brief},
  volume = {55},
  pages = {110691},
  year = {2024},
  issn = {2352-3409},
  doi = {https://doi.org/10.1016/j.dib.2024.110691},
  url = {https://www.sciencedirect.com/science/article/pii/S2352340924006589},
  author = {Xiao Yang and Beatriz {Jové de Castro} and Lidia Sánchez-González and Francisco Javier {Rodríguez Lera}},
  keywords = {Semantic segmentation, Precision livestock farming, Animal identification, Wolf presence detection}
}
``` 


## Code to split dataset into train, test and validation
Proposal to use a particular split of the DORIS dataset

## Download Dataset.
- In this link, you can find the dataset in YOLO format, distributed into the train(70%), validation(20%), and test(10%) subsets, with all images randomly distributed.
[Click to download](https://drive.google.com/file/d/16P_vEtlVgtOIkbZFGuGXktawlKLhO0jz/view?usp=sharing).

- In this link, you can find the dataset in YOLO format, where the images are distributed by videos into the train and validation subsets, 29 videos (55,734 frames) for training and 9 videos (11,473 frames) for validation.
[Click to download](https://drive.google.com/file/d/1sQHkfCoeg_HElh0QJ5KkF_c-ex4S8kUh/view?usp=sharing).

## Using Dataset example.
See more details in the jupyter notebook ``load_dataset.ipynb`` or click the colab icon: 
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://drive.google.com/file/d/1Y1LOpaQrFe3vX7QFDLcIaoaLVsLhe95y/view?usp=sharing)


## Acknowledgment: SELF-AIR Project

Supporting Extensive Livestock Farming with the use of Autonomous Intelligent Robots 

<img src="https://raw.githubusercontent.com/shepherd-robot/.github/main/profile/robotics_wolf_minimal.png" alt= "SELF_AIR_logo" width="50%" height="50%">

Grant TED2021-132356B-I00 funded by MCIN/AEI/10.13039/501100011033 and by the “European Union NextGenerationEU/PRTR"

![SELF_AIR_EU eu_logo](https://raw.githubusercontent.com/shepherd-robot/.github/main/profile/micin-financiadoUEnextgeneration-prtr-aei.png)

