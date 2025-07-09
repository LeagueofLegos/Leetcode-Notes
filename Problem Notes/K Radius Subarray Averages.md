# PROBLEM LINK
https://leetcode.com/explore/interview/card/leetcodes-interview-crash-course-data-structures-and-algorithms/703/arraystrings/4836/

# Given: 
0-indexed array "nums" of n integers and an integer "k"

# Objective: 
return an array "avgs" of length n where `avgs[i]` is the k-radius average for the subarray centered at index i



# Problem-defined terms: 
* k-radius average
	* For a subarray of `nums` **centered** at some index `i` with the **radius** `k` is the average of **all** elements in `nums` between the indices `i - k` and `i + k` (**inclusive**).
* average
	* The **average** of `x` elements is the sum of the `x` elements divided by `x`, using **integer division**.
* integer division
	* The integer division truncates toward zero, which means losing its fractional part.

# Example Inputs/Outputs:
Input_1: `nums = [7,4,3,9,1,8,5,2,6], k = 3`
Output_1: `[-1,-1,-1,5,4,4,-1,-1,-1]`
Input_2:  `nums = [100000], k = 0`
Output_2: `[100000]`
Input_3: `nums = [8], k = 100000`
Output_3 = `[-1]` 
# Things I learned:
  * The requirements for k-radius average
	  * there must be an element that exists for the k long radius within the array
  * What `vector<long long>` is 
	  * bigger int
  * What each argument of `vector averages(n, -1);` do
	  * the -1 initializes each value in the array while n sets how big the array can become length-wise.
  * PEMDAS  is real
	  * code still uses PEMDAS lol

# Completions
## Completion 1:
Solution Peeks: 8 times
Solution Code:
``` 
	f 
```
Solution Diagram: ![[Diagram 7.png|200]]
