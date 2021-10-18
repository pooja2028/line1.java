# line1.java
import java.util.Scanner;

public class linecomparisonuc2{
	public static void main(String[] args) {

		System.out.println("Welcome to Line Comparison Computation Program ");

		Scanner sc = new Scanner(System.in);

		System.out.print("Enter the value of starting point according to x-axis  of frist line: ");
		double x1 = sc.nextDouble();

		System.out.print("Enter the value of starting point according to y-axis  of frist line: ");
		double y1 = sc.nextDouble();

		System.out.print("Enter the value of end point according to x-axis  of frist line: ");
		double x2 = sc.nextDouble();


		System.out.print("Enter the value of end point according to x-axis  of frist line: ");
		double y2 = sc.nextDouble();


		double length_of_line = Math.sqrt(Math.pow((x2 - x1),2) + Math.pow((y2 - y1 ),2));


		System.out.println(length_of_line); 

		System.out.print("Enter the value of starting point according to x-axis  of Second line: ");
		double x3 = sc.nextDouble();

		System.out.print("Enter the value of starting point according to y-axis  of Second line: ");
		double y3 = sc.nextDouble();


		System.out.print("Enter the value of end point according to x-axis  of Second line: ");
		double x4 = sc.nextDouble();


		System.out.print("Enter the value of end point according to x-axis  of Second line: ");
		double y4 = sc.nextDouble();

		double Sec_length_of_line = Math.sqrt(Math.pow((x3 - x4),2) + Math.pow((y3 - y4 ),2));


		Double lineOne = length_of_line;
		Double lineTwo = Sec_length_of_line;

		System.out.println("Equality of two line: " + lineOne.equals(lineTwo));
	}

}
