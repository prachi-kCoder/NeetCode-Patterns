
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
