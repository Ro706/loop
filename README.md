# loop
In computer science, a loop is a programming structure that repeats a sequence of instructions until a specific condition is met. Programmers use loops to cycle through values, add sums of numbers, repeat functions, and many other things.

Loops are supported by all modern programming languages, though their implementations and syntax may differ. Two of the most common types of loops are the while loop and the for loop.
While Loop

A while loop is the simplest form of a programming loop. It states that while a condition is valid, keep looping. In the PHP example below, the while loop will continue until i is equal to num.

   $i = 1;
   $num = 21;

   while ($i < $num)  // stop when $i equals $num
   {
       echo "$i, ";
       $i++;   // increment $i
   }

If $i is 1 and $num is 21, the loop will print out 1, 2, 3, 4… etc. all the way to 20. Then the loop will stop or "break" after 20 iterations because the while condition has been met.
For Loop

A for loop is similar to a while loop, but streamlines the source code. The for loop statement defines the start and end point as well as the increment for each iteration. Below is the same loop above defined as a while loop.

   $num = 21;

   for ($i = 1; $i < $num; $i++)  // stop when $i equals $num
   {
       echo "$i, ";
   }

Though for loops and while loops can often be used interchangeably, it often makes more sense to use one over the other. In most cases, for loops are preferred since they are cleaner and easier to read. However, in some situations, a while statement can be more efficient. For instance, the following PHP statement can be used to load all the values from a MySQL result into an array using only one line of code.

   while ($row = mysql_fetch_array($result))

NOTE: Since loops will repeat until a given specific condition is met, it is important to make sure the loop will break at some point. If the condition is never met, the loop will continue indefinitely creating an infinite loop. Writing code that allows infinite loops is bad programming practice, since they can cause programs to crash.
link - https//gtihub.com/Ro706/loop
