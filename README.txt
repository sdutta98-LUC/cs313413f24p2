Question 1: TODO also try with a LinkedList - does it make any difference?
Answer: Linked list performs faster for insertion and removal but behaviorally it remains the same.

Question 2: TODO what happens if you use list.remove(Integer.valueOf(77))?
Answer: Using list.remove(Integer.valueOf(77)) in the loop causes an error because it changes the list while the loop is iterating
Using list.remove(Integer.valueOf(77)) out side of the loop only removes one instance of 77 from the list.

Performance Report:

Size(@1000000 Reps)           Time
10 -------------------------- 114 ms
100 ------------------------- 126 ms
1000 ------------------------ 451 ms
10000 ----------------------- 4s 848ms
100000 ---------------------- 1min 9s


Inceasing the REPS from 1000000 to 10000000 significantly increases the runtimes from 4.6s to 43.2s


