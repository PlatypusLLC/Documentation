Equipment
=========

This section will provide detailed explanations of the various pieces of equipment that are used with the boat.

[Back to the Introduction](Manual_Intro__Lutra.html)

## Batteries and Chargers

### LiPo Batteries
1. Info dump on batteries we use.
2. LiPo batteries in general.
3. Safety.
4. Image of 16000 mAh battery.
5. Peak output current (the #-C system), typical run-time.
6. Terminations we use (pp75).

### LiPo Balancer/Chargers
1. Balancer/Charger general info.
2. The basic charger we typically use.
3. More advanced chargers.
4. Maximum recommended charging current.
5. Charge time. 

## Boat Deck/Hull
Vacuum-formed ABS. Tough, capable of sustaining significant hull damage and remains intact. Space between deck and hull contains buoyant foam.

### Compartments
1. Back compartment. Picture of back compartment. Contains motors, cooling loop, and ESC's.
2. Front compartment. Picture of front compartment. Contains battery, phone, eboard.

### Compartment Plates
Made from acrylic. Compresses o-ring to create seal. Held in place by the rotating tabs.

### Drain plug
Covers a hole that can be used to manually drain any water that may have leaked into the space between deck and hull.

### Sensor Porthole
Sensor cables are routed through this hole. ABS pipe, inner diameter = X. (or say it is X-size sch. 40 etc.)

### Mounting Locations
Any universal mounting blocks that we have installed. If none, remove this section.

## Drivetrain
Two types of propulsion: submerged propellers ("prop-boat") and one- or two- fan airboat.

### Prop-boat
Two motors mounted on modules called "powerpods".

#### Powerpod
One motor, 2:1 belt pulleys, drive shaft, stuffing tube.
Motor info. Motor mounting info. Motor cooling sleeves.

#### Propellers
L/R reversed plastic, X mm size.

### Airboat
Can be one fan that rotates at base or two fans that do not rotate.

#### Shroud
Protects fan from the environment and vice versa. Rotating base info (e.g. make sure it aligns straight back when ESC's beep on boot)

#### Fan and Motor
Fan blade info. Motor info.

#### Fan-Rotation Servo
Servo info? Is this level of detail necessary? Plugs into sensor port 0. Rotates the base of the fan.

## ESC's and Power Handling

### ESC
ESC (Electronic Speed Control), one per motor. General ESC info (link?).
Hooked up to eboard.

### Fuse/Breaker
80A. Closed and open pictures.

## Cooling Loop
Closed cooling loop with food-coloring water. Cools ESC's and motors.

### Pump
Pump info

### Resevoir
Info? How to open it?

### Tubing
Too much detail?

### Heat Exchanger
Aluminum tube. 

## Phone
Typically Nexus 5. Android 5+. Must have gyro. USB-C possible but not recommended. Connects to eboard with USB. Mounting info: orientation, velcro, etc.

### USB-C Adapter
Part info.

## E-Board
If phone is the brain, this is the spine. Acts like a middleman between the components in the boat.

### Arduino
Arduino DUE.

### 8-pin Ports
Micro Con X. Wiring layout.

## Wiring
Cables route power and control signals to various components. Show simple flow chart of signal (blue) and power (red) being routed from battery through eboard to rest of system. Label the lines.

#### ESC Control Wires
Screenshots. Explanation of left/right vs. port/starboard.

#### Pump Power
Screenshot

#### Bullet Power
Screenshot

## Wireless Comms
Boat uses 2.4 GHz WiFi network. The wireless access point that generates the network is on the boat and starts when the eboard is turned on.

### Access Point (Router)
Bullet info. 

### Antenna
Laird antenna info.

## Sensors
Sensors can either log their own data and just be ferried around by the boat, or they can be routed through the board.

### ES2
ES2 info. Temperature compensated EC.

### Dissolved Oxygen (DO)
DO sensor info.

### PH
PH sensor info.

### Lowrance Bathymetry
Lowrance info.

### Additional E-board Sensors
Any sensor that requires 5V or 12V power, < X amps current, and uses serial can be routed through the 8 pin connectors on the eboard.