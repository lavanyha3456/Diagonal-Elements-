# Diagonal-Elements-
public class DiagonalElements {

public static void main(String[] args) {

int[][] squareMatrix = {

{1, 2, 3},

{4, 5, 6},

{7, 8, 9}

};

System.out.println("Diagonal elements:");

for (int i = 0; i < squareMatrix.length; i++) {

System.out.print(squareMatrix[i][i] + " ");

}

System.out.println();

}

}

OUTPUT:

Diagonal elements:

1 5 9
