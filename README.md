# Demoo
package Demo;

import java.util.Scanner;

public class Practice 
{
	public void getdata(int number)
	{
		int sum=1;
		for(int i=number;i>=1;i--)
		{
			sum=sum*i;
		}
		System.out.println(sum);
	}
	public static void main(String[] args) 
	{
		Practice ob = new Practice();
		Scanner sc = new Scanner(System.in);
		System.out.println("Please enter any number");
		int input=sc.nextInt();
		ob.getdata(input);
		
		sc.close();
	}
}
