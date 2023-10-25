# Machine_Learning
Where I'll put all my projects from my ML self-study.

# Table of Contents
1. [Essential Concepts](https://github.com/AlexA2304/Machine_Learning/edit/main/README.md#essential-concepts)
  
2. [Classification: The Basics](#classification-the-basics)
3. [NLP: The Basics](#nlp-the-basics)
4. [Recommendation Systems](#recommendation-systems)
5. [Recommendation Systems: Collaborative Filtering - The Basics](#recommendation-systems-collaborative-filtering---the-basics)


# Essential Concepts:

- ******************************************Supervised Learning:****************************************** Teaching the model to make predictions using labeled data.
    
    ******************************************************************************like learning to cook with a recipe.******************************************************************************
    
    - **************Label:************** The thing you’re trying to predict.
    - ******************Feature:****************** Variables that help the model make a prediction.
- ****Unsupervised Learning:**** The model learns patterns in the data without any labels.
    
    **********************************************************************************************Like learning to cook by tasting and adjusting.**********************************************************************************************
    
    - ********Clustering:******** Grouping similar data points.
    - ****************************************************Dimensionality Reduction:**************************************************** Reducing the number of features while keeping important info.
- ****************Reinforcement Learning:**************** The model learns by interacting with an environment to achieve a goal.
    
    ****************************************************************************************************Like training a dog with treats for good behavior.**************************************************************************************************** 
    
- ****************************************Overfitting and Underfitting:****************************************
    - **************************Overfitting:************************** When your model learns the training data too well, failing on new data.
    - ****************************Underfitting:**************************** When your model is to simple to capture the complexity of the data.
- ************************************Cross-Validation:************************************ A technique to assess how well your model will perform on unseen data.
- **********************Metrics:**********************  Ways to measure your model’s performance
    - ******************************Classification:****************************** Accuracy, Precision, Recall, F1 Score.
    - ************************Regression:************************ MSE (Mean Squared Error), RMSE (Root Mean Squared Error)

# Classification: The Basics

<aside>
💡 In classification, the aim is to categorize items into one of several classes, For example, you might want to classify emails as spam or not spam.

</aside>

- ****************************************************Essential Concepts and Vocab:****************************************************
    - **********************************************Binary Classification:********************************************** Classifying items into one of two categories.
    - ****************Multi-Class Classification:**************** More than two categories are involved.
    - ********************************Confusion Matrix:******************************** A table that describes the performance of a classification model.
    - **************************Precision, Recall, F1 Score:************************** Matrices used to evaluate classification models.

# NLP: The Basics

<aside>
💡 Natural Language Processing (NLP) is about teaching machines to understand, interpret, and respond to human language. It is super useful for things like chatbots, search engines, and recommendation systems.

</aside>

## NLP Basics:

- **************************Tokenization:************************** Splitting text into smaller pieces, usually words or subwords.
- ********Word Embeddings:******** Converting words into vectors or numbers so that the machine can understand them.
- ****************************************Text Classification:**************************************** Assigning predefined categories to text, for example, spam detection.
- ********************************Named Entity Recognition (NER):******************************** Identifying entities like names, organizations, locations, etc. in text.
- ****************************************Machine Translation:**************************************** Converting text from one language to another.

# Recommendation Systems:

<aside>
💡 Recommendation Systems are the algorithms that power suggestions like “You might also like…” or “People who bought this also bought…” on websites like Amazon and Netflix.

</aside>

****Types of Recommendation Systems:****

- ************************************************Collaborative Filtering:************************************************ Recommends items based on what similar users have liked.
    - **********************User-User:********************** Finds similar users and recommends items they have liked.
    - ************************Item-Item:************************ Finds similar items based on user interactions and recommends them
- ********Content-based Filtering:******** Recommends items similar to ones the user likes, based on item features.
- **************Hybrid Systems:************** Combines both Collaborative and Content-Based methods for better recommendations.

# Recommendation Systems: Collaborative Filtering - The Basics

<aside>
💡 One of the most commonly used techniques in real-world recommendation systems: The idea behind Collaborative FIltering is straightforward: if two users agree on one issue, They’ll likely agree on others as well. There are mainly two types:

</aside>

- **********************************************************************User-User Collaborative Filtering:********************************************************************** If User A and User B have similar tastes on certain items, then the items liked by a but not yet interacted with by B can be recommended to B (and vice versa).
- ************************************************************Item-Item Collaborative Filtering:************************************************************ If Item 1 and Item 2 have been liked by a similar set of users, then a user who has liked item 1 can be recommended Item 2 (and vice versa)
