import java.util.Scanner;

public class TimeToHMS
{
   public static void main(String[] args)
   {
      Scanner keyboard = new Scanner(System.in);
      System.out.print("enter total seconds: ");
      int totalSeconds = keyboard.nextInt();
      int hours = totalSeconds/3600;
      int minutes =(totalSeconds - hours*3600)/60;
      int seconds = totalSeconds - hours*3600 - minutes*60;
      System.out.println(totalSeconds + " seconds is equivalent to " + hours + " hours, " + minutes + " minutes, "
                         + seconds + " seconds.");
   }
}
