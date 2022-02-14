micro:bit Rock Paper Scissors
--------------------
In this assignment you and a partner will program two micro:bits to play the rock paper scissors game against each another.

Like the previous teleporting duck program, this one uses the micro:bit’s radio function to send data from one micro:bit to another when the accelerometer detects a shake gesture. The program first configures the radio and sets its group. It doesn’t matter what group you pick as long as your partner’s micro:bit is using the same group number, and no-one else nearby is using the same group. When you shake your microbit, it randomly chooses rock, paper or scissors and sends it's choice on that radio group and clears. It compares it's choice with the other micro:bit's choice and displays whether it won, lost or tied

Program requirements
-----------------
* Your program will need at least three images that represent rock, paper and scissors
* Your program must use the micro:bit's accelerometer and radio features
* Each person will submit the Python code for their program and an animated gif showing the two programs running to Google Classroom

Suggested steps to completing this assignment
----------
1. Add code to import the radio library, turn the radio on and set the group number
2. Create three different images to represent rock, paper and scissors
3. Create a variable `num`and initialize it to `3`
3. Inside of the `while True:` write an `if` statement that checks if the micro:bit was shaken. You can go back and look at the previous [dice assignment](https://github.com/Computer-Programming-B/MicrobitDice/blob/main/README.md#microbit-dice) to see how. If the microbit has been shaken, clear the display and set the `num` variable to a random integer from 0 to 2. For each of the 3 random numbers from 0 to 2, display a different image
4. Create a message variable, and store the received radio message `message = radio.receive()`
5. Inside of the `while True:` write another `if` statement `if message and num!=3:` Compare the message with random number and display whether the player won, lost or tied

Samples of Student Work
----------
*none yet!*
