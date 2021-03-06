# Seat Heating System
## Introduction
Heating method is generally used to regulate the temperature. The system has the option to turn on the heater. The temperature sensor continues to monitor the temperature and transmits the analogue value to the microcontroller. Through serial communication, the microcontroller processes the temperature sensor's analogue input and outputs a temperature value. The control system's activities are carried out entirely on a microcontroller known as the Atmega328. The heat control system's functionality is coded in embedded C, and the work is demonstrated using simulation in SimulIDE software.
## Research
-   Car seat heating was first commercialised in Sweden about fifteen years ago. Seat heaters are now standard equipment or options on Saab, Volvo, Jaguar, BMW, Opel, and Mercedes vehicles, with acceptance and customer demand spreading throughout European markets. In Sweden, all passenger cars sold in the country must include electrical seat heating systems as standard equipment.
-   Seat heating system design is more complicated and sophisticated than one might think. Seat heating systems today are far more advanced than simple heating components like those found in household heating blankets and cushions.
-  A high level of human engineering goes into a properly designed seat heating system, which only supplies heat loss experienced by a person's body and only at the major contact points in the seat cushion.
## Components Required
### ATmega328
-   The ATmega328 is a single-chip microcontroller produced by Atmel and a member of the megaAVR series. It is based on the 8-bit Atmel AVR processor, which is complemented by flash memory and various peripherals. After programming, the controllers can work on their own, using power and clock speed quartz crystal.
-   [Atmega328 PIN Diagram](https://user-images.githubusercontent.com/98877997/157062921-6d20c6dc-cb50-4b29-980f-2341730079fc.png)
### Temperature Sensor
-   The measurement of the temperature sensor is about the coolness or hotness of an entity. The working of the sensor is the voltage that is read across the diode. If there is an increment in voltage, then the temperature increases and there is a voltage decrement between the transistor terminals of the emitter and the base. That data is saved by the sensor.
-   If the difference in voltage is amplified, then an analog signal is generated by the device, and it is directly proportional to the temperature.
### Thermostat
-   A thermostat is a regulating device component which senses the temperature of a physical system and performs actions so that the system's temperature is maintained near a desired setpoint.
-   A thermostat exerts control by switching heating or cooling devices on or off, or by regulating the flow of a heat transfer fluid as needed, to maintain the correct temperature. A thermostat can often be the main control unit for a heating or cooling system, in applications ranging from ambient air control to automotive coolant control. Thermostats are used in any device or system that heats or cools to a setpoint temperature.
### Heater core
-   A heater core is a radiator-like device used to heat a vehicle's cabin. Hot coolant from the vehicle's engine is routed through the core's winding tube, which acts as a heat exchanger between the coolant and the cabin air. Fins attached to the core tubes increase the surface area for heat transfer to air forced past them by a fan, thus heating the passenger compartment.
### LCD (liquid crystal display)
-   Liquid Crystal Display (LCD) is an electronic device, which is frequently used in many applications for displaying the information in a text or image format.
### LED (Light-emitting diode)
-   The lighting emitting diode is a p-n junction diode. It is a specially doped diode and made up of a special type of semiconductors. When the light emits in the forward biased, then it is called a light-emitting diode.
## Diagram
### Block Diagram
![Block Diagram]![WhatsApp Image 2022-04-24 at 3 06 49 PM](https://user-images.githubusercontent.com/101260690/164970964-ca1d445a-ee2a-4890-91d7-8887be3691d4.jpeg)
### Flow Chart
![Flow Chart]!![WhatsApp Image 2022-04-24 at 3 08 06 PM](https://user-images.githubusercontent.com/101260690/164971033-7d4ad429-7073-49f2-bb57-a93d79211a86.jpeg)
## 4W's 1-H
### What
In the winter, heating the seat can make cars much more comfortable. Heating system that raises the surface temperature of the automated seat to the comfort of the occupants.
### Where
-   In the winter, a heated seat is extremely useful. If you are an early riser, you may find the early morning commute to work unbelievably cold and uncomfortable, especially if you have to sit in a cold driver's seat.
### When
-   All heated car seat covers have some form of temperature-control mechanism to allow car users to set a high or low-temperature setting, and when there???s no need to heat up the seats, the heat can be turned off.
### Why
-   It is ideal for older drivers or those who live in cold climates because it heats the seat and makes it more comfortable for both the driver and the passenger.
### How
-   While heated seats are no longer considered a luxury item, many vehicles still come standard with non-heated seats.
-   People who want to convert their regular car seats into heated seats can do so by using heated car seat covers.
## SWOT Analysis
|Strength|Weakness|Opportunities|Threats|
|:--:|:--:|:--:|:--:|
|Seat can be easily heated|High investment|Increased market growth|High electrical resistance|
|Very comfortable for the old persons|Use very protective|Automatic Heating|Over heating|
|Not wait for warm the car|Heavy use harmfull for body|Grow demand|Produces EMF radiation|
|Useful for winter drive|Can not wash the seats|Capability|Third degree burns condition|
## Requirement
### High Level Requirement
|ID|Description|
|:--:|:--:|
|HLR01|Check when the person is sit on the seat heater will automatically start|
|HLR02|Check temperature sensor is work properly|
|HLR03|Check the temperature value|
|HLR04|Check seat heating is work proper or not|
### Low Level Requirement
|ID|Description|
|:--:|:--:|
|LLR01|Check coolant level is running low|
|LLR02|Check the power supply|
|LLR03|Check it display the temperature|
|LLR04|Check it run in all system|
## Example
### Ventilated seats work
-   Cooled and ventilated seats both help you stay cool, according to Chevrolet, although ventilated seats don't use cold air. Inside the seat cushion and backrest of ventilated seats are small fans and ducts. Some systems draw air into the seat, while others use fans to blow air away from the occupant. Small perforations in the fabric allow air to travel through the seat.
-   You may turn on and off the option for chilled or ventilated seats, as well as modify the air force. If the outside temperature is hot, some Chevrolet vehicles include a feature that turns on the ventilated seats when the remote start is used. The ventilated seats turn off whenever the car is turned on. Other Chevrolet vehicles can be set to auto mode, which turns on the ventilated seats when the interior temperature reaches a temperature the driver specifies.
-   [YouTube Video](https://www.youtube.com/watch?v=5XDuvbyIfWs)
## References
|S.No.|Links|
|:-:|:--:|
|1|[MotorBiscuit](https://www.motorbiscuit.com/heated-cooled-ventilated-seats-work/)|
|2|[SAE](https://www.sae.org/publications/technical-papers/content/890848/)|
|3|[Seat heating work](https://www.yourmechanic.com/article/how-a-car-s-heating-system-works)|
|4|[Wikipedia](https://en.wikipedia.org/wiki/Heating_system#:~:text=A%20heating%20system%20is%20a%20mechanism%20for%20maintaining,may%20be%20a%20central%20heating%20system%20or%20distributed.)|
## Conclusion
-   This invention relates to a heated seat for autos, specifically a heated car seat for passenger vehicles. Synthetic materials are widely used in the upholstery of car seats by automobile makers. In cold climates, such fabrics feel quite cold, especially when the car is parked outside for long periods of time during the winter. In addition, the owner covers the automotive seats with a plastic seat cover to protect the fabric. The passenger's discomfort is exacerbated by the plastic covering. The heated seats that have been offered so far have used a lot of electricity. This is a significant drawback because autos have a limited source of such energy.
-   Heating seats are quite comfortable for persons who live in colder climates and assist the driver and passenger in enjoying the winter ride. The heating system is also advantageous to the elderly because it promotes physical comfort during long rides.
