## REORGER LL
- We can keep the mid 2 nodes as it is so slow->next and onwards reversed : {REVERSE THE SEC 1/2 , DISCONNECT THEM , INTERWEAVE !}
- Do :https://leetcode.com/problems/reorder-list/submissions/1915649750/?envType=problem-list-v2&envId=rr2ss0g5
  
## CLONE LL
- 3PHASE IMPLEMENTATION :
- `1) clone creation & weave` , `2) random pts connection {it can also point backward so need to be done once LL formed}`, `3) Separation , individually incrementing`
- In all 3 phases : we always increment by `+2` hops as we keep ourselve at original nodes , and all 3 are necessary 
- Do : https://www.geeksforgeeks.org/problems/clone-a-linked-list-with-next-and-random-pointer/1
  
## REVERSE NODES IN K-GROUP
- never forget getting count of nodes in LL , first be sure about k count of nodes then reverse and take gpstart , groupprev ptrs as well !
- do :https://leetcode.com/problems/reverse-nodes-in-k-group/?envType=problem-list-v2&envId=rr2ss0g5

## MULTILEVEL - FLATTEN
- Don't forget to check the next_node exist or not before `next_node->prev = child_tail` , and child_tail should be made null , and its Double LL
- do:https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/description/
  
## ADD nos ;
- Keep in mind they're already reverse, no need to reverse them agagin they are inthe order LSB to MSB so just sum them up ! O(max(n,m)+1)
- DO : https://leetcode.com/problems/add-two-numbers/description/?envType=problem-list-v2&envId=rr2ss0g5 

# Remove nth node from end:
- use fast-slow ptr technique
- Do : https://leetcode.com/problems/remove-nth-node-from-end-of-list/submissions/1902839402/?envType=problem-list-v2&envId=rr2ss0g5

# HappyNumber 
- O(N) slow,fast cycle detection
- Do :https://leetcode.com/problems/happy-number/submissions/1916908728/?envType=problem-list-v2&envId=rr2ss0g5
