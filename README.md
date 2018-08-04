# User_Package
package mypack;   //a user defined package
public class example   //a class in user defined package
{
 public void disp()
{
 System.out.println("Somya Raj Sinha");
}
}

package mypack;
public class example1    //another class in the same user defined package
{
 public void display()
{
 System.out.println("I Am a Beginner");
}
}

import mypack.*;   // importing all the class of user defined package by using "*"symbol
class Test21   // a class extending user defined package 
{
 public static void main(String args[])
{
 example obj=new example();   //creating object of the example class
 example1 obj1=new example1();    //creating object of the example1 class
 obj.disp();
 obj1.display();
}
}
