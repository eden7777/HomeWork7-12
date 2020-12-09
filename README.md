# HomeWork7-12
package com.company;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

      /*    && before ||
            (a || b) && c
            short-circuit
            Targil:
1. input two int numbers from the user, check if they are both zeros, if so print "both zeroes" otherwise print "not both zeroes"
2. input a,b,c (int)
    check if all numbers are different from each-other, if so print "diff" otherwise print "similar"
3. input x,y,z (float)
    check and print how many of them are positive
    for example:
    for input of -1, 4 ,2.98 your program should print 2 positive numbers
    for input of -4.5, 0, -12 your program should print 0 positive numbers
4. input a, b, c.
   print the biggest
   hint: if a is bigger than b and bigger than c THEN a biggest
       else if b is bigger than c THEN b biggest
       else THEN c biggest


       */
        // question 1

        Scanner s = new Scanner(System.in);
      /*  System.out.println("please enter two numbers:");
        int a = s.nextInt();
        int b = s.nextInt();
        if ( a==0&&b==0 ) {
            System.out.println("both zeroes");
        }
        else {
            System.out.println("not both zeroes");
        }
        */

        // question 2

    /*    System.out.println("please enter three numbers:");
        int a = s.nextInt();
        int b = s.nextInt();
        int c = s.nextInt();

        if (a!=b||b!=c) {
            System.out.println("diff");
        }
        else {
            System.out.println("similar");
        }
    */  // question 3 
     /*   System.out.println("please enter three numbers:");
        float x = s.nextFloat();
        float y = s.nextFloat();
        float z = s.nextFloat();
        int count = 0;
        if (x>0) {
            count++; // count = count + 1
        }
        if (y>0) {
            count++;
        }
        if (z>0) {
            count++;
        }
        System.out.println(count + " positive numbers");
    */  // question 4 
        int a = s.nextInt();
        int b = s.nextInt();
        int c = s.nextInt();
        if (a>b&&a>c){
            System.out.println(" a biggest");
        }
        else if (b>c){
            System.out.println("b biggest");
        }
        else {
            System.out.println("c biggest");
        }

    }

}
