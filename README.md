# Assignments-using-java

1.Stringreverse using Scannerprogram

import java.util.Scanner;
class ReverseStringNumber 
{
	public static void main(String[] args) 
	{
		Scanner sc=new Scanner(System.in);
		System.out.println("Enetr a string");
		String s=sc.nextLine();
		String rev="";
		for (int i=s.length()-1;i>=0;i-- )
		{
			char ch=s.charAt(i);
			rev=rev+ch;
		}
	System.out.println(rev);

	}
}






2.Stringreverse check it is palindrone or not by using Scannerprogram

 import java.util.Scanner;
class ReverseStringNumber 
{
	public static void main(String[] args) 
	{
		Scanner sc=new Scanner(System.in);
		System.out.println("Enetr a string");
		String s=sc.nextLine();
		String rev="";
		for (int i=s.length()-1;i>=0;i-- )
		{
			char ch=s.charAt(i);
			rev=rev+ch;
		}
	if (rev.equalsIgnoreCase(s))
	{
		System.out.println("palindrome");
	}
	else
		{
             		System.out.println(" not palindrome");
	}
	}










 
		
 	





