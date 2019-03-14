# Assignment-3
Class: Programming Fundamentals (COMP112) - Assignment #3 - Scanner Class Methods in Java

package asig3;

import java.util.Scanner;

public class Main {

public static void main(String[] args) {
	
 // TODO Auto-generated method stub
	
  Scanner scan = new Scanner (System.in);
		
  System.out.println("Enter Name");
  
  System.out.println(scan.next());
		
  Scanner scan2 = new Scanner(System.in);
	
  System.out.println("Enter name and last name");
	
  String nameLast = scan2.nextLine();
	
  System.out.println(nameLast);
		
  Scanner scan3 = new Scanner (System.in);

  System.out.println("Enter age");
	
  int age = scan3.nextInt();
	
  System.out.println(age);
	
  Scanner scan4 = new Scanner (System.in);
	
  System.out.println("Enter decimal number");

  double decimalnumber = scan4.nextDouble();
	
  System.out.println(decimalnumber);
		
  Scanner scan5 = new Scanner (System.in);
	
  System.out.println("Enter number");
	
  long number = scan5.nextLong();
	
  System.out.println(number);
		
  Scanner scan6= new Scanner (System.in);
	
  System.out.println("Enter you name");
	
  String yourname = scan6.nextLine();
	
  System.out.println(yourname.length());	
		
  Scanner scan7= new Scanner (System.in);
	
  System.out.println("Enter your name in lowercase");
	
  String yournamelowercase = scan7.nextLine();
	
  System.out.println(yournamelowercase.toUpperCase());		
		
  Scanner scan8= new Scanner (System.in);
	
  System.out.println("Enter your name");
	
  String input3 = scan8.nextLine();
	
  System.out.println(input3.charAt(1));		
		
  }

}
