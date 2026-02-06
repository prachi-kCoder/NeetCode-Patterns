-- Keep revising 

# Word ladder from begin -> endword 
`{min shortest path variation}`  : O(N * L*L * 26) ,{L^2 is for mutation then insert/hash in nextlevel !} sc = O(N) for head and tail , wordset  
- 2 way bfs using head & tail sets as soon as any of these empty or you get the other end in other list then converge , and `ladder increments +1` , smaller of these
- Do; https://leetcode.com/problems/word-ladder/submissions/1788948662/?envType=problem-list-v2&envId=rr2ss0g5 
