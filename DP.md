
# LCS VARIATION
- Formation of t string Dp states keep cnt of ways of forming t string! o(NxM) , optimise its for sc = O(N) space
- Do :https://leetcode.com/problems/distinct-subsequences/submissions/1900790043/?envType=problem-list-v2&envId=rr2ss0g5


# JUMP-GAME 2
- DON'T do this with dp as it take O(N^2) TC , O(N) space ,do it greedily as you found the range intuition!
- Do :https://leetcode.com/problems/jump-game-ii/submissions/1904255386/?envType=problem-list-v2&envId=rr2ss0g5

# coin-change2 
- Here take all set , all combinations was need so NO sorting but in case permutation would have been asked so sorting become imp !
- Do:https://leetcode.com/problems/coin-change-ii/?envType=problem-list-v2&envId=rr2ss0g5
  
# STRIVER DP - STRING :
### STRING - DP
- `LONGEST PALINDROMIC SUBSEQ` : do : https://leetcode.com/problems/longest-palindromic-subsequence/submissions/1906597968/
- use this to compute insertion to get palindrome , ie` n-LPS` insertion to make to get complete string changed to palindrome 
- `MINIMUM INSERTION TO MAKE STRING PALINDROME` : DO : https://leetcode.com/problems/minimum-insertion-steps-to-make-a-string-palindrome/description/

####  STRANGE-PRINTER : 
- Here match the first char s[i] to any other in s[i+1 to j] so that you don't need to pay for the front character , and worst case is if not matched so pay  + 1 + dp[i+1][j] 
- https://leetcode.com/problems/strange-printer/


# edit distance;
- 1d pass , {single pass !} varations : https://leetcode.com/problems/edit-distance/submissions/1902002337/?envType=problem-list-v2&envId=rr2ss0g5
