# Remove Duplicates from Sorted Array II

LeetCode Q # 80.

Given an integer array nums sorted in non-decreasing order, remove some duplicates in-place such that each unique element appears at most twice. The relative order of the elements should be kept the same.

Since it is impossible to change the length of the array in some languages, you must instead have the result be placed in the first part of the array nums. More formally, if there are k elements after removing the duplicates, then the first k elements of nums should hold the final result. It does not matter what you leave beyond the first k elements.

Return k after placing the final result in the first k slots of nums.

> Do not allocate extra space for another array. You must do this by modifying the input array in-place with O(1) extra memory.

Custom Judge:

> The judge will test your solution with the following code:
>
> int[] nums = [...]; // Input array</br>
> int[] expectedNums = [...]; // The expected answer with correct length
>
> int k = removeDuplicates(nums); // Calls your implementation
>
> assert k == expectedNums.length;</br>
> for (int i = 0; i < k; i++) {</br>
> &nbsp;&nbsp;&nbsp;&nbsp;assert nums[i] == expectedNums[i];</br>
> }</br>
> If all assertions pass, then your solution will be accepted.

Example 1:

> Input: nums = [1,1,1,2,2,3]</br>
> Output: 5, nums = [1,1,2,2,3,_]</br>
> Explanation: Your function should return k = 5, with the first five elements of nums being 1, 1, 2, 2 and 3 respectively.</br>
> It does not matter what you leave beyond the returned k (hence they are underscores).

Example 2:

> Input: nums = [0,0,1,1,1,1,2,3,3]</br>
> Output: 7, nums = [0,0,1,1,2,3,3,_,_]</br>
> Explanation: Your function should return k = 7, with the first seven elements of nums being 0, 0, 1, 1, 2, 3 and 3 respectively.</br>
> It does not matter what you leave beyond the returned k (hence they are underscores).

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Remove-Duplicates-from-Sorted-Array-II-LeetCode/assets/171427226/2c5e2009-b850-4643-ab11-92f9e6b274f7)

  Time complexity: O(n).</br>Space complexity: O(1).
</div>
