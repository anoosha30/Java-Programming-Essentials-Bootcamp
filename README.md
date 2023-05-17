# Java-Programming-Essentials-Bootcamp
Assignment - Java Programming Essentials Bootcamp

import java.io.*;

public class myclass 
{
public static void main(String[] args) {
int var M=9;
if ((M % 3 == 0) && (M % 5 == 0))
System.out.println("Good Number"); 
else if ((M % 3 == 0) && (!(M % 5 == 0)))
System.out.println("Bad Number");
else if ((!(M % 3 == 0)) && (M % 5 == 0))
System.out.println("Poor Number");
else
System.out.println(" -1 ");
}
}
