Water tank overflow is a common problem which leads to the wastage of water. Though there are many solutions to it like ball valves which automatically stop the water flow once the tank gets full. But being an electronics enthusiastic wouldn’t you like an electronic solution for it? So here is a simple and handy DIY that will guide you to make a circuit which will detect the water level and will raise an alarm upon getting the water tank full or a preset level. 
 
This simple transistor based water level indicator circuit is very useful to indicate the water levels in a tank. Whenever tank gets filled, we get alerts on particular levels. Here we have created 4 levels (low, medium, high and full), we can create alarms for more levels. We have added 3 LEDs to indicate initial three levels (A, B, C), and one Buzzer to indicate FULL level (D). When tanks gets filled completely we get beep sound from Buzzer.
 
Circuit Components

4 - BC547 transistors
6 - 220 ohm resistors
3 - Colour led
1 – Buzzer
5 - 9v battery + battery clip
 
Circuit Diagram

 Water Level Indicator Alarm Circuit
We can consider this whole circuit as 4 small circuits, each one for indicating/alarming, when a particular level (A,B,C,D) of water have been reached.
When water level reaches to point A, circuit with RED LED & transistor Q1 gets completed and RED LED glows. Similarly when water level reaches to point B, circuit with YELLOW LED and transistor Q2 gets completed and Yellow LED glows, same goes with point C. And finally when tank gets full (Point D), circuit with buzzer gets completed and buzzer starts beeping.
 
Working

Here we are using transistor (of NPN type) as a Switch. Initially there is no voltage applied to the base of the Transistor Q1 and the transistor is in OFF state and no current is flowing through collector and emitter and LED is OFF (See below diagram to understand Transistor Pin structure).
Transistor Pin Structure
When the water level reaches to Point A in the tank, the positive side of the battery gets connected to the base of the Transistor Q1 through the water. So when a positive voltage has been applied to the base of the Transistor Q1, it gets into ON state and current starts flowing from collector to emitter. And RED LED glows.
 
You can see resistors (R1, R2, R3) at the base of each transistor, which is used to limit the maximum Base current. Generally a transistor gets its ON state fully when a voltage of 0.7 V is applied to the base. There are also resistors (R4, R5, R6) with each of the LEDs, to drop the voltage across LEDs, otherwise LED may blow up.
 
Same phenomenon happens when water level reaches to Point B. As soon as water level reaches to Point B, a positive voltage gets applied to the Transistor Q2, it gets ON and current started flowing through YELLOW LED, and LED glows. With same principle, GREEN LED glow when water level reaches to Point C.And finally Buzzer beeps when water level reaches to D.
 
Note that Left most wire in the tank must be lengthier than other four wires in the tanks, because this is the wire which is connected to positive voltage.

[![image](https://cdn2.iconfinder.com/data/icons/snipicons/5000/home-32.png)](https://arjunhari2704.github.io/)
