MassiveDataAnalysis
===================

1. MTA Traffic Analysis
  
  Contains a .vt file developed on the software Vistrails (http://vistrails.org/index.php/Main_Page)
  The data sets released by MTA (http://web.mta.info/developers/fare.html) are analysed using Vistrails
  
2. Hadoop
  
  Contains solutions implemented in Java for the following exercises
   These programs have been executed on Amazon Web Services using an Elastic Map Reduce and S3 bucket

  Exercise 1: Fixed-Length WordCount
    For this exercise, you will only count words with 5 characters
    Output: Key is the word, and value is the number of times the word appears in the input.

  Exercise 2: InitialCount
    Count the number of words based on their initial (first character), i.e., count the number of words per initial
    The letter case should not be taken into account. For example, Apple and apple will be both counted for initial A
    Output: Key is the initial (A to Z in UPPERCASE), and value is the number of words having that initial (in either uppercase or lowercase).

  Exercise 3: Top-K WordCount
    Output the top 100 most frequent 7-character words, in descending order of frequency
    Output: Key is the word, and value is the number of times the word appears in the input.
