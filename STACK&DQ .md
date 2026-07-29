# shortest subarray with sum atleast K 
-> amazing ques:https://leetcode.com/problems/shortest-subarray-with-sum-at-least-k/ 
-> Dono use kadane's as it , refreshing any neg prefix sum = 0 , may leads to testcase miss ,
```cpp
eg pre[i] = -10 and if refreshed to 0 but some j > i gave pre_sum = 5 then for k = 15 we won't cover pre[j] - pre[i] >= k
```

# VALID PARENTHESIS WITH *
- Just keep a range of min-max opening parenthesis range of cnt {mnOpen = only `(` and `*` & `)` -> are closing ones} , {mxOpen = {`)` , `*`} , `(` are is closing only} 
- Do : https://leetcode.com/problems/valid-parenthesis-string/?envType=problem-list-v2&envId=rr2ss0g5


# Car fleet
- O(N) , Sort based on which one is nearer to target , as soon as can car can't catch then any prev car will then catch the curr one!
- dO :https://leetcode.com/problems/car-fleet/description/?envType=problem-list-v2&envId=rr2ss0g5
  
# Stack & DQ
- Min stack : Don't complicate this , keep track of the min upto a value pushed into by looking at minima pushed into so far and new ele at any time 
- Do : https://leetcode.com/problems/min-stack/?envType=problem-list-v2&envId=rr2ss0g5
