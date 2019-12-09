# Hash-Tables

What are hash tables and why should you care?

Hash tables help solve the problem with retrieving data in very large data sets. Essentially what happens is a hashing algorithm will turn an input into an output and store this information as needed. Important note... the algorithm must always get that same output. 

Lets use finding a word in the dictionary as an example of using a hash table. Normally you would need to search through the dictionary one by one to find the word. With a hashing algorithm of using the length of each word you could put them into a table. 
Enter collisions. The problem with adding your words in at a certain number (in this case the length of the word) is that there are many words with length 4, 5, and 6. To solve this what a hash table will do is have a bucket of sorts that can store multiple values.

For instance, the words "four", "none", and "dice" all have length four and would be in the four length bucket.

What the hashing algorithm would also be able to do is find that a certain word is in a particular bucket. This helps effectively skip the line so that the developer can get to the correct bucket and search there.

Real world example of hash tables
Example 1.
When you go bowling and you swap your shoes for bowling shoes. They take your shoes, put them in the bowling shoe box that includes your size, and give you the shoes and a token which has the size (hash) and the shoe pair number (element in the hash box).


Example 2.
A more physical example of a hash table might be a library card catalog.  Most libraries will hold thousands of books at a time, and it is unreasonable to expect anyone to look through every book in a library to find the one they are looking for.  Enter the card catalog, a way of entering some information about a particular book, and recieving a general location in return.  You can look up the title of a book, and a card catalog will tell you, in general, where to look for it.  It may not be a perfect location, but looking through one shelf of books is a lot easier then searching through the whole library.


Different type of Questions that can be solved using Hash Tables:
1. Calculation of hash values for given keys.
2. Insertion of keys into hash table using linear probing as collision resolution technique.
3. Given a hash table with keys, verify/find possible sequence of keys leading to hash table.

Sources

https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/
https://leetcode.com/tag/hash-table/
https://www.geeksforgeeks.org/practice-problems-on-hashing/
