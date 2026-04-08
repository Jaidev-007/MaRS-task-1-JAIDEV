# MaRS-task-1-JAIDEV
this is my task 2 for MaRS club recruitment (and my first read me :> ).
so there are 2 sections and I will explain one by one.

--------------------------------------------------------------------------------------------------------
**section A**
--------------------------------------------------------------------------------------------------------
**Q1)Blinking LED with different time interval**

here in the project there are 3 leds which need to go on and off with a specific time which is here 500,1000,and 1500 ms without interrupting other leds

components used -
1.arduino uno (microcontroller which is basically brain of the project here)
2.breadboard (to make connections)
3. 3 x LED(to lit up and on different time interval)
4. 3 x 345 ohm resistor (to protect leds form drawing to much current n not let them burn out )
5.jumperwires(for connections)

challenges faced - I faced in challenege from shifting from delays to millis and controlling each led
how i solved - i jsut learned how to use millis nicely so that i can control all the htings and learnd millis help write non blocking code nicely as they use a timer which starts when the code starts to get executed.

--------------------------------------------------------------------------------------------------------
**Q2)Controlling colour of RGB LED and blinking speed of another LED with potentiometer**

here one potenetiometer need ot control the changing colours of the rgb led and then at the same time it should control the frequence of off and on of a normal led 

components used -
1.arduino uno (microcontroller which is basically brain of the project here)
2.breadboard (to make connections)
3. LED(to lit up )
4. 3 x 11 ohm resistor (to protect leds form drawing to much current n not let them burn out )
5.jumperwires(for connections)
6.potenetiometer(a variable voltage divider , here it gives analog values from 0 to 1023 according to the knob placement so that we can use map function )
7. rgb led(to lit up in different colours)

challenges face - i didn't know how to change th values of rgb led and normal led when the potentiometer changes (liek i idndt know htat map function existed) and i didn't kno how to use rgb led

how i solved - i learned how rgb led works and potentiometer works . and i learned how to use map function which makes that conversion eays and we can change the new units and it wilchange the value according which is very nice

--------------------------------------------------------------------------------------------------------

**Q3)Build a reaction time tester**

here in this project we need to make raction time tested by onnning and led randomly and check after how much time the user clicks a push button and check their reaction speedand inform them how fast or slow they are 

components used -
1.arduino uno (microcontroller which is basically brain of the project here)
2.breadboard (to make connections)
3. one LED(to lit up randomly and check the reaction time)
4. 234 ohm resistor (to protect led form drawing to much current n not let it burn out )
5.jumperwires(for connections)
6.10 ohm resistor ( as a pull down resistor for the push button)

challenges faced - i didn't know how to use a push button and i didn't know thi spull up and pull down resistor
how i solved - i learned how a push button works and how a pull up and pull down resistor works with this push button and made pull down . and i even got to know there is inpuilt pull up resistor in Arduino uno 

--------------------------------------------------------------------------------------------------------
section B
--------------------------------------------------------------------------------------------------------
**option 1 - Smart Distance Alert System**

i chose this roject because i wanted to learn about ultrasonic sensor and how to use a buzzer and how to use that trig and echo an dthen i wanted ot even once try map function so ya i just did option 1.
here in this project this works as a alarm system or uk a alert system . if an object comes closer the ultrasonic sensor it will on the 5 leds depending on the distance if it is very close all 5 get on 
and then even the buzzer gets on and if its an other distance buzzer wont go on but maybe few leeds depending on the lvl of distance they are at.


components used -
1.arduino uno (microcontroller which is basically brain of the project here)
2.breadboard (to make connections)
3. 5 x LED(to lit up at different levels )
4. 6 x 123 ohm resistor (to protect leds form drawing to much current n not let them burn out and one for buzzer jsut to limit current flow )
5.jumperwires(for connections)
6.buzzer( to make sound when object is too close)

challenges faced - i didnt know how to use a buzzer and a ultrasonic sensor and i dindt know how to use that trig and echo .
how i solved - i learned about how to use a buzzer and ultrasonic form the internet and implemented in on the code . like it wasnt much hard i already learned how ot code in sec A so ya

--------------------------------------------------------------------------------------------------------

**option 2 -Morse Code Transmitter**
i chose this because i wanted to learn how to take inputs in that serial monitor i jsut know how to print till no wbut idk how ot use the serial monitor for tkaing inputs and all and the morse code name only looked intresting so ya i jsut did this

this project jsut converts ur sentence or letters or ur words into morse code wiht the help of a simple led bllinking in a prticular time intervals as a morsce code should be lile

components used -
1.arduino uno (microcontroller which is basically brain of the project here)
2.breadboard (to make connections)
3. 1 x LED(to lit up and do the morse code )
4. 123 ohm resistor (to protect leds form drawing to much current n not let them burn out )
5.jumperwires(for connections)

challenges i faced - i didnt knw how to take input form the user into serial monitor in the c++ liek basically in the arudino ide .
how i solved - i solved my going through google how ot take inpouts and i learne dhow to make stings and all in cpp and thne i for to know . and i got to know different baud rates in arduino ide serial monitor and put more sppeed baud rate then the usual 9600 and implemeneted it in code and solved this problem.


thank you : )

