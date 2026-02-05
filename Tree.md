# VALIDATE BST 
- Keep the range , but not using the INT_MIN OR INT_MAX this will cause INTEGER OVERFLOW , keep `min_node` , `max_node` that will even handle the case if the root have int_min, int_max values
- Do : https://leetcode.com/problems/validate-binary-search-tree/submissions/1909021004/?envType=problem-list-v2&envId=rr2ss0g5
- O(N) SC recusion stk in skewed tree , O(N) TC

# Subtree of Another tree
- donot forget to make helper function to exactly match the subtree at any level , O(N * M) , N-> nodes is tree and M->node in subtree , O(H) in wost case O(N) for skewed tree -> H->max ht (ht of trre or subtree)
- Do : https://leetcode.com/problems/subtree-of-another-tree/submissions/1711176345/?envType=problem-list-v2&envId=rr2ss0g5

# Binary tree from preorder & inorder 
- Taking preIndex as `global` and `inorder idx map` is the right approach!
- Do : https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/submissions/1909052927/?envType=problem-list-v2&envId=rr2ss0g5
