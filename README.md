package com.company;
import java.util.*;

public class Main
{
    public static void main(String[] args)
    {
       Scanner in =new Scanner (System.in);
       System.out.print("Enter any integers from 1 to 5 ");
       int number=in.nextInt();
       switch(number)
       {
           case 1:
               System.out.println("One");
               break;
           case 2:
               System.out.println("Two");
               break;
           case 3:
               System.out.println("Three");
               break;
           case 4:
               System.out.println("Four");
               break;
           case 5:
               System.out.println("Five");
               break;
       }
    }
}
