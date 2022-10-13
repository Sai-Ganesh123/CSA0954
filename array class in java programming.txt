import java.util.*;
public class array
{
	public static void main(String[] args) 
	{
	    int x,i,j,m,desc,max;
	    Scanner sc=new Scanner(System.in);
		System.out.print("Enter no. of elements: ");
		x=sc.nextInt();
		int a[]=new int[x];
		System.out.println("Enter elements: ");
		for(i=0;i<x;i++)
		{
		    a[i]=sc.nextInt();
		}
		System.out.print("enter nth max number= ");
		if(!sc.hasNextInt())
		{
			System.out.println("Invalid data");
		      return;
		}
		m=sc.nextInt();
		if(m>x || m==0||m<=0)
		{
		    System.out.println("Invalid data");
		    return;
		}
		for(i=0;i<x;i++)
		{
		    for(j=i+1;j<x;++j)
		    {
		        if(a[i]<a[j])
		        {
		            desc=a[i];
		            a[i]=a[j];
		            a[j]=desc;
		        }
		    }
		}
		max=a[m-1];
		System.out.println(m+" Maximum number is: "+max);
	}
}
