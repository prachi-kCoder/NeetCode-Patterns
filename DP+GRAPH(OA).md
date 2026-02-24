
# OA LEVEL : DIY
- https://leetcode.com/problems/count-all-possible-routes/

- `GRID DP PARTITION PIZZA-APPLES `
- https://leetcode.com/problems/number-of-ways-of-cutting-a-pizza/description/

### `EULERIAN PATH- HEIZER HOLZER ALGO : ` : TC O(E) , {ques: path may contain a node more then once ... covering all edges}
`SIMPLE EULERIAN PATH :`- either completely cyclic is for all nodes in_deg = out_deg , or Exactly 2 of the nodes at ends {one of them with more indeg  and the other one with more outdeg , take the outdeg one to start rightly and reach the other dead end } 
- steps : 1) POST ORDER , 2) AS DFS reaches DEAD END , then get the node added , 3) REVERSE the ckt to get the right order of EULERIAN PATH {start->end}
- Itinery:https://leetcode.com/problems/reconstruct-itinerary/description/?envType=problem-list-v2&envId=rr2ss0g5
- Valid arr: https://leetcode.com/problems/valid-arrangement-of-pairs/description/
