# Constructor
class constructor
{
	String studentName;
    int passOutYear;
    public constructor(String name,int year)
    {
    	studentName=name;
        passOutYear=year;
  	}
}
class main {

  public static void main(String[] args) 
  {
  	constructor c = new constructor("Sri Charan",2021);
    System.out.println("Student name is "+c.studentName);
    System.out.println("Completed his graduation in "+c.passOutYear);
  }
}
