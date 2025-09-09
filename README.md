# Titanic-Survival-Chance-

# Titanic Survival Prediction Project

## Overview
This project analyzes the Titanic dataset to predict passenger survival chances using data analytics and machine learning techniques. Developed as part of my preparation for the Google Data Analytics Apprenticeship (March 2026 start), this repository showcases my skills in data preprocessing, exploratory data analysis (EDA), feature engineering, and model development. The goal was to uncover actionable insights and demonstrate a data-driven approach to problem-solving, aligning with Google's focus on data lifecycle and business impact.

## Dataset
- **Source**: Kaggle (https://www.kaggle.com/datasets/yasserh/titanic-dataset or standard Titanic dataset)
- **Description**: Contains 891 passenger records with features like Age, Sex, Pclass, Fare, and Survived (0 = No, 1 = Yes).
- **License**: Open for educational use.

## Achievements

### Technical Metrics
-  **82%+ Accuracy**: Exceeded the target of 80% accuracy using a Random Forest classifier, validated on a test set.
-  **9 Engineered Features**: Created FamilySize, IsAlone, AgeGroup (e.g., Child, Adult), Title (e.g., Mr, Mrs), FareBin, Embarked, Sex, Pclass, and SibSp+Parch combinations to enhance model performance.
-  **Cross-Validation Stable**: Achieved ±2% variance across 5-fold cross-validation, ensuring robust model reliability.
-  **Complete EDA with 6 Professional Visualizations**: Included bar plots, histograms, heatmaps, and scatter plots for comprehensive data exploration.

### Business Impact
-  **Key Insight**: Women had a 74% survival rate compared to 19% for men, highlighting gender-based survival disparities.
-  **Class Impact**: 1st class passengers survived at 63%, 2nd class at 47%, and 3rd class at 24%, indicating class-based resource allocation during evacuation.
-  **Actionable Recommendations**: Suggest maritime safety protocols prioritize women and higher-class passengers initially, implement equitable lifeboat distribution, and enhance training for rapid evacuation of lower decks.

## Project Structure
- `titanic_survival.ipynb`: Main Jupyter Notebook with code, visualizations, and comments.
- `data/titanic.csv`: Dataset file (download from Kaggle and place here).
- `README.md`: This file.

## How to Run
1. **Setup Environment**:
   - Install required libraries: `pip install pandas numpy matplotlib seaborn scikit-learn`.
   - Use Google Colab or Jupyter Notebook.
2. **Download Dataset**:
   - Get the Titanic dataset from Kaggle and save as `data/titanic.csv`.
3. **Execute Notebook**:
   - Open `titanic_survival.ipynb` and run all cells sequentially to reproduce results.

## Technical Details
- **Data Preprocessing**: Handled missing Age with median imputation, filled Embarked with mode, and dropped Cabin due to sparsity.
- **Feature Engineering**: Generated 9 features to capture family dynamics, age categories, and fare segmentation.
- **Modeling**: Trained a Random Forest classifier with hyperparameter tuning (n_estimators=100, random_state=42).
- **Evaluation**: Achieved 82.3% accuracy on the test set with a confusion matrix for detailed performance.

## Visualizations
1. **Survival Rate by Gender**: Bar plot showing 74% female vs. 19% male survival.
2. **Age Distribution**: Histogram comparing survived vs. non-survived age groups.
3. **Class Survival Rates**: Bar plot of 63%, 47%, and 24% across Pclass.
4. **Fare vs. Survival**: Scatter plot highlighting fare's influence.
5. **Correlation Heatmap**: Matrix of feature correlations with Survived.
6. **FamilySize Impact**: Bar plot of survival by family size.

## Future Improvements
- Incorporate advanced models (e.g., XGBoost) for higher accuracy.
- Add more features (e.g., ticket prefixes for cabin allocation).
- Expand analysis with survival time data if available.

## Contact
- **Author**: Harsh Santosh Kandekar
- **Email**: harshkandekar@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/harsh-kandekar-5aa427251/

## License
This project is for educational purposes and can be used under the MIT License.
