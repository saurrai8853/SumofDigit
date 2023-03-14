# SumofDigit
Find Sum of Digits in Number
package mypackage;
import java.util.Scanner;
public class SumofDigits {
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("Enter Digits");
		Scanner sc=new Scanner(System.in);
		int n=sc.nextInt();
		int sum=0;
		
	for(int i=1;i<=n;) {
			int temp=n%10;
			sum=sum+temp;
			 n = n/10;
	}
			System.out.println(sum);
			
//	while(n>0) {
//			int temp=n%10;
//			sum=sum+temp;			
//			//int temp=n%10;
//			n=n/10;
//
			}
		//System.out.println(sum);
		
		
	}

	
