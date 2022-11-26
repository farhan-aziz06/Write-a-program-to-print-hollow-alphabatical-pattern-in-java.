# Write-a-program-to-print-hollow-alphabatical-pattern-in-java.
Write a program to print hollow alphabatical pattern in java.


        import java.util.Scanner;

        public class Main {
            public static void main(String[] args) {
                Scanner console = new Scanner(System.in);
                System.out.println("Enter Number of Rows:");
                int row = console.nextInt();
                for (int i =1; i<= row; i++) {
                    for (int j= 1; j<=row/2;j++){
                        if(i==1||j==1||i==row/2||j==row/2){
                            System.out.print("*");
                        }
                        else
                            System.out.print(" ");
                    }
                    System.out.println();
                }
            }
        }



              Enter Number of Rows:
              6
                    ***
                    * *
                    ***
                    * *
                    * *
                    * *
