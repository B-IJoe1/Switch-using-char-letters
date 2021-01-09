# Switch-using-char-letters
Using a case operation by utilising switch for specific phrases output


    package lab02;
    import java.util.Scanner;

     public class HelloWorld
     {

	public static void main (String[] args)
    {
      Scanner input = new Scanner(System.in);
      System.out.println("Enter the first letter");
      char letters = input.next().charAt(0);
      
      
	switch (letters)
      {
      
      case 'N': System.out.println("North");break;
      case 'E': System.out.println("East");break;
      case 'S': System.out.println("South");break;
      case 'W': System.out.println("West");break;
      
      default:
    	  System.out.println("Please enter N, E, S, or W");  
		  } 
    	 } 	
      }
