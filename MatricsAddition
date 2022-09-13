public class MatricsAddition {

    public static void main(String[] args) {
        int rows = 2, columns = 2;
        int[][] firstMatrix = { {1,2}, {5, 3} };
        int[][] secondMatrix = { {2, 3}, {4,1} };

        int[][] sum = new int[rows][columns];
        for(int i = 0; i < rows; i++) {
            for (int j = 0; j < columns; j++) {
                sum[i][j] = firstMatrix[i][j] + secondMatrix[i][j];
            }
        }

        System.out.println("Sum of two matrices is: ");
        for(int[] row : sum) {
            for (int column : row) {
                System.out.print(column + "    ");
            }
            System.out.println();
        }
    }
}
