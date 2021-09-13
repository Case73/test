import java.util.Scanner;

class Main {
  public static void main(String[] args) {

    //GUESS MY NUMBER 
    //THERE ARE NO TESTS FOR THIS PROJECT - YOU MUST TEST YOURSELF
    System.out.println("Think of a number between 1 & 10 (dont tell me - I will guess by asking you a max of four questions");
    System.out.println("Please enter your number");

    Scanner keyboard = new Scanner(System.in);

    String userIn;
    boolean lessThanFive, divisibleByTwo, lessThanThree, lessThanEight, moreThanSix, moreThanNine;

    System.out.println("Is the number less than 5? Y/N");
    userIn = keyboard.nextLine();

   if(userIn == "Y")
   {
     lessThanFive = true; //Leaving you 1 to 4
   }
   else
   {
     lessThanFive = false;
   }

   System.out.println("Does it divide perfectly by 2?");
   userIn = keyboard.nextLine();

   if(userIn == "Y")
   {
     divisibleByTwo = true;
   }
   else
   {
     divisibleByTwo = false;
   }

   System.out.println("Is the number less than 3?");
   if(userIn == "Y")
   {
     lessThanThree = true;
   }

   if(lessThanFive = false)
   {
     System.out.println("Is your number more than 6?");
     if(userIn == "Y")
     {
       moreThanSix = true;
     }
     else
     {
       System.out.println("Is your number more than 9?");
       moreThanNine = true;
     }
   }

   if()

     
  
   }


   


  }
}
