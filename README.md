# work-project-2
ANN Models on Coffee and Health Data

What it is: Two Artificial Neural Networks built on a synthetic dataset of 10,000 records about coffee intake and health, covering age, sleep, BMI, heart rate, stress, occupation, country and more. The work was also run as an AutoML experiment on Qlik (links included).

Models:

Classification ANN: Predicts a caffeine-consumption category, created by binning Caffeine_mg into 100 mg ranges. It uses two hidden layers (64 and 32 neurons) with dropout, one-hot encoding, MinMax scaling and early stopping. Test accuracy was 94.3%, precision 93.9%, recall 94.3% and F1 94.0%.
Regression ANN: Predicts Caffeine_mg directly using a similar architecture. Test MAE was about 4.19 mg, RMSE 5.31 and R² 0.9985.

Contents: Two notebooks, the dataset, an analysis report (PDF) and the Qlik experiment links.

Skills shown: ANN design for classification and regression, feature engineering, preprocessing pipelines, metric interpretation, and AutoML with Qlik.

One thing to prepare for: Coffee_Intake is used as an input, and Caffeine_mg (the target) is almost certainly calculated from it. That would explain the near-perfect R² of 0.9985. In an interview, expect to be asked about this possible data leakage. You could mention it in the README, or re-run the models without Coffee_Intake and report both results, which would show strong analytical judgment.

Suggested CV bullets
Cotton Disease Classification (CNN, Transfer Learning, XAI): Compared a baseline CNN with VGG16, ResNet50 and EfficientNetB0 on a four-class image dataset, reaching 98.1% test accuracy, and used LIME to validate the model’s decisions.
ANN Classification and Regression (Python, Keras, Qlik AutoML): Built neural networks on a 10,000-record health dataset, reaching 94.3% classification accuracy and R² of 0.998 for regression.
PharmaGlobal BI Solution (SSIS, SSAS, Power BI): Built an ETL pipeline, a star-schema tabular model and a six-page dashboard analysing hospital purchasing and consumption.
