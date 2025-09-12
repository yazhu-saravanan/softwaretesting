# softwaretesting
package testing;
import java.util.Scanner;
public class animal {
	
	public static void main(String[]args)
	{
		Scanner a=new Scanner(System.in);
		System.out.println("Enter your Name");
		String name=a.nextLine();
		System.out.println("Enter your age");
		int age=a.nextInt();
		if(age<=18)
		{
			System.out.println("young citizen");
		}
		else if(age<=45)
		{
			System.out.println("Middle citizen");
		}
		else
		{
			System.out.println("Senior citizen");
		}
	}

}
