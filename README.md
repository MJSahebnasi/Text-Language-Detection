# Language Detection for Text:

**languages supported:**

Farsi, Arabic, Pashto, English, German, French


**accuracy (%) of differnet methods:**



|                                              | TF-IDF        |CountVec|TF-IDF + the feature I defined   |
| :-------------:                              |:-------------:| :-----:|:---------:                      |
| sklearn.svm.LinearSVC (c=0.1)                |         100   | 100    | 100                             |
| sklearn.neighbors.KNeighborsClassifier (k=5) | 98            | 85     | -                               |
| KNN (k=3) (my Implementation)                | 96            | -      | -                               |
| sklearn.linear_model.SGDClassifier           | 100           |  100   | -                               |
