# Java-
Java program to print diamond

package diamond;

import java.util.Scanner;
public class Diamond {

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println(" Rows : ");
        int n = sc.nextInt();
        int i , j;
        for(i=0;i<=n;i++)
        {
            for(j=1;j<=n-i;j++)
            {
                System.out.print(" ");
            }
            for(j=1;j<=2*i-1;j++)
            {
                System.out.print("*");
            }
             System.out.println();
        }
        for(i=n-1;i>=0;i--)
        {
            for(j=1;j<=n-i;j++)
            {
                System.out.print(" ");
            }
            for(j=1;j<=2*i-1;j++)
            {
                System.out.print("*");
            }
             System.out.println();
        }
    }
    
}
