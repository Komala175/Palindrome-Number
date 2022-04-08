# Palindrome-Number


  public class Palidrome{
	public static void main(String[] args) {
		Scanner sc=new Scanner(System.in);
		System.out.println("Enter the number:");
		int n=sc.nextInt();
		int sum=0,r;
		int temp;
		temp=n;
		while(n>0) {
			r=n%10;
			sum=(sum*10)+r;
			n=n/10;
		}
       if(sum==temp) {
	           System.out.println("Yes");
         }
       else {
	         System.out.println("No");
         }
	}
}
