# Coursera Data Science 

## Machine Learning Course Project

Please view my submission at [http://asreynolds.github.io/CourseraMachineLearning/MachLrning.html](http://asreynolds.github.io/CourseraMachineLearning/MachLrning.html).

### Goal

The topic of this project is Human Activity Recognition (HAR). We use data from accelerometers on the belt, forearm, arm, and dumbbell of 6 participants, who were asked to perform barbell lifts correctly and incorrectly in five different ways. The goal of the project is to use the measurements collected by the accelerometers to predict which of the five ways a person is lifting the weights. 

### Data

The data is available for download [here](http://groupware.les.inf.puc-rio.br/static/WLE/WearableComputing_weight_lifting_exercises_biceps_curl_variations.csv). More information about the data is available from the website [here](http://groupware.les.inf.puc-rio.br/har#weight_lifting_exercises).

### Methods

The data is divided into a test set and a training set. For the purpose of this project, the course instructors (Jeff Leek, PhD, Roger D. Peng, PhD, Brian Caffo, PhD) made this division. Students were asked to build a prediction algorithm from the training set. The accuracy of the algorithm is evaluated based on its performance on the test set, which consists of 20 observations. That is, once a prediction algorithm is built, students apply their algorithm to predict which of the five lifting methods each of 20 new subjects were using.

I've chosen to implement a Random Forest algorithm, as implemented in the R packages `caret` and `randomForest`. Cross validation is used to get an estimate of the out-of-sample error of the algorithm, which turns out to be less than 1 percent! All 20 observations in the test set are correctly classified. 

### Submission

Please view my submission at [http://asreynolds.github.io/CourseraMachineLearning/MachLrning.html](http://asreynolds.github.io/CourseraMachineLearning/MachLrning.html).

## References

The data used in this project comes from the following study:

Velloso, E.; Bulling, A.; Gellersen, H.; Ugulino, W.; Fuks, H. Qualitative Activity Recognition of Weight Lifting Exercises. Proceedings of 4th International Conference in Cooperation with SIGCHI (Augmented Human '13) . Stuttgart, Germany: ACM SIGCHI, 2013.

The above study can be read [here](http://groupware.les.inf.puc-rio.br/public/papers/2013.Velloso.QAR-WLE.pdf).
