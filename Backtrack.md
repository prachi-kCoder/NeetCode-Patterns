# COMBINATION-SUM 
- TC : `O( N ^ (T/M + 1))` , sc = O(T/M)
- T = TARGET , M = MIN ELEMENT OF NUMs , Now here branching factor is N as every recursive depth
- D = T/M at max , so at any D depth N^D nodes as all levels , d=0 , N^0 {ie 1node }, d=1 , {N nodes} , d=2 {N^2 .. corresding to all prev level node} , so from every node of prev level , N branches of N nodes are being branched out so `{1 , n , n^2 , n^3 ,....}` all nodes added give GP sum , and +1 for copying the curr->result , when match is found
- Do:https://leetcode.com/problems/combination-sum/submissions/1901943012/?envType=problem-list-v2&envId=rr2ss0g5


# COMBINATION SUM2 
- tc = (2^N) as any element can atmost be taken at once , incluce / exclude so comb for n elements : `2 x 2 x 2 x ....`
- sc = O(N) recursion stack  
- DO : https://leetcode.com/problems/combination-sum-ii/?envType=problem-list-v2&envId=rr2ss0g5
