-- Keep revising 

# WORD BREAK II
- TC : `O(2^N-1 * n   * m *L) ` , SC = `O(2^N x N)`->memo dp , 
- DP optimisation by O(2*N-1) .
- Do :https://leetcode.com/problems/word-break-ii/submissions/1912754458/
  
# WORD BREAK
- Make use of maxLen of beginWord , not more that 10 in this , O(N^2 * k) k->substring formation , don't go beyond the maxlen , O(N) sc 
- DP :https://leetcode.com/problems/word-break/submissions/1912725781/?envType=problem-list-v2&envId=rr2ss0g5

# ConcatedNates Words
- do : https://leetcode.com/problems/concatenated-words/

# Word ladder from begin -> endword 
`{min shortest path variation}`  : O(N * L*L * 26) ,{N *L * 26 -> BFS visible  , O(L) for hashing operations!} , sc = O(N) for head and tail , wordset  
- 2 way bfs using head & tail sets as soon as any of these empty or you get the other end in other list then converge , and `ladder increments +1` , smaller of these
- Do; https://leetcode.com/problems/word-ladder/submissions/1788948662/?envType=problem-list-v2&envId=rr2ss0g5 

# Word ladder II
- Do : https://leetcode.com/problems/word-ladder-ii/description/

# WORD-SEARCH II
- TC = O(NXM x 3^NXM ) , SC = O(NXM)
- DO: https://leetcode.com/problems/word-search-ii/?envType=problem-list-v2&envId=rr2ss0g5
