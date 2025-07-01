Given: 0-indexed array "nums" of n integers and an integer "k"

Objective: return an array "avgs" of length n where `avgs[i]` is the k-radius average for the subarray centered at index i

Problem-defined terms: 
* k-radius average
	* For a subarray of `nums` **centered** at some index `i` with the **radius** `k` is the average of **all** elements in `nums` between the indices `i - k` and `i + k` (**inclusive**).
* average
	* The **average** of `x` elements is the sum of the `x` elements divided by `x`, using **integer division**.
* integer division
	* The integer division truncates toward zero, which means losing its fractional part.

Example Inputs/Outputs:
Input_1: `[7,4,3,9,1,8,5,2,6], k = 3`
Output_1: `[-1,-1,-1,5,4,4,-1,-1,-1]`

Inquiries:
Why does looking at explanations make me want to barf/scream?