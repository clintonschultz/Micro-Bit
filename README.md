# Micro-Bit
10 Activities for Using C/C++ with Micro::Bit

1. Make 10 Shapes. Scroll the shapes continuously. Understand how to use display related functions.
   
   *** See scroll_shapes in code.
   
2. Display 25 dots randomly one by one. Clear the dots, and display the dots one by one over and over again.

   *** See randomly_populate_display in code.

3. Show A when Button A is clicked. B when Button B is clicked, and C when both buttons a clicked.
   Make the code using an infinite loop and interrupt.
   
   *** See buttons_abc in code.
   
4. Display one dot randomly in the matrix. Use Button A and B to move the dot left or right. Click both buttons to move the      dot up. When the dot is at the highest row and both buttons are clicked, move the dot to the bottom.

   *** See move_led_with_buttons in code.

5. Make the same program as 4, but this time move the board so that accelerometer can catch the direction to move the dot.

   *** See move_led_accelerometer in code.
   
6. Display current temperature in Celsius first when button A is clicked, and in Fahrenheit when button B is clicked.

   *** See buttons_show_temp in code.

7. Make a timer, it displays 0 to 9 and 0 again. Use both timer and nested loops. 

   *** See display_timer in code.
   
8. Make a dice that randomly generates a number between 1 and 6 when thrown. Measure the acceleration, and make a random          number from the measured data.

9. Send a message A and display A when button A is clicked, and likewise with B. The other board receives the message and show    the corresponding character.

   *** See send_message_radio in code.

10.Send current temperate to the other board in Celsius first when button A is clicked, and in Fahrenheit when button B is        clicked.

   *** See send_temp_radio in code.

   ***I used the DAL from Lancaster University on ARM Mbed https://ide.mbed.com/.***
