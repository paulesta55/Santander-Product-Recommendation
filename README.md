# Santander Product Recommendation


**Instruction:**

1. Download dataset from https://www.kaggle.com/c/santander-product-recommendation/data, unzip and put them into input folder.

2. Create preprocessed data by running all cells in the following notebooks
  - MakeJuneExtraData.ipynb 
  - MakeDataMulticlass2.ipynb
  - MakeTestSet2.ipynb
  - MakeTestDatawithpast3.ipynb
  
3. Choose model to create prediction from the following notebooks:
  - Baseline model: run MostProbableProductRecent2.ipynb
  - Basic logistic regression: run CollaborativeFiltering.ipynb
  - A bit more adavanced logistic regression: run LogisticRegression2.ipynb
  - Simple XGBoost model: run XGBmulticlass.ipynb
  - XGBoost with feature engineering: run XGBmulticlass_withpast5.ipynb
  - Basic Neural Network: run Keras1.ipynb
  - Ensemble model: run Ensemble6_Keras1_XGB5_popular.ipynb

Special thanks to anokas (for starter script), breakfastpirate (for contributing important insight to the community) and other people in the kaggle forum!
