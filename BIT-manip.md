# SUM 2 INTERGERS {without +}
- SUM with `a^b` ,  Carry = `a & b` , keep taking the carry value , as it must be propagated till it reaches 0
- O(32) as at most carry value will propagate to all 32 bit pos {if range is 64 then O(64)}
  
# BINARY LONG DIVISION
- {WITHOUT USING / , * , % ..} TC = O(LOG(DIVIDEND)) , SC O(1)
- https://leetcode.com/problems/divide-two-integers/submissions/1913123523/

# 1)Count Bits
- https://leetcode.com/problems/sum-of-all-subset-xor-totals/
- https://leetcode.com/problems/total-hamming-distance/
- https://leetcode.com/problems/reverse-bits/?envType=problem-list-v2&envId=rr2ss0g5

# 2) State masking
- https://leetcode.com/problems/subsets/
- https://leetcode.com/problems/beautiful-arrangement/

# 3) counting 
# xor of valus in [L,R] :
- use property (1-r)^(1-(l-1))  keeping the xor of values in range[L,R]
- https://www.geeksforgeeks.org/problems/find-xor-of-numbers-from-l-to-r/1
- <img width="563" height="321" alt="image" src="https://github.com/user-attachments/assets/b9c3c878-532b-4b4c-81d4-e52f3036ca11" />

- `SINGLE NUM2` :https://leetcode.com/problems/single-number-ii/
- `SINGLE NUM3` :https://leetcode.com/problems/single-number-iii/description/


# 4) and/or properties
- `keep in mind: ` for any differing bit {0->1} on high bit index , all the bit on its right must have been flipped atleast once !! 
- https://leetcode.com/problems/bitwise-and-of-numbers-range/
- 
- `OR SUBARRAYS` : shows monotonic property of subarray or's , as it keeps on increasing , at max N element can increase by all 32 bits ! O(N x 32)
- Do : https://leetcode.com/problems/bitwise-ors-of-subarrays/
- `all subset summed !` : https://www.geeksforgeeks.org/problems/sum-of-xor-of-all-possible-subsets/1

# --------------------------
- `IMPORTANT ONES `:
- 1) :https://leetcode.com/problems/minimum-one-bit-operations-to-make-integers-zero/
- 2) https://leetcode.com/problems/maximum-xor-with-an-element-from-array/
  3) https://leetcode.com/problems/bitwise-ors-of-subarrays/description/
  4) https://leetcode.com/problems/smallest-sufficient-team/
  5) https://leetcode.com/problems/maximum-genetic-difference-query/
  
