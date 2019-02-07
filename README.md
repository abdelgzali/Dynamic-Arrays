## Dynamic-Arrays

### Bitwise operation queries to demonstrate the flexibility of dynamic arrays like ArrayList (fixed test case)

- Create a list of 'N' empty sequences, where each sequence is indexed from 0 to N - 1. 
- Create int 'lastAnswer' initialized at 0.
- The  types of queries that can be performed on your list of sequences () are described below:
  1.Query: 1 x y
    - Find the sequence at index ((x^lastAnswer)%N) in your list.
    - Append integer y to sequence.
  2.Query: 2 x y
    - Find the sequence at index ((x^lastAnswer)%N) in your list.
    - Find the value of element y%(seq size) in the sequence and assign it to 'lastAnswer'.
    - Print the new value of lastAnswer on a new line.
