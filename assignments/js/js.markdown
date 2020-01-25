# JavaScript Fundamentals

Lets add two numbers and get the outcome.

	var width = 10; //  represents the width of the rectangle
	var length = 20;// represents the height of the rectangle
	var area = width*length; // calculate the area
	console.log(area);

What if we have to add numbers again and again. Then we have to write the above code **again and again**.

Assume we have four rectanges of different dimenstions and we have to calculate their **areas** and **sum** them together to find out the final area.

	/* for first rectangle */
 	var firstWidth = 10;
 	var firstLenght = 10;
 	var firstArea = firstWidth*firstLength;
 	
 	/* for second rectangle */
 	var secondWidth = 10;
 	var secondLenght = 10;
 	var secondArea =secondWidth*secondLength;
 	
 	// similar for other rectangles
 	....
 	
 	var totalArea = firstArea + secondArea + thirdArea + fourthArea;
 	
  In the above solution we have written the similar code angain again. 
  
  Let's think about about above solution deeply.
  
  1.What if we have to deal with 100 rectangles.
  2.What if we have to calculate the area of circles rather than rectangles.
  
  So repeated code will cause the repeated changes. So **code repetition** is problem.
  
   
  
  
  
  
  
	
	

