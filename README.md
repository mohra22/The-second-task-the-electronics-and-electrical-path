# Turning on and off an electrical circuit

# circui
The switch needs effort to function , so we connected one of the switch legs with a voltage equal to 5 volts

The resistance is important to protect the circuit in the event that the value of the voltage given to the switch exceeds 5 volts
# code
1. we defined both gate 13 and 7 as LED and BUTTON for ease of use within the code
2. Then we configured gate 13 as output and gate 7 as input
3. We assign the instantaneous state of the key in the variable val, that is, if it is pressed, the value of val will be equal to HIGH, and in the absence of pressure, the value will be LOW before taking any action
4. After that, using the conditional if statement, we asked the program that if val==HIGH, that is, we pressed the key, the controller will light the LED, otherwise the LED will be turned off
