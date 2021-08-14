# Traklab
import java.util.*;

class EmployeeDetails

{
   int emp_id, age;
   String emp_name, emp_department;
   double salary;

   public int getEmp_id()
   {
      return emp_id;
   }

   public void setEmp_id(int emp_id)
   {
      this.emp_id = emp_id;
   }

    public String getName()
    {
       return emp_name;
    }

    public void setName(String emp_name)
    {
       this.emp_name = emp_name;
    }

    public String getDepartment()
    {
      return emp_department;
    }

    public void setDepartment(String
emp_department)
    {
       this.emp_department = emp_department;
    }

    public double getSalary()
    {
    return salary;
    }

    public void setSalary(double Salary)
    {
    this.salary=salary;
    }

     public String toString()

     {
        return " Employee details{ Id = "+ emp_id + "\n Salary = " +salary + "\n Name = " + emp_name +" Age = "+age+"\n Department = " + emp_department ";

     }
}

public class Department
{
  int dept_id;
  String dept_name;

 public int getDept_id()
 {
 return dept_id;
 }

public void getDept_id(int dept_id)
{
 this.dept_id=dept_id;
}

public String getDept_name()
 {
 return dept_name;
 }

public void getDept_name(String dept_name)
{
 this.dept_name=dept_name;
}

}

public class Employee
{
   public static void main(String args[])
   {
      EmployeeDetails emp = new EmployeeDetails();

      Department emp = new Department();

      emp.setDept_id(1000)

      emp.setDept_name("HR");
      
      emp.setEmp_id(63);

      emp.setName("Shivam Shinde");

      emp.setDepartment("HR");

      emp.setSalary(25000);

      System.out.println(toString());

   }

}
// To create database, we have SQL commands

create table Employee(Id number, Name varchar2(100), Age number);

create table Department(I'd number, DeptName varchar2(100);

