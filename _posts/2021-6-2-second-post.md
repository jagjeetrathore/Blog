---
layout: Classification Post
title : Classification (Imbalanced Dataset)
tages: imabalance Data
categories: demo
---

![oversampling image](https://miro.medium.com/max/725/0*FeIp1t4uEcW5LmSM.png)


[iterative Metric learning for imbalanced Data Classification](https://www.ijcai.org/Proceedings/2018/0389.pdf)

![Imbalance dataset handling](https://www.mdpi.com/2227-7102/9/4/275/htm)

[Techniques for imblanced Datasets](https://www.kdnuggets.com/2020/01/5-most-useful-techniques-handle-imbalanced-datasets.html)

[cross-validation with oversampling](https://www.marcoaltini.com/uploads/1/3/2/3/13234002/2639934.jpg?401)

`From left to right, we start with the original dataset where we have a minority class with two samples. We duplicate those samples, and then we do cross-validation. At this point there will be iterations, such as the one showed, where the training and validation set contain the same sample, resulting in overfitting and misleading results. Here is how this should be done:`
![](https://www.marcoaltini.com/uploads/1/3/2/3/13234002/9101820.jpg?372)

First, we start cross-validating. This means that at each iteration we first exclude the sample to use as validation set, and then oversample the remaining of the minority class (in orange). In this toy example I had only two samples, so I created three instances of the same. The difference from before, is that clearly now we are not using the same data for training and validation. Therefore we will obtain more representative results. The same holds even if we use other cross-validation methods, such as k-fold cross-validation.

[correct with cross validation](https://www.marcoaltini.com/uploads/1/3/2/3/13234002/9101820.jpg?372)

-------------------------------------

>Block quote.
>> is like this.
>> 
Tables look like:
|header | Precision | recall|
|---|---|---|
|Classifier_1|78|67|
|Classifier_2|76|56|


