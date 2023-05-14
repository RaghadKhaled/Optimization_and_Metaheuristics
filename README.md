# Metaheuristic-Based Hyperparameter Tuning on Deepfake Video Detection using Jaya Algorithm

---
This is a college project required for Optimization course (CS467) .<br>
It is done as teamwork by Alhanouf Almansour, Khloud Alnufaie, Raghad Albosais and Weaam Alghaith.

---
## Table of content
* [Project overview](#project-overview)
* [Data description](#data-description)
* [Proposed Method](#proposed-method)
* [Tools](#tools)
* [How to run](#how-to-run)
* [Contributors](#contributors)
---

### Project overview

In light of our accelerating world and the huge amount of data transmitted over the internet specifically in social media, an individual sees dozen or even hundreds of images and types of media every day. Deepfake is a newly emerged issue in our modern days which is media of a person in which their face or body has been digitally altered so that they appear to be someone else, typically used maliciously or to spread false information. In this project, we aim to enhance deepfake videos detection method based on Convolutional Neural Networks (CNNs) by using Jaya optimization algorithm. 

---

### Data description


We plan to detect fake videos by using Celeb-DF (v2) [2](https://arxiv.org/pdf/1909.12962.pdf). Celeb-DF (v2) is a large-scale challenging dataset for deepfake forensics. It includes 890 real MP4 videos and 5639 fake MP4 videos, total of 9 GB. The average length of all videos is approximate 13 seconds with the standard frame rate of 30 frame-per-second. The real videos are collected from YouTube with subjects of different ages, ethnic groups, and genders. The fake videos are generated by swapping faces. Dataset available on this link [3](https://github.com/yuezunli/celeb-deepfakeforensics).


---

### Proposed Method

![Proposed method](https://github.com/RaghadKhaled/Optimization_and_Metaheuristics/blob/main/proposed%20method.jpg)

The overall model architecture that follows the step of implementation is illustrated in figure above. We describing and explain our approach to tackling the CNN model by following the approach applied in this paper “Novel Convolutional Neural Networks based Jaya algorithm Approach for Accurate Deepfake Video Detection”[1](https://journals.mesopotamian.press/index.php/CyberSecurity/article/view/58). We used their proposed method regarding the hyperparameter tuning of CNN using Jaya optimization algorithm. You can find more detiles about each step i the report.

---

### Tools

#### Libraries: 
- Pandas
- PIL
- PyTorch
- TensorFlow
- openCV
- NumPy
- scikit-learn
- seaborn
- matplotlib


#### Softwares: 
- Jupyter Notebook
- PyCharm

---

### How to run
-	Download the dataset and put it in `data` folder. 
-	Prepare the dataset to be used in the model by run the following file:
```
python prepare_data.py
```
- Then you can follow the code in the jupyter notebook `Deepfake video detection with using Jaya optimization algorithm.ipynb`.


---

### Contributors

[@AlhanoufAlmans](https://github.com/AlhanoufAlmans)

[@hkh7897](https://github.com/hkh7897)

[@RaghadKhaled](https://github.com/RaghadKhaled)

[@Weaam20](https://github.com/Weaam20)
