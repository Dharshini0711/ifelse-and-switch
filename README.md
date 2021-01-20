# ifelse
import java.util.Scanner;
public class Decisionmaking {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int input;
		System.out.println("Enter yor age : ");
		Scanner s = new Scanner (System.in);
		input = s.nextInt();
		if(input >18)
			System.out.println("Eligible to vote ");
		else
			System.out.println(" Not eligible to vote ");
			
			}
}

#switch
import java.util.Scanner;
public class Decisionmaking {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		int choice;
		System.out.println("pick one colour : 1.blue\t2. yellow\t3. green\t");
		Scanner s = new Scanner(System.in);
		choice= s.nextInt();
		switch(choice)
		{
			case 1: System.out.println("yellow");
			       break;
			case 2: System.out.println("blue");
			       break;
			case 3 : System.out.println("green");
			       break;
			default : System.out.println("Invalid");
			
	}
		
			}

}
