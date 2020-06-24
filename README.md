
import java.util.Scanner;
class Even_Odd{
    public static void main(String args[])
    {
      int value;
        System.out.println("Enter an Integer value:");
        
   Scanner input = new Scanner(System.in);
        value = input.nextInt();
        if (value % 2 == 0)
          System.out.println("Your entered value is even !")
        else
          System.out.println("Your entered value is Odd !")
          }
}
