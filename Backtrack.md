# COMBINATION-SUM 
- TC its no 2^n !!! , ie Actually O(N ^ (T/M + 1)) , SC = O(T/M) due to recusion stack depth
- M => mini ele in nums , T-> target , Recursion stack depth at max = T/M and BRANCHING FACTOR  = N , ie becoz at every level we have N possible choice {0...n-1} any element
- At every level when target = 0 , so curr->copied to result taking O(T/M) extra at all braches so the total power = T/M + 1 with a braching factor of N => `O(N ^ (T/M + 1))`
  
- Do:https://leetcode.com/problems/combination-sum/submissions/1901943012/?envType=problem-list-v2&envId=rr2ss0g5

# COMBINATION SUM2 
