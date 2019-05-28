# NLP_IMDB_ScoreFromReviews NLP Project: Predicting ratings associated with reviews on IMDB through supervised learning

This project compares different approaches to classifying the multivariate sentiments of IMDB movie reviews using supervised learning and the bag-of-words model. The use of n-grams and Tf-Idf are compared and contrasted to see how much influence they have on the results attained by both a Support Vector Machine (SVM) classifier and a Naive Bayes (NB) classifier. Next to predicting the sentiment review scores from 1-4 and 7-10, the tests are also performed for binomial sentiment classification and grouped classification (very negative {1-2}, negative {3-4}, positive {7-8}, very positive {9-10}).

* **_The paper_** accompanying the research [can be found in the repository](https://github.com/pdisbeschl/NLP_IMDB_ScoreFromReviews/blob/master/NLP_Project.pdf).

* **_The program_** containing the model and experiments can be found in the [Jupyter notebook in our repository](https://github.com/pdisbeschl/NLP_IMDB_ScoreFromReviews/blob/master/classifiersFINAL.ipynb). Graphs of the results are included in the notebook below each set of experiments.

* **_Graphs of the results_** (included in the paper and the Jupyter notebook linked above) can be found in the [graphs folder](https://github.com/pdisbeschl/NLP_IMDB_ScoreFromReviews/tree/master/graphs)
  * Binary sentiment classification
    * A comparison of the accuracy of SVM with and without n-grams and Tf-Idf on binary sentiment
    * A comparison of the accuracy of NB with and without n-grams and Tf-Idf on binary sentiment
    * [The accuracy of the best SVM classifier compared to that of the best NB classifier](https://github.com/pdisbeschl/NLP_IMDB_ScoreFromReviews/blob/master/graphs/binarybest.png)
  * Group sentiment classification
    * A comparison of the accuracy of SVM with and without n-grams and Tf-Idf on binary sentiment
    * A comparison of the accuracy of NB with and without n-grams and Tf-Idf on binary sentiment
    * The accuracy of the best SVM classifier compared to that of the best NB classifier


The dataset used can be found [here](https://mega.nz/#F!8aRBDYYa!-P3lEjN0jOJgGRTaq91yOg) , it is a slightly modified version of the [SAR14 dataset of Dai Quoc Nguyen et al.](https://drive.google.com/open?id=14ZXV_RWdBgyLYECd7XJnxf2G2fCEfQkp). Our dataset differs from the original in that each mention of "ca n't" has been replaced by "can't", this is assumed to be a parsing error in the original. The original paper for which this dataset was created can be found [here](http://www.aclweb.org/anthology/W14-2621)

SAR14 is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.

SAR14 is free for non-commercial use and distributed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA) License.
