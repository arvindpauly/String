# String
import java .util.Scanner;
public class Guvi1 {
public static void main(String[] args) {
	Scanner a=new Scanner(System.in);
	System.out.println("enter the  first string");
	String S1=a.next();
	System.out.println("enter the secong string");
	String s2=a.next();
	int x=S1.length();
	int y=s2.length();
	if(x==y)
	{
		System.out.println("true");
	}
	else
	{
		System.out.println("false");
	}
	}
}
