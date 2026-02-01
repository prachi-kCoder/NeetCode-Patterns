# COMBINATION-SUM 
- TC : `O( N ^ (T/M + 1))` , sc = O(T/M)
- T = TARGET , M = MIN ELEMENT OF NUMs , Now here branching factor is N as every recursive depth
- D = T/M at max , so at any D depth N^D nodes as all levels , d=0 , N^0 {ie 1node }, d=1 , {N nodes} , d=2 {N^2 .. corresding to all prev level node} , so from every node of prev level , N branches of N nodes are being branched out so `{1 , n , n^2 , n^3 ,....}` all nodes added give GP sum , and +1 for copying the curr->result , when match is found
- Do:https://leetcode.com/problems/combination-sum/submissions/1901943012/?envType=problem-list-v2&envId=rr2ss0g5


# COMBINATION SUM2 
- tc = (2^N) as any element can atmost be taken at once , incluce / exclude so comb for n elements : `2 x 2 x 2 x ....`
- sc = O(N) recursion stack  
- DO : https://leetcode.com/problems/combination-sum-ii/?envType=problem-list-v2&envId=rr2ss0g5

# GENERATE PARENTHESIS
- nth Catalan Number {1/(n+1) (2n)C(n)}-> All valid parenthesis, where open - closing parenthesis constraint is followed, as we can't blindly generate all permutation eg ))(( are invalids .
- TC = `O(4^n / sqrt(n))` -> because catalan nos grows -> `4^n / n*sqrt(n)  * O(n)` for `copying string` so simplies to-> 4^n / sqrt(n) ,you can say `O(4^n * n)` in interview as well for loose bound
- https://leetcode.com/problems/generate-parentheses/description/?envType=problem-list-v2&envId=rr2ss0g5
- SC = O(n) , recu stack depht O(2N) 

# SUDOKU SOLVER
- You always forget : 3 rows for row,col,box : to keep the mask of rows,cols,boxes separate !
- Do :https://leetcode.com/problems/valid-sudoku/?envType=problem-list-v2&envId=rr2ss0g5
- TC : O(9x9) , SC = O(27) nearly constant space for bitmasks .
  
# LETTER-COMBINATIONS
- TC = O(3^N x 4^m x L) where N+M = L length of digits , 3/4 choices & all comb: `3^n + 4^m x O(L)` O(L)-> string copying in result for all combination
- SC= O(N)
- Do : https://leetcode.com/problems/letter-combinations-of-a-phone-number/?envType=problem-list-v2&envId=rr2ss0g5
