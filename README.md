# Iris_Classifier_App
An interactive Iris Flower Prediction app built with Python and Streamlit that lets users adjust sepal and petal measurements to instantly predict the Iris species with confidence scores. Explore interactive visualizations, dataset insights, and feature analysis to understand the model and how each feature influences predictions.

Live App : https://irisclassifierapps.streamlit.app/


## 🚀 Features
- **Real-time Predictions:** Input custom measurements to get instant species classification.
- **Visual Insights:** Embedded data visualisations showing where user inputs fall within the overall Iris dataset cluster.
- **Interactive UI:** Clean, responsive, and minimalist sidebar controls built for non-technical users.

## 🛠️ Tech Stack
- **Frontend/Deployment:** [Streamlit](https://streamlit.io)
- **Machine Learning:** [Scikit-Learn](https://scikit-learn.org) (Model training, evaluation, and serialization via `.joblib`)
- **Data Manipulation & Visualisation:** Pandas, Seaborn, Matplotlib
- **Version Control:** Git & GitHub

## 📂 Project Structure
```text
├── Iris_app.py          # Main Streamlit web application script
├── training_model.py     # Script used to train and export the ML model
├── data_exploration.py  # Exploratory Data Analysis (EDA) scratchpad
├── iris_model.joblib    # Pre-trained serialization of the classifier model
├── requirements.txt     # Complete environment dependencies
└── README.md            # Project documentation
```

## 📊 How It Works
1. The user adjusts sliders for **Sepal Length, Sepal Width, Petal Length, and Petal Width**.
2. The values are fed instantly into the pre-trained Machine Learning classifier (`iris_model.joblib`).
3. The app displays the predicted flower species (*Iris-setosa*, *Iris-versicolor*, or *Iris-virginica*) along with an illustrative image or distribution plot.

---

## 🛠️ Local Setup and Installation

To run this project locally on your machine, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd Iris-Classifier-App
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit application:**
   ```bash
   streamlit run Iris_app.py
   ```

