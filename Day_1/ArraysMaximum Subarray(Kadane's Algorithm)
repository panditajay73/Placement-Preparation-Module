class Solution {
    public int maxSubArray(int[] nums) {
        int ans=nums[0],i,sum=0;
        for(i=0;i<nums.length;i++){
            sum+=nums[i];
            if(ans<sum)ans=sum;
            if(sum<0)sum=0;
        }
        return ans;
    }
}
