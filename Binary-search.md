# KOKO-EATING-BANANA
- we wnat `minspeed` low : 1 is right {as we are' sayign if h > n so she can be slower so min goes down}  , high = max(nums) {as from any piles he can at max eat all and in next hr koko move to next pile!} 
- dO: https://leetcode.com/problems/koko-eating-bananas/description/?envType=problem-list-v2&envId=rr2ss0g5


# BINARY-SEARCH
- look for all variation in microsoft repo , `staircase ques`, `without any row-wise sorting` , `flattened array variations` all !
- Do :https://leetcode.com/problems/search-a-2d-matrix/?envType=problem-list-v2&envId=rr2ss0g5

# FIND MIN IN ROTATED-SORTED ARRAY 
- Compare `nums[min] with nums[high]` to know the part is rotated or not, or where the minima lies
- Do:https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/?envType=problem-list-v2&envId=rr2ss0g5

# Rotate array :
- `gcd is determined that within n elements when with the cycle of k rotation ends` and just move elements for all si = [0,cycles)
- `REVERSE LOGIC IS EASY -> REVERSE 3 TIME SIMPLE , GET LASTk, REVERSE OR RESTORE THE ORDER OF ELEMENTS`
- https://leetcode.com/problems/rotate-array/submissions/1913564864/?utm_source=copilot.com
  
# TASK-SCHEDULAR
- `this is not the job scheduling !! don't conufue simple GAP MANAGEMENT which is mathematically solved !`
- It simply look as maxf and keep in mind to greedily to take maxf as seq , whereas if n is not to big then the elements can be jumbled so that we'are left with unique set of elements for the last gp . , for small n it -> similar tasks are not a problem and for large n , the maxf will be able to make enough gaps for the rest of elements
- Do : https://leetcode.com/problems/task-scheduler/submissions/1910182063/?envType=problem-list-v2&envId=rr2ss0g5

# GAS STATION
- Not binary search just important ones :
- Keep total_surplus >= 0 gurantees that the minima' can be balanced and start_idx righ after the minima is the best choice as `A`->`B` if at B we go curr < 0 so b/w A TO B-1 >= 0 and couldn't pass so any point b/w A & B couldn't so we fresh start just after the mini idx i, to get the right starting pts , if the total_surplus can be balanced !
- Do:https://leetcode.com/problems/gas-station/?envType=problem-list-v2&envId=rr2ss0g5 

# Minimise the subarray sum maxima's
- its known to you O(N * LOG(N)) : https://leetcode.com/problems/split-array-largest-sum/submissions/1914765315/


# max_prod_subarray - not the binary search quers
- consider `0`->seg- separators , and for a seg of odd neg nos , we can either take prefix {excluding the last neg no.} or suffix {excluding the first neg no.} -> prefix,suff prod is enough to handle .
- Do :https://leetcode.com/problems/maximum-product-subarray/submissions/1915737766/?envType=problem-list-v2&envId=rr2ss0g5
