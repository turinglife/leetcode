
- Algorithms Interview

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

- Coding Interview

Most important is the ability to write clean and correct code—it’s not enough just to be correct. A lot of people will be interacting with your code once you’re on the job, so it should be readable, maintainable, and extensible where appropriate.

Break the problem down and define abstractions. One crucial skill we look for is the ability to handle complexity by breaking problems into manageable sub-problems. For anything non-trivial, you’ll want to avoid writing one giant, monolithic function. Feel free to define helper functions, helper classes, and other abstractions to reach a working solution. You can leverage design patterns or other programming idioms as well. Ideally, your solution will be well-factored and as a result easy to read, understand, and prove correct.

Think about edge cases. Naturally, you should strive for a solution that’s correct in all observable aspects. Sometimes there will be a flaw in the core logic of your solution, but more often your only bugs will be in how you handle edge cases. (This is true of real-world engineering as well.) Make sure your solution works on all edge cases you can think of. One way you can search for edge-case bugs is to…

Clean Code: A Handbook of Agile Software Craftsmanship - Robert C. Martin
Code Complete: A Practical Handbook of Software Construction - Steve McConnell
The Practice of Programming - Brian Kernighan, Rob Pike
Design Patterns: Elements of Reusable Object-Oriented Software - Erich Gamma, et al.
Effective Java - Joshua Bloch

- System Design Interview

the systems design interview is all about communication.

For the most part, you’ll be steering the conversation. It’s up to you to understand the problem. That might mean asking questions, sketching diagrams on the board, and bouncing ideas off your interviewer. Do you know the constraints? What kind of inputs does your system need to handle? You have to get a sense for the scope of the problem before you start exploring the space of possible solutions. And remember, there is no single right answer to a real-world problem. Everything is a tradeoff.

Systems are complex, and when you’re designing a system you’re grappling with its full complexity. Given this, there are many topics you should be familiar with, such as:

-- Concurrency. Do you understand threads, deadlock, and starvation? Do you know how to parallelize algorithms? Do you understand consistency and coherence?
-- Networking. Do you roughly understand IPC and TCP/IP? Do you know the difference between throughput and latency, and when each is the relevant factor?
-- Abstraction. You should understand the systems you’re building upon. Do you know roughly how an OS, file system, and database work? Do you know about the various levels of caching in a modern OS?
-- Real-World Performance. You should be familiar with the speed of everything your computer can do, including the relative performance of RAM, disk, SSD and your network.
-- Estimation. Estimation, especially in the form of a back-of-the-envelope calculation, is important because it helps you narrow down the list of possible solutions to only the ones that are feasible. Then you have only a few prototypes or micro-benchmarks to write.
-- Availability and Reliability. Are you thinking about how things can fail, especially in a distributed environment(https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing)? Do know how to design a system to cope with network failures? Do you understand durability?
Remember, we’re not looking for mastery of all these topics. We’re looking for familiarity. We just want to make sure you have a good lay of the land, so you know which questions to ask and when to consult an expert.

leveldb(https://github.com/google/leveldb, http://leveldb.googlecode.com/svn/trunk/doc/impl.html)

- UI Interview


- Decomp Interview

Short for ‘decomposition of problems,’ the decomp interview helps us get a sense of how well you’re able to break down a problem into its nitty-gritty components, before the actual nitty-gritty building begins.




