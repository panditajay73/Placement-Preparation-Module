class Solution {
    public void nextPermutation(int[] nums) {
        int lastIndex = nums.length-2;
        int swapIndex = nums.length-1;
        
        while(lastIndex>=0 && nums[lastIndex]>=nums[lastIndex+1]){
            lastIndex--;
        }
       if(lastIndex>=0){
          while( nums[swapIndex]<=nums[lastIndex]){
            swapIndex--;
        } 
           swap(nums,lastIndex,swapIndex);
       }
        reverse(nums, lastIndex+1);
    }
     public void swap(int[] nums, int i, int j){
        
        int temp = nums[i];
        nums[i] = nums[j];
        nums[j] = temp;
        
    }
     public void reverse(int[] nums, int i){
        
        int j = nums.length-1;
         while(i<j){
             swap(nums,i,j);
             i++;
             j--;
         }
        
    }
}
