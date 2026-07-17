# Course-Schedule3 
- hint :https://leetcode.com/problems/course-schedule-iii/description/

# GREEDY-OA
- `2PASS GREEDY is enough` as just L,R nbr are to be so start from left most having no left , rightmost having no right are right and keep up with constraints!
- Here: https://leetcode.com/problems/candy/description/
- 
## MAX EVENTS TO ATTEND 
-https://leetcode.com/problems/maximum-number-of-events-that-can-be-attended/description/
-{DON'T just think of early start / end time as both matter in case earlier end time may lead to events getting missed of those whose start < the start of event with earliest end eg [1,5][2,3][3,4][4,5]} -> here early end sorting leads to : [[2,3][3,4],[4,5],[1,5]] then you don't reallycount [1,5] but incorrect !!

 # IPO :
 - Halwa ques hai! -> `pure profit is given !` , O(NLOGN) : sorting + pq
 - dO: https://leetcode.com/problems/ipo/description/

# MAX-ELEGANCE
- Swap b/w topK categories duplcates and rest of values : https://leetcode.com/problems/maximum-elegance-of-a-k-length-subsequence/description/
# min-transaction ;
- cred-debit simplify the transaction value!
- https://www.geeksforgeeks.org/problems/minimize-cash-flow/1


# Mini Interval-to-include 
- `LAZY QUERY PROCESSING` , `SORT queries` 
- Do :https://leetcode.com/problems/minimum-interval-to-include-each-query/description/?envType=problem-list-v2&envId=rr2ss0g5
- Flowers - Difference array{start time and endtimes the diff {leverage bsearch to get cnt !}}: O(MlogM + NlogN)
-  https://leetcode.com/problems/number-of-flowers-in-full-bloom/submissions/1938214995/
