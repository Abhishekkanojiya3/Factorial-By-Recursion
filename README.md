# Factorial-By-Recursion

// Online Java Compiler
// Use this editor to write, compile and run your Java code online

import java.util.Scanner;

class FactorialCalculator {


             public static void main(String[]args){

             
               Scanner scanner = new Scanner(System.in);

               
               System.out.println("enter a Number");

               
               int num = scanner.nextInt();

               
               int factorial = fact(num);

               
               System.out.println("Factorial of the number is " + factorial);

               
             }
         static int fact (int n) {

         
             int output;

             
             if(n==0) {

             
                 return 1;
                 
             }
             
             output = fact(n-1)*n;

             
             return output;
         }
         
}
