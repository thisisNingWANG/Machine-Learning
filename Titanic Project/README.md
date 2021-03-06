# MACHINE LEARNING

## 1.Description of the Project

The goal of the project is to apply machine learning techniques in order to predict the passengers that survived at the shipwreck of Titanic. Titanic was a British passenger liner that sank in the North Atlantic Ocean in the early morning of 15 April 1912 after colliding with an iceberg during her maiden voyage from Southampton to New York City. The sinking resulted in the loss of more than 1, 500 passengers and crew making it one of the deadliest commercial peacetime maritime disasters in modern history. One of the reasons that the shipwreck led to such loss of life was that there were not enough lifeboats for the passengers and crew. Although there was some element of luck involved in surviving the sinking, some groups of people were more likely to survive than others, such as women, children, and the upper-class. In this project, we ask you to complete the analysis of what sorts of people were likely to survive. The problem can be expressed as a two-class classification problem (survived or not) and the goal is to design a model that achieves high classification accuracy.

This project constitutes a competition on Kaggle (www.kaggle.com/), a platform that hosts predic- tive modeling and analytics competitions. As we will discuss later, the final evaluation of your model will be done using the Kaggle platform. More information about the competition can be found on the Kaggle website: https://www.kaggle.com/c/titanic.

## 2.Summary of the Pipeline

The pipeline that will be followed in the project is similar to the one followed in the labs. Next we briefly describe each part of the pipeline. The pipeline is contained in the main.py python script.

 * Data preprocessing: After loading the data, a preprocessing task should be done to transform the data into an appropriate format. In the previous section, we described some of the tasks that need to be performed.
 * Featureengineeringanddimensionalityreduction:Thenextstepinvolvesthefeatureengineeringtask, i.e., how to select a subset of the features that will be used in the learning task (feature selection) or how to create new features from the already existing ones (see also previous section). Moreover, it is possible to apply dimensionality reduction techniques in order to improve the performance of the algorithms. For example, in the classify.py file, you can see that by retaining only the sex of the passengers, we can achieve fairly good performance (∼ 78%).
 * Learning algorithm: The next step of the pipeline involves the selection of the appropriate learning (i.e., classification) algorithm for the problem. Here, you can test the performance of different al- gorithms and choose the best one (e.g., logistic regression, SVMs, decision trees, neural networks). Additionally, you can follow an ensemble learning approach, combining many classification al- gorithms.
