# cmpt276-a2
Assignment2: Student Database Web Application

Web app link:<br/>
https://thawing-crag-75319.herokuapp.com/students

EXTRA FEATURES: (outside basic features)

1. Creating New Students or editing one
  - Only allows integer for weight and height, and only allows 0.01 step for gpa. All of those has a minimum number, weight & height = 1, and gpa =0. Max for gpa =4.33
2. Layout/Design
  - Customize links into buttons with logo, which apparently not easy as adding button on a link tag on plain html.
    This allows me to learn how to actually use buttons within rails, also how to use oper source css button and icons library.
    * Button: https://github.com/alexwolfe/Buttons
    * Icons: http://getbootstrap.com/components/
  - Displaying diagram
    Opens a boostrap modal box instead of crowding the whole page with the data, and diagram
3. Displaying data
  - Added svg (vector) circle to display how high (big) the gpa of students. Filled with colour from the database.
4. Extra information about each student
  - Added BMI calculation for each student, rounded up to 2 decimal points. BMI is weight/height
