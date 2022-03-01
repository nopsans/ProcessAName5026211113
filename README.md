import java.util.Scanner;

public class ProcessAName5026211113 {

	public static void main(String[] args) {

		Scanner console = new Scanner(System.in);
		System.out.print("Input your name: ");
		String name = console.nextLine();
		int space = name.indexOf(' ');
		String firstname = name.substring(0,1);
		space++;
		String lastname = name.substring(space);
		System.out.println("Your name is: "+lastname+", "+firstname+".");
	}
} 
