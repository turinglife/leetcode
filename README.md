

Algorithms

Sorting (plus searching/binary search)
Divide-and-conquer
Dynamic programming/memoization
Greediness
Recursion
Algorithms associated with a specific data structure
Bloom filter
suffix tree



Data Structures

Array
Stack/Queue
Hashset/Hashmap/Hashtable/Dictionary
Tree/binary tree/balanced binary tree, complexity on time and storage.
Heap
Graph



You should know these data structures inside or outside.
What are the insertion/deletion/lookup characteristics?(O(logn) for a balanced binary tree)
what are the common caveats?(hashing is tricky, and usually takes O(k) time when k is the size of the object being hashed)
what algorithms tend to go along with each data structure?(Dijkstra's for a graph)


code interview

Most important is the ability to write clean and correct code—it’s not enough just to be correct. A lot of people will be interacting with your code once you’re on the job, so it should be readable, maintainable, and extensible where appropriate.

Break the problem down and define abstractions. One crucial skill we look for is the ability to handle complexity by breaking problems into manageable sub-problems. For anything non-trivial, you’ll want to avoid writing one giant, monolithic function. Feel free to define helper functions, helper classes, and other abstractions to reach a working solution. You can leverage design patterns or other programming idioms as well. Ideally, your solution will be well-factored and as a result easy to read, understand, and prove correct.

Think about edge cases. Naturally, you should strive for a solution that’s correct in all observable aspects. Sometimes there will be a flaw in the core logic of your solution, but more often your only bugs will be in how you handle edge cases. (This is true of real-world engineering as well.) Make sure your solution works on all edge cases you can think of. One way you can search for edge-case bugs is to…

Clean Code: A Handbook of Agile Software Craftsmanship - Robert C. Martin
Code Complete: A Practical Handbook of Software Construction - Steve McConnell
The Practice of Programming - Brian Kernighan, Rob Pike
Design Patterns: Elements of Reusable Object-Oriented Software - Erich Gamma, et al.
Effective Java - Joshua Bloch
