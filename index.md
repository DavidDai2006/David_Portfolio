# Automated Cat Laser
<!---
Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails!
-->
| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| David D | Homestead High School | Electrical Engineering | Incoming Senior

<!---
**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**
-->
<img src="David-D-Headshot.png" width="400" height="500">

# Final Milestone

<!---
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

-->

# Second Milestone
<!---
For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

-->
## Project Summary
In my second milestone, I installed a laser diode to the double-servo arm device, and programmed the laser to turn off and off while the servos were rotating. Additionally, I altered the code for the servos to make a consistent and streamlined movement instead of erratics jumps every second. This involved the use of "while" statements to constantly run a command that turns the servos little by little. I also added a wooden board and drilled holes into it so that I could screw in the arduino uno board and the double-servo arm.

## Parts Used
- A 5V laser diode was taped onto the servo arm. There are two wires on a 5V laser diode: the red wire acts as both the control and power wire, and the blue wire acts as the ground wire, and goes into the negative side of the breadboard.
- Two male-to-female jumper wires were soldered to the laser diode's wires, so that the laser diode could actually be connected to the breadboard and the digital pins in the arduino uno board.
- An 8 in. by 8 in. wooden board was cut and holes were drilled in so that the Arduino Uno board and the servo arm could be screwed in and stay stationary while the program is being run.

## Challenges
- Laser diodes work in a much different way, and required further reading of documentation to fully understand how to activate and de-activate the laser diode I installed. The laser had two wires instead the three wires I was accustomed to from LEDs and servo motors. It turns out that the laser diode's red wire acts as both the power and control wire. Additionally, laser diodes require a completely different set of methods to turn themselves on and off.

## Next Steps
- I plan to replace the breadboard with a circuit board where I solder on the jumper wires. This will allow the wires to stay on the board without the risk of falling out.
- I will add a button to the Automated Cat Laser, so I can choose whether or not the program runs.
- I can also add an ultra-sonic sensor or a camera to detect if there's movement or if there's a cat within frame, so the Automated Cat Laser can turn itself on by itself.

# First Milestone
## Project Summary
My project is the Automated Cat Laser. In the first milestone, I built the device that allows two micro servos to rotate it, effectively creating an arm for the laser to be installed on. I connected all of the motors to the Arduino Uno board and the breadboard.

## Parts Used
- There are two micro servos in the device, both of which can rotate up to 180 degrees, and have three wires, that being a power, control, and ground wire.
- The Arduino Uno board connects with the motors' control wire, and allows the program to manipulate the motors.
- The breadboard allows the connection of multiple motors to the arduino board. There is a positive and negative row on the breadboard, and the ground wires from the motors go to the negative side of the breadboard, and the power wires from the motors go to the positive side of the breadboard. It also connects to the Arduino Uno board to allow power to be transferred to the servos.

## Challenges
- The servo horn that is supposed to go into the base of the servo device was too large, and it required me to file the servo horn down to the correct size, so that it could fit inside of the mold in the device's base.
- It was difficult to figure out where each of the wires from the servos went. I had to scan through multiple servo documentations to figure out and understand why each wire went to their respective areas in the arduino board and breadboard.

## Next Steps
- I will add the laser diode to the servo device and the arduino board, and program it to turn on.
- I will also refine the code for the servos, so that the servos move in a consistent pattern, rather than choppy moves in one-second intervals.

<iframe width="560" height="315" src="https://www.youtube.com/embed/KUVGFRCeZjM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

# Starter Project
## Project Summary
My starter project is the Useless Box. The Useless Box consists of a lever installed on the motherboard, which when turned on, activates a rotating servo. The servo has an arm attached to it, and when the servo is activated, the arm inside the Useless Box will rotate to the lever, turning the Useless Box off, which will return the arm that turned off the machine to the original position.

The Useless Box consists of the following parts:
- The motherboard, which connects all of the parts together
- A switch
- A servo that rotates around 90 degrees when the switch is activated
- A plastic arm that is attached to the servo, which, when the lever is switched, rotates to turn off the lever.
- A small LED light that turns green when the switch is on, and red when the switch is off
- A battery holder to power the Useless Box
- Resistors which limit the power used on specific parts, such as the LED
- Screw terminals to allow wires to connect from the battery to the board

## Challenges
One challenge I faced with the project was when the arm attached to the servo missed the lever, and rendered the box *actually* useless. I had to re-adjust the servo and the arm to make sure it hit the lever when the lever was flipped. Another issue I faced was the soldering. I had to hold each piece in the correct orientation when soldering, and I consistently burned myself during the first few tries. I was eventually able to learn some tips and tricks, and finished soldering the rest of the parts without burning myself.

After the starter project, I will work on my intensive project, which is the Automated Cat Laser.

<iframe width="560" height="315" src="https://www.youtube.com/embed/-w8U305zvZM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<!---
# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
-->
