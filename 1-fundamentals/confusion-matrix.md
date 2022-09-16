# Confusion Matrix, Precision and Recall

> [Classification: Precision and Recall](https://developers.google.com/machine-learning/crash-course/classification/precision-and-recall)

## Confusion Matrix

- True Positive
  - Model truthfully classified as positive
- True Negative
  - Model truthfully classified as negative
  - i.e. label is negative, and classified as negative
- False Positive
  - **Falsely classified as positive**
- False Negative
  - **Falsely classifier as negative**

## Precision and Recall

Precision:

- (True Positive) / (True Positive + False Positive)
- What proportion of positive classification is actually correct?
- Of all classified/predicted as positive, how many are actually (labelled as) positive?
- **Precision of the model**
  - considering cases that model classified as positive
  - how many "precisely" hit the target (circle containing the actual labels)
    - really hit: true positive
    - total tries: true positive + false positive
  - how many are actually positive?
- When Precision = 1.0, there's zero case of False Positive
- Use Precision when trying to find the true positive

Recall:

- (True Positive) / (True Positive + True Negative)
- What proportion of labelled positives was identified correctly?
- Of all positive cases, how many are predicted correctly?
- **Recall by the model**
  - considering cases that are actually positive
  - how many are "recalled" by the model
  - what proportion are "recalled" byt the model
- When Recall = 1.0, there's zero case of True Negative
- Use Recall when trying to find the true negative
