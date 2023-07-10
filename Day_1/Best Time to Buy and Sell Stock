class Solution {
    public int maxProfit(int[] prices) {
        int maxProfit = 0;
        int minimum = prices[0];

        for(int i=0; i<prices.length; i++){
             minimum=Math.min(minimum,prices[i]);
            int profit = prices[i] - minimum;
            maxProfit = Math.max(maxProfit,profit);
        }
        return maxProfit;
    }
}
