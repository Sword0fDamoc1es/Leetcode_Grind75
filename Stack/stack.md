## Grind75 - stack.
1. lc 232
   1. use double stack, 倒来倒去
2. lc 150
   1. use stack. if +-*/, pop 2 prev int and operate.
3. lc 155
   1. minstack. using two stacks, the minstack always get min. Thus think about snapshot of minstack to stack. stack pop, minstack may not pop.
   2. or we can create a node. node contains prev min and current val. 
4. lc 42 trapping rainwater. (DP can also solve this.)
   1. using stack, mono stack - decrease.
   2. storing index, to remember to tranfer from index to height.
5. lc 224
   1. stack is used to hold the number.
   2. in each recursion, we hold a stack. end of recursion, we output the sum in the stack.
   3. next recurtion will get val from prev recursion, mainly happens at an end of block calculation, like end of ).
4. 