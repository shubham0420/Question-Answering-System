# Question-Answering-System
#Task
The task is simple, build a Retrieval System to pick the right answer to a certain question, from a dataset.

An user ask a question, your model, process the question and pick the most suitable answer from a knowledge base dataset, in which the right answer is.

The user input can be slightly(or even totally different, that can be cover later on) different from the based question

Example:
In dataset:
Q: what's your address  
A: I don't have any address  
User input:  
Q: where are you located  
A: I don't have any address  

#Data
4 files to work with, 2 files for each steps(training and test):

train_dataset.txt, train_dataset_2.txt, are the dataset for training, it's formatted in a way to be easy to process:
1- first line is a question  
2- second line is the answer to the question  

you can take it another way:
1- Odd line number is a question  
2- Even line number is an answer  

test_dataset.txt, test-data.txt are the dataset for testing, it's formatted in a way to be easy to process:
1- first line is a question
2- second line is the right answer to the question
you can take it another way:
1- Odd line number is a question
2- Even line number is a right answer
