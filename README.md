# COVID-19 Detection using Deep Learning on Chest X-rays and CT Scans

## 📖 Project Overview
This project presents a comparative study of deep learning models — VGG16, ResNet50, InceptionV3, and Xception — for automated COVID-19 diagnosis based on Chest X-ray and CT images.

## 🎯 Objectives
- Automate COVID-19 detection to assist radiologists.
- Compare the performance of different deep learning architectures.
- Evaluate models based on precision, recall, f1-score, accuracy, and confusion matrices.

## 🧠 Deep Learning Models Used
- VGG16
- ResNet50
- InceptionV3
- Xception

## 📂 Dataset
- Chest X-ray images
- Chest CT scan images

## ⚙️ Methodology
1. Data preprocessing
2. Model training and validation
3. Performance evaluation using classification reports and confusion matrices

## 📊 Results
### EVALUATION AND RESULT 

<h4> Sample output of the test images<h4> <br> 

![sample_ct](https://user-images.githubusercontent.com/54431128/109398757-fe9a0b00-7968-11eb-9911-ab29645a1dbb.png)
![sample_chest](https://user-images.githubusercontent.com/54431128/109398762-0063ce80-7969-11eb-866e-6661238da7f2.png)


<h4> Classification Reports for Chest X-rays: VGG, InceptionV3, ResNet50, Xception </h4>

![xcep](https://user-images.githubusercontent.com/54431128/109398816-559fe000-7969-11eb-896a-f60ee54fd899.png)
![resn](https://user-images.githubusercontent.com/54431128/109398818-56d10d00-7969-11eb-81ab-fdf3dd23dfd9.png)
![incep](https://user-images.githubusercontent.com/54431128/109398819-5769a380-7969-11eb-95eb-bfdfda19bc8b.png)
![vgg](https://user-images.githubusercontent.com/54431128/109398820-5769a380-7969-11eb-8dfa-24c341fe98d4.png)

<h4> Confusion Matrix for Chest X-rays: VGG, InceptionV3, ResNet50, Xception </h4>

![cnf4](https://user-images.githubusercontent.com/54431128/109398897-b9c2a400-7969-11eb-9d8d-9c42aae4fc8f.png)
![cnf3](https://user-images.githubusercontent.com/54431128/109398900-baf3d100-7969-11eb-9e9e-040a04851fb9.png)
![cnf2](https://user-images.githubusercontent.com/54431128/109398901-bb8c6780-7969-11eb-96ae-28f5239a87d5.png)
![cnf1](https://user-images.githubusercontent.com/54431128/109398902-bc24fe00-7969-11eb-9f4c-2de48911cf4d.png)

<h4> Classification Reports for CT Scans: VGG, InceptionV3, ResNet50, Xception </h4>

![ct4](https://user-images.githubusercontent.com/54431128/109398954-0ad29800-796a-11eb-833c-2ffbaef328b1.png)
![ct3](https://user-images.githubusercontent.com/54431128/109398955-0b6b2e80-796a-11eb-9692-e68e49159a92.png)
![ct2](https://user-images.githubusercontent.com/54431128/109398957-0c03c500-796a-11eb-98dc-b74eb9a92c05.png)
![ct1](https://user-images.githubusercontent.com/54431128/109398958-0c03c500-796a-11eb-8aad-045742532fdf.png)

<h4> Confusion Matrix for CT Scans: VGG, InceptionV3, ResNet50, Xception </h4>

![ctcon4](https://user-images.githubusercontent.com/54431128/109399052-951afc00-796a-11eb-9f35-3db75d416343.png)
![ctcon3](https://user-images.githubusercontent.com/54431128/109399054-977d5600-796a-11eb-93b3-722b4f9135a7.png)
![ctcon2](https://user-images.githubusercontent.com/54431128/109399056-9815ec80-796a-11eb-866c-9946b8087e70.png)
![ctcon1](https://user-images.githubusercontent.com/54431128/109399057-98ae8300-796a-11eb-931b-e49e6f461fc0.png)


Sample outputs and confusion matrices are available in the `/results` folder.

## 🚀 Tech Stack
- Python
- TensorFlow / Keras
- Matplotlib, scikit-learn

## 🏁 How to Clone
```bash
git clone https://github.com/eliashossain001/SARS-CoV-2Detection.git
cd covid19-diagnosis-dl

