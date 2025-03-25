# calculator1
simple calculation
package beginning;
import java.util.Scanner;
public class calci 
{
	public static void main(String a[])
	{
		Scanner in= new Scanner(System.in);
		System.out.println("enter the value of x :");
		float x=in.nextFloat();
		System.out.println("Enter the value of y :");
		float y =in.nextFloat();
		System.out.println("value of x is"+x+"\n value of y is "+y);
		System.out.println("enter the desired option for an operation \n1.addition \n2.subtraction \n 3.multiplication \n4.division \n 5.remainder");
		int option = in.nextInt();
		switch(option)
		{
		case 1:
			System.out.println("x+y= :"+x+y );
			break;
		case 2:
			System.out.println("x-y="+ (x-y));
			break;
		case 3:
			System.out.println("x*y= "+x*y);
			break;
		case 4:
			System.out.println("x / y = "+ x/y);
			break;
		case 5:
			System.out.println("remainder of x,y ="+x%y);
			break;
		default:
			System.out.println("only 1 to 5 inputs are allowed");
			break;
		
		}
	}
}
