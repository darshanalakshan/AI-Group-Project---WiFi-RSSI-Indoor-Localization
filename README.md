# 📍 Wi-Fi RSSI Indoor Localization

### Machine Learning for Indoor Positioning

**Can Wi-Fi signals help us find our location inside a building?**

This project explores indoor localization using Wi-Fi Received Signal Strength Indicator (RSSI) measurements and machine learning. It uses Wi-Fi signal fingerprints to predict indoor positions based on X and Y coordinates.

## 🎯 Project Overview

GPS signals are often unreliable inside buildings. This project investigates how existing Wi-Fi networks can be used as an alternative for indoor positioning.

The main objective is to develop and compare machine learning models that can estimate indoor locations using Wi-Fi signal measurements.

## 📊 Dataset

The project uses the Wi-Fi RSSI Indoor Localization dataset.

**Dataset source:** [Kaggle – Wi-Fi RSSI Indoor Localization](https://www.kaggle.com/datasets/brosnanyuen/wifi-rssi-indoor-localization)

The dataset contains:
- Wi-Fi RSSI measurements from multiple access points.
- Indoor location coordinates (X and Y).
- Signal measurements from different Wi-Fi frequency bands.

The project focuses on selected 2.4 GHz Wi-Fi signal features.

## 🔬 Project Workflow

1. **Data Exploration** – Understand the dataset and visualize Wi-Fi signal measurements.
2. **Data Preprocessing** – Clean the data, select relevant features and handle missing values.
3. **Data Splitting** – Separate training and testing data based on physical locations.
4. **Model Development** – Build and compare machine learning regression models.
5. **Cross-Validation** – Evaluate model performance using grouped cross-validation.
6. **Model Evaluation** – Analyse predictions and identify a suitable model for indoor localization.

## 🤖 Machine Learning Models

The project investigates the following algorithms:

- Dummy Regressor
- K-Nearest Neighbors (KNN)
- Random Forest Regressor
- Extra Trees Regressor

## 🛠️ Technologies Used

- Python
- NumPy
- pandas
- Matplotlib
- scikit-learn
- Jupyter Notebook

## ⚙️ Getting Started

**1. Clone the repository**

```bash
git clone https://github.com/darshanalakshan/AI-Group-Project-WiFi-RSSI-Indoor-Localization.git
```

**2. Install the required libraries**

```bash
pip install numpy pandas matplotlib scikit-learn jupyter joblib
```

**3. Download the dataset**

Download the dataset from [Kaggle](https://www.kaggle.com/datasets/brosnanyuen/wifi-rssi-indoor-localization).

**4. Run the notebook**

```bash
jupyter notebook
```

Open `Project_020_corrected.ipynb` and run the cells in order. Update the dataset path if required.

## 📂 Repository Structure

```text
AI-Group-Project-WiFi-RSSI-Indoor-Localization/
│
├── Project_020_corrected.ipynb
└── README.md
```

## 👥 Project Team

Developed as a group project for the **Master's Programme in AI and Automation** at **University West, Trollhättan, Sweden**.

- Degirige Darshana Lakshan Silva
- Junoj Sivaneswaran
- Thambara Dasun Karuna Pathirage
- Akshaya Nagendran

## 🔭 Future Improvements

- Test the models in different indoor environments.
- Explore additional machine learning algorithms.
- Improve localization accuracy.
- Investigate real-time indoor positioning applications.

## 🙌 Acknowledgements

- University West, Sweden.
- The Kaggle dataset contributor.
- The Python and scikit-learn communities.

---

<p align="center">
  <strong>Turning Wi-Fi signals into location intelligence.</strong>
  <br>
  <sub>AI & Automation | University West | 2026</sub>
</p>
