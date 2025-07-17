# 🪐 Kepler Exoplanet Classifier

This machine learning project uses NASA's Kepler dataset to classify exoplanet candidates as **confirmed planets** or **false positives** using multiple ML models.

## 📊 Dataset

- **Source**: [NASA Kepler Exoplanet Dataset](https://www.kaggle.com/datasets/nasa/kepler-exoplanet-search-results)
- **Total Rows**: 9564  
- **Goal**: Predict whether a planetary candidate is a confirmed exoplanet or not.

## 🎯 Target Variable

- `koi_disposition`: [‘CONFIRMED’, ‘FALSE POSITIVE’, ‘CANDIDATE’]

We converted this into a binary classification problem.

## 🧠 Models Used

- Logistic Regression
- Random Forest Classifier
- K-Nearest Neighbors
- Support Vector Machine

## 📈 Model Performance

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 78%    |
| Random Forest       | 80%    |
| KNN                 | 78%    |
| SVM                 |77%    |

### Confusion Matrix

<img width="387" height="488" alt="c1" src="https://github.com/user-attachments/assets/35ec1bba-3ae2-4fa2-91f1-01d027676419" />
<img width="378" height="488" alt="c2" src="https://github.com/user-attachments/assets/31f77cc7-9c7b-42b6-ac79-2b5021c7ae4d" /> 
<img width="387" height="488" alt="c3" src="https://github.com/user-attachments/assets/98f35dbc-c8be-4757-8ff6-70f7c5b40742" />
<img width="378" height="488" alt="c4" src="https://github.com/user-attachments/assets/2013b5df-953c-4f57-998a-da98c01325c2" />

## ⚙️ Tech Stack

- Python
- Scikit-learn
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

## ▶️ How to Run

```bash
git clone https://github.com/your-username/kepler-exoplanet-classifier.git
cd kepler-exoplanet-classifier
pip install -r requirements.txt
jupyter notebook

## Output Sample
Input Features: koi_period = 10.2, koi_prad = 1.1, koi_teq = 500
Prediction: CONFIRMED

