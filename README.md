package bintodeci;

import java.util.Scanner; 

public class bintodeci 
{ 
    public static void main(String [] args)
    { 
      Scanner keyboard = new Scanner(System.in); 
        
      System.out.println("Enter a binary number: " );
      String binNum1 =keyboard.nextLine(); 
  
      int decinum1 =  Integer.parseInt(binNum1, 2);

      System.out.println("The decimal value of " + binNum1 + " is " + decinum1);
    }
}
