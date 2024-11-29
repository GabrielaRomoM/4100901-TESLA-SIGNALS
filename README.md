# 4100901-TESLA-SIGNALS
This repository contains an aproach to implement the tesla turn and hazard signals.

# Current Functionality 
- Heartbeat blinks every 1000ms/1 sec (frecuency on 1Hz).
- When left button is pressed once: left light blink 3 times.
- When left button is pressed twice in less than 300ms : left light blink indefinitely.
- When right button is pressed once: right light blink 3 times.
- When right button is pressed twice in less than 300ms : right light blink indefinitely.
- If a turn botton is pressed (right or left), and the opposite light is on this light gonna off and the one to the button is gonna on.
- The parking signal gonna work if the third and last button is pressed, this gonna turn on a parking light with blinks for 2 minutes straight.

# Other Settings 

Accord to the general rules of circulation, i made the next setting of blink times:
- Hearbeat dont has possibilites of turn off by the user, its just turning off when the whole system is off. 
- Turn lights has blinks every 500ms
- Parking signal has blinks for 2 minutes, each blink every 500ms (this configuration can have variations on the blinking speed and minutes blinking but i think the setting i did is the better one for this application). 
