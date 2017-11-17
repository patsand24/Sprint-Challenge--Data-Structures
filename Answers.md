# Question Answers

### 1. What are the order of insertions/removals for the following data structures?
   - **Stack**
   - **Queue**

 - Stacks follow the LIFO or Last In First Out Principle and use the push and pop method for insertion and removal. Queue's utilize the FIFO or First in First Out property and use the enqueue and dequeue method to accomplish this.

### 2. What is the retreival time complexity for the following data structures?
   - **Linked List**
   - **Hash Table**
   - **Binary Search Trees**

 - Linked List has a retrieval time complexity of O(n)
- Hash Table has a retrieval time complexity of O(1)
- Binary Search Trees have a retrieval time complexity of O(log n)

- Definitely going to spens the week break reviewing time complexity and data structures in general. I feel pretty good about implementing data structures we've covered but definitely need to get a better feel for time complexity.

### 3. What are some advantages to using a Hash Tables over an array in JavaScript?

- In an array there is a time complexity of O(n) since retrieval is proportional to the number of items in the array. In a hash table on the other hand, retrival is done by matching a key provided and having the hashing function return the match. Instead of loping through multiple elements to find a match, the hash table knows where to retrieve the value.
 