# vaccine-sentiment-classifier-softmax-regression

Develop a vaccine sentiment classifier using softmax regression.
The classifier is trained on twitter data and distinguished 3 classes (0 (neutral), 1 (anti-vax) or 2 (pro-vax)).

Validation dataset used also for predictions.
Scores for test set:

- Precision:
 0.5529044180976361
- Recall:
 0.4926789893187218
- F1 scoret:
 0.5077844124303713
- Accuracy:
 0.7367498904949628
 
 - Classification Report:


               precision    recall  f1-score   support

           0       0.81      0.76      0.79      1065
           1       0.73      0.39      0.51       296
           2       0.67      0.82      0.74       921
       label       0.00      0.00      0.00         1

    accuracy                           0.74      2283
   macro avg       0.55      0.49      0.51      2283
weighted avg       0.74      0.74      0.73      2283
