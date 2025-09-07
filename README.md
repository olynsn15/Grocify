# GROCIFY 🍎🛒
### AI Final Project (LA03)

**Grocify** is an **AI-powered grocery stock detection tool** designed to help users keep track of their household essentials with ease. Instead of relying on memory or manual checklists, Grocify intelligently monitors your grocery items and notifies you when stocks are running low. By making stock awareness simple and automated, Grocify helps prevent overbuying, waste, and shortages—empowering users to shop smarter, save money, and manage their groceries effortlessly.
<br><br>

## Features
- Built with **YOLOv11**, trained on a custom groceries dataset  
- **Webcam integration** for real-time grocery stock recognition
- **HTML integration** using the **Flask** web framework
- Simple and interactive UI built with **Gradio**
<br><br>

## Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF6F00?logo=gradio&logoColor=white)
<br><br>

## Model Performance
| Metric       | Value  |
|--------------|--------|
| **mAP**      | 61.7%  |
| **Precision**| 71.3%  |
| **Recall**   | 54.4%  |
> Explore the model : [Roboflow Project Page](https://universe.roboflow.com/lyn15/ai_grocify)
<br>

## Project Structure
```
Grocify/
├── GROCIFY2/
│   ├── best_train4.pt
│   ├── grocify_flask.py
│   ├── grocify_gradio.py
│   ├── pytorch-retinanet-master.zip
│   ├── templates/
│   │   └── grocify.html
│   ├── train_huggingface_detr_on_custom_dataset.ipynb
│   └── train_yolo11_object_detection_on_custom_dataset.ipynb
└── README.md
```
<br>

## Notes
```
- Dataset Credit : Ingredients Computer Vision Dataset by Ingredients (https://universe.roboflow.com/ingredients-wzqqk/ingredients-ctbug)

Grocify is a semester-long final group project developed for the Artificial Intelligence course
```
<br><br>
