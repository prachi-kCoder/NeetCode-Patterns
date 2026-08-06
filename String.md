- YOUR MISTAKE {handling getline stream , strlen(chArr) where chArr -> chArr}
```cpp
#include <bits/stdc++.h>
using namespace std;
int main() {
	// your code goes here
	char* s = "Prachi char_array" ;
	string str = "Prachi string" ;
	
	int i = 0 ;
	while (s[i] != '\0') {
	    cout << s[i]  ;
	    i++ ;
	}
	cout<< endl ;
	
	cout << "SIZE OF CHAR ARRY :" << strlen(s) << endl ;
	cout << "SIZE OF str :" << str.size() << endl ;
	
	string input = "" ;
	getline(cin , input) ; // with spaces !
	cout << input << endl ;
	
	return  0 ;
}
```
# Subarray with K different element / integers 
-> `EXACTLY K = ATMOST K - ATMOST K-1` => simple intution!
- using sliding window calculation for subarray with elements atmost k ending at any index i
-> link :https://leetcode.com/problems/subarrays-with-k-different-integers/


# REVERSE - WORDS IN A STRING
- DO :https://leetcode.com/problems/reverse-words-in-a-string/

# Encode and DEcode Strings
- DON'T JUST stick is delimiter use :`{length , '#' , string_content}` use this compeletecan be any ASCII character before
- Do :https://www.geeksforgeeks.org/problems/encode-and-decode-strings/1
- TC = O(M) M-> length of encoded strings M =  N*L {no of string}* avg len


# postfix exp eval 
- do it without stack : O(1) extra space : do: https://leetcode.com/problems/evaluate-reverse-polish-notation/?envType=problem-list-v2&envId=rr2ss0g5
-----------------------------------------------------------------------------------
- `in this substring needed so matched updateed from both end as fixed len window with match cnt was need`
# SLIDING WINDOW :
-  `MATCHES` COUNTER {Do corect this from both ends , LEFT : if targetfreq reached or lowered , RIGHT: if targetfreq reached or by passed } make matches updates carefully
- Do :https://leetcode.com/problems/permutation-in-string/submissions/1907751558/?envType=problem-list-v2&envId=rr2ss0g5

# MIN-WINDOW-SUBSTRING:
- `here target is atleast to be maintained as soon as a found reached we left compress till we don't lose the cnt of any essential target char`
- do: https://leetcode.com/problems/largest-rectangle-in-histogram/submissions/1907860027/?envType=problem-list-v2&envId=rr2ss0g5
-------------------------------------------------------------------------------------------------------

