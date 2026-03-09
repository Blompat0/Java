# package ec;
import java.util.Scanner;
public class clas {
	static void fibo(int f) {
		int i,n1,n2,newnum;
		n1=0;  n2=1; System.out.print(n1+" "+n2);
		for(i=1;i<=f-2;i++) {
		newnum=n1+n2;
		System.out.print(newnum+" ");
		n1=n2;
		n2=newnum;
		}			
	}
	
	static void reading()
	{
		Scanner read=new Scanner(System.in);
		System.out.println("Enter the how see fibonacci numbers: "); 
		int number=read.nextInt();
		fibo(number);
	}
	
	public static void main(String[] args) {
	reading();	
}
	}
