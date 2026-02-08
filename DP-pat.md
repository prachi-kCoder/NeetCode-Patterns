

# LCS VARIATION
- `count DISTINCT SUBSEQ IN S = T` o(NxM) , optimise its for sc = O(N) space
- Do :https://leetcode.com/problems/distinct-subsequences/submissions/1900790043/?envType=problem-list-v2&envId=rr2ss0g5

# JUMP-GAME 2
- DON'T do this with dp as it take O(N^2) TC , O(N) space ,do it greedily as you found the range intuition!
- Do :https://leetcode.com/problems/jump-game-ii/submissions/1904255386/?envType=problem-list-v2&envId=rr2ss0g5

# coin-change2 
- Here take all set , all combinations was need so NO sorting but in case permutation would have been asked so sorting become imp !
- Do:https://leetcode.com/problems/coin-change-ii/?envType=problem-list-v2&envId=rr2ss0g5
  
------------------------------------------------------------------------------------------------------------------------------
# STRIVER DP - STRING :
### STRING - DP
- `LONGEST PALINDROMIC SUBSEQ` : do : https://leetcode.com/problems/longest-palindromic-subsequence/submissions/1906597968/
  
- `MINIMUM INSERTION TO MAKE STRING PALINDROME` :
- method1 : `n - LPS(s)` ,  method2 = `LCS(s , reverse(s))` : tc : O(N^2) , sc = O(N) for both 
- DO : https://leetcode.com/problems/minimum-insertion-steps-to-make-a-string-palindrome/description/

- `PALINDROME PATITIONING` : https://leetcode.com/problems/palindrome-partitioning/submissions/1875067053/?envType=problem-list-v2&envId=rr2ss0g5
- TC =  `O(N * 2^N)` as O(N) string copying time for all partitions , for every n length n-1 cuts / partitions possible 
####  STRANGE-PRINTER : 
- Here match the first char s[i] to any other in s[i+1 to j] so that you don't need to pay for the front character , and worst case is if not matched so pay  + 1 + dp[i+1][j] 
- https://leetcode.com/problems/strange-printer/

------------------------------------------------------------------------------------------------------------------------------
## MAXIMAL RECTANGLE ,{MATRIX & DP , SQUARE }
- simple approach is `max-rect histogram` just keep the consecutive 1's count while incrementing i, giveing the hts of towers to get max-rect area , O(NXM) tc 
- DO :https://leetcode.com/problems/maximal-rectangle/
- Do :https://leetcode.com/problems/count-square-submatrices-with-all-ones/



# -----------------------------------------
# FROG-JUMP :
- just keep in mind starting , memo based on idx, jump magnitude as they can overreach 2000 as, at any index +1 is max increse in jump so , jump mag won't every exceed 2000
- dO : https://leetcode.com/problems/frog-jump/submissions/1907485778/

# decode ways
- single dp :https://leetcode.com/problems/decode-ways/submissions/1908909483/?envType=problem-list-v2&envId=rr2ss0g5

# SUBSET Array to get diff from 2 subset partioning types
- s1 - s2 = diff , so s1 + s2 = total_sum , so s1= target = (total_sum - diff)/2 ;
- you can handle zeroes sep or standard dp both works fine as every zero can make in total 2^Z combination of z for all subsets formed !
- do :https://www.geeksforgeeks.org/problems/partitions-with-given-difference/1

# edit distance;
- 1d pass , {single pass !} varations : https://leetcode.com/problems/edit-distance/submissions/1902002337/?envType=problem-list-v2&envId=rr2ss0g5


# BURST-BALLONS 
- keep in mind , `PADDING+1 both sider` , len =1 so loop start hoga , `if kth the last balloon in [i,j]` so `curr_val = nums[i-1] * nums[k] * nums[j+1]` 
- https://leetcode.com/problems/burst-balloons/submissions/1909223342/
