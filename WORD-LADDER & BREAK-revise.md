-- Keep revising 

# WORD BREAK II
- TC : O(2^N-1 + N^3) , SC = O(2^N x N)->memo dp ,
- Total strings `2^N-1` ? s : `a_p_p_l_e`   then n-1 slots to cut/not : 2x2x2.. n-1 times so total strings formed 2^n-1
- N^3 : for start {all ends iterated} , and for any [s,e] we do string slicing that itself take O(N)!
- Do :https://leetcode.com/problems/word-break-ii/submissions/1912754458/
  
# WORD BREAK
- Make use of maxLen of beginWord , not more that 10 in this , O(N^2 * k) k->substring formation , don't go beyond the maxlen , O(N) sc 
- DP :https://leetcode.com/problems/word-break/submissions/1912725781/?envType=problem-list-v2&envId=rr2ss0g5


# Word ladder from begin -> endword 
`{min shortest path variation}`  : O(N * L*L * 26) ,{L^2 is for mutation then insert/hash in nextlevel !} sc = O(N) for head and tail , wordset  
- 2 way bfs using head & tail sets as soon as any of these empty or you get the other end in other list then converge , and `ladder increments +1` , smaller of these
- Do; https://leetcode.com/problems/word-ladder/submissions/1788948662/?envType=problem-list-v2&envId=rr2ss0g5 

# Word ladder II
- Do : https://leetcode.com/problems/word-ladder-ii/description/
