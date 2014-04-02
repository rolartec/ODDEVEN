ODDEVEN
=======

ODD-EVEN NUMBER


// By Reina Olarte
// Midterm

		
public class OddEven {

int A= 0;
int W = 0;
int L = 0;


public void displaymessage(String number){

	// Typing the Variables
	int computerNumber;

    String CEven;

    computerNumber = 0 + (int)(Math.random() *10);

	if (computerNumber % 2 == 0)
{
		CEven = "EVEN";
}
else
{
		CEven = "ODD";
}

		if (number.toUpperCase().startsWith(CEven) )
{
			System.out.println("Your number is right:");


			System.out.printf("Your numberis %s  and computer number is %d", number, computerNumber);

A ++;

W ++;
}
		else
{
			System.out.println("Your number is wrong");


			System.out.printf("Your number is %s  and computer number is %d ", number, computerNumber);


				A ++;
				
				
				L ++;
}

}
			public void results()
{
		if(W > L)
{
				System.out.println("You Win");
}
			else if( W < L)
{
				System.out.println("The Computer win");
}
				else if(W == L)
{
					System.out.println(" Tied ");
}

} // END METHOD
}  // eND cLASS
