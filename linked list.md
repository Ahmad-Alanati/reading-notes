# linked list

## big O

big O is a way to describe your algorithm efficiency

there is two factors to evaluate your algorithm:
1. the running time
2. the memory space

to analyze the limits of you algorithm you should consider those 4 key areas:
1. input size
2. units of measurement
3. orders of growth
4. best case, worst case ,and average case

### input size 

we refer to the input size as "n" and our algorithm efficiency has inversely proportional to n.

### units of measurement

in algorithm efficiency there are three Sources of measurements for time complexity:

1. milliseconds:"different machines will have different run time"
2. operations:"the number of lines of code that got executed"
3. basic operations:the operation that takes most of the tunning time

in algorithm efficiency there are four Sources of measurements for space complexity:

1. the amount of space to hold the code for the algorithm:
2. The amount of space needed to hold the input data.
3. The amount of space needed for the output data.
4. The amount of space needed to hold working space during the calculation.

### orders of growth

for every algorithm how much the input size effect the running time and the memory space.


## linked list

### what is linked list?

link list is a group of nodes that is organize and every node points to the node after her.

### thinks to remember

1. linked list is a data structure.
2. linked list has type of references there is singly and doubly, singly means that the every node can point to the next node, doubly means that every node can point to the next and the previous node.
3. every node contain  data.
4. each node contain a property call next
5. head is a pointer that point to the first element in the linked list
6. current is a reference of type node that point to the node you are currently being looked at.
7. in linked list you can't use foreach or for so your only option is to the next.