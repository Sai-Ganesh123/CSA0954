import java.util.Scanner;  
public class table  
{  
public static void main(String args[])   
{  
Scanner sc = new Scanner(System.in);  
System.out.print("Enter number: ");       
int num=sc.nextInt();
int nom=sc.nextInt();
if(num<0 || nom<0){
    System.out.println("invalid data");
}

for(int i=1; i <= 10; i++)  
{  
 
System.out.println(num+" * "+i+" = "+num*i); 

}
for(int j=1; j <= 10; j++)  
{  
 

System.out.println(nom+" * "+j+" = "+nom*j);
}
 
}  
}
