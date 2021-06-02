# Project-3
Created by:Bhavya Raj Singh
import java.util.Scanner;
public class Project2 {
    public static void main(String[] args) {
        System.out.println("Enter the total marks of the subject (Eg: 80,100):  ");
        Scanner scan = new Scanner(System.in);
        float total = 0;
        int total_marks = scan.nextInt();
        System.out.println("Enter the marks you got in science:  ");
        float science = scan.nextFloat();
        total = total+ science;
        System.out.println("Enter the marks you got in mathematics: ");
        float mathematics = scan.nextFloat();
        total = total+ mathematics;
        System.out.println("Enter the marks you got in computer science: ");
        float computer  = scan.nextFloat();
        total = total+ computer;
        System.out.println("Enter the marks you got in geography: ");
        float geography = scan.nextFloat();
        total = total+ geography;
        float grandtotal = total * 100 /(total_marks*4);
        System.out.println("Your total percentage = "+grandtotal + "%");
        

    }
    
}
