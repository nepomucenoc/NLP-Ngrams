# Measure of Similarity Between Texts - Containment
In this notebook, we will implement a containment function. This function will compare two texts and analyze the similarity in relation to n-grams intersection. First, we will understand the vocabulary concepts, and n-grams to posteriorly implement the function.

## Count N-grams
The sequence of the n elements in a phrase:

* letters
* words
* symbols
* grammar classification
* 
First, we have to count the occurrences of n-grams of our texts. We will use CountVectorizer to convert the text dataset into a count array.
In the code, we can vary the value of n and use the CountVectorizer to count occurrences of n-grams. We can see that in the cell we are creating a vocabulary through the use of the CountVectorizer and, later, we will analyze the count matrix.
