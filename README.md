import java.util.*;

 class Main {

    public static void main(String[] args) {
        Scanner scn = new Scanner(System.in);
        int n = scn.nextInt(); 
       
       int row = 1;
       int nsp = 4;
       int nst = 1;
      // work
      while(row <= n){
          int csp = 1;
         while(csp <= nsp){
           
           System.out.print(" ");
           csp++;

         }

            int  cst = 1;
         while(cst <= nst){
         cst++;
          System.out.print("*");
          
         }
         System.out.println(" ");
         row++;
         nsp--;
         nst++;

      }
        

    }
}





// c sharp solution

// Include namespace system
using System;
using System.IO;

public class Main
{
    public static void Main(String[] args)
    {
        var scn =  "Inputs";
        var n = Convert.ToInt64(Console.ReadLine());
        var row = 1;
        var nsp = 4;
        var nst = 1;
        //  work
        while (row <= n)
        {
            var csp = 1;
            while (csp <= nsp)
            {
                Console.Write(" ");
                csp++;
            }
            var cst = 1;
            while (cst <= nst)
            {
                cst++;
                Console.Write("*");
            }
            Console.WriteLine(" ");
            row++;
            nsp--;
            nst++;
        }
    }
}
