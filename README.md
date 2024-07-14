

For this phase, a dataset titled "Dataset1" was provided. After loading and visualizing it, we implemented the algorithms and requirements mentioned below. We plotted the accuracy chart based on the number of estimators for each of the Bagging, Random Forest, and AdaBoost algorithms in sections 1 to 3 of this phase. At the end of each section, 1 to 4, we obtained the evaluation metrics Precision, Recall, and F1-Score for the Train and Test data (we used built-in functions for these metrics).

**Section 1.1: Bootstrap Aggregating (Bagging)**

In this section, we implemented the Bagging algorithm using the DecisionTreeClassifier and BaggingClassifier classes from the sklearn library. We set the hyperparameters and improved the algorithm's performance by adjusting them. We then visualized the predicted output of the Bagging algorithm and five Decision Tree classifiers on the dataset and documented our observations about the performance of each classifier in six images in our report (we selected trees with noticeable differences in performance in the visualizations).

**Section 1.2: Random Forest**

In this section, we implemented the Random Forest algorithm using the RandomForestClassifier class from the sklearn library. We determined and improved the hyperparameters, then visualized and analyzed the algorithm's output and five of the randomized trees on the dataset.

**Section 1.3: AdaBoost**

In this section, we executed the AdaBoost algorithm on the dataset using the AdaBoostClassifier class. After achieving satisfactory results and testing various hyperparameter values, we plotted the algorithm's performance at different stages of execution. We visualized eight stages of the algorithm on the dataset and examined the performance of the weak classifiers, noting which parts were correctly classified and how these parts improved and changed during the algorithm's execution (we chose these eight stages at intervals to better highlight the differences). We selected the weak classifiers as per our discretion.

**Section 1.4: Stacked Learners**

For the implementation of the Stacked Learners algorithm, we first implemented the K-Nearest Neighbors (KNN) algorithm using the KNeighborsClassifier class after familiarizing ourselves with it as briefly introduced in class. We then used this classifier along with several other classifiers to implement the Stacked Learners algorithm (we also used classifiers from sections 1 to 3 when possible). Note that we wrote the code for this section ourselves without using built-in libraries or classes for combining classifiers (we were allowed to use the classes mentioned in this and previous sections). If any classifiers used in this section overfitted, we implemented the solutions discussed in class to address this issue, earning extra points. (If none of the classifiers overfitted and we wanted to earn extra points, we added an overfitting classifier to the initial set of classifiers for this algorithm.)

**Phase Two: Using the Algorithms**

A dataset titled "Dataset2" was provided. After reviewing this dataset, we applied the algorithms from Phase One (Bagging, Random Forest, AdaBoost, and Stacked Learners) to this dataset as well. We noted that this dataset required preprocessing. We earned extra points by plotting and analyzing the correlation between features at one of the preprocessing stages and removing features with a high correlation. After running the algorithms, we calculated Precision, Recall, and F1-Score for the Train and Test data (using built-in functions for these metrics).

---
