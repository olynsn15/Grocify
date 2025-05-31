# 🛒 GROCIFY - AI Final Project (LA03)

**Grocify** is an AI-powered shopping assistant designed to help users make smarter purchasing decisions. It reduces impulsive buying and optimizes shopping lists by providing **budget tracking**, **personalized product recommendations**, and **real-time spending insights**. With Grocify, users can shop efficiently while maintaining financial discipline.<br><br>

## 🚀 Features

- 🧠 Built with **YOLOv11**, trained on a custom groceries dataset  
  > [Dataset Credit](https://universe.roboflow.com/ingredients-wzqqk/ingredients-ctbug)
- 📷 **Webcam integration** for real-time grocery recognition
- 🌐 **HTML integration** using the **Flask** web framework
- 🖥️ Simple and interactive UI built with **Gradio**<br><br>



## 📊 Model Performance

| Metric       | Value  |
|--------------|--------|
| **mAP**      | 61.7%  |
| **Precision**| 71.3%  |
| **Recall**   | 54.4%  |

> 🔗 Explore the model: [Roboflow Project Page](https://universe.roboflow.com/lyn15/ai_grocify)
<br><br>


## 🧰 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF6F00?logo=gradio&logoColor=white)<br><br>



## 📎 Project Structure
```

GROCIFY2/
├── templates/
│   └── grocify.html               # HTML template for Flask interface
├── best_train4.pt                 # Trained YOLOv11 model weights
├── grocify_flask.py               # Flask backend integration script
├── grocify_gradio.py              # Gradio interface script
├── pytorch-retinanet-master.zip  # Additional object detection code (unused backup or reference)
├── train_huggingface_detr_on_custom_dataset.ipynb  # DETR training notebook
├── train_yolo11_object_detection_on_custom_dataset.ipynb  # YOLOv11 training notebook
└── README.md                      # Project documentation

```
<br><br>

## 🔧 Installation & Usage

> ⚠️ Ensure you have **Python 3.8+** installed.

```bash
# Clone the repository
git clone https://github.com/your-username/grocify.git
cd grocify

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py
<br><br>
