import java.util.Scanner;
class Main{
    public static void main(String[] args){
        int d;
        Scanner sc=new Scanner (System.in);
        System.out.print("Enter the grade of Employee:");
        String a=sc.nextLine();
        System.out.print("Enter the Employee salary:");
        int b=sc.nextInt();
        if(a=="A"){
            d=b/20;
            System.out.println("Bonous:"+d);
            System.out.print("Total salary payed:"+(d+b));
        }
        else{
            d=b/10;
            System.out.println("Bonous:"+d);
            System.out.print("Total salary payed:"+(d+b));
            
        }
    }
}
