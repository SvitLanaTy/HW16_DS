# HW16_DS

Fashion Image Classification App

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://hw16st.streamlit.app)

A bilingual (English/Ukrainian) web application for classifying fashion items using CNN and VGG16 neural networks.

## 🌟 Features

- Image classification using two different models:
  - Custom Convolutional Neural Network (CNN)
  - Modified VGG16 Architecture
- Bilingual interface (English/Ukrainian)
- Real-time predictions with confidence scores
- Visual probability distribution for all classes
- Training history visualization
- Responsive design

## 🔧 Technologies

- Python 3.11
- Streamlit
- TensorFlow
- Matplotlib
- NumPy

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/SvitLanaTy/HW16_DS.git
cd fashion-classification-app
```

2. Create and activate a virtual environment:

```bash
# Windows
python -m venv venv
venv\Scripts\activate

# Linux/macOS
python3 -m venv venv
source venv/bin/activate
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

## 🚀 Usage

1. Run the Streamlit app:

```bash
streamlit run app.py
```

2. Open your browser and navigate to `http://localhost:8501`

3. Select your preferred language (English/Ukrainian)

4. Choose a model (CNN or VGG16)

5. Upload an image to classify

## 📊 Model Information

The application uses two pre-trained models:

- CNN model trained on Fashion MNIST dataset
- Modified VGG16 model fine-tuned for fashion classification

Supported classes:

- T-shirt/top
- Trouser
- Pullover
- Dress
- Coat
- Sandal
- Shirt
- Sneaker
- Bag
- Ankle boot

## 🌐 Live Demo

The application is deployed on Streamlit Cloud and can be accessed [here](https://hw16st.streamlit.app).

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/SvitLanaTy/HW16_DS/issues).

## ⭐️ Show your support

Give a ⭐️ if this project helped you!
