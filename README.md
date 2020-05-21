# 1.java

import java.util.Scanner;
public class Calculate 
{
    public static void main(String[] args) 
    {
        int a, b, opt;
        double div,add,sub,mul;
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter first number:");
        a = sc.nextInt();
        System.out.print("Enter second number:");
        b = sc.nextInt();
        while(true)
        {
            System.out.println("Enter 1 for addition");
            System.out.println("Enter 2 for subtraction");
            System.out.println("Enter 3 for multiplication");
            System.out.println("Enter 4 for division");
            System.out.println("Enter 5 to Exit");
            opt = sc.nextInt();
            switch(opt)
            {
                case 1:
                add = (double)a + b;
                System.out.println("Result:"+add);
                break;
 
                case 2:
                sub = (double)a - b;
                System.out.println("Result:"+sub);
                break;
 
                case 3:
                mul = (double)a * b;
                System.out.println("Result:"+mul);
                break;
 
                case 4:
                div = (double)a / b;
                System.out.println("Result:"+div);
                break;    
 
                case 5:
                System.exit(0);
            }
		}
        }
    }
