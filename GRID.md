
### PACIFIC & ATLANTIC CONNECT
- Here keep in mind to avoid race condition we have to start from boundaries of both ! so reach all reachable cell from both and mark in diff 2-D and this si cleaner!
- Do : https://leetcode.com/problems/pacific-atlantic-water-flow/submissions/1900942029/?envType=problem-list-v2&envId=rr2ss0g5
 
#####
- multisrc bfs : https://leetcode.com/problems/as-far-from-land-as-possible/
- {Donot forget edges cases}

# LANDMINES 
- YOUR MISTAKES : `Donot mark the adjacent of landmines as 0 otherwise then may start chain rxn`  mistaken assumed as landmines, use 2 instaead 
- `Donot mark blindly the nbr cells` , do check i should be 1 -> 2 , never a landmines itself should be marked as 2 , leading to loss to landmines 
- Do level wise bfs with marking as 0 with vis , and donot 
- Do :https://www.geeksforgeeks.org/problems/find-shortest-safe-route-in-a-matrix/1
