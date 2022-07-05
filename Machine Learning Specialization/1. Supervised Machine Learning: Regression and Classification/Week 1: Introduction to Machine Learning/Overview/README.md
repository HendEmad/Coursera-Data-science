Building machines as intelligent as people is called `Artificial General Intelligence (AGI)`.

# Supervised Learning
- we input `(X)` to get the output `(y)`. The output is based on the right answers that given to the model to learn from it (be trained).
- Based on the right answers given to it, it outputs `the correct label `(y)`.
- In other words, we train the model on inputs `(X) (right answers)`, then the model outputs the `label (y)` after learning from its input.
- What happens is mapping input `X` to output `y`

#### Examples
Input (X) | Output (Y) | Applications 
--- | --- | ---
mail | spam ? (0 / 1) | Spam filtering
audio | text transcripts | speech recognition
english | spanish | machine translation
ad, user info | click ? (0 / 1) | online advertising
image, radar info | position of the cars | self-driving cars
image of phone | defect ? (0 / 1) | Visual inspection(companies used it while manufacturing to detect any defects in the products.)

## 1. Regression:
- predict a number from many possible outputs.
- ex. prediction of houses' prices.

## 2. Classification:
- inputs may be 1, 2, .... (May be hundreds in real data sets)
- Outputs are small, finite, and limited (`0` OR `1`, ***not all numbers between them***).
- output categories may be numeric or non-numeric (`0` or `1` / `0` or `1` or `2` / `benign` or `malignant`).
- The algorithm fits (finds best) boundry that separates out the categories of the output.
- ex. Calssify if a tumor is benign or malignant.
- visualized examples:

![classification 1](https://user-images.githubusercontent.com/91827137/177371908-ccf9bb2b-a012-4a3d-b044-399556b92f63.PNG)

![classification 2](https://user-images.githubusercontent.com/91827137/177371960-73bbabd6-b0d4-41ea-a5d8-d556c6ea9b8e.PNG)

# Unsupervised learning

