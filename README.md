# Power-Management-Unit on STM32

## Assembly
* Connectors for PWM control
* Cooler - PWM regulator impeller cooling
* Starter - PWM regulator starter
* Injector - PWM gas damper machines
* A square connector will indicate a common point.

## Power Connectors
* SWITCH - switch
* Servos_12V - power supply 6 Volt; The right shoe is a common point
* LED - board power indication
* BAT; BAT1 (+ -) - battery connection connectors
* ChgIN (+ -) - battery charging connector
* Starter (+ -) - starter control power connector
* Cooler (+ -) - cooling controller power connector
* X1..X8 (+ -) - load power connector
* A; B; C - the connector of the phases of the generator windings
## R26 - 8.2 kΩ (pair to the voltage divider for the temperature sensor)
### U6 replace with ACS758xCB sensor
* http://www.allegromicro.com/~/media/Files/Datasheets/ACS724-Datasheet.ashx?la=en
* Solder contacts are soldered as directed by the designer
##### solder a jumper between the second pins of the Injector and Valve connectors to power the flap servo
##### For workings solder the middle point of the potentiometer to the seat of the resistor R3 on the MK board
