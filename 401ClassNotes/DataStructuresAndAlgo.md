# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Data Structure and Algorithms

### Watch

[Basic Recursion](https://www.youtube.com/watch?v=vPEJSJMg4jY)

- Recursion is a more effective way of breaking down problems by calling on a function of itself, even if loops can be better for performance.  
- Recursion allows code to be more readable and clearer of its goal.
- Every recursion has a base case and recursive case, the base case acts as the "conditional" to prevent the recursive case from recalling itself creating an infinite loop.

[Data Structures in 15 minutes](https://www.youtube.com/watch?v=sVxBVvlnJsM)

- Data structure are compound data being stored in a structure like the stock prices throughout a day.
- Linked lists contain a value and pointer that points to the next node, easy to add and delete nodes. However, it is bad at retrieval.
- Arrays are a continous block of cells in a computer memory and it can easily retrieve items, but adding to arrays can be difficult.
- Hash Table/ Object in Javascript. Similar to an array, but these memory points DONT need to be next to each other.  Easy to add, remove, and retrieve, but bad due to key collisions that happen under the hood.
- Stack + Que. The stack is last in, first out structure that utilizes the call stack. Que is first in, first out. Efficient with add and remove.
- Graph Trees, similar to linked lists with nodes being attached to a parent element, each parent element can only have 2 children that allow for data to be structured in a way that is easy to access that information.  However, this can become complicated if the nodes being added are not balanced properly.

[Big O Explained](https://www.youtube.com/watch?v=v4cd1O4zkGw)

- Big O goes into how data can scale in size to computation / run time.  How time scales with respect to the input variables.
- O(N) where n is the size of the array. N will be altered by being squared as its size or computation increases such as N^2. N is just a variable, most times N will represent whatever the data we are analyzing is.
- Big O is a computational representation of how runtime changes, so if we were manipulating 2 arrays( a & b) it could be represented as O(a*b).
- 4 rules : 1. Different steps get added, 2. Drop constants, 3. Different inputs => different variables, 4. Drop non-dominate terms.

### Read

[Basic Data Structures](https://towardsdatascience.com/8-common-data-structures-every-programmer-must-know-171acf6a1a42)

- Continuing with examples of data structures from the previous video.
- Heaps are special cases of binary trees where parent nodes are compared to their children with their values and are arranged accordingly. There are two types, Min heap and Max Heap. Min heap has a key that is less than or equal to those of its children, while Max heap is greater than or equal to those of its children. Heaps are used in heapsort algos, implement priority ques as the priority values can be ordered according to heap property.

[Why Big O](https://triplebyte.com/blog/why-you-should-learn-big-o-and-stop-hacking-your-way-through-algorithms)

### Questions

- When approaching a problem that requires the use of a data structure, I should analyze what the problems data will consist of and how I need to either add, remove, alter it within that structure.  If I need to add data like numbers stored in a list style an array seems best since they will be stored next to each other and accessed easily.  Or if I needed to create lists of information based on sports stats as an example, a hash table may be best since I can store individual data on each player in their own object information and assign a specific key for each to access.  It will come down to understanding how I want to use the information and how I will need to manipulate in the future.

- We need to ensure we have a base case in EVERY use of recursion.  The base case acts as the conditional of a loop.  It is what stops the recursive case from being invoked since our conditional was met, the base case.
