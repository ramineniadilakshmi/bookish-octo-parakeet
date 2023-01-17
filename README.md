# bookish-octo-parakeet
import java.lang.*;

import java.util.Scanner;





class Employee{

  float salary,hr,x;



  void getInfo(){

    Scanner sc=new Scanner(System.in);

    salary=sc.nextFloat();

    hr= sc.nextFloat();

  }



   

  void AddSal(){

    if (salary<500){

      salary+=10;

    }

  }

  void AddWork(){

    if (hr>6){

      salary+=5;

    }

  }

}

public class EmpInfo {

  public static void main(String[] args) {

    Employee e1=new Employee();

    e1.getInfo();

    e1.AddSal();

    e1.AddWork();

    System.out.println(e1.salary);

  }

}
