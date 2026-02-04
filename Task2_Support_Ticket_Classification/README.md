# Task 2: Support Ticket Classification

## Objective
To build a machine learning model that automatically classifies customer support tickets into priority levels such as Critical, High, Medium, and Low.

## Dataset
The dataset contains real-world customer support tickets with information such as ticket subject, ticket description, and assigned priority levels.

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- TF-IDF Vectorizer
- Naive Bayes Classifier
- Jupyter Notebook (VS Code)

## Approach
1. Loaded and inspected the customer support ticket dataset
2. Combined ticket subject and ticket description into a single text feature
3. Converted textual data into numerical features using TF-IDF
4. Trained a Naive Bayes model for multi-class classification
5. Evaluated the model using accuracy and classification metrics
6. Tested the model using new, unseen support tickets

## Results
The model successfully classifies support tickets into different priority levels.  
Due to overlapping language patterns and subjective labeling, the achieved accuracy represents a realistic baseline for this real-world NLP problem.

## Conclusion
This project demonstrates the application of Natural Language Processing and machine learning techniques to automate ticket prioritization, helping support teams respond more efficiently to critical issues.