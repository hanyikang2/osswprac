# Final Project - OSSW(23-2)

## Brain Tumor Classification

This is final project of OSSW(23-2) about classification for brain tumor classification.
Given data is (첨부되어 있다)
 
Considering some conditions(estimator, n_estimators, learning_rate) with Adaboost classifier, I concluded that the condition "Decision tree(max_depth = 5)" takes too much time for training.
These are examples. 
<img width="1089" alt="image" src="https://github.com/hanyikang2/osswprac/assets/146947519/395b6e46-2192-4645-9f88-92153725d461">
<img width="1086" alt="image" src="https://github.com/hanyikang2/osswprac/assets/146947519/0825a7eb-41f7-4bdd-b41f-a00fb732816d">
<img width="1093" alt="image" src="https://github.com/hanyikang2/osswprac/assets/146947519/2c84c877-b981-44d8-94ae-1af6cecc820d">


Taking estimator as Decision Tree with max_depth = 4 was time-effective, and thus what I needed for hyperparameter tuning was n_estimators and learning rate. 
By using GridsearchCV from scikit learn module, best hyper-parameter that shows the highest accuracy for the test dataset is included at the attached file.
<img width="1086" alt="image" src="https://github.com/hanyikang2/osswprac/assets/146947519/d6d112aa-f895-4d08-8d65-941860d28e03">
<img width="1084" alt="image" src="https://github.com/hanyikang2/osswprac/assets/146947519/b9fbb487-b876-4960-be57-1305c212bd73">
<img width="1084" alt="image" src="https://github.com/hanyikang2/osswprac/assets/146947519/239c3008-9303-413d-b1e9-90ddd120a319">

Thak you.
