# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Hash Tables

WHY:
Hash tables, also known as hash maps, are widely used data structures in computer science and programming. They provide efficient storage and retrieval of data, making them suitable for tasks that involve quick lookups, insertions, and deletions. The main advantage of hash tables is their ability to achieve constant-time complexity (O(1)) for these operations in the average case, making them highly efficient for handling large amounts of data.

WHAT:
A hash table is a data structure that stores key-value pairs. It uses a hash function to map each key to a unique index in an array, called the hash table or hash map. The hash function takes the key as input and computes a hash code, which is then used to determine the index where the value associated with the key will be stored. In other words, the hash function converts the key into a numerical representation that corresponds to an index in the hash table.

HOW:

1. Hash Function: A good hash function is essential for the proper functioning of a hash table. It should generate a uniform distribution of hash codes to minimize collisions (when multiple keys map to the same index). Ideally, a hash function should be fast and produce unique hash codes for different keys.

2. Hash Table Structure: A hash table typically consists of an array (buckets) and a hash function. The size of the array depends on the expected number of elements and the desired load factor (the average number of elements per bucket). The load factor helps maintain a balance between space efficiency and performance.

3. Storing Data: To store a key-value pair in a hash table, the hash function is applied to the key to compute the hash code. The hash code is then converted to an index within the array using a technique called modulo division (hash code % array size). The value associated with the key is stored at the computed index in the hash table.

4. Handling Collisions: Collisions occur when two or more keys produce the same hash code and map to the same index. Different techniques can be used to handle collisions, such as separate chaining or open addressing. In separate chaining, each bucket of the hash table contains a linked list to store multiple values that map to the same index. In open addressing, collisions are resolved by finding the next available index in the array.

5. Retrieving and Updating Data: To retrieve a value based on a key, the hash function is applied to the key to compute the hash code. The hash code is then used to determine the index in the hash table where the value is stored. Similarly, to update or delete a value, the key is hashed to locate the corresponding index and modify the value accordingly.

## Bookmark

[Intro to Hash Tables](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-30/resources/Hashtables.html)

[What is a hash table?](https://www.youtube.com/watch?v=MfhjkfocRR0)

[Basics of hash tables](https://www.hackerearth.com/practice/data-structures/hash-tables/basics-of-hash-tables/tutorial/)

[hash table wiki](https://en.wikipedia.org/wiki/Hash_table)

## Class Notes

## Things I want to know more about
