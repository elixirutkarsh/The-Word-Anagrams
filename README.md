# The-Word-Anagrams
Problem Statement: Given a list of words, write a program to find all pairs of words that are anagrams of each other. An anagram is a word formed by rearranging the letters of another word. Your program should return a list of these anagram pairs.

Solution:
To solve this problem, you can use a hash table or a dictionary. Iterate through each word in the list and sort its characters to obtain a sorted version of the word. Create a hash table where the keys are the sorted words, and the values are lists of original words that produce the sorted word. After iterating through all the words, iterate through the hash table and add pairs of words from each list value that have more than one word. This will give you the list of word anagram pairs.
