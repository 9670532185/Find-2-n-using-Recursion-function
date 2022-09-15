# Find-2-n-using-Recursion-function
import java.util.Scanner;
public class Find2kipowern {
    public static int power(int n,int x)
    {
        
        if(x==0)
        return 1;
int ans=power(n,x-1);
int res=n*ans;
return res;

    }
    public static void main(String[] args)
    {
  int n,x;
Scanner obj=new Scanner(System.in);
n=obj.nextInt();
x=obj.nextInt();
int pr=power(n,x);
System.out.println(pr);

    }
    
}
