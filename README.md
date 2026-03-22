# assignments
this repo for assignments which i am enrolled.
Why is a linked list good for a stack?

A linked list is great because the stack can grow and shrink whenever we need. Unlike an array, we don’t have to pick a size ahead of time. Adding or removing items is simple and doesn’t waste memory.

2. How fast are push and pop?

Both push adding an item and pop (removing the top item) are very fast. They happen in constant time, which means it doesn’t matter how big the stack is — the operations take about the same amount of time.

3. What happens if memory is not freed after pop?

If we don’t delete a node when we pop it, the memory it used stays taken up even though we’re not using it anymore. This is called a memory leak and it can make the program slow or crash if it keeps happening.

4.  Feature                Array Stack                     Linked List Stack               

 size                Fixed size, can run out         Can grow or shrink easily      
  Memory usages        Might waste space              |Uses only what we need         
  Overflows         Can happen if full              Rare, only if memory is full   
  How easy to make     Easy                            A little harder (needs pointers) 
  Access top element   Fast                            Fast                           
  push / pop            Fast                            Fast                           


In short: Linked lists are more flexible, and arrays are simpler if you know the size in advance.
