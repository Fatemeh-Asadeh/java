# java
//Inheretence Example
class Employee{
float salary=80000.09;
}
class Programmer extends Employee{
int bonus=100000;
public static void main(String args[]){
Programmer p=new Programmer();
System.out.println("Programmer salary is:"+p.salary);
System.out.println("Bonus of Programmer is:"+p.bonus);
}
  }
