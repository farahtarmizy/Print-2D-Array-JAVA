# Print-2D-Array-JAVA
this is how to print a 2D integer array somehow... though i don't understand why j<matrix[i].length yet

      int[][] matrix = {{6,9},{2,5},{4,6}};
        
        
        matrix[1][1] = 4;
        matrix[2][0] = 3;
        matrix[2][1] = 7;
        
        for(int i=0; i<matrix.length; i++) {       
            for(int j=0; j<matrix[i].length; j++) { 
                System.out.print(matrix[i][j] + "  ");
            }
            System.out.println(); 
        }
