# Practical6
package part1;
import java.util.Scanner;
public class Practical6 {
	
	
	    public static void main(String[] args) {
	        Scanner sc=new Scanner(System.in);

	        System.out.println("Enter no. of testcase : ");
	        int t=sc.nextInt();
	        for(int i=0;i<t;i++)
	        {

	            System.out.println("Enter size array : ");
	            int arr1size=sc.nextInt();
	            String arr1[]=new String[arr1size];
	            System.out.println("Enter String array : ");
	            for(int j=0;j<arr1size;j++)
	            {
	                arr1[j]=sc.next();
	            }

	            System.out.println("Enter String you want to remove: ");
	            String s=sc.next();
	            int count=0;
	            String arr2[]=new String[arr1size];
	            for(int j=0;j<arr1.length;j++) {
	                if (!arr1[j].contains(s)){
	                    arr2[count]=arr1[j];
	                    count++;
	                }
	            }


	            for(int l=0;l< count;l++)
	            {
	                System.out.print(arr2[l]+' ');
	            }
	            System.out.println(" ");

	        }

	    	//Created by Manav_21CE063.
	    }
}

