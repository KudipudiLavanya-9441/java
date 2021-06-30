 import java.util.Scanner;
public class Harshadnumber {

	public static void main(String[] args){
          Scanner in=new Scanner(System.in);
          System.out.println("Enter the number: ");
          int num=in.nextInt();
          int rem=0,sum=0;
          int temp;
          temp=num;
          
          while(num>0) {
        	   rem=num%10;
        	   sum=sum+rem;
        	   num=num/10;
          }
          if(temp%sum==0) {
        	   System.out.println(temp + " is a harshad number");
          }
          else 
          {
        	  System.out.println(temp +" is not a harshad number");
          }
          in.close();
        		  
	}

}
output:
Enter the number:
18
18 is a harshadnumber
