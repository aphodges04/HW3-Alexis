Read the paper and answer the following:
1. Briefly describe one important lesson about modularity that the paper describes and that you think is still relevant today.
   Design decisions from traditional modularity divides a stem based on order. Decouple by decisions, not flowcharts because Parnas demonstrates that the structure leaks implementation and how a change to a data structure requires modification at every module. Each module should be responsible for a specific design choice. Object oriented programming isolated design decisions inside modules so developers can rewrite data structures without causing a break within the code.

   Peer Response: I had a similar answer in talking about how the paper explains to us to organize our systems by decision rather them constructing them as a flowchart. Using modules also makes it much easier to go back and change your code, and avoid major damage if mistakes are made. 
   
3. Computing has advanced significantly since this paper was written. Briefly describe one challenge (not necessarily with modularity) or perspective that, while realistic in 1972, does not apply today.
   Today we have hardware like CPU and RAM as modern compilers to manage memory avoiding subroutines. In 1972, system memory was not as developed and without the hardware we have today, there is significant function calls overhead from procedural abstractions.

   Peer Response: I also used hardwares my example, but my answer was less in depth. I like how you went into describing CPU and RAM as actual examples of hardware that has improved since 1972. It also relates to our paper because without our more advanced hardware, it would be much more difficult to implement modularity. 
   
5. Have you used modularity or information hiding in a previous CS course? Briefly describe where and how. If not, how would you apply it to a past assignment.
   Yes, in my previous data structures class we have used modularity. For abstract data types we manipulate stacks with push(), pop(), and peek(). This means we can swap an array for a linked list without changing the code in the program that uses the stack. 

Peer Response: I personally haven't used modularity or info hiding, but I did say I would use modularity to organize my projects if. I knew about it at the time. I like your example from algorithms and how you explained that using those commands does not change the code. 
