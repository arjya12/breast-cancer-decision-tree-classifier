# **Breast Cancer Classification with Decision Trees**

**Overview**  
This machine learning classification project implements decision tree algorithms to analyze the Wisconsin Breast Cancer dataset. The project leverages Python's scientific computing ecosystem to build, optimize, and visualize decision tree models that classify breast cancer cases as malignant or benign based on cell nucleus features.

**Key Features**  
✔ **Data Analysis** – Loads and examines the Wisconsin Breast Cancer dataset from scikit-learn.  
✔ **Stratified Sampling** – Creates balanced training and test sets while preserving class distributions.  
✔ **Decision Tree Modeling** – Develops classification models with configurable parameters including entropy criteria.  
✔ **Hyperparameter Tuning** – Utilizes GridSearchCV to systematically find optimal tree depth and split thresholds.  
✔ **Performance Visualization** – Plots training and testing accuracy across different tree depths to identify optimal model complexity.

**Project Components**  
📌 **Data Loading** – Imports the Wisconsin Breast Cancer dataset directly from scikit-learn.  
📌 **Model Training** – Implements decision tree classifiers with entropy-based split criteria.  
📌 **Cross-Validation** – Performs 10-fold cross-validation to evaluate model generalization.  
📌 **Tree Visualization** – Creates detailed graphical representations of the decision tree structure.  
📌 **Performance Analysis** – Compares accuracy metrics to identify the optimal model configuration.

**How to Run**  
📊 **Setup**: `pip install scikit-learn matplotlib numpy`  
🚀 **Execute**: `main.py`  
📈 **Results**: View console output and visualizations showing dataset statistics, decision tree structure, and model accuracy comparisons

**How It Works**  
1️⃣ The program loads the breast cancer dataset with features describing cell nuclei characteristics.  
2️⃣ Data is split into training (60%) and testing (40%) sets while maintaining class proportions.  
3️⃣ Multiple decision trees are trained with varying depths and minimum split thresholds.  
4️⃣ Model performance is visualized to identify the optimal configuration balancing complexity and accuracy.  
5️⃣ GridSearchCV performs exhaustive parameter search to find the best-performing model.

**Technologies Used**  
🔹 **Python** (Primary programming language)  
🔹 **scikit-learn** (Machine learning algorithms, dataset access, and model evaluation)  
🔹 **matplotlib** (Data and decision tree visualization)  
🔹 **NumPy** (Underlying array operations)
