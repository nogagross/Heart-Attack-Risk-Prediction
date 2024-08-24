# Heart-Attack-Risk-Prediction

This project aims to predict whether a patient is at risk of having a heart attack based on personal and medical data using machine learning techniques. I utilized a Random Forest model due to its effectiveness in handling complex datasets and providing interpretable results.

## Project Overview

Cardiovascular diseases are among the leading causes of death globally. Early detection and risk prediction can significantly improve patient outcomes by facilitating timely intervention. This project explores a machine learning approach to predict heart attack risk using patient data, including demographics and medical measurements.

## Data

The data used in this project comes from two main sources:
- **Personal Information**: Contains demographic data such as age, gender, and lifestyle factors.
- **Medical Measurements**: Includes clinical measurements like cholesterol levels, blood pressure, and other relevant biomarkers.

### Data Processing

- **Interpolation**: Missing values in the dataset were filled using interpolation to ensure completeness of the data.
- **Merging**: Personal information and medical measurements were merged to create a comprehensive dataset for model training and evaluation.

## Methodology

1. **Feature Selection**: Relevant features were selected based on domain knowledge and initial exploratory data analysis.
2. **Handling Imbalanced Data**: SMOTE (Synthetic Minority Over-sampling Technique) was applied to handle class imbalance in the dataset, which is a common issue in medical data.
3. **Model Training**: A Random Forest classifier was used to train the model on the processed data.
4. **Model Evaluation**: The model's performance was evaluated using accuracy scores to determine its predictive power.

## Results

The Random Forest model achieved an accuracy of 70% on the test dataset. These results indicate the model's potential for predicting heart attack risk based on the available data.

## Getting Started

To reproduce this project:
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/heart-attack-risk-prediction.git
    cd heart-attack-risk-prediction
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the Jupyter Notebook to see the full analysis and model training steps:
    ```bash
    jupyter notebook HW4.ipynb
    ```

## Tools and Technologies

- **Programming Languages**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, Imbalanced-learn (SMOTE)
- **Tools**: Jupyter Notebook

## Conclusion

This project demonstrates the use of machine learning techniques to predict health risks, providing a foundation for further exploration into more advanced models and larger datasets. Future work could involve refining the model, exploring different algorithms, or incorporating additional data features.

## License

This project is licensed under the MIT License.

