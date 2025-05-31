# 🛒 GROCIFY - AI Final Project (LA03)

**Grocify** is an AI-powered shopping assistant designed to help users make smarter purchasing decisions. It reduces impulsive buying and optimizes shopping lists by providing **budget tracking**, **personalized product recommendations**, and **real-time spending insights**. With Grocify, users can shop efficiently while maintaining financial discipline.

---

## 🚀 Features

- 🧠 Built with **YOLOv11**, trained on a custom groceries dataset  
  > [Dataset Credit](https://universe.roboflow.com/ingredients-wzqqk/ingredients-ctbug)
- 📷 **Webcam integration** for real-time grocery recognition
- 🌐 **HTML integration** using the **Flask** web framework
- 🖥️ Simple and interactive UI built with **Gradio**

---

## 📊 Model Performance

| Metric       | Value  |
|--------------|--------|
| **mAP**      | 61.7%  |
| **Precision**| 71.3%  |
| **Recall**   | 54.4%  |

> 🔗 Explore the model: [Roboflow Project Page](https://universe.roboflow.com/lyn15/ai_grocify)

---

## 🧰 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab&logoColor=white)
![Gradio](https://img.shields.io/badge/Gradio-FF6F00?logo=gradio&logoColor=white)

---

## 📎 Project Structure
grocify/
│
├── static/ # Static assets (CSS, images)
├── templates/ # HTML templates
├── app.py # Flask app with YOLO integration
├── yolo_model/ # YOLOv11 model and config files
├── utils.py # Helper functions
├── requirements.txt # Project dependencies
└── README.md # Project documentation


---

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
