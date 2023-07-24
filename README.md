# Operators.java
com.java.basics

package com.java.basics;

public class Operators {

	public static void main(String[] args) {
		
		
		//unary Operators
		
		byte b = 127;
		b += 3;
		
		byte c = 60;
		b = (byte) (b + c);
		System.out.println(b);
		
		
		
		int x = 100;
		System.out.println(x++);
		System.out.println(x);
		
		
		x = 200;
		System.out.println(++x);
		System.out.println(x);
		
		
		x = 300;
		System.out.println(x--);
		System.out.println(x);
		
		
		x = 100;
		int y = 10;
		int m = ++x - --y + ++x + x++ - --y + x--;
		System.out.println(m);
		
		
		// SHORTEND
		y = 10;
		y = y * 3;
		y *= 3;
		System.out.println(y);
		
		
		
		//ARITHMETIC 
		y = 100;
		y = 100%6;
		System.out.println(y);
		
		y = 8 +((9/3)*2);
		System.out.println(y);
		
		
		//COMPARISION OPERATORS
		System.out.println(6==7);
		System.out.println(6<7);
		System.out.println(6>7);
		System.out.println(6>=7);
		System.out.println(6<=7);
		
		
		
		//BIT WISE OPERATORS
		//LOGIC GATES TRUTH TABLE
		
		System.out.println(-9);//NOT
		//1. convert to binary
		//2. Apply the logic gates
		//3. Convert the result to decimal again
		
		System.out.println(9 | 78);
		System.out.println(86 & 7);
		System.out.println(9^5);
		System.out.println(68 ^ 68);
		
	}

}
