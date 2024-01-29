# Bitonic-Point-program
Given an array arr of n elements that is first strictly increasing and then maybe strictly decreasing, find the maximum element in the array. Note: If the array is increasing then just print the last element will be the maximum value.

class Solution {
    int findMaximum(int[] arr, int n) {
        Arrays.sort(arr);
        return arr[n-1];
    }
}
