## 1. NSL KDD: The enhanced KDD Cup 99 [Refer](https://www.unb.ca/cic/datasets/nsl.html)
<br>[The KDD Cup 99 dataset](https://www.tensorflow.org/datasets/catalog/kddcup99) contains a standard set of data to be audited, which includes a wide variety of intrusions simulated in a military network environment.
The competition task was to build a network intrusion detector, a predictive model capable of distinguishing between ''bad’’ connections, called intrusions or attacks, and “good” normal connections.
### Improvements to the KDD'99 dataset
The NSL-KDD data set has the following advantages over the original KDD data set:

* It does not include redundant records in the train set, so the classifiers will not be biased towards more frequent records.
* There is no duplicate records in the proposed test sets; therefore, the performance of the learners are not biased by the methods which have better detection rates on the frequent records.
* The number of selected records from each difficultylevel group is inversely proportional to the percentage of records in the original KDD data set. As a result, the classification rates of distinct machine learning methods vary in a wider range, which makes it more efficient to have an accurate evaluation of different learning techniques.
* The number of records in the train and test sets are reasonable, which makes it affordable to run the experiments on the complete set without the need to randomly select a small portion. Consequently, evaluation results of different research works will be consistent and comparable.
