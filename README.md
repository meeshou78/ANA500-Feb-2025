# Song Popularity Prediction

## Overview

This repository contains a **machine learning project** focused on predicting the **popularity of songs** based on various audio and metadata features. The project involves data preprocessing, feature engineering, and applying different machine learning models to classify song popularity.

## Project Structure

```
📦 song-popularity-prediction
├── 📜 song_popularity_analysis.py   # Combined Python script for full analysis
├── 📜 data/                         # Raw and cleaned datasets (if applicable)
├── 📜 models/                       # Trained machine learning models
├── 📜 requirements.txt              # Dependencies for the project
├── 📜 README.md                     # Project Documentation
```

## 🔗 Dataset
The dataset used for this project is publicly available on Kaggle:
[Spotify Tracks Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset/data)

## 🚀 Installation

Clone this repository and install the required dependencies:
```bash
git clone https://github.com/yourusername/song-popularity-prediction.git
cd song-popularity-prediction
pip install -r requirements.txt
```

## 🛠️ Usage
Run the complete analysis by executing the following command:
```bash
python song_popularity_analysis.py
```

## 📊 Machine Learning Models

This project applies multiple machine learning models to classify song popularity:

- **Logistic Regression**
- **Decision Trees**
- **Random Forest**
- **Gradient Boosting**
- **Neural Networks (MLPClassifier)**
- **LSTM (Long Short-Term Memory)**

## Key Findings

- **Random Forest achieved the highest accuracy and lowest Mean Squared Error (MSE), making it the best model.**
- **LSTM performed well for sequential dependencies but struggled with binary classification.**
- **Feature selection and normalization significantly improved model performance.**

## 🖼️ Visualizations

- **ROC Curves** to compare model performance.
- **Actual vs. Predicted Scatterplots** for evaluating regression-based models.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to improve the project.

## Contact

For inquiries, please reach out via [your email] or create an issue in the repository.

---

**Song Popularity Prediction** - Predicting music trends with machine learning!

