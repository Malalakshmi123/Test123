# Test123
1. WAP to reverse a String.
Input: “iNeuron”
Output: “norueNi”

Code: 


package com.firstproject;

import java.util.Scanner;
class Reverse
{
	public String reverseString(String str)
	{
		String temp="";
		for(int i=str.length()-1;i>=0;i--)
		{
			temp=temp+str.charAt(i);
		}
		return temp;
	}
}
public class Helloworld {
	public static void main(String[] args) {
		Scanner scan =new Scanner(System.in);
		System.out.println("Enter the string to Reverse");
		String str= scan.nextLine();
		Reverse s=new Reverse();
		System.out.println(s.reverseString(str));
	
		}
		
	}
