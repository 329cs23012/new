import java.util.Scanner;
public class Posneg {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the Number");
        int num=sc.nextInt();
        if(num < 0){
            System.out.println("Number Negative");
        }
        else{
            System.out.println(" Number positive");
        }
    }
}
