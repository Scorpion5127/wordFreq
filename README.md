# wordFreq
Csc113 Project

Project Report
Project Topic Introduction:
The “Word Count Project” demanded an algorithm to read a file and count each logical word in the file into another file with the name of our choosing, via a data structure.

Design:
To start off our program reads a file line by line, each line is filtered through for coherent words and put into a dictionary data structure where the keys are the words, and the values are the frequency of each word. The Dictionary is then written to a file. The filtering of each line starts with a list of strings separated by a space for said line. The re class is utilized to replace all literals that are not letters with a null/empty character.

Results Analysis:
For our test results we check our code to see if it omits non-letters, given this: “G47)oo@#d”.
   
And as expected our results give meaningful words. Using any threads will not give us good results as it will read and write for each thread running.
