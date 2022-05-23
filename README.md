# sum-of-odd-numbers
import java.util.Scanner;

public class sumofprimenumbers {

	public static void main(String[] args) {
		Scanner input = new Scanner(System.in);
		System.out.println("Enter The starting Number : ");
		int SN = input.nextInt();
		System.out.println("Enter The Ending Number : ");
		int EN = input.nextInt();
		int sum =0;
		int N = SN;
		while(N%2==1) {
			if(N<=EN)
				sum+=N;
			N++;
		}
		input.close();
		System.out.println("Sum of the Odd Numbers : "+ sum);
	}

}
