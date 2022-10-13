import java.util.Scanner;
class Main{
    public static void main(String[] args){
        
        Scanner sc=new Scanner(System.in);
        System.out.print("Enter the principle amount:");
        int a=sc.nextInt();
        System.out.print("Enter the no of years:");
        int b=sc.nextInt();
        System.out.print("Customer is senior citizen(y/n):");
        String c=sc.next();
        if(c=="y"){
            int d;
            d=a*b*12/100;
            System.out.print("Interest "+d);
        }
        else{
            int d;
            d=a*b*10/100;
            System.out.print("Interest "+d);
        }
    }
}
