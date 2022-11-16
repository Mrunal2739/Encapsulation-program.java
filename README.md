# Encapsulation-program.java

public class Rectangle {

   private int length; 
   
   private int breadth; 

Rectangle(int length, int breadth) {

  this.length = length; 
  
  this.breadth = breadth; 
  
} 

public int getLength()

{ 

return length; 

} 

public int getBreadth()

{ 

return breadth; 

} 

public void setLength(int length)

{ 

this.length = length; 

} 

public void setBreadth(int breadth)

{ 

this.breadth = breadth; 

} 

}

public class RectangleTest 

{ 

public static void main(String[] args)

{ 

   Rectangle rt = new Rectangle(20,30); 


  int lth = rt.getLength(); 
  
  int bth = rt.getBreadth(); 


  int Area = lth * bth; 
  
  System.out.println("Area: " +Area); 


  rt.setLength(50); 
  
  rt.setBreadth(60); 


  int ln = rt.getLength(); 
  
  int br = rt.getBreadth(); 
  
  int newArea = ln * br; 
  
System.out.println("New area: " +newArea); 

} 

}
