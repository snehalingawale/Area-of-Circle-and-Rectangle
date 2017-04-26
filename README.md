# Area-of-Circle-and-Rectangle
//Calculate area


package com.inportia;

public class Circle {
	int radius;
	float pi=(float) 3.14;
	float c;
    Circle(int x){
    	radius=x;
    	
    }
public void arc(){
	c=pi*radius*radius;
	System.out.println("area of circle"+c);
}
}



package com.inportia;

public class Rectangle {
	int length,breadth,area;
    Rectangle(int x,int y){
    	length=x;
    	breadth=y;
    }

public void area(){
	area=length*breadth;
	System.out.println("area of rectangle"+area);
}
}
