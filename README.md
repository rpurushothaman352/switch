# switch
this is my first practice program 
import java.util.Scanner;
public class Main
{
	public static void main(String[] args) 
	{
	    int a,b,c;
	    Scanner babu= new Scanner(System.in);
	    System.out.println("Enter your num");
	    a =babu.nextInt();
	    System.out.println("Enter your second number ");
	    b = babu.nextInt();
	     System.out.println("Enter your operator % * - + / ");
	     c=babu.next().charAt(0);
	    switch(c)
	    { 
	        case'+':
	            System.out.println(a +"+" + b+"="+ (a+b));
	            break;
	        case'-':
	             System.out.println(a + "+" + b+"="+ (a-b));
	             break;
	        case'*':
	             System.out.println(a +"+" + b+"="+ (a*b));
	             break;
	        case'%':
	             System.out.println(a +"+" + b+"="+ (a%b));  
	             break;
	        case'/':
	             System.out.println(a +"+" + b+"="+ (a/b));    
	             break;
	       default:
	            System.out.println("you are entering a wrong num");
	    }
		System.out.println("you are completed");
	}
}
