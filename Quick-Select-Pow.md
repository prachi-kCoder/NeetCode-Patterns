# Longest Consec- Seq :
- reach the start of seq ie such that start-1 does not exist and reach until the consec are found in set!
- https://leetcode.com/problems/longest-consecutive-sequence/?envType=problem-list-v2&envId=rr2ss0g5

  
# POW
- its similar to mod_expo , as it also does the same just without `mod` and with double type precision maintained
- Never forget to take long long to compute pos power as  neg->pos in can go out of integer out of range
- Do :https://leetcode.com/problems/powx-n/?envType=problem-list-v2&envId=rr2ss0g5
- tc : O(logN) , sc = O(1)


# Kth largest 
- Do :https://leetcode.com/problems/kth-largest-element-in-an-array/description/?envType=problem-list-v2&envId=rr2ss0g5
-  For BEST& AVG cases : Pivot partition the array in balanced way so O(N) , whereas in Worst case if min-max take as pivot -> partitions are unbalanced giving O(N^2)

# subarray-sum-divbyK
- 3pts :`neg rem handling r += k` , `Zero rem : mp[0] = 1` crucial and its all on prefix sum of arrays!
- Do:https://leetcode.com/problems/subarray-sums-divisible-by-k/description/
