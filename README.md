import java.util.Scanner;
public class Main
{
	public static void main(String[] args) {
		int a,b;
		System.out.println("enter any two numbers");
		Scanner sc = new Scanner(System.in);
		a = sc.nextInt();
		b = sc.nextInt();
		System.out.println("before swapping"+a+" "+b);
		a=a+b;
		b=a-b;
		a=a-b;
		System.out.println("after swapping"+a+" "+b);
	}
}
--->
