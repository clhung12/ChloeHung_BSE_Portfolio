# Knock Detecting Lock
The Knock Detecting Lock is a project that reads in a sequence of knocks and checks it to the correct sequence to see whether or not it will open a box. It is also able to input any sequence of knocks as the answer when the program button is pressed.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Chloe Hung | Monta Vista Highschool | Mechanical Engineering | Incoming Freshman

![Headstone Image](https://bluestampengineering.com/wp-content/uploads/2016/05/improve.jpg)
  
# Final Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
My second milestone involved finishing up the main build and code of the project. I started by taking my original code and changing it to involve sequences of knocks instead of just two by putting the times into an array. Once all the values were stored, the program compared if the number of knocks is correct, the individual time between each knock is fairly correct, and the sequence overall is not too different. Then I recieved the piezo sensor which detects vibrations and replaced the button with it. I also implemented a programming button so that I could enter in a new knock sequence whenever I held it down instead of at the beginning of the program. I also bought the main box portion and the lock mechanism and glued all the pieces into it. One of the main problems I faced was with the program being very unreliable for when it recorded a knock. It would sometimes read in multiple of not read in at all. I fixed this by adding a resistor so that there was no extra noise, which allowed me to change the threshold value to as low as 20. 

[![Milestone2](https://res.cloudinary.com/marcomontalbano/image/upload/v1626803629/video_to_markdown/images/youtube--j6_tQjlKj94-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=j6_tQjlKj94&ab_channel=BlueStampEng "Milestone2"){:target="_blank" rel="noopener"}
# First Milestone
  

For my first milestone, I created a circuit and worked on building the main coding of the knocks. The circuit is fairly simple with the board reading in a sensor and then triggering an LED to light up. Originally, I had used a button which used a digital pin, but I also switched it to the piezo sensor which detects vibrations and was analog. My first revision of code was to light up the LED when a button was pressed around 1 second after each other. It would read the number of milliseconds that passed since the program started and found the difference between the two presses. Then it would compare the difference with 1 second allowing a small margin of error. One problem I faced was getting the code to not read in all the values if a button is accidently held down, but I was able to fix this with a simple Boolean for changing states. After that; I wrote code that allowed the user to input the time by pressing the correct sequence in the beginning of the program.  

[![Chloe Hung Milestone1](https://res.cloudinary.com/marcomontalbano/image/upload/v1626453989/video_to_markdown/images/youtube---qq1D9D6qxc-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=-qq1D9D6qxc&ab_channel=BlueStampEng "Chloe Hung Milestone1"){:target="_blank" rel="noopener"}

