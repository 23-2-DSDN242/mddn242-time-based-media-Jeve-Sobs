[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/JAZAP9dv)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=11462214&assignment_repo_type=AssignmentRepo)
## MDDN 242 Project 1: Time-based Media  

## Week 1
My idea for my clock sketch was to represent the hour hand as a segment that is uncovered and the minute hand is shown on the outside of the clock. In this example the time is 8:10 
![plot](./images/sketch.png)

## Week 2
This is my clock so far I have been playing around with mapping sin and cos functions to create cool effects. I plan on making my alarm do something with z axis rotation and colours
![plot](./images/image-week2.png)

## Week 3
I have been working on my alarm, I have found it difficult to make both my main clock and my alarm look good because I find that each time I improve one the other one gets worse. I have now got my alarm to a point where I am pretty happy with however I still need to work on my actually clock and work out how I will make it display the time. For seconds I will have it pulse and for hours I will use the circles around the house but I still need to find a way to represent minutes and display which circle is currently active. 
![plot](./images/image-week3-1.png)
![plot](./images/image-week3-2.png)

## Week 4
In week 4 my focus was on making my clock function better as a clock. I first did this by making the number of elements represent the hours. This worked well however it created a new much more difficult problem to deal with. Since I used the number of elements or the hours to calculate the radius of the shapes, changing the hour meant there would be a slight change in the size of the object. It also meant there would be a sudden jump in the shape itself so I had to find a way to smoothly transition between hours. I did this by reducing the size of the clock to make the slight jump in size less noticeable and by increasing the thickness of the frame any change of the shape is hidden. 
![plot](./images/image-week4.png)