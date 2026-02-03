
# ROTATE IMAGE :
- Don't make it complex : 2 simple steps : take `transpose` + reverse `all rows`
- Do : https://leetcode.com/problems/rotate-image/?envType=problem-list-v2&envId=rr2ss0g5
    
## PACIFIC & ATLANTIC CONNECT
- Here keep in mind to avoid race condition we have to start from boundaries of both ! so reach all reachable cell from both and mark in diff 2-D and this si cleaner!
- Do : https://leetcode.com/problems/pacific-atlantic-water-flow/submissions/1900942029/?envType=problem-list-v2&envId=rr2ss0g5

# ROTTEN ORANGE :
- Just keep count of fresh_orange to eliminate last pass , Do : https://leetcode.com/problems/rotting-oranges/?envType=problem-list-v2&envId=rr2ss0g5
#####
- multisrc bfs : https://leetcode.com/problems/as-far-from-land-as-possible/
- {Donot forget edges cases}

# LANDMINES 
- YOUR MISTAKES : `Donot mark the adjacent of landmines as 0 otherwise then may start chain rxn`  mistaken assumed as landmines, use 2 instaead 
- `Donot mark blindly the nbr cells` , do check i should be 1 -> 2 , never a landmines itself should be marked as 2 , leading to loss to landmines 
- Do level wise bfs with marking as 0 with vis , and donot 
- Do :https://www.geeksforgeeks.org/problems/find-shortest-safe-route-in-a-matrix/1


# Spiral-Mat :
- {top,btm , left,  right } keep all of these in at right boundaries 
- Do https://leetcode.com/problems/spiral-matrix/?envType=problem-list-v2&envId=rr2ss0g5

# 0-1 BFS :
- can use djiktra but on o,1 cost tradeoff use deq , with LOWER COST entry at front and high cost at back, , get O(V + E) tc where V = NXM, e-> 4 for each . and every cell is visited at once and low cost , monotonic dq keep sorted entries as per cost , as any cel can have a diff of at most x , x+1 so 0/1 entry is enough! 
- https://leetcode.com/problems/minimum-cost-to-make-at-least-one-valid-path-in-a-grid/description/
