# Read 30
# Hashtables

## Intro to Hash Tables
A Hash Table is a data structure that stores data in an associative manner. It is made up of two parts: an array, where the data is stored, and a Hash Function which is a mapping function. Basically, a Hash Function is a function that takes things from one space and maps them to a space for indexing.
A Hash Table is used to implement structures such as dictionary, map, or associative array and it is a data structure in which insertion and search operations are very fast.
The idea behind a Hash Table is that for each element we want to store, we calculate a unique address and we put the value at this index in the array. When we need to find a value, we once again calculate its index and then return the value. In other words, a Hash Table allows us to store and retrieve objects by key.

## What is a hash table?
A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.

## Hash table wiki
In computing, a hash table (hash map) is a data structure that implements an associative array abstract data type, a structure that can map keys to values. A hash table uses a hash function to compute an index, also called a hash code, into an array of buckets or slots, from which the desired value can be found. During lookup, the key is hashed and the resulting hash indicates where the corresponding value is stored.<br/>
Ideally, the hash function will assign each key to a unique bucket, but most hash table designs employ an imperfect hash function, which might cause hash collisions where the hash function generates the same index for more than one key. Such collisions are typically accommodated in some way.<br/>
In a well-dimensioned hash table, the average cost (number of instructions) for each lookup is independent of the number of elements stored in the table. Many hash table designs also allow arbitrary insertions and deletions of key–value pairs, at (amortized) constant average cost per operation.<br/>
