class Solution {
    public void setZeroes(int[][] matrix) {

        //1st method
       /* int m = matrix.length;
        int n= matrix[0].length;
        int row[]=new int[m];
        int col[]= new int[n];

        for(int i=0;i<m;i++){
            for(int j=0;j<n;j++){
                if(matrix[i][j]==0){
                    row[i]=1;
                    col[j]=1;
                }
            }
        }
        for(int i=0;i<m;i++){
            for(int j=0;j<n;j++){
                if(row[i]==1 || col[j]==1){
                    matrix[i][j]=0;
                }
            }
        }
        return;*/

        //2nd method
          int val=1, rows=matrix.length, cols=matrix[0].length;
        for(int i=0;i<rows;i++){
            if(matrix[i][0]==0)
            val=0;
            for(int j=1;j<cols;j++)
                if(matrix[i][j]==0)
                matrix[i][0]=matrix[0][j]=0;
            
        }
        for(int i=rows-1;i>=0;i--){
            for(int j=cols-1;j>=1;j--)
                if(matrix[i][0]== 0 || matrix[0][j]==0)
                matrix[i][j]=0;
                if(val==0)
                matrix[i][0]=0;
            
        
    }
    }
}
