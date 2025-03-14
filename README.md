# WSN_Attack_Detection
Machine Learning model for detecting attacks in Wireless Sensor Networks
# Wireless Sensor Network Attack Detection

## Project Overview
This project applies machine learning techniques to detect attacks in Wireless Sensor Networks (WSNs). It involves data cleaning, preprocessing, and model training to classify network behavior as normal or malicious.

## Dataset
The dataset contains various network-related features used to detect anomalies and intrusions in WSNs.

### Data Preprocessing:
- **Dropped irrelevant columns** (e.g., highly correlated or single-value columns).
- **Handled missing values** using mean imputation and forward fill.
- **Encoded categorical variables** using label encoding.
- **Normalized numerical features** for better model performance.

## Machine Learning Models
Three models were trained and compared:
1. **Random Forest Classifier**
2. **K-Nearest Neighbors (KNN)**
3. **Decision Tree Classifier**

### Model Evaluation Metrics:
| Model  | Accuracy | Precision | Recall | F1-Score |
|--------|----------|-----------|--------|----------|
| Random Forest | 99.25% | 99.07% | 96.75% | 97.72% |
| KNN | 95.72% | 91.23% | 84.23% | 87.59% |
| Decision Tree | 99.98% | 99.97% | 99.93% | 99.95% |

## Visualizations
- **Box Plot**: Visualizes the distribution of data.
- **Bar Chart**: Compares model performance.
- **Radar Chart**: Highlights differences in evaluation metrics.


## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/WSN_Attack_Detection.git
   cd WSN_Attack_Detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook for training:
   ```bash
   jupyter notebook notebooks/DS_Final_(RANEEM).ipynb
   ```

## Dependencies
- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

## Future Improvements
- Implement deep learning models for improved accuracy.
- Enhance feature selection techniques.
- Optimize model hyperparameters.
