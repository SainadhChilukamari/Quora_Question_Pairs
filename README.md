# Quora_Question_Pairs

The goal is to predict which of the provided pairs of questions contain two questions with the same meaning. 
The ground truth is the set of labels that have been supplied by human experts. 

Data fields
id - the id of a training set question pair
qid1, qid2 - unique ids of each question (only available in train.csv)
question1, question2 - the full text of each question
is_duplicate - the target variable, set to 1 if question1 and question2 have essentially the same meaning, and 0 otherwise.
