
# CLONE GRAPH
- Do : https://leetcode.com/problems/clone-graph/?envType=problem-list-v2&envId=rr2ss0g5
- Tc = O(N), SC = O(N) map

# prims's apply !
- MIN COST TO CONNECT PTS : {Apply `PRIM's modified` more efficient version as DENSE GRAPH{ E = V^2} , SC = O(V) } 
- Do:https://leetcode.com/problems/min-cost-to-connect-all-points/submissions/1916853479/?envType=problem-list-v2&envId=rr2ss0g5
  
## DSU IN grid :
- Most stones removed :
- Do:https://leetcode.com/problems/most-stones-removed-with-same-row-or-column/
- Do :https://leetcode.com/problems/swim-in-rising-water/description/


- template
```
struct DSU {
        vector<int> par;
        vector<int> ranks;

        DSU(int n) {
            par.resize(n);
            ranks.assign(n, 0);
            for (int i = 0; i < n; i++) par[i] = i;
        }
        int find(int x) {
            if (x == par[x]) return x;
            return par[x] = find(par[x]);
        }
        bool unite(int u, int v) {
            u = find(u);
            v = find(v);

            if (u == v) return false ;
            if (ranks[u] < ranks[v]) swap(u, v);
            par[v] = u ;
            if (ranks[u] == ranks[v]) ranks[u]++;
            return true ;
        }
    };
```
