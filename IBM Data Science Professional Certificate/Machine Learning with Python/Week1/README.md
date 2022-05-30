# Supervised vs. Unsupervised
In ***Supervised*** means that we supervise a machine learning model which is done by teaching the model by loading it with knowledge so that it can predict future instances. The question now, how do we teach a model?
- We teach the model by training it with some data from a labeled dataset. So, what does a labeled dataset mean?
    * The data where we have historical data, and we know the class of each row

![Capture](https://user-images.githubusercontent.com/91827137/171025586-3ae14032-0316-4530-ae06-d83dfa8190cb.PNG)

Supervised machine learning techniques: `Classification`, `Regression`

`Classification` is the process of predicting a discrete class label, or category (categorical value). but what do discrete and class label mean here?
- In probability, discrete random variable is random variable that can have one of a finite set of specific outcomes
- Class label is the discrete attribute whose value you want to predict based on the values of other attributes.
- So, discrete class label means the value we want to predict from a set of specific outputs which these values are based on the other values.

`Regression` is the process of predicting a continuous value.

In ***Unsupervised*** means that we don't supervise the model, the model trains on the dataset itself and works on its own to discover information.

Unsupervised learning techniques: `Dimension reduction`, 'Denisty estimation', 'Market basket analysis', `clustering`.
- Dimension reduction --> reduces the redundant features to make the classification easier.

| Supervised learning | Unsupervised learning
| ------ | ------ |
| Classification: Classifies labeled data | Clustering: Find patterns and groupings from unlabeled data, Has fewer evaluation methods than supervised learning, Less controlled environment |
| Regression: Predicts trends using previus labeled data, has more evaluation methods than unsupervised learning, controlled environment |     |
