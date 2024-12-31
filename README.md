# Heart Health Risk Analysis Program

## Overview
The **Heart Health Risk Analysis Program** is a data mining project aimed at leveraging demographic and medical data to predict heart health risk levels among individuals. By utilizing machine learning classifiers, this program empowers early detection and intervention for heart disease risk, contributing to both improved patient outcomes and business profitability.

---

## Features
- **Classification Models**: Implemented and compared K-Nearest Neighbors (KNN), Random Forest, and Logistic Regression classifiers to predict heart health risk categories.
- **Cost-Driven Analysis**: Evaluated model performance using a customized net benefit cost function for decision-making.
- **Data Insights**: Provided actionable insights through feature importance and class-specific accuracy metrics.
- **Balanced Dataset Handling**: Tackled data imbalance using under-sampling and oversampling techniques.
- **Visualization**: Generated intuitive visualizations, including confusion matrices, feature importance plots, and cost-driven performance metrics.

---

## Dataset
The dataset includes:
- **Patient Demographics**: Age, sex, etc.
- **Medical Parameters**: Cholesterol, peak heart rate, blood pressure, etc.
- **Classes**: Heart health risk classified into 5 levels:
  - No Risk
  - Slight Risk
  - Moderate Risk
  - High Risk
  - Extreme Risk

---

## Key Results
- **Best Classifier**: Random Forest with 63% accuracy and the highest net benefit of $22,400 (approx. $128/patient).
- **Net Benefits**:
  - **Random Forest**: $22,400
  - **KNN**: $21,400
  - **Logistic Regression**: $10,100
- Highlighted the need for more balanced data to improve minority class predictions.

---

## Project Workflow
1. **Data Preprocessing**: Handled missing values, normalized features, and addressed data imbalance.
2. **Model Training and Evaluation**:
   - Used precision, recall, F1-score, accuracy, and net benefit metrics.
   - Compared models based on cost-effectiveness and classification performance.
3. **Feature Importance**: Identified key predictors using Random Forest.
4. **Visualization**: Generated plots for model evaluation and insights.

---

## Recommendations
- Collect more data for minority classes to improve prediction accuracy.
- Explore advanced techniques like ensemble methods and deep learning for better predictions.
- Integrate additional features like lifestyle and family history to enrich the dataset.

---

## Future Work
- Real-time model calibration for production use.
- Expansion of the model to cover diverse populations.
- Incorporation of more sophisticated health metrics to improve predictions.

---

## Files in Repository
1. **Executive Report**: Detailed project overview and recommendations.
2. **Presentation Slides**: Key insights and findings.
3. **Source Code**: Python scripts for data preprocessing, model training, and evaluation.

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Heart-Health-Risk-Analysis.git
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
3. Run the main analysis script:
  ```bash
python heart_health_risk_analysis.py
```
---

## License
- This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgments
- Dr. John Papparizos for providing the initial problem statement and data.
- American Heart Association for insights into cardiovascular health statistics.
- Support from academic resources for data mining and classification.


  
