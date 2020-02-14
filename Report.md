 Name:Kevin Pangottil        

EID:ksp2235

Team Number:F9

## Questions

1. Why does your program need a setup and a loop?

    THe setup initializes the board, and the loop keeps the code running repeatedly to keep the LED blinking. 

2. What is the downside to putting all your code in a loop?

   The initialization only needs to be run once so it's unnecessary to implement that in the loop.  
   
3. Why does your code need to be compiled?

 So the code will be converted to assembly so the board can read it. It can also be used to check for errors before being uploaded to the board. In addition, the code is saved when you compile it. 
 
4. When lowering the frequency in procedure A, step 4, what is going wrong? Brainstorm some solutions. Dimmers exist in the real world. What is their solution?

The LED is flickering and the frequency is too low that our eyes can see the duty cycle. The solution is to increase the frequency  

5. Why do you need to connect the logic analyzer ground to the ESP32 ground?

    To complete the circuit. 
    
6. What is the difference between synchronous and asynchronous communication?

 Synchronous depends on the clock while asynchronous occurs without depending on a clock. 
 
7. Profile of UART: Sent X bytes in Y time 

    5 bytes in 6.149 ms

8. Profile of SPI: Sent X bytes in Y time

    4 bytes in 0.123 ms
    
9. Why is SPI so much faster than UART?

    your answer here

10. list one pro and one con of UART

Pro: It doesn't depend on the clock
Con: It's slower

11. list one pro and one con of SPI

Pro: It's faster
Con: It relies on the clock

12. list one pro and one con of I2C

    your answer here

13. Why does I2C need external resistors to work?

    your answer here

## Screenshots

Procedure A, step 1:
![Put path to your image here ->](img/PAp1.png)

Procedure A, step 4:
![Put path to your image here ->](img/PAs4.png)

Procedure B, UART:
![Put path to your image here ->](img/PBs1.png)

Procedure B, SPI:
![Put path to your image here ->](img/SIPtimer.png)
