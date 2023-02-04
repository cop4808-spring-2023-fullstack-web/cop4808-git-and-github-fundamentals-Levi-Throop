## Name: Levi Throop :wave:
## GitHub Username: Levi-Throop
## https://github.com/cop4808-spring-2023-fullstack-web/cop4808-git-and-github-fundamentals-Levi-Throop.git

## Calculator GIF :sunglasses:
![](https://github.com/cop4808-spring-2023-fullstack-web/cop4808-git-and-github-fundamentals-Levi-Throop/blob/main/Calculator_test.gif)

## First step - Adding new buttons 
In the first step I added 4 new lines of buttons with a new class labeled 'operator_new'. This is for the 4 new functions which are natural log, square root, x squared, and absolute value. 

## Second step - Modifying style.css file (styling the new buttons)
The second step consisted of modifying the existing container div id, which allowed me to include my new row into the same sizing attributes as the rest of the buttons. Then I added my new operator_new class and added a different background color and bolded the text per the instructions. I also decided to add the focus attribute to my buttons that the original operator buttons had so that it matched, besides the color of course.

## Third step - Modifying script.js file (adding functionality and logic)
After the buttons were added and the style was how I wanted it and followed the instruction I had to modify the javascript file to add functionality. Since it is a new class I made the application does not recognize when the buttons are clicked. So I went into the existing clickButton() function and added my new buttons. Next, I had to add the actual arithmetic of the buttons. This was down adding to the operate(x,y,op) function and including 4 more else-if statements with the proper logic. 

## Fourth step - Adding Comments for readability (Helps reusability) 
Finally, after I tested the calculator app and successfully made a gif showcasing its proper usage as per the instructions I went back and adding some well needed comments. This helps the next user to understand the changes that were made and what their designed purpose or functionality is. 
