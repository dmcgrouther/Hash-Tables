# Hash-Tables

What are hash tables and why should you care?

Hash tables are alogorithms that help solve the problem of very large data sets. Essentially what they do is turn a certain input into an output. Important note... the algorithm must always get that same output. 

Lets use finding a word in the dictionary as an example of using a hash table. Normally you would need to search through the dictionary one by one to find the word. With a hashing algorithm of using the length of each word you could put them into a table. 
Enter collisions. The problem with adding your words in at a certain number (in this case length) is that there are many words with length 4, 5, and 6. To solve this what a hash table will do is be be able to have a bucket of sorts that can store multiple values.

For instance, the words "four", "none", and "dice" all have length four and would be in the four length bucket.

What the hashing algorithm would do is find that a certain word is in a particular bucket. This helps effectively skip the line so that the developer can get to the correct bucket and search there.


