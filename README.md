package com.techweb.interestcompound;

import java.util.Scanner;

public class InterestCompound {

    public static void main(String[] args) {
        
        Scanner input = new Scanner (System.in);
        
        double A,P,I,N;
        
        System.out.println("Enter the principal amount");
         P = input.nextDouble();
         
         System.out.println("Enter the annual interest rate");
          I = input.nextDouble();
          
            System.out.println("Enter the period");
             N = input.nextDouble();
             A = P* Math.pow (1+I,N);
             
             System.out.println("The final amount is"+A);
             
    }
   
}
