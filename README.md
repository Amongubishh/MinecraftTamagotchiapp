# Tamagotchi-app
I have created a Minecraft Tamagotchi app


Essay

[Comprehensive report tamagotchi app.docx](https://github.com/Amongubishh/Tamagotchi-app/files/15220148/Comprehensive.report.tamagotchi.app.docx)

Comprehensive report: History application
IMAD assignment2
Name: Mikhail Govender
ST10441946


Contents page:
Page:
1 introduction
2 purposes of the app
4 design considerations
6 testing
7 Utilization of GitHub and GitHub Actions
8 codes
9 conclusions



Comprehensive report: Minecraft Tamagotchi app
Introduction

The Tamagotchi application I have designed is Minecraft theme to appeal to a wide audience of people who already love and play the game.  It is simple for users of almost all ages to play and enjoy. They can pick between 2 pets and then take care of them. This game is fun and made so that
 you feel you are taking care of a real pet. This application was a success as it feels just like the 
 popular 1990s virtual pet toy, Tamagotchi. 

2. Purpose of the App
The purpose of the app is to bring entertainment to the user, it is purely made for fun. It really mimics what it is like to take care of a real pet without having to do any boring physical labour tasks. It is very addictive and easy to use. I have also put my words to the test by giving the application too many to try it. Kids in general seemed to love the idea of my game and couldn’t seem to put it down.
  Even adults were very impressed and loved to play with their new pets. The app will in some way also teach children to be responsible and take care of things. You can feed, play with, and attend to their virtual pets to keep them happy and healthy. I also added the option for 2 pats instead of just 1.

Key Objectives:
•	Teaches responsibility.
•	Entertainment.
•	Mimics a real pet.
•	It’s addictive.
•	It is loved by all ages.

The other objectives were also met well as I had 4 pages instead of 2, I have a welcome page, choose your pet page and the 2 pet pages. They can keep a close eye on the pet's health, hunger, and cleanliness status on the last 2 pages
3. Design Considerations
3.1 User Interface Design
The design is very colourful and captures the user’s attention. I used many different colours to achieve this desirable look. There are many different pictures to make handling the app a lot better and smoother. The pictures used also were part of a consistent them to make everything flow better. I used constraints to make sure everything didn’t move, and I placed it strategically to make it feel better and faster to use. I placed buttons, text views and edit text as well as plain text. All of which I also customized the colours and the fonts to make it look more attractive and appealing to the user. I also coloured the backgrounds because the white didn’t feel as warm as other colours. All these things combined made my application unique. I also went above and beyond and tried to implement a lot of pictures. Not only that but I have added 2 pets to choose from meaning I basically doubled my workload for the coding. 

3.2 The addition feature
I designed the code so that when you press the button for feed it would then add values to the edit text. This was done using code such as set on click listener and other simple code to achieve this. Once the button is pressed then a value of 10 would be added to the edit text. It will continue to do this if you keep pressing the button.

3.3 Educational Content
The user would learn to take care of a virtual pet and get ready to take on the responsibility to take care of their own pet. This would in turn make our children which are the future, more responsible. It is also a fun way to teach small children about life and how you need to be fed, clean and happy in the form of a fun game.

3.4 The image change
The pet's image changes according to the type of action it is performing for both pets. It will change depending on what button you press for an appropriate image to pop up corresponding to said action as well. The code for this is also discussed further down.

3.5 Screen logic
The first screen has a welcome with a start button, the second screen has aa back button to return to screen one. It also has the option to select which pet you want. The 3rd/4th screen has your selected pet with the feed, clean and play button that will add points once pressed. There is also a return button to return to page 2.
Testing
I performed manual testing to ensure that the application runs, which it does. I also made sure there were no errors and then also got help from git hub and ran more tests to make sure that the code runs flawlessly. 


4. Utilization of GitHub and GitHub Actions
4.1 Version Control with GitHub
I used git hub as a version control system to control the development of this application. Git hub really helped develop my project. The people on git hub are always very nice and willing to help with your code. They looked through my code and helped me fix any errors I had and test to see if my code ran properly. Whenever I was stuck, they would always give me hints and explain what exactly I needed to do. I highly recommend git hub for any coding projects as they also give a different perspective and make your application even better. They also helped me write out some code too get my application to run better. People online helped me in groups, and it was very good and efficient. I had some issues making the user interface link to another user interface through a button and they were good at explaining what I needed to add to create that. It helps connect the world so we can work together to make revolutionary code.  Their community and their website honestly helped me so much. Setting up my account was very easy and the whole website was very user friendly. The whole community was very nice and super helpful. 
 

5.Code
For the code I had to first give everything good understandable ids. I then declared any buttons and text views etc… I then made the set on click listener for the buttons and linked the user interfaces to each other so you can move back and forth with ease. I also implemented back buttons to return to previous user interfaces. I then made it so that when you pressed a button that would in turn activate the edit text and add 10 to an original value that is there:

var counter = 0

        feedButton.setOnClickListener {
            counter += 10
            editText.setText(counter.toString())
        }
 When that happens, the original image would then also be swapped to the desired image using:

// Change the image resource of the ImageView
            imageView.setImageResource(R.drawable.another_image)
 

After I added comments everywhere explaining what the code did. I made sure that I closed all brackets, curly brackets and the quotation marks. I checked through the code toughly to see if there are any errors as well and that the app ran fine. I also went further to go above and beyond to add return buttons everywhere so that you can go back to previous pages. Not only that but I also have 4 pages instead of the required 2 pages.

5. Conclusion
All in all, my application is enjoyed my all ages and is very addictive. It teaches very valuable life lessons. I could not have done it without the support from git hub and the people there who helped me. I tried to make my application as vibrant as possible and eye captivating. I tested the application by letting some friends and some family members use it, they all loved the idea and how the app functioned. They were very impressed by my coding skills as well. I implemented all the coding and knowledge I have developed from imad and everything our lecturer told us as well as the modal manual. I went above and beyond multiple times to add more things to my application to active the best app in the class as well as a high mark. 



YouTube Video
https://youtu.be/Urzx5YehVns?si=qAWbmMFfFdS3Ya5s 
