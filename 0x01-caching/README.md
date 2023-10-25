# Caching; The ALX Project
-----------
Caching is essential in optimizing the performance of applications, 
especially those dealing with large datasets or complex computations. 
This project provides a simple caching system that stores key-value pairs in memory, 
allowing for fast retrieval of data.

__Features__

- `Basic Caching`: Implements a basic caching mechanism with methods for storing, retrieving, and deleting key-value pairs.
- `LRU` (__Least Recently Used__) __Policy__: Uses the LRU policy to manage cache size. 
When the cache reaches its limit, the least recently used items are removed first.
- `Thread-Safe`: Implements thread-safe operations to ensure data consistency in a multi-threaded environment.
- `Customizable`: Allows users to set the cache size limit and customize the caching policies
