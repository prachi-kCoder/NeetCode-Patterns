# Course-Schedule3 
-> { Task schdule of dur , and (s,e)}
- hint :https://leetcode.com/problems/course-schedule-iii/description/

# Mini Money Req Before :
- {Intuiontion : Any way you will be paying all losses , and lossy last transaction {MAX CashBack + Loss of ti transaction{already taken}-> you may have already paid while starting up / Max Cost amount any profit tx -> you may pay anyway }
- Link :https://leetcode.com/problems/minimum-money-required-before-transactions/

# GREEDY-OA
- `2PASS GREEDY is enough` as just L,R nbr are to be so start from left most having no left , rightmost having no right are right and keep up with constraints!
- Here: https://leetcode.com/problems/candy/description/

# Max tasks 
- https://leetcode.com/problems/minimum-time-to-complete-all-tasks/description/

## EQUALIZE Array 
-> With every ith elemnt , can used now why not any other element outside nums may come out as global minima , but here think 
-> SORTED ARR , then any ```x element num[i] , nums[i+1]  if any x  in this range so effective the range follows a CONSTANT FUNCTION so all element in that range will effective give the same no. of operation to transform as [12,28] let x from this range so SUM of (x-12) + (28-x) => 16 as net effect of x gets cannecelled out giving out a constant function at intersection !``` 
- DO = https://leetcode.com/problems/minimum-moves-to-equal-array-elements-ii/
- Better DO :https://leetcode.com/problems/minimum-cost-to-make-array-equal/description/
- {Hard one think of every individual element as a cluster of element of 1 operation cnt {with weighted cnt ! , hecen left_cnt becomes left_pref_sum and Right cnt become right suffix sum of COSTS }}

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
