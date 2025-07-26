# Windows

5 Select 

All 
Programs
6 Select 

JLR
7
NOTE:
PINPOINT TEST A : NON START FROM KEYLESS VEHICLE ENTRY
Do not disconnect the battery or perform a hard reset on the vehicle, at least 
until this flow chart has been followed
TEST CONDITIONS
DETAILS/RESULTS/ACTIONS
Do not disconnect the battery or perform a hard reset on the 
vehicle, at least until this flow chart has been followed

/START 
SWITCH
DTS), start 
CAN log as 
per correct 
process. 
Ensure that 
MONITOR 
WITHOUT 
DIAGNOSTICS 
is selected
icon 
(Windows 
XP) from 
bottom 
tool bar
Is the ignition on"
Yes
Are the KVM 	 CJB responding as required"
Follow SDD system mapping and navigate to:- Powertrain / Engine 
system / Starting system (	 further sub symptoms) or Electrical / 
Battery / Power distribution / Ignition supplies (	 further sub 
symptoms), then perform the Security-start authorisation status app 
following this process
Stop SDD session then stop CAN link monitor. Raise Technical 
Assistance report and then attach CAN log and session file. Mention 
any further comments from customer that may be relevant. Raise 
Technical Assistance report and send all data to DTS
No
 .
GO to A3
A3: CHECK THE SMART KEY IS FOUND

1 Is 
smart key not 
found
 displayed"
2 Place the key at the IAU. Press the stop / 
start switch without pressing the brake pedal
Is the ignition on"
Yes
 .
GO to A4
No
Confirm the correct keys are being used by confirming the correct 
key blades
Run SDD IAU replacement App
 . Ignition on question
GO to A2
A4: CJB RESET
1 Switch the ignition 
OFF
2 Remove and put back fuse 17 from the 
CJB
Are all functions restored"
Yes
Follow SDD system mapping and navigate to:- Powertrain / Engine 
system / Starting system (	 further sub symptoms) or Electrical / 
Battery / Power distribution / Ignition supplies (	 further sub 
symptoms), then perform the Security-start authorisation status app 
following this process
Stop SDD session then stop CAN link monitor. Raise Technical 
Assistance report and then attach CAN log and session file. Mention 
any further comments from the customer that may be relevant. Raise 
Technical Assistance report and send all data to DTS
No
 .
GO to A5
A5: CHECK FOR LOST COMMUNICATIONS
1 Check RFR for any KVM lost comms with RFR related DTCs. Rectify 
as required
Are all the functions restored"
Yes
Follow SDD system mapping and navigate to:- Powertrain / Engine 
system / Starting system (	 further sub symptoms) or Electrical / 
Battery / Power distribution / Ignition supplies (	 further sub

symptoms), then perform the Security-start authorisation status app 
following this process
Stop SDD session then stop CAN link monitor. Raise Technical 
Assistance report and then attach CAN log and session file. Mention 
any further comments from the customer that may be relevant. Raise 
Technical Assistance report and send all data to DTS
No
 .
GO to A6
A6: CJB TEST
1 Now you need to confirm, if the 
CJB is functioning correctly
2 Carry out flasher test, press the 
hazard warning lamp switch
Do the front and rear turn signal indicators work"
Yes
 .
GO to A7
No
 .
GO to A8
A7: SIDE REPEATER LAMP OPERATION
1 Check the vehicle for side repeater lamp operation
Do the side repeater lamps work"
Yes
The CJB is responding as required
Now outside the scope of this pin point test
Record this detail and include in the Technical Assistance report
Stop SDD session then stop CAN link monitor. Raise Technical 
Assistance report and then attach CAN log and session file. Mention 
any further comments from the customer that may be relevant. Raise 
Technical Assistance report and send all data to DTS
No
 .
GO to A9
A8: SIDE REPEATER SWITCH OPERATION
1 Check vehicle for side repeater operation
Do the side repeater lamps work"
Yes
Record this detail and include in the Technical Assistance report

Stop SDD session then stop CAN link monitor. Raise Technical 
Assistance report and then attach CAN log and session file. Mention 
any further comments from the customer that may be relevant. Raise 
Technical Assistance report and send all data to DTS
No
 .
GO to A9
A9: HA=ARD ILLUMINATION LAMP SWITCH OPERATION
1 Check the hazard illumination lamp switch is operational
Does the hazard lamp switch illumination work"
Yes
 .
GO to A10
No
 .
GO to A11
A10: CAN INTEGRITY CHECK
1 Check for CAN integrity MS or MS (BODY), repair as necessary
Are the KVM 	 CJB Start 	 Entry functions restored"
Yes
The CJB is responding as required
Now outside the scope of this pin point test
Record this detail and include in the Technical Assistance report
Stop SDD session then stop CAN link monitor. Raise Technical 
Assistance report and then attach CAN log and session file. Mention 
any further comments from the customer that may be relevant. Raise 
Technical Assistance report and send all data to DTS
No
Now outside the scope of this pin point test
Record this detail and include in the Technical Assistance report
Stop SDD session then stop CAN link monitor. Raise Technical 
Assistance report and then attach CAN log and session file. Mention 
any further comments from the customer that may be relevant. Raise 
Technical Assistance report and send all data to DTS
A11: HA=ARD WARNING LAMP IC TELL-TALE CHECK
1 Check that the IC is operational
Does the IC tell-tale work"

Yes
Now outside the scope of this pin point test
Record this detail and include in the Technical Assistance report
When the vehicle function has completed, select CAN link Monitor tab 
from the tool bar
Select 
CAPTURE
Select 
STOP LOGGING
. A pop-up window will display 
Logging 
stopped successfully
Locate the CAN link Monitor file on the USB
Open file and make sure the data has recorded correctly
Close the file
Remove the USB flash drive from SDD machine
Stop SDD session then stop CAN link monitor. Raise Technical 
Assistance report and then attach CAN log and session file. Mention 
any further comments from the customer that may be relevant. Raise 
Technical Assistance report and send all data to DTS
No
Record this detail and include in the Technical Assistance report
Stop SDD session then stop CAN link monitor. Raise Technical 
Assistance report and then attach CAN log and session file. Mention 
any further comments from the customer that may be relevant. Raise 
Technical Assistance report and send all data to DTS
For a list of diagnostic trouble codes that could be logged on this 
vehicle, please refer to Section 100-00. 
REFER to: Diagnostic Trouble Code (DTC) Index - DTC: Keyless 
 (100-00 General Information, Description and 
Vehicle Module (KVM)
Operation). 
DTC INDEX

2015. 0 F-TYPE (X152), 419-01
ANTI-THEFT - PASSIVE
DESCRIPTION AND OPERATION

ITEM
DESCRIPTION
1
LF antenna - luggage compartment left side
2
LF antenna - luggage compartment right side
3
LF antenna - floor console
COMPONENT LOCATION - SHEET 1 OF

4
LF antenna - cross-car beam

ITEM
DESCRIPTION
1
Immobilizer antenna unit
2
Keyless vehicle module
The PATS (passive anti-theft system) prevents the vehicle from being 
driven away by unauthorized persons. This is achieved by having 
uniquely coded keys (both passive and transponder) and an encoded 
data exchange between multiple control modules. Unauthorized 
starting is prevented by inhibiting the engine crank, fuel and ignition 
systems.
The PATS is a function of the passive start system. The system uses 
the following components:
COMPONENT LOCATION - SHEET 2 OF
OVERVIEW

A KVM (keyless vehicle module).
Four LF (low frequency) antennas.
An IAU (immobilizer antenna unit).
Smart key(s). 
For additional information, refer to: Handles, Locks, Latches and 
 (501-14 Handles, Locks, Latches and Entry Systems, 
Entry Systems
Description and Operation). 
The RF (radio frequency) receiver. 
For additional information, refer to: Handles, Locks, Latches and 
 (501-14 Handles, Locks, Latches and Entry Systems, 
Entry Systems
Description and Operation). 
The 
 .
CJB (central junction box)
The 
 .
ECM (engine control module)
The instrument cluster.
The system is automatic and requires no input from the driver. 
Engine starting is initiated by pressing the stop/start switch with the 
transmission in park and the brake pedal pressed. The engine 
management system will then allow engine crank and fueling when 
an authorization data message is received from the 
 .
CJB
LOW FRE4UENCY ANTENNAS
DESCRIPTION

Four LF antennas for the passive start system are positioned in the 
following locations:
On the instrument panel cross-car beam, behind the center stack 
carriers.
In the floor console, under the stowage compartment.
On the rear floor, under the left and right side trims of the luggage 
compartment.
The KVM transmits an LF signal via the antennas which is received by 
the smart key. The smart key then responds by transmitting a RF 
signal, which is received by the RF receiver and passed to the KVM 
for authorization.
KEYLESS VEHICLE MODULE
The KVM is located on the right A pillar. The module controls signal 
transmissions to and from the smart key and provides authorization 
to allow the vehicle to be entered and started. The KVM has a serial 
communication line connection to the RF receiver and a medium 
speed 
 connection to the 
 for 
CAN (controller area network)
CJB
authorizing vehicle unlocking and starting.
IMMOBILI=ER ANTENNA UNIT

The IAU is installed on the inside of the steering column opening 
cover of the instrument panel.
The IAU is used if the KVM is unable to authorize the smart key. If 
the KVM is unable to identify the smart key, for example if the smart 
key battery voltage is low or there is local RF interference, the driver 
will be alerted to this by a chime and a message in the instrument 
cluster message center. The transponder within the smart key can 
then be read by the IAU.
When it receives a hardwired signal from the stop/start switch, the 
 sends a message via the medium speed 
 bus to the KVM 
CJB
CAN
initiating the vehicle starting process. The KVM then prompts each of 
the internal LF antennas to output a signal. When a smart key is in 
the vehicle, it detects the LF signal and responds with a RF 
identification signal back to the KVM via the RF receiver. If the data 
received matches that stored in the KVM it continues the passive 
OPERATION

start process by communicating a 
smart key valid¶ signal to the 

CJB
via the medium speed 
 bus.
CAN
Once the 
 receives the authorization and confirms the response 
CJB
with an internal calculation, it passes coded data to the instrument 
cluster on the medium speed 
 bus. Upon confirmation from the 
CAN
instrument cluster the ignition is enabled.
Before 
 sends a mobilization signal to the 
 , it will exchange 
CJB
ECM
encrypted data with the electric steering column lock (where fitted) to 
authorize unlocking of the steering column. The instrument cluster 
only provides a ground for the steering lock motor.
Provided there is a hardwired P/N (park/neutral) signal from the TCS 
(transmission control switch), and a valid brake pressure signal from 
the 
 control module on the high speed 
ABS (anti-lock brake system)
 bus, the 
 then allows the start request and:
CAN
CJB
Energizes the fuel pump relay, which supplies battery voltage to the 
FPDM (fuel pump driver module) to operate the fuel pump in 
conjunction with the ECM
Sends a hardwired crank request to the 
 to start the engine.
ECM
NOTE:
To ensure optimum long term reliability of the smart key the battery 
must be replaced with a brand new, unused battery. If a used battery 
is installed the SMART KEY BATTERY LOW message may not be 
cleared. To avoid contamination of the contacts the battery should be 
removed from its packaging and installed into the smart key while 
wearing gloves. To confirm that the replacement battery is working 
correctly press the unlock button twice while holding the smart key 
For the brake pressure signal to be valid it must be greater than 
a threshold value stored in the 
 . This ensures the vehicle 
CJB
remains stationary when the engine starts.

outside the vehicle, then enter the vehicle with the smart key, press 
the start button and confirm that the SMART KEY BATTERY LOW 
message is not displayed.
KEYLESS START BACKUP
If the vehicle has been unlocked using the emergency key blade or 
the smart key is not detected by the vehicle, it will be necessary to 
use the keyless start backup to disarm the alarm and start the 
engine. The following process must be followed in this event:
Press the stop/start switch, if the KVM fails to locate the smart 
key a message to that effect is displayed in the message center.
1
Position the smart key in the depression in the instrument panel, 
below the auxiliary lighting switch, with the not found key 
switches facing outwards.

Press the stop/start switch with the brake pedal depressed to 
start the engine.


NOTE:
This process bypasses the data exchange between the KVM and the 
 . This is an inductive process and will operate even if the battery 
CJB
in the smart key is discharged. A transponder within the smart key is 
detected by the IAU. The IAU communicates this code with the 

CJB
via a 
 bus connection. The 
 then 
LIN (local interconnect network)
CJB
initiates the vehicle start process in the normal manner.
INPUT/OUTPUT DIAGRAM - KEY DETECTION
A   HARDWIRED CONNECTION N   MEDIUM SPEED 
 BUS AH   
CAN
SERIAL COMMUNICATION LINE.
ITEM
DESCRIPTION
1
Keyless vehicle module
2
Central junction box
If the smart key not found message is no longer displayed (only 
displayed for 10 seconds), then the sequence would have to be 
repeated.

3
LF antenna - luggage compartment left side
4
LF antenna - luggage compartment right side
5
LF antenna - floor console
6
LF antenna - cross-car beam
7
Smart key
8
Ground
9
Permanent power feed
10
Smart key
11
RF receiver
INPUT/OUTPUT DIAGRAM - PASSIVE START
A   HARDWIRED CONNECTION D   HIGH SPEED 
 BUS N   
CAN
MEDIUM SPEED 
 BUS O   
 BUS.
CAN
LIN
ITEM
DESCRIPTION
1
Central junction box
2
Fuel pump relay
3
Engine control module

2015. 0 F-TYPE (X152), 100-00
GENERAL INFORMATION
4
Ground
5
Permanent power feed
6
Transmission selector switch
7
Stop/Start switch
8
Immobilzer antenna unit
9
Keyless vehicle module
10
Instrument cluster
11
Electric steering column lock
12
Engine control module
13
Anti-lock brake system control module
DESCRIPTION AND OPERATION
CAUTION:
Diagnosis by substitution from a donor vehicle is 

NOT
acceptable. Substitution of control modules does not guarantee 
confirmation of a fault, and may also cause additional faults in 
the vehicle being tested and/or the donor vehicle
KEYLESS VEHICLE MODULE (KVM)

NOTES:
If the control module or a component is suspect and the 
vehicle remains under manufacturer warranty, refer to the 
Warranty Policy and Procedures manual, or determine if any 
prior approval programme is in operation, prior to the 
installation of a new module/component
Generic scan tools may not read the codes listed, or may read 
only 5-digit codes. Match the 5 digits from the scan tool to the 
first 5 digits of the 7-digit code listed to identify the fault (the 
last 2 digits give extra information read by the manufacturer-
approved diagnostic system)
When performing voltage or resistance tests, always use a 
digital multimeter accurate to three decimal places and with a 
current calibration certificate. When testing resistance, always 
take the resistance of the digital multimeter leads into account
Check and rectify basic faults before beginning diagnostic 
routines involving pinpoint tests
Inspect connectors for signs of water ingress, and pins for 
damage and/or corrosion
If diagnostic trouble codes are recorded and, after performing 
the pinpoint tests, a fault is not present, an intermittent 
concern may be the cause. Always check for loose connections 
and corroded terminals
Where an 
on demand self-test
 is referred to, this can be 
accessed via the 
diagnostic trouble code monitor
 tab on the 
manufacturers approved diagnostic system
Check DDW for open campaigns. Refer to the corresponding 
bulletins and SSMs which may be valid for the specific 
customer complaint and carry out the recommendations as 
required

The table below lists all Diagnostic Trouble Codes (DTCs) that could 
be logged in the keyless vehicle module, for additional Diagnosis and 
Testing information refer to the relevant Diagnosis and Testing 
Section. 
For additional information, refer to: Locks, Latches and Entry Systems
(501-14 Handles, Locks, Latches and Entry Systems, Diagnosis and 
Testing) / 
 (419-01B Anti-Theft - Passive, Diagnosis and 
Anti-Theft - Passive
Testing). 
DTC
DESCRIPTION
POSSIBLE CAUSES
ACTION
B102B-
00
Passive Key - 
No sub type 
information
NOTE:
Encryption error. 
Incorrect smart key
Smart key is not 
configured 
correctly
NOTE:
Check the smart key 
being used is the correct 
key
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. If the fault 
persists, re-configure the 
smart key with the latest 
level software
B10A9-
00
Remote 
Keyless Entry 
Less Than
Keys 
Programmed - 
No sub type 
information
Less than 2 key 
fobs have been 
programmed
Clear DTC and retest. If 
the fault persists, 
configure the key fobs 
using the manufacturers 
approved diagnostic 
system
B10C1-
15
Left Front 
Unlock Pull 
Switch - Short 
circuit to 
battery or open
NOTE:
This DTC is set 
after four 
failed attempts 
to recognise 
the smart key
This DTC is set if an 
invalid smart key is 
detected when the 
ECO switch is 
operated
Circuit 
reference - FL 
UNLOCK SW

Front left exterior 
door handle power 
or ground circuit 
open circuit, high 
resistance
Front left exterior 
door handle unlock 
switch circuit short 
circuit to power, 
open circuit, high 
resistance
Front left exterior 
door handle switch 
internal failure
NOTE:
Refer to the electrical 
circuit diagrams and 
check the front left 
exterior door handle 
power and ground 
circuits for open circuit, 
high resistance
Refer to the electrical 
circuit diagrams and 
check the front left 
exterior door handle 
unlock switch circuit for 
short circuit to power, 
open circuit, high 
resistance
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. If the fault 
persists, check and 
install a new front left 
exterior door handle as 
required
B10C1-
23
Left Front 
Unlock Pull 
Switch - Signal 
stuck low
NOTE:
Front left exterior 
door handle unlock 
switch circuit short 
circuit to ground
Front left exterior 
door handle switch 
internal failure
NOTE:
This DTC is set after 
the front left latch 
switch has been 
activated six times, 
without the front left 
unlock switch being 
activated
Circuit 
reference - FL 
UNLOCK SW
This DTC is set when 
the door handle 
unlock switch is 
pressed for
seconds. If the 
switch is released 
before 45 seconds 
have passed, the 
timer will stop and 
DTC will not set

Refer to the electrical 
circuit diagrams and 
check the front left 
exterior door handle 
unlock switch circuit for 
short circuit to ground
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. If the fault 
persists, check and 
install a new front left 
exterior door handle as 
required
B10C2-
15
Left Rear 
Unlock Pull 
Switch - Short 
circuit to 
battery or open
NOTE:
No power supply 
to door handle
Unlock switch 
circuit - Short 
circuit to power, 
open circuit, high 
resistance
Switch fault
NOTE:
Refer to the electrical 
circuit diagrams and 
check the power and 
ground circuits to the 
door handle. Repair 
circuit as required. Clear 
DTC and retest
Refer to the electrical 
circuit diagrams and 
check the unlock switch 
circuit for short circuit to 
power, open circuit, high 
resistance. Repair circuit 
as required. Clear DTC 
and retest
If fault persists, check 
and install a new door 
handle as required
B10C2-
23
Left Rear 
Unlock Pull 
Switch - Signal 
stuck low
NOTE:
NOTE:
This DTC is 
not applicable 
to two-door 
vehicles
This DTC is not 
applicable to two-
door vehicles
This DTC is 
not applicable 
to two-door 
vehicles
This DTC is not 
applicable to two-
door vehicles

Unlock switch 
circuit - Short 
circuit to ground
Switch fault
Refer to the electrical 
circuit diagrams and 
check the unlock switch 
circuit for short circuit to 
ground. Repair circuit as 
required. Clear DTC and 
retest
If fault persists, check 
and install a new door 
handle as required
B10C3-
15
Right Front 
Unlock Pull 
Switch - Short 
circuit to 
battery or open
NOTE:
Front right 
exterior door 
handle power or 
ground circuit 
open circuit, high 
resistance
Front right 
exterior door 
handle unlock 
switch circuit short 
circuit to power, 
open circuit, high 
resistance
Front right 
exterior door 
handle switch 
internal failure
NOTE:
Refer to the electrical 
circuit diagrams and 
check the front right 
exterior door handle 
power and ground 
circuits for open circuit, 
high resistance
Refer to the electrical 
circuit diagrams and 
check the front right 
exterior door handle 
unlock switch circuit for 
short circuit to power, 
open circuit, high 
resistance
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. If the fault 
persists, check and 
install a new front right 
exterior door handle as 
required
B10C3-
23
Right Front 
Unlock Pull 
Switch - Signal 
NOTE:
NOTE:
Circuit 
reference - 
FRONT RIGHT 
UNLOCK SW
This DTC is set after 
the front right latch 
switch has been 
activated six times, 
without the front 
right unlock switch 
being activated

stuck low
Front right 
exterior door 
handle unlock 
switch circuit short 
circuit to ground
Front right 
exterior door 
handle switch 
internal failure
Refer to the electrical 
circuit diagrams and 
check the front right 
exterior door handle 
unlock switch circuit for 
short circuit to ground
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. If the fault 
persists, check and 
install a new front right 
exterior door handle as 
required
B10C4-
15
Right Rear 
Unlock Pull 
Switch - Short 
circuit to 
battery or open
NOTE:
No power supply 
to door handle
Unlock switch 
circuit - Short 
circuit to power, 
open circuit, high 
resistance
Switch fault
NOTE:
Refer to the electrical 
circuit diagrams and 
check the power and 
ground circuits to the 
door handle. Repair 
circuit as required. Clear 
DTC and retest
Refer to the electrical 
circuit diagrams and 
check the unlock switch 
circuit for short circuit to 
power, open circuit, high 
resistance. Repair circuit 
as required. Clear DTC 
and retest
Circuit 
reference - 
FRONT RIGHT 
UNLOCK SW
This DTC is set when 
the door handle 
unlock switch is 
pressed for
seconds. If the 
switch is released 
before 45 seconds 
have passed, the 
timer will stop and 
DTC will not set
This DTC is 
not applicable 
to two-door 
vehicles
This DTC is not 
applicable to two-
door vehicles

If fault persists, check 
and install a new door 
handle as required
B10C4-
23
Right Rear 
Unlock Pull 
Switch - Signal 
stuck low
NOTE:
Unlock switch 
circuit - Short 
circuit to ground
Switch fault
NOTE:
Refer to the electrical 
circuit diagrams and 
check the unlock switch 
circuit for short circuit to 
ground. Repair circuit as 
required. Clear DTC and 
retest
If fault persists, check 
and install a new door 
handle as required
B10C5-
23
Trunk Unlock 
Pull Switch - 
Signal stuck low
NOTE:
Upper tailgate 
exterior switch 
circuit short circuit 
to ground
Upper tailgate 
exterior switch 
internal failure
NOTE:
Refer to the electrical 
circuit diagrams and 
check the upper tailgate 
exterior switch circuit for 
short circuit to ground
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. If the fault 
persists, check and 
install a new upper 
tailgate exterior switch 
as required
This DTC is 
not applicable 
to two-door 
vehicles
This DTC is not 
applicable to two-
door vehicles
Circuit 
reference - 
EXT BOOT 
RELEASE SW
This DTC is set when 
the tailgate unlock 
switch is pressed for 
45 seconds. If the 
switch is released 
before 45 seconds 
have passed, the 
timer will stop and 
the DTC will not set

B10C6-
00
Exterior Trunk 
Antenna - No 
sub type 
information
NOTE:
Tailgate antenna 
circuit short circuit 
to ground, short 
circuit to power
Tailgate antenna 
incorrect position
Tailgate antenna 
internal failure
NOTE:
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
tailgate antenna circuit 
for short circuit to 
ground, short circuit to 
power
Check the position of the 
tailgate exterior antenna 
and reposition as required
If the fault persists, 
check and install a new 
tailgate antenna as 
required
B10C6-
Exterior Trunk 
NOTE:
NOTE:
For the 
antenna to be 
tested once, 
the vehicle 
must go 
through five 
ignition on 
cycles and 
exceed a 
speed of
kph each cycle
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below

11
Antenna - 
Circuit short to 
ground
Tailgate antenna 
circuit short circuit 
to ground or short 
circuit between 
positive and 
negative
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
tailgate antenna circuit 
for short circuit to 
ground, short circuit 
between positive and 
negative
B10C6-
12
Exterior Trunk 
Antenna - 
Circuit short to 
battery
NOTE:
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
tailgate antenna circuit 
for short circuit to power
For the 
antenna to be 
tested once, 
the vehicle 
must go 
through five 
ignition on 
cycles and 
exceed a 
speed of
kph each cycle
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below
For the 
antenna to be 
tested once, 
the vehicle 
must go 
through five 
ignition on 
cycles and 
exceed a

Tailgate antenna 
circuit short circuit 
to power
B10C6-
13
Exterior Trunk 
Antenna - 
Circuit open
NOTE:
Tailgate antenna 
circuit open 
circuit, high 
resistance
NOTE:
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
tailgate antenna circuit 
for open circuit, high 
resistance
B10C7-
00
Interior Trunk 
Antenna - No 
sub type 
NOTE:
NOTE:
speed of
kph each cycle
For the 
antenna to be 
tested once, 
the vehicle 
must go 
through five 
ignition on 
cycles and 
exceed a 
speed of
kph each cycle
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below

information
Luggage 
compartment left 
antenna circuit 
short circuit to 
ground, short 
circuit to power
Luggage 
compartment left 
antenna incorrect 
position
Luggage 
compartment left 
antenna internal 
failure
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
luggage compartment 
left antenna circuit for 
short circuit to ground, 
short circuit to power
Check the position of the 
luggage compartment 
left antenna and 
reposition as required
If the fault persists, 
check and install a new 
luggage compartment 
left antenna as required
B10C7-
11
Interior Trunk 
Antenna - 
Circuit short to 
ground
NOTE:
NOTE:
For the 
antenna to be 
tested once, 
the vehicle 
must go 
through five 
ignition on 
cycles and 
exceed a 
speed of
kph each cycle
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below
For the 
antenna to be 
This DTC may be 
logged as a result of

Luggage 
compartment left 
low frequency 
antenna circuit 
short circuit to 
ground or short 
circuit between 
positive and 
negative
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
luggage compartment 
left low frequency 
antenna circuit for short 
circuit to ground, short 
circuit between positive 
and negative
B10C7-
12
Interior Trunk 
Antenna - 
Circuit short to 
battery
NOTE:
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
luggage compartment 
left antenna circuit for 
short circuit to power
tested once, 
the vehicle 
must go 
through five 
ignition on 
cycles and 
exceed a 
speed of
kph each cycle
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below
For the 
antenna to be 
tested once, 
the vehicle 
must go 
through five 
ignition on 
cycles and 
exceed a 
speed of
kph each cycle

Luggage 
compartment left 
antenna circuit 
short circuit to 
power
B10C7-
13
Interior Trunk 
Antenna - 
Circuit open
NOTE:
Luggage 
compartment left 
antenna circuit 
open circuit, high 
resistance
NOTE:
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
luggage compartment 
left antenna circuit for 
open circuit, high 
resistance
B10C8-
00
Interior Center 
Antenna - No 
NOTES:
NOTE:
For the 
antenna to be 
tested once, 
the vehicle 
must go 
through five 
ignition on 
cycles and 
exceed a 
speed of
kph each cycle
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below

sub type 
information
Passenger 
compartment right 
antenna circuit 
short circuit to 
ground, short 
circuit to power
Passenger 
compartment right 
antenna incorrect 
position
Passenger 
compartment right 
antenna internal 
failure
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
passenger compartment 
right antenna circuit for 
short circuit to ground, 
short circuit to power
Check the position of the 
passenger compartment 
right antenna and 
reposition as required
If the fault persists, 
check and install a new 
passenger compartment 
right antenna as required
B10C8-
11
Interior Center 
Antenna - 
Circuit short to 
ground
NOTES:
NOTE:
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
REAR CABIN 
ANT POS / 
REAR CABIN 
ANT NEG
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below

Passenger 
compartment right 
antenna circuit 
short circuit to 
ground or short 
circuit between 
positive and 
negative
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
passenger compartment 
right antenna circuit for 
short circuit to ground, 
short circuit between 
positive and negative
B10C8-
12
Interior Center 
Antenna - 
Circuit short to 
battery
NOTES:
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
passenger compartment 
right antenna circuit for 
short circuit to power
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
REAR CABIN 
ANT POS / 
REAR CABIN 
ANT NEG
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of

Passenger 
compartment right 
antenna circuit 
short circuit to 
power
B10C8-
13
Interior Center 
Antenna - 
Circuit open
NOTES:
Passenger 
compartment right 
antenna circuit 
open circuit, high 
resistance
NOTE:
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
20 kph each 
cycle
Circuit 
reference - 
REAR CABIN 
ANT POS / 
REAR CABIN 
ANT NEG
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
REAR CABIN 
ANT POS / 
REAR CABIN 
ANT NEG
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below

the electrical circuit 
diagrams and check the 
passenger compartment 
right antenna circuit for 
open circuit, high 
resistance
B10C9-
00
Interior Front 
Antenna - No 
sub type 
information
NOTES:
Passenger 
compartment front 
antenna circuit 
short circuit to 
ground, short 
circuit to power
Passenger 
compartment front 
antenna incorrect 
position
Passenger 
compartment front 
antenna internal 
failure
NOTE:
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
passenger compartment 
front antenna circuit for 
short circuit to ground, 
short circuit to power
Check the passenger 
compartment front 
antenna position and 
reposition as required
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
FRONT 
CABIN ANT 
POS / 
FRONT 
CABIN ANT 
NEG
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below

If the fault persists, 
check and install a new 
passenger compartment 
front antenna as required
B10C9-
11
Interior Front 
Antenna - 
Circuit short to 
ground
NOTES:
Passenger 
compartment front 
antenna circuit 
short circuit to 
ground or short 
circuit between 
positive and 
negative
NOTE:
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
passenger compartment 
front antenna circuit for 
short circuit to ground, 
short circuit between 
positive and negative
B10C9-
12
Interior Front 
Antenna - 
Circuit short to 
battery
NOTES:
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
FRONT 
CABIN ANT 
POS / 
FRONT 
CABIN ANT 
NEG
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below

Passenger 
compartment front 
antenna circuit 
short circuit to 
power
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
passenger compartment 
front antenna circuit for 
short circuit to power
B10C9-
13
Interior Front 
Antenna - 
Circuit open
NOTES:
NOTE:
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
FRONT 
CABIN ANT 
POS / 
FRONT 
CABIN ANT 
NEG
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
FRONT 
CABIN ANT 
POS / 
FRONT 
CABIN ANT 
NEG
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then

Passenger 
compartment front 
antenna circuit 
open circuit, high 
resistance
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
passenger compartment 
front antenna circuit for 
open circuit, high 
resistance
B10CA-
00
Left rear door 
handle 
Antenna - No 
sub type 
information
NOTE:
Passive rear left 
door open does 
not function, 
antenna failure
NOTES:
continue with the 
diagnostic actions 
detailed below
This DTC is 
not applicable 
to two-door 
vehicles
This DTC is not 
applicable to two-
door vehicles
This DTC may be 
logged as a result 
of a short to power 
fault on another LF 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test 
and monitor the 
test output to 
check for any short 
circuit to power 
DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short 
circuit to power 
faults on other 
antennas have 
been resolved, 
then continue with 
the diagnostic 
actions detailed 
below

First record, then clear 
the DTC. Using the 
manufacturer approved 
diagnostic system, 
perform an on demand 
self-test and monitor the 
test output to check if 
DTC reoccurs
If the fault persists, refer 
to the electrical circuit 
diagrams and check the 
rear left door handle 
antenna circuit for short 
circuit to ground, short 
circuit to power. Repair 
circuit as required. Clear 
DTC and retest
If the fault persists, 
check and install a new 
rear left door handle 
antenna as required
B10CA-
11
Left rear door 
handle 
Antenna - 
Circuit short to 
ground
NOTE:
Rear left door 
handle antenna 
circuit - One or 
both antenna 
wires short circuit 
to ground or 
shorted to each 
other
NOTES:
This DTC is 
not applicable 
to two-door 
vehicles
This DTC is not 
applicable to two-
door vehicles
This DTC may be 
logged as a result 
of a short to power 
fault on another LF 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test 
and monitor the 
test output to 
check for any short 
circuit to power 
DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short 
circuit to power 
faults on other 
antennas have 
been resolved,

First record, then clear 
the DTC. Using the 
manufacturer approved 
diagnostic system, 
perform an on demand 
self-test and monitor the 
test output to check if 
DTC reoccurs
If the fault persists, refer 
to the electrical circuit 
diagrams and check the 
rear left door handle 
antenna circuit antenna 
wires for short circuit to 
ground or short to each 
other. Repair circuit as 
required. Clear DTC and 
retest
B10CA-
12
Left rear door 
handle 
Antenna - 
Circuit short to 
battery
NOTE:
Rear left door 
handle antenna 
circuit - One or 
both antenna 
wires short circuit 
to power
NOTES:
then continue with 
the diagnostic 
actions detailed 
below
This DTC is 
not applicable 
to two-door 
vehicles
This DTC is not 
applicable to two-
door vehicles
This fault may 
cause other DTCs 
to log on other 
antennas. If this 
DTC has logged 
alongside other 
antenna circuit 
fault DTCs, this 
short circuit to 
power fault should 
be addressed first. 
Once this short 
circuit to power 
fault has been 
resolved, using the 
manufacturer 
approved 
diagnostic system, 
perform an on 
demand self-test

First record, then clear 
the DTC. Using the 
manufacturer approved 
diagnostic system, 
perform an on demand 
self-test and monitor the 
test output to check if 
DTC reoccurs
If the fault persists, refer 
to the electrical circuit 
diagrams and check the 
rear left door handle 
antenna circuit antenna 
wires for short circuit to 
power. Repair circuit as 
required. Clear DTC and 
retest
B10CA-
13
Left rear door 
handle 
Antenna - 
Circuit open
NOTE:
Rear left door 
handle antenna 
circuit - One or 
both antenna 
wires open circuit, 
high resistance
NOTES:
and monitor the 
test output to 
check if any other 
antenna circuit 
DTCs reoccur
This DTC is 
not applicable 
to two-door 
vehicles
This DTC is not 
applicable to two-
door vehicles
This DTC may be 
logged as a result 
of a short to power 
fault on another LF 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test 
and monitor the 
test output to 
check for any short 
circuit to power 
DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short 
circuit to power 
faults on other

First record, then clear 
the DTC. Using the 
manufacturer approved 
diagnostic system, 
perform an on demand 
self-test and monitor the 
test output to check if 
DTC reoccurs
If the fault persists, refer 
to the electrical circuit 
diagrams and check the 
rear left door handle 
antenna circuit antenna 
wires for open circuit, 
high resistance. Repair 
circuit as required. Clear 
DTC and retest
B10CB-
00
Right rear door 
handle 
Antenna - No 
sub type 
information
NOTE:
Passive rear right 
door open does 
not function, 
antenna failure
NOTES:
antennas have 
been resolved, 
then continue with 
the diagnostic 
actions detailed 
below
This DTC is 
not applicable 
to two-door 
vehicles
This DTC is not 
applicable to two-
door vehicles
This DTC may be 
logged as a result 
of a short to power 
fault on another LF 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test 
and monitor the 
test output to 
check for any short 
circuit to power 
DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short 
circuit to power

First record, then clear 
the DTC. Using the 
manufacturer approved 
diagnostic system, 
perform an on demand 
self-test and monitor the 
test output to check if 
DTC reoccurs
If the fault persists, refer 
to the electrical circuit 
diagrams and check the 
rear right door handle 
antenna circuit for short 
circuit to ground, short 
circuit to power. Repair 
circuit as required. Clear 
DTC and retest
If the fault persists, 
check and install a new 
rear right door handle 
antenna as required
B10CB-
11
Right rear door 
handle 
Antenna - 
Circuit short to 
ground
NOTE:
Rear right door 
handle antenna 
circuit - One or 
both antenna 
wires short circuit 
to ground or 
shorted to each 
other
NOTES:
faults on other 
antennas have 
been resolved, 
then continue with 
the diagnostic 
actions detailed 
below
This DTC is 
not applicable 
to two-door 
vehicles
This DTC is not 
applicable to two-
door vehicles
This DTC may be 
logged as a result 
of a short to power 
fault on another LF 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test 
and monitor the 
test output to 
check for any short 
circuit to power 
DTCs on other

First record, then clear 
the DTC. Using the 
manufacturer approved 
diagnostic system, 
perform an on demand 
self-test and monitor the 
test output to check if 
DTC reoccurs
If the fault persists, refer 
to the electrical circuit 
diagrams and check the 
rear right door handle 
antenna circuit antenna 
wires for short circuit to 
ground or short to each 
other. Repair circuit as 
required. Clear DTC and 
retest
B10CB-
12
Right rear door 
handle 
Antenna - 
Circuit short to 
battery
NOTE:
Rear right door 
handle antenna 
circuit - One or 
both antenna 
wires short circuit 
to power
NOTES:
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short 
circuit to power 
faults on other 
antennas have 
been resolved, 
then continue with 
the diagnostic 
actions detailed 
below
This DTC is 
not applicable 
to two-door 
vehicles
This DTC is not 
applicable to two-
door vehicles
This fault may 
cause other DTCs 
to log on other 
antennas. If this 
DTC has logged 
alongside other 
antenna circuit 
fault DTCs, this 
short circuit to 
power fault should 
be addressed first.

First record, then clear 
the DTC. Using the 
manufacturer approved 
diagnostic system, 
perform an on demand 
self-test and monitor the 
test output to check if 
DTC reoccurs
If the fault persists, refer 
to the electrical circuit 
diagrams and check the 
rear right door handle 
antenna circuit antenna 
wires for short circuit to 
power. Repair circuit as 
required. Clear DTC and 
retest
B10CB-
13
Right rear door 
handle 
Antenna - 
Circuit open
NOTE:
Rear right door 
handle antenna 
circuit - One or 
both antenna 
wires open circuit, 
high resistance
NOTES:
Once this short 
circuit to power 
fault has been 
resolved, using the 
manufacturer 
approved 
diagnostic system, 
perform an on 
demand self-test 
and monitor the 
test output to 
check if any other 
antenna circuit 
DTCs reoccur
This DTC is 
not applicable 
to two-door 
vehicles
This DTC is not 
applicable to two-
door vehicles
This DTC may be 
logged as a result 
of a short to power 
fault on another LF 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test 
and monitor the 
test output to 
check for any short

First record, then clear 
the DTC. Using the 
manufacturer approved 
diagnostic system, 
perform an on demand 
self-test and monitor the 
test output to check if 
DTC reoccurs
If the fault persists, refer 
to the electrical circuit 
diagrams and check the 
rear right door handle 
antenna circuit antenna 
wires for open circuit, 
high resistance. Repair 
circuit as required. Clear 
DTC and retest
B10CC-
23
Left Front 
Latch Clutch 
Switch - Signal 
stuck low
NOTE:
Front left door 
latch clutch switch 
circuit short circuit 
to ground
Front left door 
latch clutch switch 
internal failure
NOTE:
circuit to power 
DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short 
circuit to power 
faults on other 
antennas have 
been resolved, 
then continue with 
the diagnostic 
actions detailed 
below
Circuit 
reference - FL 
CLUTCH SW
This DTC is set when 
the front left door 
latch clutch switch is 
pressed for
seconds. If the 
switch is released 
before 45 seconds 
have passed, the 
timer will stop and 
the DTC will not set

Refer to the electrical 
circuit diagrams and 
check the front left door 
latch clutch switch circuit 
for short circuit to ground
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. If the fault 
persists, check and 
install a new front left 
door latch clutch switch 
as required
B10CD-
23
Left Rear Latch 
Clutch Switch - 
Signal stuck low
NOTE:
Rear left latch 
clutch switch 
circuit - Short 
circuit to ground
Switch fault
NOTE:
Refer to the electrical 
circuit diagrams and 
check the rear left latch 
clutch switch circuit for 
short circuit to ground. 
Repair circuit as 
required. Clear DTC and 
retest
If fault persists, check 
and install a new front 
left latch clutch switch as 
required
B10CE-
23
Right Front 
Latch Clutch 
Switch - Signal 
stuck low
NOTE:
Front right door 
latch clutch switch 
circuit short circuit 
to ground
Front right door 
latch clutch switch 
internal failure
NOTE:
This DTC is 
not applicable 
to two-door 
vehicles
This DTC is not 
applicable to two-
door vehicles
Circuit 
reference - FR 
CLUTCH SW
This DTC is set when 
the front right door 
latch clutch switch is 
pressed for
seconds. If the 
switch is released 
before 45 seconds 
have passed, the 
timer will stop and 
the DTC will not set

Refer to the electrical 
circuit diagrams and 
check the front right 
door latch clutch switch 
circuit for short circuit to 
ground
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. If the fault 
persists, check and 
install a new front right 
door latch clutch switch 
as required
B10CF-
23
Right Rear 
Latch Clutch 
Switch - Signal 
stuck low
NOTE:
Rear right latch 
clutch switch 
circuit - Short 
circuit to ground
Switch fault
NOTE:
Refer to the electrical 
circuit diagrams and 
check the rear right latch 
clutch switch circuit for 
short circuit to ground. 
Repair circuit as 
required. Clear DTC and 
retest
If fault persists, check 
and install a new front 
right latch clutch switch 
as required
B10D1-
23
Left Front Lock 
Button - Signal 
stuck low
NOTE:
Front left door 
exterior handle 
lock switch circuit 
short circuit to 
ground
NOTE:
This DTC is 
not applicable 
to two-door 
vehicles
This DTC is not 
applicable to two-
door vehicles
Circuit 
reference - FL 
CLUTCH SW
This DTC is set when 
the rear right door 
latch clutch switch is 
pressed for
seconds. If the 
switch is released 
before 45 seconds 
have passed, the 
timer will stop and 
the DTC will not set

Front left door 
exterior handle 
lock switch 
internal failure
Refer to the electrical 
circuit diagrams and 
check the front left door 
exterior handle lock 
switch circuit for short 
circuit to ground
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. If the fault 
persists, check and 
install a new front left 
door exterior handle lock 
switch as required
B10D2-
23
Left Rear Lock 
Button - Signal 
stuck low
NOTE:
Rear left lock 
switch circuit - 
Short circuit to 
ground
Switch fault
NOTE:
Refer to the electrical 
circuit diagrams and 
check the rear left lock 
switch circuit for short 
circuit to ground. Repair 
circuit as required. Clear 
DTC and retest
If fault persists, check 
and install a new rear 
left door handle as 
required
B10D3-
23
Right Front 
Lock Button - 
Signal stuck low
NOTE:
Front right door 
exterior handle 
lock switch circuit 
short circuit to 
ground
Front right 
exterior handle 
NOTE:
This DTC is 
not applicable 
to two-door 
vehicles
This DTC is not 
applicable to two-
door vehicles
Circuit 
reference - FR 
CLUTCH SW
This DTC is set when 
the front right door 
latch clutch switch is 
pressed for
seconds. If the 
switch is released 
before 45 seconds 
have passed, the 
timer will stop and 
the DTC will not set

lock switch 
internal failure
Refer to the electrical 
circuit diagrams and 
check the front right 
door exterior handle lock 
switch circuit for short 
circuit to ground
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. If the fault 
persists, check and 
install a new front right 
door exterior handle lock 
switch as required
B10D4-
23
Right Rear 
Lock Button - 
Signal stuck low
NOTE:
Rear right lock 
switch circuit - 
Short circuit to 
ground
Switch fault
NOTE:
Refer to the electrical 
circuit diagrams and 
check the rear right lock 
switch circuit for short 
circuit to ground. Repair 
circuit as required. Clear 
DTC and retest
If fault persists, check 
and install a new rear 
right door handle as 
required
B12D5-
16
Door Handle 
Proximity 
Sensor - 
Circuit voltage 
below threshold
NOTE:
Door handle 
proximity sensor 
circuit short circuit 
to ground
Keyless vehicle 
module power or 
Refer to the electrical 
circuit diagrams and 
check the door handle 
proximity sensor circuit 
for short circuit to ground
Using the manufacturer 
approved diagnostic 
system, check 
datalogger signal - ECU 
Power Supply Voltage 
(0xD111). Refer to the 
electrical circuit diagrams 
and check the keyless 
vehicle module power 
and ground circuits for 
This DTC is 
not applicable 
to two-door 
vehicles
This DTC is not 
applicable to two-
door vehicles
Circuit 
reference - 
DOOR HANDLE 
SUPPLY

ground circuit 
open circuit, high 
resistance
Keyless vehicle 
module internal 
failure
open circuit, high 
resistance
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. If the fault 
persists, check and 
install a new keyless 
vehicle module as 
required
B12D6-
11
Fast Door 
Unlock/Open 
Actuator - 
Circuit short to 
ground
NOTES:
E latch circuit(s) - 
Short circuit to 
ground
NOTES:
Refer to electrical circuit 
diagrams and check E 
latch relay output circuits 
for short circuit to 
ground. Repair circuit as 
required. Clear DTC and 
retest
This DTC 
only applies 
to vehicles 
fitted with 
an active e-
latch system
Circuit 
reference FL 
E-LATCH 
MOTOR 
NEG, FR E-
LATCH 
MOTOR 
NEG, RL E-
LATCH 
MOTOR 
NEG, RR E-
LATCH 
MOTOR 
NEG. Faults 
on individual 
pins/circuits 
cannot be 
detected. A 
short on any 
one output 
pin will be 
detected as 
a short on 
all pins
/circuits
This DTC only 
applies to vehicles 
fitted with an 
active e-latch 
system
Circuit reference 
FL E-LATCH 
MOTOR NEG, FR E-
LATCH MOTOR 
NEG, RL E-LATCH 
MOTOR NEG, RR E-
LATCH MOTOR 
NEG. Faults on 
individual pins
/circuits cannot be 
detected. A short 
on any one output 
pin will be 
detected as a short 
on all pins/circuits

B12D6-
12
Fast Door 
Unlock/Open 
Actuator - 
Circuit short to 
battery
NOTES:
E latch circuit(s) - 
Short circuit to 
power
NOTES:
Refer to electrical circuit 
diagrams and check E 
latch relay output circuits 
for short circuit to power. 
Repair circuit as 
required. Clear DTC and 
retest
B12EA-
96
Radio 
Frequency (RF) 
Receiver - 
Component 
internal failure
RF receiver - 
Internal failure
Clear DTC and retest. If 
the fault persists, check 
and install a new RF 
receiver as required
B1334-
23
Tailgate Glass 
Release Switch 
- Signal stuck 
low
NOTE:
NOTE:
This DTC 
only applies 
to vehicles 
fitted with 
an active e-
latch system
Circuit 
reference FL 
E-LATCH 
MOTOR 
NEG, FR E-
LATCH 
MOTOR 
NEG, RL E-
LATCH 
MOTOR 
NEG, RR E-
LATCH 
MOTOR 
NEG. Faults 
on individual 
pins/circuits 
cannot be 
detected. A 
short on any 
one output 
pin will be 
detected as 
a short on 
all pins
/circuits
This DTC only 
applies to vehicles 
fitted with an 
active e-latch 
system
Circuit reference 
FL E-LATCH 
MOTOR NEG, FR E-
LATCH MOTOR 
NEG, RL E-LATCH 
MOTOR NEG, RR E-
LATCH MOTOR 
NEG. Faults on 
individual pins
/circuits cannot be 
detected. A short 
on any one output 
pin will be 
detected as a short 
on all pins/circuits
This circuit
/switch is 
This DTC is set when 
the tailgate window

Tailgate window 
release switch 
circuit - Short 
circuit to ground
Tailgate window 
release switch 
internal failure
Refer to the electrical 
circuit diagrams and 
check the tailgate glass 
release switch circuit for 
short circuit to ground. 
Repair circuit as 
required. Clear DTC and 
retest
If the fault persists, 
check and install a new 
tailgate window release 
switch as required
B1335-
00
Front 
Triangulation / 
Loadspace 
Antenna - No 
sub type 
information
NOTE:
Luggage 
compartment right 
antenna circuit 
short circuit to 
ground, short 
circuit to power
Luggage 
compartment right 
antenna incorrect 
position
Luggage 
compartment right 
NOTE:
available as an 
option
release switch is 
pressed for
seconds. If the 
switch is released 
before 45 seconds 
have passed, the 
timer will stop and 
the DTC will not set
For the 
antenna to be 
tested once, 
the vehicle 
must go 
through five 
ignition on 
cycles and 
exceed a 
speed of
kph each cycle
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below

antenna internal 
failure
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
luggage compartment 
right antenna circuit for 
short circuit to ground, 
short circuit to power
Check the luggage 
compartment right 
antenna position and 
reposition as required
If the fault persists, 
check and install a new 
luggage compartment 
right antenna as required
B1335-
11
Front 
Triangulation / 
Loadspace 
Antenna - 
Circuit short to 
ground
NOTE:
Luggage 
compartment right 
antenna circuit 
short circuit to 
ground or short 
circuit between 
positive and 
negative
NOTE:
Using the manufacturer 
approved diagnostic 
For the 
antenna to be 
tested once, 
the vehicle 
must go 
through five 
ignition on 
cycles and 
exceed a 
speed of
kph each cycle
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below

system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
luggage compartment 
right antenna circuit for 
short circuit to ground, 
short circuit between 
positive and negative
B1335-
12
Front 
Triangulation / 
Loadspace 
Antenna - 
Circuit short to 
battery
NOTE:
Luggage 
compartment right 
antenna circuit 
short circuit to 
power
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
luggage compartment 
right antenna circuit for 
short circuit to power
B1335-
13
Front 
Triangulation / 
Loadspace 
Antenna - 
Circuit open
NOTE:
NOTE:
For the 
antenna to be 
tested once, 
the vehicle 
must go 
through five 
ignition on 
cycles and 
exceed a 
speed of
kph each cycle
For the 
antenna to be 
tested once, 
the vehicle 
must go 
through five 
ignition on 
cycles and 
exceed a 
speed of
kph each cycle
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are

Luggage 
compartment right 
antenna circuit 
open circuit, high 
resistance
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
luggage compartment 
right antenna circuit for 
open circuit, high 
resistance
B1336-
00
Left Front Door 
External 
Antenna - No 
sub type 
information
NOTES:
Front left door 
handle antenna 
NOTE:
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
LEFT ANT 
POS / LEFT 
ANT NEG
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below

circuit short circuit 
to ground, short 
circuit to power
Front left door 
handle antenna 
incorrect position
Front left door 
handle antenna 
internal failure
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
front left door handle 
antenna circuit for short 
circuit to ground, short 
circuit to power
Check the front left door 
handle antenna position 
and reposition as required
If the fault persists, 
check and install a new 
front left door handle 
antenna as required
B1336-
11
Left Front Door 
External 
Antenna - 
Circuit short to 
ground
NOTES:
Front left door 
handle antenna 
circuit short circuit 
to ground or short 
circuit between 
positive and 
negative
NOTE:
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
LEFT ANT 
POS / LEFT 
ANT NEG
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below

and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
front left door handle 
antenna circuit for short 
circuit to ground, short 
circuit between positive 
and negative
B1336-
12
Left Front Door 
External 
Antenna - 
Circuit short to 
battery
NOTES:
Front left door 
handle antenna 
circuit short circuit 
to power
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
front left door handle 
antenna circuit for short 
circuit to power
B1336-
13
Left Front Door 
External 
Antenna - 
Circuit open
NOTES:
NOTE:
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
LEFT ANT 
POS / LEFT 
ANT NEG
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and

Front left door 
handle antenna 
circuit open 
circuit, high 
resistance
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
front left door handle 
antenna circuit for open 
circuit, high resistance
B1337-
00
Right Front 
Door External 
Antenna - No 
sub type 
information
NOTES:
NOTE:
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
LEFT ANT 
POS / LEFT 
ANT NEG
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
RIGHT ANT 
POS / 
RIGHT ANT 
NEG
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then

Front right door 
handle antenna 
circuit short circuit 
to ground, short 
circuit to power
Front right door 
handle antenna 
incorrect position
Front right door 
handle antenna 
internal failure
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
front right door handle 
antenna circuit for short 
circuit to ground, short 
circuit to power
Check the front right 
door handle antenna 
position and reposition 
as required
If the fault persists, 
check and install a new 
front right door handle 
antenna as required
B1337-
11
Right Front 
Door External 
Antenna - 
Circuit short to 
ground
NOTES:
NOTE:
continue with the 
diagnostic actions 
detailed below
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
RIGHT ANT 
POS / 
RIGHT ANT 
NEG
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then

Front right door 
handle low 
frequency antenna 
circuit short circuit 
to ground or short 
circuit between 
positive and 
negative
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
front right door handle 
antenna circuit for short 
circuit to ground, short 
circuit between positive 
and negative
B1337-
12
Right Front 
Door External 
Antenna - 
Circuit short to 
battery
NOTES:
Front right door 
handle antenna 
circuit short circuit 
to power
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
front right door handle 
antenna circuit for short 
circuit to power
B1337-
13
Right Front 
Door External 
NOTES:
NOTE:
continue with the 
diagnostic actions 
detailed below
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
RIGHT ANT 
POS / 
RIGHT ANT 
NEG

Antenna - 
Circuit open
Front right door 
handle antenna 
circuit open 
circuit, high 
resistance
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
front right door handle 
antenna circuit for open 
circuit, high resistance
B133D-
00
Loadspace
/Interior Boot 
Antenna - No 
sub type 
information
NOTES:
NOTE:
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
RIGHT ANT 
POS / 
RIGHT ANT 
NEG
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to

Luggage 
compartment left 
antenna circuit 
short circuit to 
ground, short 
circuit to power
Luggage 
compartment left 
antenna incorrect 
position
Luggage 
compartment left 
antenna internal 
failure
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
luggage compartment 
left antenna circuit for 
short circuit to ground, 
short circuit to power
Check the luggage 
compartment left 
antenna position and 
reposition as required
If the fault persists, 
check and install a new 
luggage compartment 
left antenna as required
B133D-
11
Loadspace
/Interior Boot 
Antenna - 
Circuit short to 
ground
NOTES:
NOTE:
a speed of 
20 kph each 
cycle
Circuit 
reference - 
LOADSPACE 
ANT POS / 
LOADSPACE 
ANT NEG
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any

Luggage 
compartment left 
antenna circuit 
short circuit to 
ground or short 
circuit between 
positive and 
negative
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
luggage compartment 
left antenna circuit for 
short circuit to ground, 
short circuit between 
positive and negative
B133D-
12
Loadspace
/Interior Boot 
Antenna - 
Circuit short to 
battery
NOTES:
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
luggage compartment 
left antenna circuit for 
short circuit to power
Circuit 
reference - 
LOADSPACE 
ANT POS / 
LOADSPACE 
ANT NEG
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
LOADSPACE 
ANT POS / 
LOADSPACE 
ANT NEG

Luggage 
compartment left 
antenna circuit 
short circuit to 
power
B133D-
13
Loadspace
/Interior Boot 
Antenna - 
Circuit open
NOTES:
Luggage 
compartment left 
antenna circuit 
open circuit, high 
resistance
NOTE:
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. Perform 
routine - On Demand 
Self Test (0x0202). If the 
fault persists, refer to 
the electrical circuit 
diagrams and check the 
luggage compartment 
left antenna circuit for 
open circuit, high 
resistance
C1017-
23
Boot/Trunk 
Primary Switch 
- Signal stuck 
NOTE:
NOTE:
For the 
antenna to 
be tested 
once, the 
vehicle must 
go through 
five ignition 
on cycles 
and exceed 
a speed of 
20 kph each 
cycle
Circuit 
reference - 
LOADSPACE 
ANT POS / 
LOADSPACE 
ANT NEG
This DTC may be 
logged as a result of 
a short to power 
fault on another 
antenna. Before 
proceeding further, 
first perform an on 
demand self-test and 
monitor the test 
output to check for 
any short circuit to 
power DTCs on other 
antennas. If any 
such faults are 
found, they should 
be resolved first. 
Once all short circuit 
to power faults on 
other antennas have 
been resolved, then 
continue with the 
diagnostic actions 
detailed below

low
Tailgate lock 
switch circuit short 
circuit to ground
Tailgate lock 
switch internal 
failure
Refer to the electrical 
circuit diagrams and 
check the tailgate lock 
switch circuit for short 
circuit to ground
If the fault persists, 
check and install a new 
tailgate lock switch as 
required
U0010-
88
Medium Speed 
CAN 
Communication 
Bus - Bus off
Medium speed 
CAN failure - Bus 
off
Refer to the electrical 
circuit diagrams and 
check the keyless vehicle 
module medium speed 
CAN bus for short circuit 
to ground, short circuit 
to power, open circuit, 
high resistance, or short 
circuit between the 
paired CAN wires
U0300-
00
Internal 
Control Module 
Software 
Incompatibility 
- No sub type 
information
Signal 
configuration file 
not loaded
Using the manufacturer 
approved diagnostic 
system check and update 
the car configuration file 
as required. Clear DTC 
and retest
U201F-
00
External 
Receiver - No 
sub type 
information
NOTES:
Refer to the electrical 
circuit diagrams and 
check the LIN bus circuit 
for short circuit to 
ground, short circuit to 
power, open circuit, high 
resistance
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. If the fault 
persists, check and 
install a new RF receiver
This DTC will 
set when the 
lock switch is 
pressed on 
continuously 
for
seconds. If the 
switch is 
released the 
timer will stop
This circuit/switch is 
available as an option
This DTC is 
set if there 
is no 
response 
from the RF 
receiver 
when a data 
request is 
made by the 
keyless

LIN bus circuit 
short circuit to 
ground, short 
circuit to power, 
open circuit, high 
resistance
RF receiver failure
Keyless vehicle 
module internal 
failure
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. If the fault 
persists, check and 
install a new keyless 
vehicle module as 
required.
U201F-
31
External 
Receiver - No 
signal
NOTE:
RF receiver power 
or ground circuit 
open circuit, high 
resistance
LIN bus circuit 
short circuit to 
ground, short 
circuit to power, 
open circuit, high 
resistance
RF receiver failure
Internal failure of 
the keyless vehicle 
module
Refer to the electrical 
circuit diagrams and 
check the RF receiver 
power and ground 
circuits for open circuit, 
high resistance
Refer to the electrical 
circuit diagrams and 
check the LIN bus circuit 
for short circuit to 
ground, short circuit to 
power, open circuit, high 
resistance
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. If the fault 
persists, check and 
install a new RF receiver
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. If the fault 
persists, install a new 
keyless vehicle module 
as required
U201F-
95
External 
Receiver - 
Incorrect 
The RF receiver 
frequency does 
not match the car 
Verify car configuration 
value for RF frequency is 
correct. If not, 
vehicle 
module.
Circuit 
reference RX 
SERIAL DATA
Circuit 
reference RX 
SERIAL DATA

assembly
configuration file 
parameter
reconfigure central 
junction box with correct 
car configuration file. 
Clear DTC and retest
If fault persists, check 
and install a new RF 
receiver as required. 
Clear DTC and retest
U2100-
00
Initial 
Configuration 
Not Complete - 
No sub type 
information
Calibration file has 
not been received 
or is incomplete
Clear DTC and retest. If 
fault persists, reload the 
correct calibration file for 
the vehicle type into the 
module using the 
manufacturer approved 
diagnostic system
U2101-
00
Control Module 
Configuration 
Incompatible - 
No sub type 
information
Car configuration 
parameter is 
outside expected 
value
Verify car configuration 
value sent by central 
junction box is correct 
for the vehicle. If not, 
reconfigure central 
junction box with correct 
car configuration file. 
Clear DTC and retest
If fault persists, reload 
the correct calibration 
file for the vehicle type 
into the keyless vehicle 
module using the 
manufacturer approved 
diagnostic system
U3000-
44
Control Module 
- Data memory 
failure
Keyless vehicle 
module RAM 
memory failure
First record, then clear 
the DTC. Using the 
manufacturer approved 
diagnostic system, 
perform an on demand 
self-test and monitor the 
test output to check if 
DTC reoccurs
If fault persists, check 
and install a new keyless 
vehicle module as 
required. Clear DTC and 
retest
U3000-
45
Control Module 
- Program 
First record, then clear 
the DTC. Using the

memory failure
Keyless vehicle 
program flash 
memory failure
manufacturer approved 
diagnostic system, 
perform an on demand 
self-test and monitor the 
test output to check if 
DTC reoccurs
If fault persists, check 
and install a new keyless 
vehicle module as 
required. Clear DTC and 
retest
U3000-
46
Control Module 
- Calibration
/parameter 
memory failure
Keyless vehicle 
module EEPROM 
memory failure
First record, then clear 
the DTC. Using the 
manufacturer approved 
diagnostic system, 
perform an on demand 
self-test and monitor the 
test output to check if 
DTC reoccurs
If fault persists, check 
and install a new keyless 
vehicle module as 
required. Clear DTC and 
retest
U3000-
49
Control Module 
- Internal 
electronic 
failure
Internal electronic 
failure
Refer to the electrical 
circuit diagrams and 
check the power and 
ground circuits to the 
module. Clear DTC and 
retest
If fault persists, check 
and install a new keyless 
vehicle module as 
required. Clear DTC and 
retest
U3000-
63
Control Module 
- Circuit
/Component 
Protection 
Time-Out
Keyless vehicle 
module internal 
electronic failure
Check for other keyless 
vehicle module output 
circuit short circuit to 
ground/power DTCs and 
perform the relevant 
corrective action(s)
First record, then clear 
the DTC. Using the 
manufacturer approved 
diagnostic system, 
perform an on demand

self-test and monitor the 
test output to check if 
DTC reoccurs
If fault persists, check 
and install a new keyless 
vehicle module as 
required. Clear DTC and 
retest
U3000-
95
Control Module 
- Incorrect 
assembly
Incorrect keyless 
vehicle module 
installed
Car configuration 
parameter 
indicates the 
vehicle should 
support full 
passive entry
/passive start 
functionality, but 
installed module 
supports passive 
start only
Clear DTC and retest. If 
fault persists, check and 
install the correct keyless 
vehicles module as 
required. Clear DTC and 
retest
U3002-
81
Vehicle 
Identification 
Number - 
Invalid serial 
data received
Invalid vehicle 
identification 
number
Clear DTC and retest. If 
fault persists, configure 
the car configuration file 
using the manufacturer 
approved diagnostic 
system

2015. 0 F-TYPE (X152), 501-02
FRONT END BODY PANELS
SPECIFICATIONS
Torque Specifications
DESCRIPTION
NM
LB-FT
LB-IN
Air deflector nuts and rear bolts
4.

36
Air deflector front bolts
9

80
Fender upper trim screws
3.

33
Fender main bolts
9

80
Front strut brace bolts
55

487
Engine harness multi plug bolt
6

53
Multi plug bracket bolts
4

35
Air conditioning pipe bracket bolt
4

35
Coolant hose bracket bolt
7

62
RH secondary bulkhead panel bolt
7

62

2015. 0 F-TYPE (X152), 501-02
FRONT END BODY PANELS
AIR DEFLECTOR (G1580212)
REMOVAL AND INSTALLATION
76. 11.41
ENGINE 
UNDERTRAY 
- RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
76. 11.41
ENGINE 
UNDERTRAY 
- RENEW
PROJECT
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
WARNING:
Make sure to support the vehicle with axle stands.
Raise and support the vehicle.
1.
2.

Torque:
Nuts and rear bolts  4.1 Nm
Front bolts  9 Nm
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-02
FRONT END BODY PANELS
COWL PANEL (G1580213)
REMOVAL AND INSTALLATION
76. 10.01
PLENUM 
CHAMBER 
FINISHER 
- RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
CAUTIONS:
Make sure the glass laminate is not damaged during remove 
and installation.
Always protect paintwork and glass when removing exterior 
components.
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (501-16 Wipers and 
Windshield Wiper Pivot Arm
Washers, Removal and Installation).
1.
2.

3.
4.

NOTE:
Make sure that all openings are sealed. Use new blanking 
caps.
5.

2015. 0 F-TYPE (X152), 501-16
WIPERS AND WASHERS
WINDSHIELD WIPER PIVOT ARM (G1580258)
INSTALLATION
CAUTION:
Do not use excessive force to install the component.
1.
To install, reverse the removal procedure.
2.

REMOVAL AND INSTALLATION
84. 15.01
WIPER 
ARM - 
VEHICLE 
SET - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
CAUTION:
Always protect paintwork and glass when removing exterior 
components.
REMOVAL
1.
2.

NOTE:
LH illustration shown, RH is similar.

NOTE:
3.
LH illustration shown, RH is similar.
Release the 2 clips.

INSTALLATION
Install the wiper blades.
1.

CAUTION:
Align the wiper blades onto the centre of the windshield 
circle mark.
NOTE:
2.
After the wiper pivot arm nuts have been tightened to 
the correct torque value, lift the wiper pivot arm from 
the windshield and return to the windshield. Make sure 
that wiper blades are not positioned below any point of 
the windshield circle mark.
Do not fully tighten at this stage.
3.

Torque: 23 Nm
4.

2015. 0 F-TYPE (X152), 501-02
FRONT END BODY PANELS
FENDER SPLASH SHIELD (G1580215)
REMOVAL AND INSTALLATION
76. 10.90
FRONT 
WHEEL 
ARCH 
LINER - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
76. 10.90
FRONT 
WHEEL 
ARCH 
LINER - 
RENEW
SVR
0.
USED 
WITHINS
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
LH illustration shown, RH is similar.
WARNING:
Make sure to support the vehicle with axle stands.
Raise and support the vehicle.
1.

Refer to: 
 (204-04 Wheels and Tires, Removal 
Wheel and Tire
and Installation).
2.
3.
4.
5.

2015. 0 F-TYPE (X152), 204-04
WHEELS AND TIRES
WHEEL AND TIRE (G1580071)
INSTALLATION
To install, reverse the removal procedure.
1.

REMOVAL AND INSTALLATION
74. 20.05
WHEEL 
AND TIRE 
ASSEMBLY 
- REMOVE 
AND 
INSTALL
ALL 
DERIVATIVES
0.
USED 
WITHINS
REMOVAL
All vehicles
WARNING:
Make sure to support the vehicle with axle stands.
Raise and support the vehicle.
1.
CAUTION:
Using power tools may result in damage to the wheel 
nuts. Make sure the wheel nuts are released using hand 
tools only.
2.

Remove the wheel and tire.
Vehicles with carbon ceramic brakes
1.

Remove 2 opposing wheel nuts.
NOTE:
2.
On vehicles fitted with carbon ceramic brake discs, 
remove two opposing wheel nuts and install the wheel 
guide pins supplied with the vehicle tool kit.

Install the guide pins.
Remove the remaining wheel nuts and slide the wheel and tire 
over the guide tools.
3.

Remove the road wheel.
4.
INSTALLATION
Vehicles with carbon ceramic brakes
CAUTIONS:
Apply a small amount of grease to the hub and wheel 
mating surfaces before installation. Make sure the 
grease does not come into contact with the vehicles 
braking components and the wheel stud threads. 
Failure to follow these instructions may result in 
personal injury.
Using power tools may result in damage to the wheel 
nuts. Make sure the wheel nuts are installed using 
hand tools only.
1.

Install the wheel and tire over the guide pins and fit 3 wheel 
nuts.
Remove the guide pins.
2.
3.

CAUTION:
Using power tools may result in damage to the wheel 
nuts. Make sure the wheel nuts are installed using hand 
tools only.
Install the 2 remaining wheel nuts.
Tighten the wheel nuts in the indicated sequence.
Torque:
Stage 1  15 Nm
4.

Stage 2  70 Nm
Stage 3  125 Nm
All vehicles
CAUTION:
Using power tools may result in damage to the wheel 
nuts. Make sure the wheel nuts are installed using hand 
tools only.
Install the wheel and tire.
1.
2.

Tighten the wheel nuts in the indicated sequence.
Torque:
Stage 1  15 Nm
Stage 2  70 Nm
Stage 3  125 Nm

2015. 0 F-TYPE (X152), 501-02
FRONT END BODY PANELS
FENDER (G1580214)
REMOVAL AND INSTALLATION
77. 25.01
FRONT 
FENDER - 
RENEW
ALL 
DERIVATIVES
1
USED 
WITHINS
77. 25.01
FRONT 
FENDER - 
RENEW
SVR
1
USED 
WITHINS
CAUTION:
Always protect paintwork and glass when removing exterior 
components.
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
WARNING:
Make sure to support the vehicle with axle stands.
Raise and support the vehicle.
1.

Refer to: 
 (501-08 Exterior Trim and 
Rocker Panel Moulding
Ornamentation, Removal and Installation).
2.

Torque: 3.7 Nm
3.

Torque: 9 Nm
4.
5.

Torque: 9 Nm
NOTES:
6.
Note the fitted position of the fender before removal.
Do not disassemble further if the component is 
removed for access only.

Torque: 9 Nm
7.

INSTALLATION
1.

2015. 0 F-TYPE (X152), 501-08
EXTERIOR TRIM AND ORNAMENTATION
ROCKER PANEL MOULDING (G1584132)
To install, reverse the removal procedure.
2.
REMOVAL AND INSTALLATION

76. 11.56
ROCKER 
PANEL - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
Some components shown removed for clarity.
Some variation in the illustrations may occur, but the essential 
information is always correct.
LH shown, RH similar.
WARNING:
Do not work on or under a vehicle supported only by a 
jack. Always support the vehicle on safety stands.
Raise and support the vehicle.
1.
Refer to: 
 (501-05 Interior Trim and 
Scuff Plate Trim Panel
Ornamentation, Removal and Installation).
2.
CAUTION:
Do not use excessive force to install the component.
3.

CAUTION:
Do not use excessive force to install the component.
4.
5.

CAUTION:
Make sure to protect the paintwork
6.
7.

CAUTION:
Do not use excessive force to install the component.
8.
9.

CAUTION:
Do not use excessive force to install the component.
CAUTION:
Make sure to protect the paintwork
10.

CAUTION:
Do not use excessive force to install the component.
11.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-02
FRONT END BODY PANELS
HOOD (G1580216)
REMOVAL AND INSTALLATION
76. 16.01
BONNET 
(ENGINE 
COMPARTMENT 
COVER) - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
REMOVAL
1.
2.

3.
4.

5.
INSTALLATION
1.

2.
3.

CAUTION:
Only tighten the bolts finger-tight at this stage.
NOTE:
4.
Do not tighten at this stage.

5.
Lower the hood and check for alignment.
Refer to: 
 (501-26 Body Repairs - 
Body and Frame
Vehicle Specific Information and Tolerance Checks, 
Description and Operation).
1.
Adjust as necessary.
1.
6.

Torque: 25 Nm
7.

8.
Install the special tool.
9.

10.

Gently close the hood so that the pedestrian 
protection hood stops are aligned to the actuators.
Open the hood.
Remove the special tool.
1.
11.

Torque: 8 Nm
12.

2015. 0 F-TYPE (X152), 501-26
BODY REPAIRS - VEHICLE SPECIFIC 
INFORMATION AND TOLERANCE CHECKS
DESCRIPTION AND OPERATION

Front end dimensions
ITEM
FROM
TO
DIMENSION
A
PAS reservoir bracket fixing 
hole
Fuse box bracket fixing 
hole
993.
B
Fuse box bracket fixing hole
Left support brace fixing 
hole
1008.
C
PAS reservoir bracket fixing 
hole
Right support brace fixing 
hole
1019.
D
Fuse box bracket fixing hole
Left fender fixing hole
1581.
E
PAS reservoir bracket fixing 
hole
Right fender fixing hole
1586.
F
Left fender fixing hole
Right fender fixing hole
1718.

ITEM
FROM
TO
DIMENSION
A
Left windshield aperture 
tooling hole
Right windshield aperture 
tooling hole
1139.
B
Front left bumper armature 
upper fixing hole
Front right bumper 
armature upper fixing hole
715.
Body side dimensions

ITEM
FROM
TO
DIMENSION
A
Top door hinge, rearward fixing hole
Tooling hole
1100.
B
Bottom door hinge, rearward fixing hole
Tooling hole
1062.

ITEM
FROM
TO
DIMENSION
A
Instrument panel carrier 
top left fixing hole
Instrument panel carrier top 
right fixing hole
1139.
B
Instrument panel carrier 
bottom left fixing hole
Instrument panel carrier 
bottom right fixing hole
715.

ITEM
FROM
TO
DIMENSION
A
Left seatbelt guide fixing 
hole
Right seatbelt guide fixing 
hole
1010.
Underbody dimensions

ITEM
FROM
TO
DIMENSION
A
Rear left sub-frame rear 
fixing hole
Rear right sub-frame rear 
fixing hole
1015.
B
Rear left sub-frame front 
fixing hole
Rear right sub-frame front 
fixing hole
908.
C
Left underbody brace fixing 
hole
Right underbody brace 
fixing hole
829.
D
Front left sub-frame rear 
fixing hole
Front right sub-frame rear 
fixing hole
832.
E
Front left sub-frame front 
fixing hole
Front right sub-frame front 
fixing hole
839.
F
Front left sub-frame front 
fixing hole
Front left sub-frame rear 
fixing hole
516.
G
Front left sub-frame front 
fixing hole
Left underbody brace fixing 
hole
1013.
H
Front left sub-frame front 
fixing hole
Rear left sub-frame front 
fixing hole
2768.
I
Front left sub-frame front 
Rear left sub-frame rear 
3344.

fixing hole
fixing hole
ITEM
FROM
TO
DIMENSION
A
Rear left sub-frame rear 
fixing hole
Rear right sub-frame front 
fixing hole
1137.
B
Front left sub-frame front 
fixing hole
Right underbody brace 
fixing hole
1329.
C
Front left sub-frame front 
fixing hole
Front right sub-frame rear 
fixing hole
982.
Rear end body dimensions

ITEM
FROM
TO
DIMENSION
A
Rear left wiring harness 
fixing hole
Rear right wiring harness 
fixing hole
1037.
B
Rear left bumper armature 
lower fixing hole
Rear right bumper armature 
lower fixing hole
1023.

ITEM
FROM
TO
DIMENSION
A
Rear left shock absorber 
mounting, rear fixing
Rear right shock absorber 
mounting, rear fixing
982.
B
Rear left earth stud
Rear right earth stud
943.
Rear end body dimensions - Coupe

ITEM
FROM
TO
DIMENSION
A
Rear left shock absorber 
mounting, rear fixing
Rear right shock absorber 
mounting, rear fixing
982.
B
Rear left earth stud
Rear right earth stud
943.
BODY SHELL REPLACEMENT TIMES

NOTES:
VEHICLE VARIANT
TIME
F-Type folding top
68.
F-Type coupe
73.
Gap and profile information - Front end
DETAIL
GAP
PROFILE
The following information shows the total time taken to 
replace a vehicles body shell. The time has been calculated 
using a base model variant. For example a two wheel drive 
vehicle without a roof opening panel.
The times include all mechanical, electrical and trim (MET) 
items but do not include wheel alignment or paint times.
GAP AND PROFILE DIMENSIONS

A
 - Hood to front bumper
3. 0 0.9
- 1.0 1.5

A1
 - Hood to front bumper
3. 0 1.3
0. 5 1.5

B
 - Hood to headlamp
3. 0 1.1
0 1.6

B1
 - Hood to fender
3. 0 0.8
0 1.6

C
 - Headlamp to front bumper
1. 0 0.7
0 1.5

D
 - Hood to front bumper
3. 0 1.0
- 1.0 1.5
Gap and profile information - Side and rear end
DETAIL
GAP
PROFILE

A
 - Hood to fender
4. 0 1.1
0

A1
 - Hood to fender
4. 0 1.5
0. 5 1.0

B
 - Door to fender
3. 5 +1 
- 0.5
- 1 1

C
 - Door to rear quarter
3. 5 1.1
0

D
 - Rear quarter to rear bumper
0 0.7
0 0.6

E
 - Luggage compartment lid to rear quarter
3. 5 1.1
- 1 1.1

F
 - Rear lamp to rear quarter
1 0.6
- 3.5 1.5

G
 - Rear lamp to rear bumper
1. 25 1.
25
- 5.7 1.3

H
 - Deployable spoiler to luggage compartment lid
2. 5 0.5
0 +0.25 
- 0.75

I
 - Deployable spoiler to luggage compartment lid
2. 5 0.5
0 +0.25 
- 0.75

J
 - Folding top to folding top seal (folding top closed)
0
N/A

J1
 - Folding top to folding top seal (folding top open - 
not illustrated)
8 5.3
5 1.9

K
 - Luggage compartment lid to rear bumper
6 2
N/A
Gap and profile information - Side and rear end - Coupe
DETAIL
GAP
PROFILE

A
 - Hood to fender
4. 0 1.1
0

A1
 - Hood to fender
4. 0 1.5
0. 5 1.0

B
 - Door to fender
3. 5 +1 -0.5
- 1 1

C
 - Door to rear quarter panel
3. 5 1.1
0

D
 - Rear quarter to rear bumper
0 0.7
0 0.6

E
 - Luggage compartment lid to rear quarter
3. 5 1.0
- 3.7 1.2

F
 - Rear lamp to rear quarter panel
1 0.6
- 3.5 1.4

G
 - Rear lamp to rear bumper
1. 25 1.25
- 5.7 1.3

H
 -Luggage compartment lid to rear bumper
6 
N/A

I
 - Deployable spoiler to luggage compartment lid
3 0.9
2 + 0.7

J
 -Cladding to roof panel
5 + 1.7 / -0.7
- 1  1.4

J1
 - Cladding to luggage compartment lid
0 
N/A

2015. 0 F-TYPE (X152), 501-02
FRONT END BODY PANELS
RADIATOR SPLASH SHIELD (G1580217)
REMOVAL AND INSTALLATION
76. 22.90
UNDERTRAY 
- RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
76. 22.90
UNDERTRAY 
- RENEW
SVR
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
WARNING:
Make sure to support the vehicle with axle stands.
Raise and support the vehicle.
1.
NOTE:
2.
Repeat the procedure for the other side.

NOTE:
3.
Repeat the procedure for the other side.

4.
5.

NOTES:
Note the fitted position of the washers.
Do not disassemble further if the component is 
removed for access only.
6.
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-02
FRONT END BODY PANELS
SECONDARY BULKHEAD CENTER PANEL (G1580218)
REMOVAL AND INSTALLATION
76. 11.35
ENGINE 
COMPARTMENT 
REAR COVER - 
RENEW
ALL 
DERIVATIVES
1.
USED 
WITHINS
76. 11.35
ENGINE 
COMPARTMENT 
REAR COVER - 
RENEW
MANUAL 
TRANSMISSION
1.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (501-02 Front End Body Panels, Removal 
Cowl Panel
and Installation).
1.
Refer to: 
 (501-05 Interior Trim and 
Engine Cover
Ornamentation, Removal and Installation).
2.
NOTE:
3.
The step must be carried out on both sides.

NOTE:

Torque: 55 Nm
4.
The step must be carried out on both sides.
5.

6.
NOTE:
7.
Do not disassemble further if the component is removed 
for access only.

2015. 0 F-TYPE (X152), 501-02
FRONT END BODY PANELS
INSTALLATION
To install, reverse the removal procedure.
1.

COWL PANEL (G1580213)
REMOVAL AND INSTALLATION
76. 10.01
PLENUM 
CHAMBER 
FINISHER 
- RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
CAUTIONS:
Make sure the glass laminate is not damaged during remove 
and installation.
Always protect paintwork and glass when removing exterior 
components.
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (501-16 Wipers and 
Windshield Wiper Pivot Arm
Washers, Removal and Installation).
1.
2.

3.

NOTE:
4.
Make sure that all openings are sealed. Use new blanking 
caps.

5.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
ENGINE COVER (G1580231)
INSTALLATION
CAUTION:
Do not use excessive force to install the component.
1.
To install, reverse the removal procedure.
2.

REMOVAL AND INSTALLATION
12. 29.93
ENGINE 
COVER - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
REMOVAL
NOTE:
1.
Some variation in the illustrations may occur, but the 
essential information is always correct.
INSTALLATION

To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-02
FRONT END BODY PANELS
SECONDARY BULKHEAD PANEL LH (G1580219)
REMOVAL AND INSTALLATION
76. 11.28
ENGINE 
COMPARTMENT 
LEFT HAND 
COVER - 
RENEW
ALL 
DERIVATIVES
1.
USED 
WITHINS
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
LHD illustration shown, RHD is similar.
Refer to: 
 (501-02 Front End 
Secondary Bulkhead Center Panel
Body Panels, Removal and Installation).
1.
2.

Torque: 6 Nm
3.

4.

Torque: 4 Nm

Torque: 4 Nm
5.

WARNING:
Care must be taken not to damage the air conditioning (A
/C) pipe.
6.
NOTE:
7.
Do not disassemble further if the component is removed 
for access only.

2015. 0 F-TYPE (X152), 501-02
FRONT END BODY PANELS
SECONDARY BULKHEAD CENTER PANEL (G1580218)
INSTALLATION
To install, reverse the removal procedure.
1.

REMOVAL AND INSTALLATION
76. 11.35
ENGINE 
COMPARTMENT 
REAR COVER - 
RENEW
ALL 
DERIVATIVES
1.
USED 
WITHINS
76. 11.35
ENGINE 
COMPARTMENT 
REAR COVER - 
RENEW
MANUAL 
TRANSMISSION
1.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (501-02 Front End Body Panels, Removal 
Cowl Panel
and Installation).
1.
Refer to: 
 (501-05 Interior Trim and 
Engine Cover
Ornamentation, Removal and Installation).
2.
NOTE:
3.
The step must be carried out on both sides.

NOTE:
4.
The step must be carried out on both sides.

Torque: 55 Nm
5.

6.

7.

NOTE:
Do not disassemble further if the component is removed 
for access only.
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-02
FRONT END BODY PANELS
SECONDARY BULKHEAD PANEL RH (G1580220)
REMOVAL AND INSTALLATION
76. 11.30
ENGINE 
COMPARTMENT 
RIGHT HAND 
COVER - 
RENEW
ALL 
DERIVATIVES
1.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (303-03C Engine Cooling - 
Coolant Expansion Tank
V8 S/C 5.0L Petrol, Removal and Installation).
1.
Refer to: 
 (501-02 Front End 
Secondary Bulkhead Center Panel
Body Panels, Removal and Installation).
2.
NOTE:
3.
Right hand drive only.

Torque: 7 Nm
4.
5.

Torque: 7 Nm
NOTE:
6.
Do not disassemble further if the component is removed 
for access only.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 303-03
ENGINE COOLING - V8 S/C 5.0L PETROL
COOLANT EXPANSION TANK (G1580407)
REMOVAL AND INSTALLATION
26. 15.01
EXPANSION 
TANK - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
WARNING:
Since injury such as scalding could be caused by escaping steam 
or coolant, do not remove the filler cap from the coolant 
expansion tank while the system is hot.
CAUTIONS:
Anti-freeze concentration must be maintained at 50.
Correct installation of the coolant expansion tank cap can be 
obtained by tightening the cap until 3 audible clicks are heard.
REMOVAL

NOTES:
Some variation in the illustrations may occur, but the essential 
information is always correct.
Removal steps in this procedure may contain installation 
details.
WARNING:
Release the cooling system pressure by slowly turning 
the coolant expansion tank cap a quarter of a turn. 
Cover the expansion tank cap with a thick cloth to 
prevent the possibility of scalding. Failure to follow this 
instruction may result in personal injury.
1.
2.

Torque: 9 Nm
3.

CAUTION:
Be prepared to collect escaping fluids.
4.
5.
6.

INSTALLATION
To install, reverse the removal procedure.
1.
Check and top-up the coolant.
2.

2015. 0 F-TYPE (X152), 501-02
FRONT END BODY PANELS
SECONDARY BULKHEAD CENTER PANEL (G1580218)
REMOVAL AND INSTALLATION
76. 11.35
ENGINE 
COMPARTMENT 
REAR COVER - 
RENEW
ALL 
DERIVATIVES
1.
USED 
WITHINS
76. 11.35
ENGINE 
COMPARTMENT 
REAR COVER - 
RENEW
MANUAL 
TRANSMISSION
1.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (501-02 Front End Body Panels, Removal 
Cowl Panel
and Installation).
1.
Refer to: 
 (501-05 Interior Trim and 
Engine Cover
Ornamentation, Removal and Installation).
2.
NOTE:
3.
The step must be carried out on both sides.

NOTE:

Torque: 55 Nm
4.
The step must be carried out on both sides.

5.

6.
NOTE:
7.
Do not disassemble further if the component is removed 
for access only.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-03
BODY CLOSURES
DOOR (G1580228)
REMOVAL AND INSTALLATION
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
Some components shown removed for clarity.
Some variation in the illustrations may occur, but the essential 
information is always correct.
RH shown, LH similar.
Refer to: 
 (501-09 Rear View Mirrors, Removal 
Exterior Mirror
and Installation).
1.
Refer to: 
 (501-03 Body Closures, 
Front Door Check Arm
Removal and Installation).
2.
Refer to: 
 (501-11 Glass, Frames and 
Door Window Regulator
Mechanisms, Removal and Installation).
3.
4.

CAUTION:
This step requires the aid of another technician

Torque: 13.5 Nm
5.

NOTE:
Do not disassemble further if removed for access only.
Torque:
Nuts  8 Nm
Bolts  7 Nm
6.
7.

CAUTION:
Do not use excessive force to install the component.
8.
CAUTION:
Do not use excessive force to install the component.
9.

10.
CAUTION:
Do not use excessive force to install the component.
11.
12.

CAUTION:
Note the fitted position of the component prior to 
removal.
13.

14.

NOTE:

Torque: 30 Nm
Do not disassemble further if removed for access only.
INSTALLATION
To install, reverse the removal procedure.
1.
Refer to: 
 (501-26 Body Repairs - Vehicle 
Body and Frame
Specific Information and Tolerance Checks, Description and 
Operation).
2.

2015. 0 F-TYPE (X152), 501-09
REAR VIEW MIRRORS
EXTERIOR MIRROR (G1580263)
REMOVAL AND INSTALLATION
76. 10.52
EXTERIOR 
MIRROR - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (501-05 Interior Trim and 
Front Door Trim Panel
Ornamentation, Removal and Installation).
1.
2.

Torque: 9 Nm
3.
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-11
GLASS, FRAMES AND MECHANISMS
DOOR WINDOW REGULATOR (G1585171)
REMOVAL AND INSTALLATION
76. 31.45
FRONT 
DOOR 
GLASS 
REGULATOR 
- RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (501-11 Glass, Frames and 
Door Window Glass
Mechanisms, Removal and Installation).
1.
2.

3.

Torque:
M6  8 Nm
Screws  4.1 Nm
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-03
BODY CLOSURES
FRONT DOOR CHECK ARM (G1584738)
REMOVAL AND INSTALLATION
76. 28.44
FRONT 
DOOR 
CHECK 
ARM - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
Some components shown removed for clarity.
Some variation in the illustrations may occur, but the essential 
information is always correct.
Refer to: 
 (415-01 Information and 
Front Door Speaker
Entertainment System, Removal and Installation).
1.
2.

Torque: 12 Nm
3.
4.

Torque: 12 Nm
5.
6.

2015. 0 F-TYPE (X152), 501-26
BODY REPAIRS - VEHICLE SPECIFIC 
INFORMATION AND TOLERANCE CHECKS
INSTALLATION
To install, reverse the removal procedure.
1.
DESCRIPTION AND OPERATION
Front end dimensions

ITEM
FROM
TO
DIMENSION
A
PAS reservoir bracket fixing 
hole
Fuse box bracket fixing 
hole
993.
B
Fuse box bracket fixing hole
Left support brace fixing 
hole
1008.
C
PAS reservoir bracket fixing 
hole
Right support brace fixing 
hole
1019.
D
Fuse box bracket fixing hole
Left fender fixing hole
1581.
E
PAS reservoir bracket fixing 
hole
Right fender fixing hole
1586.
F
Left fender fixing hole
Right fender fixing hole
1718.

ITEM
FROM
TO
DIMENSION
A
Left windshield aperture 
tooling hole
Right windshield aperture 
tooling hole
1139.
B
Front left bumper armature 
upper fixing hole
Front right bumper 
armature upper fixing hole
715.
Body side dimensions

ITEM
FROM
TO
DIMENSION
A
Top door hinge, rearward fixing hole
Tooling hole
1100.
B
Bottom door hinge, rearward fixing hole
Tooling hole
1062.

ITEM
FROM
TO
DIMENSION
A
Instrument panel carrier 
top left fixing hole
Instrument panel carrier top 
right fixing hole
1139.
B
Instrument panel carrier 
bottom left fixing hole
Instrument panel carrier 
bottom right fixing hole
715.

ITEM
FROM
TO
DIMENSION
A
Left seatbelt guide fixing 
hole
Right seatbelt guide fixing 
hole
1010.
Underbody dimensions

ITEM
FROM
TO
DIMENSION
A
Rear left sub-frame rear 
fixing hole
Rear right sub-frame rear 
fixing hole
1015.
B
Rear left sub-frame front 
fixing hole
Rear right sub-frame front 
fixing hole
908.
C
Left underbody brace fixing 
hole
Right underbody brace 
fixing hole
829.
D
Front left sub-frame rear 
fixing hole
Front right sub-frame rear 
fixing hole
832.
E
Front left sub-frame front 
fixing hole
Front right sub-frame front 
fixing hole
839.
F
Front left sub-frame front 
fixing hole
Front left sub-frame rear 
fixing hole
516.
G
Front left sub-frame front 
fixing hole
Left underbody brace fixing 
hole
1013.
H
Front left sub-frame front 
Rear left sub-frame front 
2768.

fixing hole
fixing hole
I
Front left sub-frame front 
fixing hole
Rear left sub-frame rear 
fixing hole
3344.
ITEM
FROM
TO
DIMENSION
A
Rear left sub-frame rear 
fixing hole
Rear right sub-frame front 
fixing hole
1137.
B
Front left sub-frame front 
fixing hole
Right underbody brace 
fixing hole
1329.
C
Front left sub-frame front 
fixing hole
Front right sub-frame rear 
fixing hole
982.
Rear end body dimensions

ITEM
FROM
TO
DIMENSION
A
Rear left wiring harness 
fixing hole
Rear right wiring harness 
fixing hole
1037.
B
Rear left bumper armature 
lower fixing hole
Rear right bumper armature 
lower fixing hole
1023.

ITEM
FROM
TO
DIMENSION
A
Rear left shock absorber 
mounting, rear fixing
Rear right shock absorber 
mounting, rear fixing
982.
B
Rear left earth stud
Rear right earth stud
943.
Rear end body dimensions - Coupe

ITEM
FROM
TO
DIMENSION
A
Rear left shock absorber 
mounting, rear fixing
Rear right shock absorber 
mounting, rear fixing
982.
B
Rear left earth stud
Rear right earth stud
943.
BODY SHELL REPLACEMENT TIMES

NOTES:
VEHICLE VARIANT
TIME
F-Type folding top
68.
F-Type coupe
73.
Gap and profile information - Front end
DETAIL
GAP
PROFILE
The following information shows the total time taken to 
replace a vehicles body shell. The time has been calculated 
using a base model variant. For example a two wheel drive 
vehicle without a roof opening panel.
The times include all mechanical, electrical and trim (MET) 
items but do not include wheel alignment or paint times.
GAP AND PROFILE DIMENSIONS

A
 - Hood to front bumper
3. 0 0.9
- 1.0 1.5

A1
 - Hood to front bumper
3. 0 1.3
0. 5 1.5

B
 - Hood to headlamp
3. 0 1.1
0 1.6

B1
 - Hood to fender
3. 0 0.8
0 1.6

C
 - Headlamp to front bumper
1. 0 0.7
0 1.5

D
 - Hood to front bumper
3. 0 1.0
- 1.0 1.5
Gap and profile information - Side and rear end
DETAIL
GAP
PROFILE

A
 - Hood to fender
4. 0 1.1
0

A1
 - Hood to fender
4. 0 1.5
0. 5 1.0

B
 - Door to fender
3. 5 +1 
- 0.5
- 1 1

C
 - Door to rear quarter
3. 5 1.1
0

D
 - Rear quarter to rear bumper
0 0.7
0 0.6

E
 - Luggage compartment lid to rear quarter
3. 5 1.1
- 1 1.1

F
 - Rear lamp to rear quarter
1 0.6
- 3.5 1.5

G
 - Rear lamp to rear bumper
1. 25 1.
25
- 5.7 1.3

H
 - Deployable spoiler to luggage compartment lid
2. 5 0.5
0 +0.25 
- 0.75

I
 - Deployable spoiler to luggage compartment lid
2. 5 0.5
0 +0.25 
- 0.75

J
 - Folding top to folding top seal (folding top closed)
0
N/A

J1
 - Folding top to folding top seal (folding top open - 
not illustrated)
8 5.3
5 1.9

K
 - Luggage compartment lid to rear bumper
6 2
N/A
Gap and profile information - Side and rear end - Coupe
DETAIL
GAP
PROFILE

A
 - Hood to fender
4. 0 1.1
0

A1
 - Hood to fender
4. 0 1.5
0. 5 1.0

B
 - Door to fender
3. 5 +1 -0.5
- 1 1

C
 - Door to rear quarter panel
3. 5 1.1
0

D
 - Rear quarter to rear bumper
0 0.7
0 0.6

E
 - Luggage compartment lid to rear quarter
3. 5 1.0
- 3.7 1.2

F
 - Rear lamp to rear quarter panel
1 0.6
- 3.5 1.4

G
 - Rear lamp to rear bumper
1. 25 1.25
- 5.7 1.3

H
 -Luggage compartment lid to rear bumper
6 
N/A

I
 - Deployable spoiler to luggage compartment lid
3 0.9
2 + 0.7

J
 -Cladding to roof panel
5 + 1.7 / -0.7
- 1  1.4

J1
 - Cladding to luggage compartment lid
0 
N/A

2015. 0 F-TYPE (X152), 501-03
BODY CLOSURES
FRONT DOOR CHECK ARM (G1584738)
REMOVAL AND INSTALLATION
76. 28.44
FRONT 
DOOR 
CHECK 
ARM - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
Some components shown removed for clarity.
Some variation in the illustrations may occur, but the essential 
information is always correct.
Refer to: 
 (415-01 Information and 
Front Door Speaker
Entertainment System, Removal and Installation).
1.
2.

Torque: 12 Nm
3.
4.

Torque: 12 Nm
5.
6.

2015. 0 F-TYPE (X152), 415-01
INFORMATION AND ENTERTAINMENT SYSTEM
FRONT DOOR SPEAKER (G1584097)
INSTALLATION
To install, reverse the removal procedure.
1.
REMOVAL AND INSTALLATION

86. 50.13
FRONT 
DOOR 
SPEAKER 
- RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (501-05 Interior Trim and 
Front Door Trim Panel
Ornamentation, Removal and Installation).
1.
2.
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-03
BODY CLOSURES
FUEL FILLER DOOR ASSEMBLY (G1585185)
REMOVAL AND INSTALLATION
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: Petrol and Petrol-Ethanol Fuel Systems Health and 
 (100-00 General Information, Description 
Safety Precautions
and Operation).
1.
WARNING:
Make sure to support the vehicle with axle stands.
Raise and support the vehicle.
2.
Refer to: 
 (204-04 Wheels and Tires, Removal 
Wheel and Tire
and Installation).
3.
4.

NOTE:
5.
Some variation in the illustrations may occur, but the 
essential information is always correct.

6.
7.
8.

CAUTION:
Protect the surrounding paintwork to avoid damage.
9.
CAUTION:
Protect the surrounding paintwork to avoid damage.
NOTE:
10.
Do not disassemble further if the component is removed 
for access only.

2015. 0 F-TYPE (X152), 204-04
WHEELS AND TIRES
WHEEL AND TIRE (G1580071)
INSTALLATION
To install, reverse the removal procedure.
1.
REMOVAL AND INSTALLATION
74. 20.05
WHEEL 
AND TIRE 
ASSEMBLY 
- REMOVE 
AND 
INSTALL
ALL 
DERIVATIVES
0.
USED 
WITHINS

REMOVAL
All vehicles
WARNING:
Make sure to support the vehicle with axle stands.
Raise and support the vehicle.
1.
CAUTION:
Using power tools may result in damage to the wheel 
nuts. Make sure the wheel nuts are released using hand 
tools only.
Remove the wheel and tire.
2.
Vehicles with carbon ceramic brakes

Remove 2 opposing wheel nuts.
1.
NOTE:
Install the guide pins.
2.
On vehicles fitted with carbon ceramic brake discs, 
remove two opposing wheel nuts and install the wheel 
guide pins supplied with the vehicle tool kit.
3.

Remove the remaining wheel nuts and slide the wheel and tire 
over the guide tools.
Remove the road wheel.
4.
INSTALLATION
Vehicles with carbon ceramic brakes

CAUTIONS:
Apply a small amount of grease to the hub and wheel 
mating surfaces before installation. Make sure the 
grease does not come into contact with the vehicles 
braking components and the wheel stud threads. 
Failure to follow these instructions may result in 
personal injury.
Using power tools may result in damage to the wheel 
nuts. Make sure the wheel nuts are installed using 
hand tools only.
Install the wheel and tire over the guide pins and fit 3 wheel 
nuts.
1.
2.

Remove the guide pins.
CAUTION:
Using power tools may result in damage to the wheel 
nuts. Make sure the wheel nuts are installed using hand 
tools only.
3.

Install the 2 remaining wheel nuts.
Tighten the wheel nuts in the indicated sequence.
Torque:
Stage 1  15 Nm
4.

Stage 2  70 Nm
Stage 3  125 Nm
All vehicles
CAUTION:
Using power tools may result in damage to the wheel 
nuts. Make sure the wheel nuts are installed using hand 
tools only.
Install the wheel and tire.
1.
2.

2015. 0 F-TYPE (X152), 100-00
GENERAL INFORMATION
Tighten the wheel nuts in the indicated sequence.
Torque:
Stage 1  15 Nm
Stage 2  70 Nm
Stage 3  125 Nm
DESCRIPTION AND OPERATION

WARNINGS:
Fuel may not give adequate warning before toxic or harmful 
effects arise.
Exposure to fuel can be harmful and can cause severe health 
damage or death.
Extreme care must be exercised when handling hot fluids. 
Always wash off spilled fluids from affected areas of skin 
immediately.
Highly flammable mixtures are always present and may ignite 
when working on fuel systems. Do not allow naked flames, 
sparks or lighted substances to come near fuel related 
components.
Fuel must not be used as a cleaning agent.
Keep fuel containers tightly closed, out of direct sunlight and 
in a cool area. Keep away from heat sources, ignition sources 
and oxidizing agents.
SKIN CONTACT: Excessive or prolonged skin contact with 
diesel fuel may cause serious skin disorders including skin 
cancer.
SKIN CONTACT: Fuel is mildly irritating to the skin and may 
cause dermatitis due to defatting effect. Remove contaminated 
clothing. Wash affected areas of skin with soap and water. 
Seek medical attention for any persistent skin irritation or 
abnormality. Wash contaminated clothing before reuse.
EYE CONTACT: Fuel is mildly irritating to the eyes. Flush with 
plenty of running water, blinking as often as possible. Do not 
force the eyelid open. Seek medical attention for any 
persistent eye irritation or abnormality.

SWALLOWED: Fuel is moderately toxic and tends to foam on 
vomiting. If drawn into the lungs, inflammation may develop. 
Do not induce vomiting. If spontaneous vomiting occurs place 
the victim in a forward position to reduce the risk of fuel being 
drawn into the lungs. Give nothing by mouth. If breathing but 
unconscious, place in the recovery position. If breathing has 
stopped, apply artificial respiration. Seek immediate medical 
attention.
INHALED: Fuel is toxic to the respiratory and other body 
systems. Exposure may result in various symptoms including 
drowsiness, unconsciousness or severe health damage. Move a 
victim to fresh air. Keep a victim warm and at rest. If 
unconscious, place in the recovery position. If not breathing, 
apply artificial respiration. Give cardiac massage if necessary. 
Seek immediate medical attention.
CAUTIONS:
Fuel injection equipment is manufactured to very precise 
tolerances and fine clearances. It is essential that absolute 
cleanliness is observed when working with these components.
Make sure that the workshop area in which the vehicle is being 
worked on is as clean and as dust free as possible.

2015. 0 F-TYPE (X152), 501-03
BODY CLOSURES
FUEL FILLER DOOR (G1267459)
REMOVAL AND INSTALLATION
76. 10.25
FUEL 
FILLER 
FLAP - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
CAUTION:
Do not align the bowl using the hinge arm.
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
1.

CAUTION:
Protect the surrounding paintwork to avoid damage.
2.
INSTALLATION
CAUTION:
Make sure that the component is correctly located on the 
retaining clip.
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-03
BODY CLOSURES
LUGGAGE COMPARTMENT LID (G1580229)
REMOVAL AND INSTALLATION
76. 19.01
LUGGAGE 
COMPARTMENT 
LID - RENEW
CABRIOLET
1.
USED 
WITHINS
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
Some components shown removed for clarity.
Some variation in the illustrations may occur, but the essential 
information is always correct.
Refer to: 
 (501-08 Exterior Trim and 
Rear Spoiler - Coupe
Ornamentation, Removal and Installation).
1.
Refer to: 
 (414-01 Battery, 
Battery Disconnect and Connect
Mounting and Cables, General Procedures).
2.
Refer to: 
 (501-05 Interior Trim 
Loadspace Trim Panel - Coupe
and Ornamentation, Removal and Installation).
3.
4.

Refer to: 
 (501-08 
Luggage Compartment Lid Moulding
Exterior Trim and Ornamentation, Removal and Installation).

Torque: 7 Nm
5.
6.
7.

Torque: 7 Nm
8.
9.

NOTE:
10.
This step must be carried out on both sides.
NOTE:
11.

NOTE:

Torque: 22 Nm
This step must be carried out on both sides.
Do not disassemble further if removed for access only
12.
CAUTION:
13.

Do not use excessive force to install the component.
NOTE:
This step must be carried out on both sides.
CAUTION:
Note the orientation of the component prior the removal.
14.

Torque: 20 Nm
15.

NOTE:
CAUTION:
Do not use excessive force to install the component.
16.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
LOADSPACE TRIM PANEL - COUPE (G1702347)
Do not disassemble further if removed for access only
INSTALLATION
To install, reverse the removal procedure.
1.
REMOVAL AND INSTALLATION
76. 19.22
LUGGAGE 
COMPARTMENT 
SIDE LINER - 
LEFT HAND - 
RENEW
CABRIOLET
0.
USED 
WITHINS
76. 19.22
LUGGAGE 
COMPARTMENT 
SIDE LINER - 
LEFT HAND - 
RENEW
COUPE
0.
USED 
WITHINS
76. 19.22
LUGGAGE 
COMPARTMENT 
SIDE LINER - 
LEFT HAND - 
RENEW
PROJECT
0.
USED 
WITHINS

NOTES:
REMOVAL
Some variation in the illustrations may occur, but the essential 
information is always correct.
Removal steps in this procedure may contain installation 
details.
1.
2.

CAUTION:
Care must be taken not to damage the component.
3.
4.
5.

6.
7.

Torque: 10 Nm
8.
9.

2015. 0 F-TYPE (X152), 501-08
EXTERIOR TRIM AND ORNAMENTATION
LUGGAGE COMPARTMENT LID MOULDING (G1584131)
INSTALLATION
To install, reverse the removal procedure.
1.

REMOVAL AND INSTALLATION
76. 43.79
LUGGAGE 
COMPARTMENT 
LID UPPER 
TRIM 
FINISHER - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
76. 43.79
LUGGAGE 
COMPARTMENT 
LID UPPER 
TRIM 
FINISHER - 
RENEW
COUPE
1.
USED 
WITHINS
CAUTION:
Make sure to protect the paintwork
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
Some components shown removed for clarity.
Some variation in the illustrations may occur, but the essential 
information is always correct.
NOTE:
1.
Note the position of the wiring harnesses clips to aid 
installation.

CAUTIONS:
2.
INSTALLATION

Make sure that the surface is clean and free of foreign material.
Do not use excessive force to install the component.
Make sure to protect the paintwork
1.
CAUTION:
Make sure that the wiring cables are secured in the 
positions noted in the removal steps.
2.

2015. 0 F-TYPE (X152), 414-01
BATTERY, MOUNTING AND CABLES
BATTERY DISCONNECT AND CONNECT (G1579511)

GENERAL PROCEDURES
86. 15.15
BATTERY 
DISCONNECTION 
AND 
RECONNECTION 
PROCEDURE 




 DO NOT 
ISSUE 



ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTES:
Some variation in the illustrations may occur, but the essential 
information is always correct.
Removal steps in this procedure may contain installation 
details.
If a new battery is installed, the battery monitoring system 
(BMS) must be reset using Jaguar approved diagnostic 
equipment.
Refer to: 
 (414-00 Battery and 
Battery Care Requirements
Charging System - General Information, Description and 
Operation).
1.
Obtain and record the audio unit preset radio frequencies.
2.
3.

4.

5.
CAUTION:
Take extra care not to damage the wiring harnesses.

Torque: 6 Nm
6.
7.

To install, reverse the removal procedure.
8.
NOTE:
Using Jaguar approved diagnostic equipment, reset the 
battery monitoring system (BMS).
9.
This step is only necessary when installing a new battery.
Door Window Motor Initialization
10.
Enter the audio unit preset radio frequencies.
11.
Reset the clock to the correct time.
12.

2015. 0 F-TYPE (X152), 501-08
EXTERIOR TRIM AND ORNAMENTATION
REAR SPOILER - COUPE (G1715738)
Start the engine and allow to idle until the engine reaches 
normal operating temperature.
13.
Switch the engine off.
14.
REMOVAL AND INSTALLATION
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
CABRIOLET
0.
USED 
WITHINS
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
CABRIOLET, 
SVR
0.
USED 
WITHINS
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
COUPE, 
SVR
0.
USED 
WITHINS
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
PROJECT
0.
USED 
WITHINS
76. 19.86
TAILGATE 
SPOILER - 
RENEW
COUPE
0.
USED 
WITHINS

CAUTION:
Make sure to protect the paintwork.
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
1.
NOTE:
2.
Do not refit the two caps until the adjustment of the 
spoiler has been carried out.

NOTE:
3.
Repeat the step for the other side.

4.
5.
CAUTION:
Do not exceed the specified torque value.
6.

Torque: 9 Nm
CAUTION:
Do not exceed the specified torque value.
7.

Torque: 3.5 Nm
NOTE:
8.
Do not disassemble further if the component is removed 
for access only.

Torque: 3.2 Nm
9.
INSTALLATION
To install, reverse the removal procedure.
1.
CAUTION:
Make sure that the surface is clean and free of foreign 
material.
2.

Adjust the rear spoiler by rotating the adjustment studs 
clockwise and counter clockwise as necessary.

2015. 0 F-TYPE (X152), 501-03
BODY CLOSURES
SPECIFICATIONS
Torque Specifications
ITEM
NM
LB-FT
LB-IN
Door check strap to body - bolt
12

106
Door check strap to door - nut
12

106
Door hinge - pin bolt
13.

119
Hood to hinge - nut
25

221
Hood hinge to body - bolt
25

221
Door hinge to body - bolts
30

265
Hinge to door nuts
30

265
Luggage compartment lid to hinge - nuts
26

230
Luggage compartment lid hinge to body - bolts
26

230

2015. 0 F-TYPE (X152), 501-03
BODY CLOSURES
TAILGATE ACTUATOR (G1716273)
REMOVAL AND INSTALLATION
76. 20.22
TAILGATE 
POWER 
STRUT - 
LEFT - 
RENEW
COUPE
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (501-05 Interior 
Liftgate Lower Trim Panel - Coupe
Trim and Ornamentation, Removal and Installation).
1.
2.

WARNING:
This step requires the aid of another technician.
3.
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
LIFTGATE LOWER TRIM PANEL - COUPE (G1702316)
REMOVAL AND INSTALLATION
76. 19.65
TAILGATE 
INTERIOR 
LOWER 
TRIM 
PANEL - 
RENEW
COUPE
0.
USED 
WITHINS
CAUTION:
Care must be taken not to damage the components.
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
1.

Torque: 5.4 Nm
2.
3.

4.
5.

Carefully align and secure the clips.
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-03
BODY CLOSURES
TAILGATE CONTROL MODULE (G1716272)
REMOVAL AND INSTALLATION
76. 20.23
TAILGATE 
CONTROL 
MODULE - 
RENEW
COUPE
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (501-05 Interior Trim 
Loadspace Trim Panel - Coupe
and Ornamentation, Removal and Installation).
1.
2.

3.
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
LOADSPACE TRIM PANEL - COUPE (G1702347)
REMOVAL AND INSTALLATION
76. 19.22
LUGGAGE 
COMPARTMENT 
SIDE LINER - 
LEFT HAND - 
RENEW
CABRIOLET
0.
USED 
WITHINS
76. 19.22
LUGGAGE 
COMPARTMENT 
SIDE LINER - 
LEFT HAND - 
RENEW
COUPE
0.
USED 
WITHINS
76. 19.22
LUGGAGE 
COMPARTMENT 
SIDE LINER - 
LEFT HAND - 
RENEW
PROJECT
0.
USED 
WITHINS
NOTES:
REMOVAL
Some variation in the illustrations may occur, but the essential 
information is always correct.
Removal steps in this procedure may contain installation 
details.
1.

2.
CAUTION:
Care must be taken not to damage the component.
3.

4.
5.

6.

7.

Torque: 10 Nm
8.
9.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-03
BODY CLOSURES
TAILGATE HINGE (G1715752)
REMOVAL AND INSTALLATION
76. 19.83
TAILGATE 
HINGE - 
RENEW
COUPE
3.
USED 
WITHINS
CAUTION:
Make sure to protect the paintwork.
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (501-03 Body Closures, Removal and 
Tailgate
Installation).
1.
2.

3.

4.

Torque: 25 Nm
CAUTION:
LH illustration shown, RH is similar.
5.

Torque: 25 Nm
CAUTION:
LH illustration shown, RH is similar.
6.
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-03
BODY CLOSURES
TAILGATE (G1715756)
REMOVAL AND INSTALLATION
76. 20.08
TAILGATE 
- RENEW
COUPE
5.
USED 
WITHINS
CAUTION:
Make sure to protect the paintwork.
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (501-08 Exterior Trim and 
Rear Spoiler - Coupe
Ornamentation, Removal and Installation).
1.
Refer to: 
 (501-05 Interior Trim and 
Headliner - Coupe
Ornamentation, Removal and Installation).
2.
Refer to: 
 (417-01 Exterior 
High Mounted Stoplamp - Coupe
Lighting, Removal and Installation).
3.

4.
5.
6.

WARNING:
Make sure the tailgate is supported.
7.

Torque: 25 Nm
8.
NOTE:
Refer to: 
 (501-08 Exterior Trim and 
Tailgate Moulding
Ornamentation, Removal and Installation).
9.
Do not disassemble further if the component is removed 
for access only.
Refer to: 
 (501-11 Glass, Frames and 
Rear Window
Mechanisms, Removal and Installation).
10.
11.

Torque: 25 Nm
12.

13.
NOTE:
14.
The procedure must be carried out on both sides.

Torque: 25 Nm
15.
16.

17.
18.

INSTALLATION
NOTE:
To install, reverse the removal procedure.
1.
Do not tighten the hinge bolts at this stage.
Refer to: Tailgate Alignment (501-03, General Procedures).
2.

2015. 0 F-TYPE (X152), 501-03
BODY CLOSURES
TAILGATE (G1715756)
REMOVAL AND INSTALLATION
76. 20.08
TAILGATE 
- RENEW
COUPE
5.
USED 
WITHINS
CAUTION:
Make sure to protect the paintwork.
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (501-08 Exterior Trim and 
Rear Spoiler - Coupe
Ornamentation, Removal and Installation).
1.
Refer to: 
 (501-05 Interior Trim and 
Headliner - Coupe
Ornamentation, Removal and Installation).
2.
Refer to: 
 (417-01 Exterior 
High Mounted Stoplamp - Coupe
Lighting, Removal and Installation).
3.
4.

5.
6.

WARNING:
Make sure the tailgate is supported.
7.
8.

Torque: 25 Nm
NOTE:
Refer to: 
 (501-08 Exterior Trim and 
Tailgate Moulding
Ornamentation, Removal and Installation).
9.
Do not disassemble further if the component is removed 
for access only.
Refer to: 
 (501-11 Glass, Frames and 
Rear Window
Mechanisms, Removal and Installation).
10.
11.

Torque: 25 Nm
12.
13.

NOTE:
14.
The procedure must be carried out on both sides.
15.

Torque: 25 Nm
16.
17.

18.
INSTALLATION
1.

2015. 0 F-TYPE (X152), 417-01
EXTERIOR LIGHTING
HIGH MOUNTED STOPLAMP - COUPE (G1702803)
NOTE:
To install, reverse the removal procedure.
Do not tighten the hinge bolts at this stage.
Refer to: Tailgate Alignment (501-03, General Procedures).
2.
REMOVAL AND INSTALLATION
86. 41.01
HIGH 
LEVEL 
STOP 
LAMP 
ASSEMBLY 
- RENEW
CABRIOLET
0.
USED 
WITHINS
86. 41.01
HIGH 
LEVEL 
STOP 
LAMP 
ASSEMBLY 
- RENEW
CABRIOLET, 
SVR
0.
USED 
WITHINS
86. 41.01
HIGH 
LEVEL 
STOP 
LAMP 
ASSEMBLY 
- RENEW
COUPE
0.
USED 
WITHINS

NOTES:
REMOVAL
Some variation in the illustrations may occur, but the essential 
information is always correct.
Removal steps in this procedure may contain installation 
details.
Refer to: 
 (414-01 Battery, 
Battery Disconnect and Connect
Mounting and Cables, General Procedures).
1.
CAUTION:
Always protect paintwork and glass when removing 
exterior components.

Torque: 3.2 Nm
2.
3.

CAUTION:
Care must be taken not to damage the component.
Release the retaining clips and disconnect the three electrical 
connectors.

Torque: 2.5 Nm
4.
5.

CAUTION:
Take extra care not to damage the clips.
6.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
HEADLINER - COUPE (G1707458)
INSTALLATION
To install, reverse the removal procedure.
1.
REMOVAL AND INSTALLATION
76. 64.01
HEADLINING 
- RENEW
COUPE
1.
USED 
WITHINS
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
Some variation in the illustrations may occur, but the essential 
information is always correct.
NOTE:
1.
Adjust the steering wheel to the lowest position.

Refer to: 
 (414-01 Battery, 
Battery Disconnect and Connect
Mounting and Cables, General Procedures).
2.
Refer to: Supplemental Restraint System (SRS) Health and 
 (100-00 General Information, Description 
Safety Precautions
and Operation).
3.
NOTE:
Refer to: 
 (501-05 Interior Trim 
A-Pillar Trim Panel - Coupe
and Ornamentation, Removal and Installation).
4.
Repeat the procedure for the other side.
NOTE:
Refer to: 
 (501-05 Interior Trim and Ornamentation, 
Sun Visor
Removal and Installation).
5.
Repeat the procedure for the other side.
6.

Refer to: 
 (501-12 Instrument Panel and 
Overhead Console
Console, Removal and Installation).
Refer to: 
 (501-09 Rear 
Auto-Dimming Interior Mirror - Coupe
View Mirrors, Removal and Installation).
7.
NOTE:
Refer to: 
 (501-05 Interior Trim 
C-Pillar Trim Panel - Coupe
and Ornamentation, Removal and Installation).
8.
Repeat the procedure for the other side.
9.
10.

11.

12.
13.

NOTE:
14.
Repeat the step for the other side.
NOTE:
15.
Repeat the step for the other side.

NOTE:
16.
Repeat the step for the other side.

Vehicles with glass roof panel
17.
CAUTION:
18.

Take extra care not to damage the component.
CAUTION:
Take extra care not to damage the component.
NOTE:
19.
Repeat the step for the other side.

CAUTIONS:
Take extra care not to damage the component.
Using a suitable plastic trim tool, release the 
magnetic fixings.
NOTE:
20.
Make sure that there is at least 50mm clearance 
between the magnetic fixings and the headliner during

Vehicles without roof opening panel
the removal procedure. The fixings will engage if too 
close to each other.
CAUTION:
Take extra care not to damage the component.
21.

CAUTION:
Take extra care not to damage the component.
22.

All vehicles
NOTE:
23.
Lower and position the headliner forward to aid access.

24.

25.

Vehicles with glass roof panel
1.

CAUTION:
Take extra care not to damage the component.
2.

CAUTION:
Take extra care not to damage the component.
NOTE:
3.
Repeat the step for the other side.

CAUTIONS:
Take extra care not to damage the component.
Using a suitable plastic trim tool, release the 
magnetic fixings.
NOTE:
4.
Make sure that there is at least 50mm clearance 
between the magnetic fixings and the headliner during 
the removal procedure. The fixings will engage if too 
close to each other.

Vehicles without roof opening panel
CAUTION:
Take extra care not to damage the component.
1.

CAUTION:
Take extra care not to damage the component.
2.

All vehicles
NOTE:
1.
Lower and position the headliner forward to aid access.

2.

3.

INSTALLATION
To install, reverse the removal procedure.
1.
NOTE:
2.
Install a new retaining clip.

NOTE:
3.
Make sure that the gap around the component is even.

2015. 0 F-TYPE (X152), 501-08
EXTERIOR TRIM AND ORNAMENTATION
TAILGATE MOULDING (G1715758)
REMOVAL AND INSTALLATION
76. 19.86
TAILGATE 
SPOILER - 
RENEW
COUPE
0.
USED 
WITHINS
76. 43.79
LUGGAGE 
COMPARTMENT 
LID UPPER 
TRIM 
FINISHER - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
76. 43.79
LUGGAGE 
COMPARTMENT 
LID UPPER 
TRIM 
FINISHER - 
RENEW
COUPE
1.
USED 
WITHINS
CAUTION:
Make sure to protect the paintwork.
NOTE:
REMOVAL

Removal steps in this procedure may contain installation details.
Refer to: 
 (501-08 Exterior Trim and 
Rear Spoiler - Coupe
Ornamentation, Removal and Installation).
1.
2.
3.
4.

Torque: 3.2 Nm
5.
6.

INSTALLATION
CAUTION:
Make sure that the component is aligned and attached as 
shown.
1.

2015. 0 F-TYPE (X152), 501-08
EXTERIOR TRIM AND ORNAMENTATION
REAR SPOILER - COUPE (G1715738)
To install, reverse the removal procedure.
2.

REMOVAL AND INSTALLATION
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
CABRIOLET
0.
USED 
WITHINS
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
CABRIOLET, 
SVR
0.
USED 
WITHINS
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
COUPE, 
SVR
0.
USED 
WITHINS
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
PROJECT
0.
USED 
WITHINS
76. 19.86
TAILGATE 
SPOILER - 
RENEW
COUPE
0.
USED 
WITHINS
CAUTION:
Make sure to protect the paintwork.
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
1.

NOTE:
2.
Do not refit the two caps until the adjustment of the 
spoiler has been carried out.
NOTE:
3.
Repeat the step for the other side.

4.
5.

CAUTION:
Do not exceed the specified torque value.
6.

Torque: 9 Nm
CAUTION:
Do not exceed the specified torque value.
7.

Torque: 3.5 Nm
NOTE:
8.
Do not disassemble further if the component is removed 
for access only.

Torque: 3.2 Nm
9.
INSTALLATION
To install, reverse the removal procedure.
1.
CAUTION:
2.

2015. 0 F-TYPE (X152), 501-11
GLASS, FRAMES AND MECHANISMS
REAR WINDOW (G1716281)
Make sure that the surface is clean and free of foreign 
material.
Adjust the rear spoiler by rotating the adjustment studs 
clockwise and counter clockwise as necessary.
REMOVAL AND INSTALLATION

76. 81.10
BACKLIGHT 
- RENEW
COUPE
2.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (417-01 Exterior 
High Mounted Stoplamp - Coupe
Lighting, Removal and Installation).
1.
Refer to: 
 (501-08 Exterior Trim and 
Rear Spoiler - Coupe
Ornamentation, Removal and Installation).
2.
NOTE:
3.
The step must be carried out on both sides.

4.

CAUTIONS:
5.
Protect the surrounding components.
Protect the surrounding paintwork to avoid 
damage.

Use a glazing cutting wire to cut the sealant.
1.
Pull glazing wire through windshield sealant to the 
inside of the vehicle.
1.
6.
INSTALLATION
CAUTION:
Make sure that the mating faces are clean and free of 
foreign material.
1.

2.

Prepare the window glass, window glass flange and trimmed 
PU adhesive in accordance with the instructions included with 
the PU adhesive kit.
3.
4.

Test the sealer for leaks, apply additional sealer if necessary. 
If water is used, allow sealer to dry before testing. Spray 
water around the glass and check for leaks. Mark any area 
that leaks. Dry the glass and sealer then apply additional 
sealer.
To install, reverse the removal procedure.
5.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
SPECIFICATIONS
Torque Specifications
ITEM
NM
LB-
FT
LB-
IN
Door trim panel - screw
9

80
Sun visor - screw
1.

13
Centre console bolts
9

80
Scuff plates - clips only

Rear console trim - clips only

B-pillar lower trim panel clips only

cowl side trim panel clips only

Luggage compartment lid trim panel clips only - vehicles with 
folding top

Loadspace trim panels clips only

A pillar trim panel clips only - vehicles with folding top

A pillar trim panel screw - vehicles without folding top
9

80
Rear quarter trim panel clips only - vehicles with folding top

Parcel shelf trim panel clips only - vehicles without folding top

C pillar trim panel clips only - vehicles without folding top

Liftgate lower trim panel bolts - vehicles without folding top
5.

47
Liftgate upper trim panel nuts - vehicles without folding top
3.

28

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
A-PILLAR TRIM PANEL - COUPE (G1707504)
REMOVAL AND INSTALLATION
76. 13.31
A-POST 
UPPER 
TRIM PAD 
- RENEW
CABRIOLET
0.
USED 
WITHINS
76. 13.31
A-POST 
UPPER 
TRIM PAD 
- RENEW
COUPE
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
CAUTION:
Care must be taken to avoid damaging the surrounding 
components.
1.

Torque: 9 Nm
2.
3.

NOTE:
RH illustration shown, LH is similar.
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
A-PILLAR TRIM PANEL - FOLDING TOP (G1584206)
REMOVAL AND INSTALLATION
76. 13.31
A-POST 
UPPER 
TRIM PAD 
- RENEW
CABRIOLET
0.
USED 
WITHINS
76. 13.31
A-POST 
UPPER 
TRIM PAD 
- RENEW
COUPE
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
1.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
B-PILLAR LOWER TRIM PANEL - COUPE (G1702777)
REMOVAL AND INSTALLATION
76. 13.08
B-POST 
TRIM PAD 
- RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
76. 13.29
B-POST 
LOWER 
TRIM PAD 
- RENEW
COUPE
0.
USED 
WITHINS
CAUTIONS:
LH illustration shown, RH is similar.
Care must be taken not to damage the components.
REMOVAL
1.

2.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
B-PILLAR LOWER TRIM PANEL - FOLDING TOP 
(G1584207)
REMOVAL AND INSTALLATION
76. 13.08
B-POST 
TRIM PAD 
- RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
76. 13.29
B-POST 
LOWER 
TRIM PAD 
- RENEW
COUPE
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
1.

2.

Torque: 40 Nm
3.
4.
5.

6.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
COWL SIDE TRIM PANEL (G1584208)
REMOVAL AND INSTALLATION
76. 13.30
A-POST 
LOWER 
TRIM PAD 
- RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTES:
REMOVAL
LH illustration shown, RH is similar.
Removal steps in this procedure may contain installation 
details.
1.

2.

3.
4.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
C-PILLAR TRIM PANEL - COUPE (G1702314)
REMOVAL AND INSTALLATION
76. 13.83
C - POST 
TRIM PAD 
- RENEW
COUPE
0.
USED 
WITHINS
NOTE:
REMOVAL
RH illustration shown, LH is similar.
Remove the parcel shelf.
Refer to: 
 (501-05 Interior Trim and 
Parcel Shelf - Coupe
Ornamentation, Removal and Installation).
1.
2.

3.

CAUTION:
Care must be taken not to damage the headliner on 
removal.
4.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
PARCEL SHELF - COUPE (G1702318)
INSTALLATION
To install, reverse the removal procedure.
1.
REMOVAL AND INSTALLATION

76. 67.06
REAR 
PARCEL 
TRAY - 
RENEW
CABRIOLET
0.
USED 
WITHINS
76. 67.06
REAR 
PARCEL 
TRAY - 
RENEW
COUPE
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Disconnect the battery ground cable.
Refer to: 
 (414-01 Battery, 
Battery Disconnect and Connect
Mounting and Cables, General Procedures).
1.
Remove both front seats.
Refer to: 
 (501-10 
Front Seat - Vehicles With: Sports Seats
Seating, Removal and Installation).
2.
CAUTION:
LH illustration shown, RH is similar.
NOTE:
3.
Repeat the procedure for the other side.

Torque: 40 Nm
CAUTION:
LH illustration shown, RH is similar.
NOTE:
4.
Repeat the procedure for the other side.

CAUTION:
LH illustration shown, RH is similar.
NOTE:
5.
Repeat the procedure for the other side.

6.
7.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
ENGINE COVER (G1580231)
REMOVAL AND INSTALLATION
12. 29.93
ENGINE 
COVER - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
REMOVAL
NOTE:
1.
Some variation in the illustrations may occur, but the 
essential information is always correct.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
FRONT DOOR TRIM PANEL (G1584209)
REMOVAL AND INSTALLATION
76. 34.01
FRONT 
DOOR 
TRIM PAD 
- RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
76. 34.01
FRONT 
DOOR 
TRIM PAD 
- RENEW
COUPE
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
1.

2.

3.
4.
5.

NOTE:
6.
Do not disassemble further if the component is removed 
for access only.

7.
8.

9.
10.

11.
12.

13.
14.

15.
16.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
HEADLINER - COUPE (G1707458)
REMOVAL AND INSTALLATION
76. 64.01
HEADLINING 
- RENEW
COUPE
1.
USED 
WITHINS
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
Some variation in the illustrations may occur, but the essential 
information is always correct.
NOTE:
1.
Adjust the steering wheel to the lowest position.

Refer to: 
 (414-01 Battery, 
Battery Disconnect and Connect
Mounting and Cables, General Procedures).
2.
Refer to: Supplemental Restraint System (SRS) Health and 
 (100-00 General Information, Description 
Safety Precautions
and Operation).
3.
NOTE:
Refer to: 
 (501-05 Interior Trim 
A-Pillar Trim Panel - Coupe
and Ornamentation, Removal and Installation).
4.
Repeat the procedure for the other side.
5.

NOTE:
Refer to: 
 (501-05 Interior Trim and Ornamentation, 
Sun Visor
Removal and Installation).
Repeat the procedure for the other side.
Refer to: 
 (501-12 Instrument Panel and 
Overhead Console
Console, Removal and Installation).
6.
Refer to: 
 (501-09 Rear 
Auto-Dimming Interior Mirror - Coupe
View Mirrors, Removal and Installation).
7.
NOTE:
Refer to: 
 (501-05 Interior Trim 
C-Pillar Trim Panel - Coupe
and Ornamentation, Removal and Installation).
8.
Repeat the procedure for the other side.
9.
10.

11.
12.

13.

NOTE:
14.
Repeat the step for the other side.

NOTE:
15.
Repeat the step for the other side.

NOTE:
16.
Repeat the step for the other side.

Vehicles with glass roof panel
17.
CAUTION:
Take extra care not to damage the component.
18.

CAUTION:
Take extra care not to damage the component.
NOTE:
19.
Repeat the step for the other side.

CAUTIONS:
Take extra care not to damage the component.
Using a suitable plastic trim tool, release the 
magnetic fixings.
20.

Vehicles without roof opening panel
NOTE:
Make sure that there is at least 50mm clearance 
between the magnetic fixings and the headliner during 
the removal procedure. The fixings will engage if too 
close to each other.
CAUTION:
Take extra care not to damage the component.
21.

CAUTION:
Take extra care not to damage the component.
22.

All vehicles
NOTE:
23.
Lower and position the headliner forward to aid access.

24.

25.
Vehicles with glass roof panel
1.
2.

CAUTION:
Take extra care not to damage the component.
CAUTION:
Take extra care not to damage the component.
NOTE:
3.
Repeat the step for the other side.

CAUTIONS:
Take extra care not to damage the component.
Using a suitable plastic trim tool, release the 
magnetic fixings.
4.

NOTE:
Make sure that there is at least 50mm clearance 
between the magnetic fixings and the headliner during 
the removal procedure. The fixings will engage if too 
close to each other.
Vehicles without roof opening panel
CAUTION:
Take extra care not to damage the component.
1.

CAUTION:
Take extra care not to damage the component.
2.

All vehicles
NOTE:
1.
Lower and position the headliner forward to aid access.

2.
3.

INSTALLATION
To install, reverse the removal procedure.
1.
NOTE:
2.
Install a new retaining clip.

NOTE:
3.
Make sure that the gap around the component is even.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
C-PILLAR TRIM PANEL - COUPE (G1702314)
REMOVAL AND INSTALLATION
76. 13.83
C - POST 
TRIM PAD 
- RENEW
COUPE
0.
USED 
WITHINS

NOTE:
REMOVAL
RH illustration shown, LH is similar.
Remove the parcel shelf.
Refer to: 
 (501-05 Interior Trim and 
Parcel Shelf - Coupe
Ornamentation, Removal and Installation).
1.
2.
3.

CAUTION:
Care must be taken not to damage the headliner on 
removal.
4.

2015. 0 F-TYPE (X152), 501-12
INSTRUMENT PANEL AND CONSOLE
OVERHEAD CONSOLE (G1588189)
INSTALLATION
To install, reverse the removal procedure.
1.
REMOVAL AND INSTALLATION

76. 13.69
ROOF 
CONSOLE 
- RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
1.
NOTE:
2.
Do not disassemble further if the component is removed 
for access only.

3.
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 100-00
GENERAL INFORMATION
DESCRIPTION AND OPERATION
WARNINGS:
Only qualified technicians are allowed to work on pyrotechnic 
components.
INHALED: Exposure to pyrotechnic residue may cause low 
blood pressure, severe headache, irritation of mucous 
membranes, fainting, shortness of breath or rapid pulse. Move 
a victim to fresh air. Seek immediate medical attention.
EYE CONTACT: Exposure to unburned pyrotechnic residue may 
cause irritation, burning and etching of the eyes. Flush 
immediately with plenty of cold running water for at least
minutes. Seek immediate medical attention.
EYE CONTACT: Exposure to burned pyrotechnic residue may 
cause irritation, burning and etching of the eyes. Flush 
immediately with diluted boric acid solution. Seek immediate 
medical attention.
SKIN CONTACT: Unburned pyrotechnic residue may be rapidly 
absorbed through the skin in toxic quantities. Wash 
immediately with plenty of soap and water. Seek medical 
attention.
SKIN CONTACT: Burned pyrotechnic residue may be rapidly 
absorbed through the skin in toxic quantities. Wash with 
plenty of water. Do not use soap. Seek medical attention.

SWALLOWED: Unburned pyrotechnic residue is extremely 
toxic. If conscious drink plenty of water then induce vomiting. 
Seek immediate medical attention. If unconscious, or in 
convulsions do not attempt to induce vomiting or give 
anything by mouth. Seek immediate medical attention.
SWALLOWED: Burned pyrotechnic residue is extremely toxic. 
Drink plenty of water and seek immediate medical attention.
The deployment key must only be accessible to authorized 
personnel.
Make sure that the deployment key remains removed from the 
deployment equipment except during deployment.
If permenantly disabling or enabling the passenger air bag a 
new seat belt for vehicles without or with a passenger air bag 
must be installed.
Undeployed pyrotechnic components must not be deployed in 
the vehicle.
Pyrotechnic components must be deployed following local 
regulations.
Check thoroughly that no loose objects can be spread during 
the deployment of pyrotechnic components.
Pyrotechnic components must be transported following local 
regulations.
Never carry out any electrical measurement on disconnected, 
undeployed pyrotechnic components.
Pyrotechnic components must not be disassembled.
Pyrotechnic components are not interchangeable between 
vehicles.
Always carry a live air bag module away from the body with 
the air bag or trim cover pointing upwards.
Live air bag modules must be placed in a suitable cage when 
removed from the vehicle. The air bag or trim cover must be 
facing upwards.

2015. 0 F-TYPE (X152), 501-09
REAR VIEW MIRRORS
AUTO-DIMMING INTERIOR MIRROR - COUPE 
(G1716713)
Do not install a rearward facing child safety seat to the 
passenger seat with an activated passenger air bag.
CAUTIONS:
Pyrotechnic components must not be subjected to 
temperatures higher than 110°C.
Never install aftermarket accessories to the vehicle on or 
adjacent to the supplemental restraint system module.
REMOVAL AND INSTALLATION
76. 10.56
AUTO DIM 
INTERIOR 
MIRROR - 
RENEW
CABRIOLET
0.
USED 
WITHINS
76. 10.56
AUTO DIM 
INTERIOR 
MIRROR - 
RENEW
COUPE
0.
USED 
WITHINS

NOTES:
REMOVAL
Some variation in the illustrations may occur, but the essential 
information is always correct.
Removal steps in this procedure may contain installation 
details.
CAUTIONS:
Take extra care not to damage the clips.
Protect the surrounding trim to avoid damage.
1.

CAUTIONS:
Take extra care not to damage the clips.
Protect the surrounding trim to avoid damage.
2.
3.

4.

CAUTION:
To avoid damage to the mirror glass, make sure force is 
only applied at the mirror base.
INSTALLATION
CAUTION:
Make sure that the component is correctly located on the 
locating pegs.
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
A-PILLAR TRIM PANEL - COUPE (G1707504)
REMOVAL AND INSTALLATION
76. 13.31
A-POST 
UPPER 
TRIM PAD 
- RENEW
CABRIOLET
0.
USED 
WITHINS
76. 13.31
A-POST 
UPPER 
TRIM PAD 
- RENEW
COUPE
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
CAUTION:
Care must be taken to avoid damaging the surrounding 
components.
1.

Torque: 9 Nm
2.
3.

2015. 0 F-TYPE (X152), 414-01
BATTERY, MOUNTING AND CABLES
BATTERY DISCONNECT AND CONNECT (G1579511)
NOTE:
RH illustration shown, LH is similar.
INSTALLATION
To install, reverse the removal procedure.
1.

GENERAL PROCEDURES
86. 15.15
BATTERY 
DISCONNECTION 
AND 
RECONNECTION 
PROCEDURE 




 DO NOT 
ISSUE 



ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTES:
Some variation in the illustrations may occur, but the essential 
information is always correct.
Removal steps in this procedure may contain installation 
details.
If a new battery is installed, the battery monitoring system 
(BMS) must be reset using Jaguar approved diagnostic 
equipment.
Refer to: 
 (414-00 Battery and 
Battery Care Requirements
Charging System - General Information, Description and 
Operation).
1.
Obtain and record the audio unit preset radio frequencies.
2.
3.

4.

5.
CAUTION:
Take extra care not to damage the wiring harnesses.

Torque: 6 Nm
6.
7.

To install, reverse the removal procedure.
8.
NOTE:
Using Jaguar approved diagnostic equipment, reset the 
battery monitoring system (BMS).
9.
This step is only necessary when installing a new battery.
Door Window Motor Initialization
10.
Enter the audio unit preset radio frequencies.
11.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
SUN VISOR (G1584210)
Reset the clock to the correct time.
12.
Start the engine and allow to idle until the engine reaches 
normal operating temperature.
13.
Switch the engine off.
14.
REMOVAL AND INSTALLATION
76. 10.47
SUN 
VISOR - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
Some variation in the illustrations may occur, but the essential 
information is always correct.
1.

Torque: 6 Nm
2.
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
LIFTGATE LOWER TRIM PANEL - COUPE (G1702316)
REMOVAL AND INSTALLATION
76. 19.65
TAILGATE 
INTERIOR 
LOWER 
TRIM 
PANEL - 
RENEW
COUPE
0.
USED 
WITHINS
CAUTION:
Care must be taken not to damage the components.
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
1.

Torque: 5.4 Nm
2.

3.
4.
5.

Carefully align and secure the clips.
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
LOADSPACE TRIM PANEL - COUPE (G1702347)
REMOVAL AND INSTALLATION
76. 19.22
LUGGAGE 
COMPARTMENT 
SIDE LINER - 
LEFT HAND - 
RENEW
CABRIOLET
0.
USED 
WITHINS
76. 19.22
LUGGAGE 
COMPARTMENT 
SIDE LINER - 
LEFT HAND - 
RENEW
COUPE
0.
USED 
WITHINS
76. 19.22
LUGGAGE 
COMPARTMENT 
SIDE LINER - 
LEFT HAND - 
RENEW
PROJECT
0.
USED 
WITHINS
NOTES:
REMOVAL
Some variation in the illustrations may occur, but the essential 
information is always correct.
Removal steps in this procedure may contain installation 
details.
1.

2.
CAUTION:
Care must be taken not to damage the component.
3.

4.
5.

6.
7.

Torque: 10 Nm
8.
9.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
LOADSPACE TRIM PANEL - FOLDING TOP (G1584212)
REMOVAL AND INSTALLATION
76. 19.22
LUGGAGE 
COMPARTMENT 
SIDE LINER - 
LEFT HAND - 
RENEW
CABRIOLET
0.
USED 
WITHINS
76. 19.22
LUGGAGE 
COMPARTMENT 
SIDE LINER - 
LEFT HAND - 
RENEW
COUPE
0.
USED 
WITHINS
76. 19.22
LUGGAGE 
COMPARTMENT 
SIDE LINER - 
LEFT HAND - 
RENEW
PROJECT
0.
USED 
WITHINS
NOTES:
REMOVAL
Some variation in the illustrations may occur, but the essential 
information is always correct.
Removal steps in this procedure may contain installation 
details.
1.

2.
3.

CAUTION:
Care must be taken not to damage the component.
4.

5.

6.
7.
8.

9.

10.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
LUGGAGE COMPARTMENT UPPER TRIM PANEL 
- COUPE (G1702317)
REMOVAL AND INSTALLATION
76. 20.16
LUGGAGE 
COMPARTMENT 
UPPER TRIM 
PANEL - RENEW
COUPE
0.
USED 
WITHINS
REMOVAL
NOTE:
1.
RH illustration shown, LH is similar.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
PARCEL SHELF - COUPE (G1702318)
REMOVAL AND INSTALLATION
76. 67.06
REAR 
PARCEL 
TRAY - 
RENEW
CABRIOLET
0.
USED 
WITHINS
76. 67.06
REAR 
PARCEL 
TRAY - 
RENEW
COUPE
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Disconnect the battery ground cable.
Refer to: 
 (414-01 Battery, 
Battery Disconnect and Connect
Mounting and Cables, General Procedures).
1.
Remove both front seats.
Refer to: 
 (501-10 
Front Seat - Vehicles With: Sports Seats
Seating, Removal and Installation).
2.
3.

CAUTION:
LH illustration shown, RH is similar.
NOTE:

Torque: 40 Nm
Repeat the procedure for the other side.
CAUTION:
LH illustration shown, RH is similar.
NOTE:
4.
Repeat the procedure for the other side.

CAUTION:
LH illustration shown, RH is similar.
NOTE:
5.
Repeat the procedure for the other side.

6.

2015. 0 F-TYPE (X152), 501-10
SEATING
FRONT SEAT - VEHICLES WITH: SPORTS 
SEATS (G1707574)
7.
INSTALLATION
To install, reverse the removal procedure.
1.
REMOVAL AND INSTALLATION

76. 70.01
FRONT 
SEAT - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
76. 70.01.82
FRONT 
SEAT - 
RENEW - 
WITH 
SPORTS 
SEATS 
FITTED
ALL 
DERIVATIVES
0.
USED 
WITHINS
REMOVAL

WARNINGS:
To avoid accidental deployment and possible personal injury, 
the backup power supply must be depleted before repairing or 
replacing any air bag supplemental restraint system (SRS) 
components. To deplete the backup power supply energy, 
disconnect the battery ground cable and wait one minute. 
Failure to follow this instruction may result in personal injury.
Always wear safety glasses when working on an air bag 
equipped vehicle and when handling an air bag module. 
Failure to follow this instruction may result in personal injury.
To minimize the possibility of premature deployment, do not 
use radio key code savers when working on the supplemental 
restraint system. Failure to follow this instruction may result in 
personal injury.
To minimize the possibility of injury in the event of premature 
deployment, always carry a live air bag module with the bag 
and trim cover pointed away from the body. Failure to follow 
this instruction may result in personal injury.
To minimize the possibility of premature deployment, live air 
bag modules must only be placed on work benches which have 
been ground bonded and with the trim cover facing up. Failure 
to follow these instructions may result in personal injury.
Never probe the electrical connectors of air bag modules or 
any other supplemental restraint system component. Failure 
to follow this instruction may result in personal injury.
Painting over the driver air bag module trim cover or 
instrument panel could lead to deterioration of the trim cover 
and air bags. Do not for any reason attempt to paint 
discolored or damaged air bag module trim covers or 
instrument panel. Install a new component. Failure to follow 
this instruction may result in personal injury.

NOTES:
Some variation in the illustrations may occur, but the essential 
information is always correct.
Removal steps in this procedure may contain installation 
details.
RH illustration shown, LH is similar.
Refer to: Supplemental Restraint System (SRS) Health and 
 (100-00 General Information, Description 
Safety Precautions
and Operation).
1.
2.
3.

4.

Torque: 47 Nm
5.
6.
7.

Torque: 47 Nm
Refer to: 
 (414-01 Battery, 
Battery Disconnect and Connect
Mounting and Cables, General Procedures).
8.
9.

WARNING:
This step requires the aid of another technician.
CAUTIONS:
Protect the surrounding paintwork to avoid damage.
Protect the surrounding trim to avoid damage.
10.

2015. 0 F-TYPE (X152), 414-01
BATTERY, MOUNTING AND CABLES
BATTERY DISCONNECT AND CONNECT (G1579511)
INSTALLATION
To install, reverse the removal procedure.
1.
GENERAL PROCEDURES
86. 15.15
BATTERY 
DISCONNECTION 
AND 
RECONNECTION 
PROCEDURE 




 DO NOT 
ISSUE 



ALL 
DERIVATIVES
0.
USED 
WITHINS

NOTES:
Some variation in the illustrations may occur, but the essential 
information is always correct.
Removal steps in this procedure may contain installation 
details.
If a new battery is installed, the battery monitoring system 
(BMS) must be reset using Jaguar approved diagnostic 
equipment.
Refer to: 
 (414-00 Battery and 
Battery Care Requirements
Charging System - General Information, Description and 
Operation).
1.
Obtain and record the audio unit preset radio frequencies.
2.
3.
4.

5.
6.

CAUTION:
Take extra care not to damage the wiring harnesses.

Torque: 6 Nm
7.

To install, reverse the removal procedure.
8.
NOTE:
Using Jaguar approved diagnostic equipment, reset the 
battery monitoring system (BMS).
9.
This step is only necessary when installing a new battery.
Door Window Motor Initialization
10.
Enter the audio unit preset radio frequencies.
11.
Reset the clock to the correct time.
12.
Start the engine and allow to idle until the engine reaches 
normal operating temperature.
13.
Switch the engine off.
14.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
SCUFF PLATE TRIM PANEL (G1584223)
REMOVAL AND INSTALLATION
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
Some components shown removed for clarity.
1.
INSTALLATION

To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
SUN VISOR (G1584210)
REMOVAL AND INSTALLATION
76. 10.47
SUN 
VISOR - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
Some variation in the illustrations may occur, but the essential 
information is always correct.
1.

2.

Torque: 6 Nm
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-08
EXTERIOR TRIM AND ORNAMENTATION
DESCRIPTION AND OPERATION

ITEM
DESCRIPTION
1
Deployable spoiler blade
COMPONENT LOCATION - SHEET 1 OF 2 - CONVERTIBLE

2
Left side hinge
3
Deployable spoiler mechanism
4
High Mounted Stop Lamp (HMSL)
5
Right side hinge
6
Deployable spoiler switch
7
Chassis Control Module (CHCM)

ITEM
DESCRIPTION
1
Deployable spoiler blade
2
Left side hinge
COMPONENT LOCATION - SHEET 2 OF 2 - COUPE

3
Deployable spoiler mechanism
4
Right side hinge
5
Deployable spoiler switch
6
Chassis Control Module (CHCM)
The Deployable spoiler provides an increased aerodynamic down 
force at the rear of the vehicle to maintain vehicle stability at high 
speed.
The Deployable spoiler is electrically operated and controlled by the 
CHCM. The basic system consists of a spoiler mechanism, which 
operates the Deployable spoiler blade. The action is a single stage 
deployment or retraction. The actuator is powered by the AJB 
(Auxiliary Junction Box), and controlled by the CHCM.
The spoiler automatically deploys when the vehicle speed exceeds the 

Auto deployable speed
 and retracts when the speed falls below the 

Auto retraction speed
. The driver can manually operate the 
Deployable spoiler with the Deployable spoiler switch, which is 
located in the floor console adjacent to the TCS (Transmission Control 
Switch).
DEPLOYABLE SPOILER
NOTE:
OVERVIEW
DESCRIPTION
Convertible variant shown, coupe similar.

ITEM
DESCRIPTION
1
Deployable spoiler blade
2
Deployable spoiler carrier plate
3
Left side hinge
4
Drive shaft
5
Deployable spoiler actuator
6
High Mounted Stop Lamp (HMSL) (convertible vehicles only)
7
Water management system
8
Right side hinge
9
Spoiler buffer (4 off)
DEPLOYABLE SPOILER ACTUATOR

ITEM
DESCRIPTION
1
Cam
2
Spoiler position microswitch - Retracted position
3
Spoiler position microswitch - Deployed position
4
Gear mechanism
5
Drive shaft

6
Direct Current (DC) motor
7
Electrical connector
The Deployable spoiler actuator is located under the spoiler 
mechanism carrier plate. The actuator is a 12V DC (Direct Current) 
motor, which is connected to a geared actuator attached to a shaft. 
The shaft mechanically rotates four bar hinge mechanisms on each 
end of the shaft, and operates the spoiler blade. The AJB supplies the 
power feed and the ground connection to each actuator connections. 
This connection allows the CHCM to operate the spoiler actuator 
rotation in both directions according the required spoiler movement. 
The Deployable spoiler position is determined using two 
microswitches operated by a cam, which is connected to the shaft. 
The nominal deployment/retraction time for the spoiler at 13.5 volts 
supply and 20°C is approximately 3 seconds. To reduce the possibility 
of motor burn-out, the maximum operation duration is limited to
seconds, controlled by the CHCM. The motor will not be powered for 
more than 5 seconds continuously in either direction.
CHASSIS CONTROL MODULE
The operation of the Deployable spoiler is controlled by the CHCM, 
which is located in the luggage compartment. The CHCM receives the 
battery feed from the comfort relay which is located in the AJB and

an ignition feed from the CJB (Central Junction Box). A connection 
with the HS (High Speed) CAN (Controller Area Network) bus allows 
the CHCM to communicate with other systems on the vehicle.
The CHCM interacts with the following systems:
ECM (Engine Control Module)
ABS (Anti-lock brake system) control module
CJB (Central Junction Box)
In the event of Deployable spoiler failure, the CHCM sends a message 
to the ECM to limit the vehicle speed to 216 km/h (135mph) via the 
HS CAN bus.
In the event of Deployable spoiler failure, the CHCM sends a message 
to the ABS to enable the DSC (Dynamic Stability Control) if it is 
switched off by the driver, to maintain the vehicle stability.
The CJB sends a message to the CHCM via the HS CAN bus to disable 
spoiler operation when the tailgate is in open position.
DEPLOYABLE SPOILER SWITCH
The Deployable spoiler switch is a momentary switch, located in the 
floor console behind the TCS and a part of the JDS (JaguarDrive 
switchpack). When the Deployable spoiler switch is operated, the JDS

sends a message to the CHCM via the HS CAN bus. The CHCM sends 
a message to the JDS, to illuminate the LED (Light Emitting Diode) 
located in the Deployable spoiler switch via the HS CAN bus.
The Deployable spoiler system has three operational modes:
Automatic operation mode
Manual operation mode
Cleaning mode (NAS market, coupe vehicles only)
AUTOMATIC OPERATION
In Automatic operation mode, the spoiler automatically deploys when 
the vehicle speed exceeds the 
Auto deployable speed
 and retracts 
when the speed falls below the 
Auto retraction speed
. The 
deployable and retraction speed thresholds depends the vehicle body 
style. In the deployed position, the spoiler provides an increased 
aerodynamic down force at the rear of the vehicle which enhances 
vehicle stability at high speeds.
Speed thresholds for automatic operation
BODY STYLE
AUTO DEPLOYABLE SPEED
AUTO RETRACTION SPEED
Convertible
96 km/h (60 mph)
64 km/h (40 mph)
Coupe
112 km/h (70 mph)
80 km/h (50 mph)
DEPLOYABLE SPOILER DISABLING
To prevent unintentional retraction of the spoiler at elevated vehicle 
speed, or in a software malfunction event, an isolation circuit is fitted 
in the AJB. This function is controlled by the CJB by a hardwired 
connection. When the vehicle speed exceeds 200 km/h (125 mph) 
the CJB disconnect the power source from the Deployable spoiler 
actuator, and keep disconnected until the speed falls below 185 km/h 
(115 mph).
OPERATION

MANUAL OPERATION - ALL VEHICLES, EXCEPT NAS MARKET COUPE
Manual mode operation is available, when the vehicle is stationary 
(Ignition is ON) or the vehicle speed below the Auto Deployable 
Speed. A LED located in the Deployable spoiler switch indicates the 
auto/manual mode status. On successful selection of manual 
operation mode, the spoiler will deploy and the LED in the Deployable 
spoiler switch is also illuminated. Manual spoiler retraction is inhibited 
above the Auto Deployable Speed. The LED switches off when the 
status returns to the Automatic operation mode. If the Deployable 
spoiler is in Manual operation mode and the speed is above the 
threshold for auto deployment, then the spoiler will remain deployed, 
even if the vehicle speed falls below the auto retraction speed.
Returning to Automatic operation mode, below 21 km/h (13 mph), 
requires a continuous operation (press and hold) of the Deployable 
spoiler switch. Returning to auto mode at this speed will retract the 
spoiler. One continuous operation of the switch is required to attain 
full retraction. The mode reverts to automatic upon completion, 
indicated by extinguishing the LED in the Deployable spoiler switch. If 
the switch is released prior to complete retraction, the spoiler will 
freeze in its current position. The next operation of the switch deploys 
the spoiler to its fully deployed position. This acts as an anti-trap 
feature. The process needs to be repeated to retract the spoiler.
CLEANING MODE - NAS MARKET COUPE VEHICLES ONLY
Cleaning mode can be activated by operating the Deployable spoiler 
switch once, while Ignition is ON and the engine is not running (or 
within 15 sec of turning the ignition off) with vehicle in PARK position 
and the tailgate is closed.
With the activation of cleaning mode, the spoiler deploys fully and the 
message 
 is displayed in the IC 
SPOILER IN CLEANING MODE
(Instrument Cluster), and a LED in the Deployable spoiler switch is 
also illuminated. The cleaning mode can be cancelled either manually 
or automatically when the vehicle speed is above 2km/h (1.2 mph). 
To cancel cleaning mode manually, press and hold the Deployable 
spoiler switch until the spoiler retracts fully, the message disappears

from the IC, and the LED in the Deployable spoiler switch 
extinguishes. The Deployable spoiler switch has to be operated while 
Ignition is ON or within 15 sec of turning ignition off with tailgate 
closed.
THERMAL PROTECTION
The CHCM is using a thermal protection model to protect the 
Deployable spoiler actuator from overheating by continuous cycles of 
operation. The CHCM estimates the actuator temperature and inhibits 
the spoiler operation when the estimated temperature reaches the 
threshold level. Further spoiler operation is prohibited for 
approximately 2 minutes. After the cooling down period, the CHCM re-
enables the spoiler operation.
NOTE:
If the Deployable spoiler is in the 
Automatic operation
 mode and in 
the deployed state after the cooling down period, automatic 
retraction will happen only if the vehicle speed is between 21 km/h 
(13 mph) and the 
Auto Retraction Speed
. If the vehicle speed is less 
than 21 km/h (13 mph) the spoiler will not retracting automatically. 
To retract the spoiler, operate the Deployable spoiler switch, or 
increase the speed above 21 km/h (13 mph).
INPUT/OUTPUT DIAGRAM
The thermal protection model uses a Heat Index that does not 
correspond to actual temperature.

A   HARDWIRED D   HS (HIGH SPEED) CAN (CONTROLLER AREA 
NETWORK)
ITEM
DESCRIPTION
1
Chassis Control Module (CHCM)
2
Instrument Cluster (IC)

3
Anti-lock brake system (ABS) control module
4
Central Junction Box (CJB)
5
Auxiliary Junction Box (AJB)
6
Deployable spoiler actuator
7
Ground
8
Ignition feed from Central Junction Box (CJB)
9
Deployable spoiler position microswitch
10
Deployable spoiler switch
11
JaguarDrive switchpack (JDS)
12
Engine Control Module (ECM)

2015. 0 F-TYPE (X152), 501-08
EXTERIOR TRIM AND ORNAMENTATION
FRONT FENDER MOULDING (G1584130)
REMOVAL AND INSTALLATION
76. 55.19
FENDER 
GRILLE - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
Some variation in the illustrations may occur, but the essential 
information is always correct.
Refer to: Front Fender (501-27, Removal and Installation).
1.
2.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-08
EXTERIOR TRIM AND ORNAMENTATION
LUGGAGE COMPARTMENT LID MOULDING (G1584131)
REMOVAL AND INSTALLATION
76. 43.79
LUGGAGE 
COMPARTMENT 
LID UPPER 
TRIM 
FINISHER - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
76. 43.79
LUGGAGE 
COMPARTMENT 
LID UPPER 
TRIM 
FINISHER - 
RENEW
COUPE
1.
USED 
WITHINS
CAUTION:
Make sure to protect the paintwork
REMOVAL

NOTES:
Removal steps in this procedure may contain installation 
details.
Some components shown removed for clarity.
Some variation in the illustrations may occur, but the essential 
information is always correct.
NOTE:
1.
Note the position of the wiring harnesses clips to aid 
installation.
2.

CAUTIONS:
Make sure that the surface is clean and free of foreign material.
Do not use excessive force to install the component.
Make sure to protect the paintwork
INSTALLATION
1.

CAUTION:
Make sure that the wiring cables are secured in the 
positions noted in the removal steps.
2.

2015. 0 F-TYPE (X152), 501-08
EXTERIOR TRIM AND ORNAMENTATION
REAR SPOILER - COUPE (G1715738)
REMOVAL AND INSTALLATION
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
CABRIOLET
0.
USED 
WITHINS
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
CABRIOLET, 
SVR
0.
USED 
WITHINS
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
COUPE, 
SVR
0.
USED 
WITHINS
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
PROJECT
0.
USED 
WITHINS
76. 19.86
TAILGATE 
SPOILER - 
RENEW
COUPE
0.
USED 
WITHINS
CAUTION:
Make sure to protect the paintwork.
REMOVAL

NOTE:
Removal steps in this procedure may contain installation details.
1.
NOTE:
2.
Do not refit the two caps until the adjustment of the 
spoiler has been carried out.
3.

NOTE:
Repeat the step for the other side.
4.
5.

CAUTION:
Do not exceed the specified torque value.
6.

Torque: 9 Nm
CAUTION:
Do not exceed the specified torque value.
7.

Torque: 3.5 Nm
NOTE:
8.
Do not disassemble further if the component is removed 
for access only.

Torque: 3.2 Nm
9.
INSTALLATION
To install, reverse the removal procedure.
1.

CAUTION:
Make sure that the surface is clean and free of foreign 
material.
Adjust the rear spoiler by rotating the adjustment studs 
clockwise and counter clockwise as necessary.
2.

2015. 0 F-TYPE (X152), 501-08
EXTERIOR TRIM AND ORNAMENTATION
REAR SPOILER - FOLDING TOP (G1584133)
REMOVAL AND INSTALLATION
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
CABRIOLET
0.
USED 
WITHINS
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
CABRIOLET, 
SVR
0.
USED 
WITHINS
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
COUPE, 
SVR
0.
USED 
WITHINS
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
PROJECT
0.
USED 
WITHINS
76. 19.86
TAILGATE 
SPOILER - 
RENEW
COUPE
0.
USED 
WITHINS
REMOVAL

NOTES:
Removal steps in this procedure may contain installation 
details.
Some components shown removed for clarity.
Some variation in the illustrations may occur, but the essential 
information is always correct.
Refer to: 
 (417-01 
High Mounted Stoplamp - Folding Top
Exterior Lighting, Removal and Installation).
1.
2.
3.

CAUTION:
Do not exceed the specified torque value.
4.

Torque: 9 Nm
NOTE:
5.
Carefully release the trim panel.

6.
7.

CAUTION:
Do not exceed the specified torque value.

Torque: 2.2 Nm
8.
9.

2015. 0 F-TYPE (X152), 417-01
EXTERIOR LIGHTING
INSTALLATION
CAUTION:
Make sure that the surface is clean and free of foreign 
material.
To install, reverse the removal procedure.
1.

HIGH MOUNTED STOPLAMP - FOLDING TOP 
(G1578906)
REMOVAL AND INSTALLATION
86. 41.01
HIGH 
LEVEL 
STOP 
LAMP 
ASSEMBLY 
- RENEW
CABRIOLET
0.
USED 
WITHINS
86. 41.01
HIGH 
LEVEL 
STOP 
LAMP 
ASSEMBLY 
- RENEW
CABRIOLET, 
SVR
0.
USED 
WITHINS
86. 41.01
HIGH 
LEVEL 
STOP 
LAMP 
ASSEMBLY 
- RENEW
COUPE
0.
USED 
WITHINS
NOTES:
REMOVAL
Some variation in the illustrations may occur, but the essential 
information is always correct.
Removal steps in this procedure may contain installation 
details.
Refer to: 
 (414-01 Battery, 
Battery Disconnect and Connect
Mounting and Cables, General Procedures).
1.
2.

Reposition the rear spoiler for access.

3.
Using a suitable tool, carefully release the 5 clips.
CAUTION:
Secure the connector with a suitable cable tie.
4.

NOTE:

Torque: 3 Nm
Remove the bolts in the indicated sequence.
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-08
EXTERIOR TRIM AND ORNAMENTATION
ROCKER PANEL MOULDING (G1584132)
REMOVAL AND INSTALLATION
76. 11.56
ROCKER 
PANEL - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
Some components shown removed for clarity.
Some variation in the illustrations may occur, but the essential 
information is always correct.
LH shown, RH similar.
WARNING:
Do not work on or under a vehicle supported only by a 
jack. Always support the vehicle on safety stands.
Raise and support the vehicle.
1.

Refer to: 
 (501-05 Interior Trim and 
Scuff Plate Trim Panel
Ornamentation, Removal and Installation).
2.
CAUTION:
Do not use excessive force to install the component.
3.
CAUTION:
Do not use excessive force to install the component.
4.

5.

CAUTION:
Make sure to protect the paintwork
6.
7.
8.

CAUTION:
Do not use excessive force to install the component.
CAUTION:
Do not use excessive force to install the component.
9.

CAUTION:
Make sure to protect the paintwork
10.
CAUTION:
Do not use excessive force to install the component.
11.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION
SCUFF PLATE TRIM PANEL (G1584223)
REMOVAL AND INSTALLATION
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
Some components shown removed for clarity.
1.
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-08
EXTERIOR TRIM AND ORNAMENTATION
TAILGATE MOULDING (G1715758)
REMOVAL AND INSTALLATION
76. 19.86
TAILGATE 
SPOILER - 
RENEW
COUPE
0.
USED 
WITHINS
76. 43.79
LUGGAGE 
COMPARTMENT 
LID UPPER 
TRIM 
FINISHER - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
76. 43.79
LUGGAGE 
COMPARTMENT 
LID UPPER 
TRIM 
FINISHER - 
RENEW
COUPE
1.
USED 
WITHINS
CAUTION:
Make sure to protect the paintwork.
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.

Refer to: 
 (501-08 Exterior Trim and 
Rear Spoiler - Coupe
Ornamentation, Removal and Installation).
1.
2.
3.
4.

Torque: 3.2 Nm
5.
6.

INSTALLATION
CAUTION:
Make sure that the component is aligned and attached as 
shown.
1.

2015. 0 F-TYPE (X152), 501-08
EXTERIOR TRIM AND ORNAMENTATION
REAR SPOILER - COUPE (G1715738)
To install, reverse the removal procedure.
2.
REMOVAL AND INSTALLATION
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
CABRIOLET
0.
USED 
WITHINS
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
CABRIOLET, 
SVR
0.
USED 
WITHINS
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
COUPE, 
SVR
0.
USED 
WITHINS
76. 10.44
LUGGAGE 
COMPARTMENT 
LID SPOILER - 
RENEW
PROJECT
0.
USED 
WITHINS
76. 19.86
TAILGATE 
SPOILER - 
RENEW
COUPE
0.
USED 
WITHINS
REMOVAL

CAUTION:
Make sure to protect the paintwork.
NOTE:
Removal steps in this procedure may contain installation details.
1.
NOTE:
2.
Do not refit the two caps until the adjustment of the 
spoiler has been carried out.

NOTE:
3.
Repeat the step for the other side.

4.
5.

CAUTION:
Do not exceed the specified torque value.
6.

Torque: 9 Nm
CAUTION:
Do not exceed the specified torque value.
7.

Torque: 3.5 Nm
NOTE:
8.
Do not disassemble further if the component is removed 
for access only.

9.

Torque: 3.2 Nm
INSTALLATION
To install, reverse the removal procedure.
1.
CAUTION:
Make sure that the surface is clean and free of foreign 
material.
Adjust the rear spoiler by rotating the adjustment studs 
clockwise and counter clockwise as necessary.
2.

2015. 0 F-TYPE (X152), 501-09
REAR VIEW MIRRORS
SPECIFICATIONS
Torque Specifications
ITEM
NM
LB-FT
LB-IN
Exterior mirror bolt
9
-
80

2015. 0 F-TYPE (X152), 501-09
REAR VIEW MIRRORS
DESCRIPTION AND OPERATION
NOTE:
COMPONENT LOCATION
 shown, 
 mirror 
RHD (right-hand drive)
LHD (left-hand drive)
image.

ITEM
DESCRIPTION
1
Passenger door mirror
2
Passenger Door Module (PDM)
3
Interior mirror
4
Driver door mirror
5
Driver Door Module (DDM)
6
Driver door switchpack
AUTOMATIC DIMMING INTERIOR MIRROR
SYSTEM OPERATION

The automatic dimming function is permanently active when the 
ignition is in power mode 4 (Accessory) and power mode 6 (Ignition). 
The forward facing light sensor monitors the ambient light level at the 
front of the vehicle the rearward facing light sensor monitors the 
light level coming from the rear of the vehicle. When light from the 
rear of the vehicle exceeds the ambient light level from the front of 
the vehicle, the automatic dimming circuit darkens the interior mirror 
surface.
Automatic dimming is inhibited when reverse gear is selected to 
provide the driver with maximum vision. On vehicles with automatic 
transmission, the reverse gear signal is provided by the Transmission 
Control Module (TCM) via the high speed CAN bus to the CJB. The 
CJB then provides a power feed to the mirror. On vehicles with 
manual transmission, the reverse gear signal is provided by a 
transmission switch that is hardwired to the CJB.
Automatic dimming interior mirrors are connected to the vehicle 
wiring by an electrical connector in the mounting stem. The 
electrochromic mirror circuits and, where fitted, the universal 
transmitter, are powered by a feed from the central junction box 
(CJB) when the ignition is in power mode 6.
HOMELINK® UNIVERSAL TRANSMITTER
WARNING:
Before programming HomeLink® to a garage door opener or 
gate operator, make sure that people and objects are out of the 
way of the device to prevent potential harm or damage.
NOTES:
Garage door openers manufactured after 1996 may be 
equipped with rolling code protection feature. If this is the

The HomeLink® wireless control system provides a convenient way 
to replace up to three hand-held Radio Frequency (RF) transmitters 
used to activate devices such as gate operators, garage door 
openers, entry door locks, security systems, even home lighting.
PROGRAMMING HOMELINK® UNIVERSAL TRANSMITTER
NOTE:
Step
Turn the ignition On.
case, you may need a stepladder or other sturdy, safe device 
to reach the 
Learn
 or 
Smart
 button on the garage door 
opener.
When programming a garage door opener, it is advised to 
park outside of the garage.
Additional HomeLink® information can be found at www.
HomeLink.com. If additional programming support is needed, 
please call the toll-free HomeLink Hotline at 1-800-355-3515.
Please note that the instructions below apply to the majority of 
HomeLink® use cases. However, there are some HomeLink® 
applications or HomeLink® compatible systems that require 
slightly different instructions. For more information and for 
custom training instructions specific to your device, visit 
http://www.HomeLink.com.
HomeLink® is a registered trademark owned by GENTEX 
CORPORATION.
It is recommended that a new battery be placed in the hand-
held transmitter of the device being programmed to HomeLink® 
for quicker training and accurate transmission of the Radio 
Frequency (RF) signal.

Step
Press and hold the outer two switches of the HomeLink® universal 
transmitter until the status indicator begins to flash.
Step
Release the swiches.
This initializes the HomeLink® universal transmitter and erases 
previous settings from all three channels.
Step

Place the signal emitting end of the hand held transmitter 2 - 8 cm (1 
- 3 inches) away against the underside of the rear view mirror. Keep 
the status indicator in view.
Simultaneously press and hold the activation switch on the hand held 
transmitter and the chosen switch of the HomeLink® universal 
transmitter. The status indicator begins to flash slowly.
NOTE:
Step
The status indicator begins to flash rapidly. This can take up to
seconds.
Step
Release both switches.
Step
Do not release the buttons until the following step has been 
completed.

Press the programmed HomeLink® universal transmitter switch. The 
solid status indicator light indicates the successful programming.
To program another channel on the HomeLink® universal 
transmitter, repeat Steps 4 to 7.
Step
Turn the ignition Off.
To operate the previously programmed device, press and hold the 
chosen switch of the HomeLink® universal transmitter. Release the 
switch when the device begins to operate.
PROGRAMMING HOMELINK® UNIVERSAL TRANSMITTER - DEVICES 
WITH CODE PROTECTION FEATURE
The Radio Frequency (RF) signals used to operate some home/office 
systems incorporate a code protection feature. After a channel has 
been programmed from the hand held transmitter, these systems will 
need to be trained to accept the signal from the HomeLink® universal 
transmitter. To check if a system is code protected, operate the 
appropriate HomeLink® universal transmitter switch. If the status 
indicator flashes rapidly for 1 to 2 seconds before illuminating 
permanently, the system has a code protection feature.

Locate the 
Learn
 or 
Smart
 button at the garage door opener 
receiver (motor-head unit) in the garage before performing the 
following steps. This can usually be found directly on the motor-head 
unit (see the Garage Door Opener manual to identify the 
Learn 
Button
).
Step
Turn the ignition On.
Step
Press and hold the outer two switches of the HomeLink® universal 
transmitter until the status indicator begins to flash.
Step
Release the swiches.
This initializes the HomeLink® universal transmitter and erases 
previous settings from all three channels.
Step

Place the signal emitting end of the hand held transmitter 2 - 8 cm (1 
- 3 inches) away against the underside of the rear view mirror. Keep 
the status indicator in view.
Simultaneously press and hold the activation switch on the hand held 
transmitter and the chosen switch of the HomeLink® universal 
transmitter. The status indicator begins to flash slowly.
NOTE:
Step
The status indicator begins to flash rapidly. This can take up to
seconds.
Step
Release both switches.
DO NOT release the buttons until the following step has been 
completed.

Step
Press and release the 
Learn
 or 
Smart
 switch at the garage door 
opener receiver. The name and color of the switch may vary by 
manufacturer.
After the 
Learn
 or 
Smart
 switch has been released, a status 
indicator on the garage door opener receiver will continously lit.
Step
NOTE:
Perform the following step within 30 seconds.

Return to the vehicle and press and hold the chosen switch of the 
universal transmitter for 3 seconds to activate the device. Repeat this 
step up to three times to complete the training.
If the device activates, programming is complete.
Step
Turn the ignition Off.
To operate the previously programmed device, press and hold the 
chosen switch of the universal transmitter. Release the switch when 
the device begins to operate.
HIGH BEAM ASSIST

The high beam assist system is controlled by a high beam assist 
control module which is located in the interior rear view mirror body. 
The module and the CJB are connected via the medium speed CAN 
bus.
The high beam assist control module receives a power supply from 
the CJB when the ignition is in power mode 6 (ignition on). The rear 
view mirror also includes a low resolution camera (image) sensor 
which detects headlamps and tail lamps of preceding vehicles. The 
sensor is connected to the control module which evaluates the image 
data, checking for light intensity and location.
If conditions are correct and auto high beam assist has been 
activated, the control module will activate the high beam assist by 
sending a high or low beam request message to the CJB via the 
medium speed CAN bus. The CJB then controls the shutter in the 
Xenon projector module together with the high beam fill-in lamp. 
For additional information, refer to: 
 (417-01 Exterior 
Exterior Lighting
Lighting, Description and Operation). 
Interior Mirrors
COMPONENT DESCRIPTION

ITEM
DESCRIPTION
1
Rear light sensor
2
Front light sensor
3
Universal Transmitter Light Emitting Diode (LED) (market dependent
4
Universal Transmitter channel switch

The interior rear view mirror is provided as a electrically operated 
automatic dimming type.
The automatic dimming mirror comprises an electro-chromatic glass 
housed within a surrounding case that is attached with a ball joint 
connector to the mirror stem.
Light sensors are mounted on the front and rear of the mirror 
surround case. The sensors control the automatic dimming feature to 
reduce glare from the headlights of following vehicles.
Heating
Heating of the exterior mirrors is controlled by the CJB and the 
respective door modules, and is active while the ignition is in power 
mode 6 or 7.
The CJB receives the ambient air temperature value from the 
instrument cluster via the CAN (controller area network) bus. The CJB 
converts the ambient air temperature value to an on-time percentage 
and transmits it on the medium speed CAN bus to the two door 
modules, which then energize the exterior mirror heating elements 
accordingly. The on-time percentage is increased while the windshield 
wipers are on.
Exterior Mirror Heating Times
Ambient Air 
Temperature in °
C (°F)

-
(14)
- 10 to
(14 to 
32)
0 to
(32 to 
59)
15 to
(59 to 
77)
25 to
(77 to 
95)
!
(!95)
On-time 
Percentage
100
75
50
25
0
0
On-time 
Percentage With 
Wipers On
100
100
75
50
25
0
On vehicles with the parked heating function, exterior mirror heating 
may also operate when the parked heating function is active, 
depending on the ambient air temperature.

For additional information, refer to: 
 (412-01 Climate 
Air Conditioning
Control, Description and Operation). 
Dimming
Exterior mirrors with automatic dimming are slaved to the interior 
mirror. The interior mirror determines the amount of dimming 
required and energizes the electrochromic elements in the exterior 
mirrors accordingly. Feed and ground wires from the interior mirror, 
for the electrochromic elements in the exterior mirrors, bypass the 
door modules and connect directly to the exterior mirrors.
Mirror Memory
The seat, exterior mirrors and steering column memory functions are 
integrated into the CJB.
The driver and front passenger door modules control the mirror 
memory while the driver seat module controls the seat and the CJB 
controls the steering column memory.
Located on the outboard side of the driver seat plinth, the memory 
switch and memory pre-set switches can be used to store 3 different 
mirror positions. When a position is stored or recalled, the 
information is transmitted to the CJB via the medium speed CAN. It is 
then relayed to the door modules. Each door module evaluates the 
recalling and storage commands transmitted via the medium 
speedCAN for positions 1 to 3 and performs the necessary 
adjustments.
If a manual adjustment is selected while the mirror memory is 
operating, it will over-ride the memory recall function.
For mirror memory to operate, the mirror adjustment potentiometers 
must deliver a voltage value in the range of 80mV - 4.8V. Should a 
voltage applied be outside of this range the mirror will not operate 
when memory is selected.
Reverse Dipping

If the customer has activated reverse dipping when reverse gear is 
selected and the vehicle is in power mode 6 or 7, the driver and 
passenger exterior mirrors dip to provide a better view of the kerb. 
The mirrors return to their original position immediately upon reverse 
gear being disengaged.
The kerb view mirror position can be adjusted using the mirror 
adjustment multi-directional switch while reverse gear is selected and 
the vehicle in power mode 6 or 7.
Blind Spot Monitoring
NOTE:
ITEM
DESCRIPTION
1
Warning alert icon
2
System status warning indicator
Blind spot monitoring function alerts the driver to a vehicle located in 
the vehicle blind spot. A warning indicator is located in each exterior 
mirror towards the outer edge. 
Some variation in the illustrations may occur, but the essential 
information is always correct.

For additional information, refer to: 

Blindspot Monitoring System
(413-09 Warning Devices, Description and Operation). 
Electrochromic Mirror
The electrochromic mirrors automatically dim to reduce glare from 
the headlights of following vehicles in dark or low light conditions. In 
addition to dimming the interior mirror, the electrochromic mirror 
circuits also control the dimming of the two exterior mirrors, via 
power feed and ground connections with the 2 exterior mirrors.
A light sensor on the front of the interior mirror monitors ambient 
light at the front of the vehicle and a light sensor in the interior 
mirror glass monitors the light coming from behind the vehicle. When 
the light from behind the vehicle exceeds the ambient light level, the 
electrochromic circuits simultaneously dim the interior and exterior 
mirrors. Dimming is inhibited when reverse gear is selected. The 
interior mirror is provided with a reverse gear signal by the Lighting 
Control Module (LCM).
NOTE:
CONTROL DIAGRAM
   Hardwired    Medium Speed 
A
N
CAN (controller area 
 bus    
 bus
network)
O
LIN (local interconnect network)

ITEM
DESCRIPTION
1
Central Junction Box (CJB)
2
Driver door switchpack
3
Interior rear view mirror

2015. 0 F-TYPE (X152), 412-01
CLIMATE CONTROL
4
Driver door mirror
5
Passenger door mirror
6
Passenger Door Module (PDM)
7
Driver Door Module (DDM)
DESCRIPTION AND OPERATION

ITEM
DESCRIPTION
1
Evaporator
2
Thermostatic expansion valve
3
Air conditioning compressor
4
Receiver drier
5
Condenser
6
Refrigerant pressure sensor
7
High pressure servicing connection
8
Low pressure servicing connection
COMPONENT LOCATION

The 
 system is a sealed, closed loop system 
A/C (air conditioning)
filled with a charge weight of refrigerant as the heat transfer medium. 
Oil is added to the refrigerant to lubricate the internal components of 
the 
 compressor. The system consists of:
A/C
An 
 compressor
A/C
A condenser
A receiver drier
A thermostatic expansion valve
An evaporator
Low and high pressure refrigerant lines.
A pressure sensor in the high pressure refrigerant line allows the 
ATCM (automatic temperature control module) to monitor the status 
of the 
 system. 
A/C
For additional information, refer to: 
 (412-01 
Control Components
Climate Control, Description and Operation). 
AIR CONDITIONING COMPRESSOR
ITEM
DESCRIPTION
OVERVIEW
DESCRIPTION

1
Pulley
2
Refrigerant outlet port
3
Pressure relief valve
4
Electronic control valve
5
Refrigerant inlet port
6
Electrical connector
On all engine variants, the 
 compressor is a variable displacement 
A/C
unit attached to the front left side of the engine with three bolts.
The compressor is driven by the engine accessory drive belt via an 
electro-magnetic clutch in the compressor pulley. The ATCM uses a 
relay in the left 
 to control the operation of 
EJB (engine junction box)
the electro-magnetic clutch. The clutch incorporates a thermal cut-off 
fuse, which disconnects the power feed from the relay if the 
temperature increases to 182  5 °C (360  9 °F).
The displacement of the compressor is controlled by an integral 
electronic control valve, which is operated by the ATCM. The ATCM 
automatically adjusts the displacement of the 
 compressor, 
A/C
between the minimum and maximum values, to match the thermal 
load of the evaporator.
To protect the refrigerant system from excessive pressure, a pressure 
relief valve is installed in the outlet side of the 
 compressor. The 
A/C
pressure relief valve vents excess pressure into the engine 
compartment.
CONDENSER AND RECEIVER DRIER

ITEM
DESCRIPTION
1
Right end tank
2
Condenser core
3
Left end tank
4
Mounting bracket (4 off)
5
High pressure compressor discharge line connector block
6
High pressure liquid outlet line connector block
7
Receiver drier outlet pipe
8
Receiver drier inlet pipe

9
Receiver drier
10
Desiccant access plug
The condenser is installed immediately in front of the radiator. Two 
brackets on each end tank attach the condenser to the end tanks of 
the radiator.
The condenser is classified as a sub-cooling condenser and consists of 
a fin and tube heat exchanger core installed between 2 end tanks. 
Divisions in the end tanks separate the heat exchanger into a 4 pass 
upper (condenser) section and a 2 pass lower (sub-cooler) section.
The left end tank provides the connections for the refrigerant lines 
from the 
 compressor and to the evaporator.
A/C
The right end tank provides the connections to the receiver drier. 
Refrigerant entering the receiver drier passes through a combined 
filter and desiccant pack then collects in the base of the unit before 
flowing through the outlet pipe back to the condenser. The receiver 
drier is part of the condenser assembly and is not serviceable 
separately. However, the receiver drier desiccant pack can be 
replaced using an access plug in the base of the receiver drier.
THERMOSTATIC EXPANSION VALVE
The thermostatic expansion valve is a block type valve attached to 
the inlet and outlet ports of the evaporator, under a thermal 
insulation cover. Two bolts secure the refrigerant pipes and the

thermostatic expansion valve to the inlet and outlet ports of the 
evaporator.
EVAPORATOR
The evaporator is a fin and tube heat exchanger installed in the 
climate control assembly, between the blower and the heater core.
REFRIGERANT LINES
The refrigerant lines consist of a combination of rigid pipes and 
flexible hoses that connect the thermostatic expansion valve on the 
evaporator to the 
 compressor and the condenser.
A/C
Low and high pressure servicing connections are incorporated into the 
refrigerant lines for system servicing. The high pressure line also 
incorporates a refrigerant pressure sensor for the climate control 
system. 
For additional information, refer to: 
 (412-01 
Control Components
Climate Control, Description and Operation). 
The 
 compressor circulates the refrigerant around the system by 
A/C
compressing low pressure, low temperature vapor from the 
evaporator and discharging the resultant high pressure, high 
temperature vapor to the condenser. In the condenser the vapor 
converts to a liquid, which then passes through the receiver drier and 
out of the condenser to the thermostatic expansion valve. As it 
passes through the thermostatic expansion valve, the liquid 
OPERATION

refrigerant changes to a fine, low pressure, spray, which is directed 
into the evaporator. In the evaporator the refrigerant changes back 
to a low pressure, low temperature vapor, as it absorbs heat from the 
air in the passenger compartment, then returns to the 

A/C
compressor to begin the cycle again.
Operation of the air conditioning system is controlled by the ATCM, 
which adjust the electronic control valve in the 
 compressor to 
A/C
match the refrigerant flow around the system to the thermal load of 
the evaporator. By matching refrigerant flow to the thermal load of 
the evaporator, the ATCM maintains the required temperature in the 
passenger compartment while maximizing fuel economy. In addition, 
the ATCM sends an engine cooling fan request on the medium speed 
 bus to the 
CAN (controller area network)
ECM (engine control module)
. The amount of cooling fan requested is dependent on the high side 
refrigerant pressure measured by the refrigerant pressure sensor.
Air Conditioning System Schematic
A   REFRIGERANT VAPOR B   REFRIGERANT LI4UID C   AIR 
FLOW.

2015. 0 F-TYPE (X152), 417-01
EXTERIOR LIGHTING
ITEM
DESCRIPTION
1
Evaporator
2
Thermostatic expansion valve
3
High pressure servicing connection
4
Refrigerant pressure sensor
5
Air conditioning compressor
6
Condenser
7
Receiver drier
8
Engine cooling fan
9
Low pressure servicing connection
10
Blower
DESCRIPTION AND OPERATION

ITEM
DESCRIPTION
1
Auto High Beam Control Module (AHBCM)
2
Left side repeater lamp
3
Left headlamp assembly
4
Front right height sensor
5
Rear right height sensor
6
Right headlamp assembly
7
Right side repeater lamp
COMPONENT LOCATION - SHEET 1 OF

A   V6 3.0L SUPERCHARGER (SC) PETROL VEHICLES B   V8 5.0L 
SC PETROL VEHICLES.
ITEM
DESCRIPTION
1
Left tail lamp assembly
2
High Mounted Stop Lamp (HMSL)
3
Right tail lamp assembly
4
Right fog/reverse lamp (all except NAS)
5
Left fog/reverse lamp (all except NAS)
6
Left fog/reverse lamp (NAS only)
COMPONENT LOCATION - SHEET 2 OF

7
License plate lamps
8
High Mounted Stop Lamp (HMSL)
9
Right fog/reverse lamp (NAS only)
10
Right tail lamp assembly
11
Right fog/reverse lamp
12
Left fog/reverse lamp
13
Left tail lamp assembly

ITEM
DESCRIPTION
1
Light control switch and left steering column multifunction switch
COMPONENT LOCATION - SHEET 3 OF

2
Rear fog lamp switch
3
Headlamp Leveling Control Module (HLCM)
4
Brake pedal switch
5
Hazard warning lamp switch

ITEM
DESCRIPTION
1
High Mounted Stop Lamp (HMSL)
Exterior lighting consists of:
Two headlamp assemblies, each containing a:
Headlamp.
Cornering lamp or static bending lamp (model dependant).
Turn signal indicator.
COMPONENT LOCATION - SHEET 4 OF 4 - COUPE HIGH MOUNTED STOP LAMP
OVERVIEW

Combined daytime running lamp and side lamp.
Side marker lamp and reflector (NAS only).
Two tail lamp assemblies, each containing a:
Turn signal indicator.
Tail lamp.
Stop lamp.
Rear side markers.
Two fog/reverse lamps.
A HMSL.
Two license plate lamps.
Two side repeater lamps.
A HLCM.
Two height sensors.
An auto high beam camera (model/market dependant).
A brake pedal switch.
A lighting control switch and steering column multifunction switch.
A rear fog lamp switch.
A hazard warning lamp switch.
Warning indicators.
The exterior lighting is controlled by the Central Junction Box (CJB). 
The CJB controls the following vehicle functions:
Control and monitoring of exterior lamps including turn signal 
indicators and hazard warning lamp functionality.
Monitoring and evaluation of check control inputs from other 
system control modules and output of applicable messages in the 
Instrument Cluster (IC) message center.
The CJB is connected to the Medium Speed (MS) and High Speed 
(HS) Controller Area Network (CAN) buses. The CJB contains a

microprocessor which performs the control, monitoring and 
evaluation of functions.
The HLCM provides signals to control headlamp leveling and, where 
fitted, the AFS (adaptive front lighting system) headlamps.
Driver lighting selections are made using the lighting control switch 
and left steering column multifunction switch, the rear fog lamp 
switch and the hazard warning lamp switch. The CJB operates the 
brake lamps using the inputs from the brake pedal switch.
Depending on model and market specification, the lighting system 
may have:
An auto high beam function, where the headlamps are 
automatically switched between low and high beam in response to 
signals from the auto high beam camera.
An autolamps function, where the exterior lights are automatically 
turned on or off in response to signals from the rain/light sensor 
used for automatic wiper operation. 
For additional information, refer to: 
 (501-16 
Wipers and Washers
Wipers and Washers, Description and Operation). 
All headlamps are xenon, with signaling functions controlled by Light 
Emitting Diode¶s (LED) within the headlamp assemblies. All tail lamp 
assemblies contain LED lamps, with no serviceable parts. The fog and 
reverse lamps for non NAS V6 3.0L SC petrol vehicles have an 
incandescent light source (P21W x2). The fog and reverse lamps for 
NAS V6 3.0L SC petrol vehicles and all V8 5.0L SC petrol vehicles use 
LED light sources.
HEADLAMP ASSEMBLIES
DESCRIPTION

ITEM
DESCRIPTION
1
Turn signal indicator
2
Daytime running lamp/side lamp
3
Cornering lamp or static bending lamp (where fitted)
4
Xenon headlamp
5
Lens
6
Side marker lamp (NAS only)
7
Reflector (NAS only)
8
Vertical adjuster
9
Horizontal adjuster
10
Xenon bulb and igniter
11
Securing bolt and washer
12
Housing
13
LED driver module

14
Xenon bulb control module
15
Securing bolt and washer
16
Vent
17
Securing bolt and washer
18
Electrical connector
19
Cap
Each headlamp assembly is secured to the front body structure with 
three bolts and washers. The rear of the headlamp assembly has a 
removable cap for access to the xenon headlamp bulb. The headlamp 
assembly has two adjustment screws on the rear which allow for the 
manual setting of the vertical and horizontal alignment.
Each headlamp assembly has an integral 16 pin connector which 
provides inputs and outputs for the various functions of the headlamp 
assembly. A xenon bulb control module and a LED driver module are 
installed on the underside of the headlamp housing, to control power 
to the xenon headlamps and the LED lamps respectively.
Two types of headlamp are available xenon or xenon with AFS. The 
xenon with AFS headlamp has a swiveling projector module which 
moves the headlamp beam in the direction of travel. Headlamp 
assemblies with the AFS headlamp also feature a cornering lamp and 
a static bending lamp, which illuminates the inside of a corner when 
turning at low speed. Both types of headlamp incorporate static 
automatic leveling.
The headlamp beam pattern is suitable for driving on either side of 
the road. There is no need for any mechanical adjustment or external 
decals.
XENON HEADLAMPS
WARNING:

The xenon system generates up to 28000 volts and contact with 
this voltage could lead to fatality. Make sure that the headlamps 
are switched off before working on the system.
The following safety precautions must be followed when working 
on a xenon headlamp system:
DO NOT attempt any procedures on the xenon headlamps 
when the lights are switched on.
Handling of the xenon bulb must be performed using suitable 
protective equipment, e.g. gloves and goggles. The glass part 
of the bulb must not be touched.
Xenon bulbs must be disposed of as hazardous waste.
Only operate the lamp in a mounted condition in the reflector.
The xenon headlamp operates as both a low and high beam unit. The 
unit comprises a reflector, an adaptor ring, the lens, a shutter 
controller and the xenon bulb, which together is an assembly known 
as the projector module. The projector module is installed in a carrier 
frame that allows the module to tilt for vertical movement of the 
headlamp beam. Vertical movement is controlled by an actuator, 
connected between the carrier frame and the projector module, 
operated by the HLCM for automatic headlamp leveling.
The reflector is curved and provides the mounting for the xenon bulb. 
The bulb locates in a keyway to ensure correct alignment in the 
reflector and is secured by a plastic mounting ring. The bulb is an 
integral part of the xenon bulb igniter. The shutter controller is a 
solenoid which operates the shutter mechanism via a lever. The 
shutter is used to change the beam projection between low and high 
beam.
The xenon headlamps are controlled by the CJB using a xenon bulb 
control module and a xenon bulb igniter for each headlamp. These 
provide the regulated power supply required to illuminate the xenon 
bulbs through their start-up phases of operation.

The xenon bulbs illuminate when an arc of electrical current is 
established between 2 electrodes within the bulb. The xenon gas 
sealed in the bulb reacts to the electrical excitation and the heat 
generated by the current flow produces the characteristic blue/white 
light.
To operate at full efficiency, the xenon bulb goes through 3 stages of 
operation before the output for continuous operation is achieved. The 
3 phases are start-up phase, warm-up phase and continuous phase.
In the start-up phase, the bulb requires an initial high voltage 
starting pulse of up to 28000 volts in order to establish the arc. This 
high voltage starting pulse is produced by the igniter and, once the 
arc is established, the warm-up phase begins. During the warm-up 
phase, the xenon bulb control module regulates the supply to the 
bulb to 2.6A which gives a lamp output of 75W. While in this phase, 
the xenon gas begins to illuminate brightly and the environment 
within the bulb stabilizes, ensuring a continual current flow between 
the electrodes. When the warm-up phase is complete, the xenon bulb 
control module changes to continuous phase. The supply voltage to 
the bulb is reduced and the operating power required for continual 
operation is reduced to 35W. The process from start-up to continuous 
phase is completed in a very short time.
The xenon bulb control modules (one per headlamp) receive an 
operating voltage from the CJB when the headlamps are switched on. 
The modules regulate the power supply required through the phases 
of start-up.
The xenon bulb igniters (one per headlamp) generate the initial high 
voltage required to establish the arc. The igniters have integral coils 
which generate the high voltage pulses required for start-up. Once 
the xenon bulbs are operating, the igniters provide a closed circuit for 
the regulated power supply from the xenon bulb control modules.
ADAPTIVE FRONT LIGHTING SYSTEM

The AFS headlamp assembly contains an additional carrier frame 
which provides a location for the horizontal actuator. The projector 
module has a central pivot point which allows the module to move 
horizontally in response to operation of the horizontal actuator.
The AFS actuators are bi-polar (2 phase) dc stepper motors which are 
driven by a power output from the AFS power module located in the 
headlamp assembly. Each stepper motor receives its position 
information from the HLCM via the applicable AFS power module. 
When the actuators are powered to their requested positions, a 
holding current is applied to maintain the actuator position.
The actuators do not supply a positional feedback signal to the HLCM. 
Each stepper motor requires referencing each time the AFS system 
becomes active. When the AFS system is active, each vertical 
actuator is driven to the low beam position and each horizontal 
actuator is driven to an inboard position until a mechanical stop in 
the actuator is reached. Once the stop is reached a step counter in 
the HLCM is set to zero and the actuator is then powered to the 
operating position as determined by the AFS software.
Headlamp Beam Diagram
ITEM
DESCRIPTION
A
Conventional headlamp beam distribution
B
AFS swivel headlamp beam distribution

TAIL LAMP ASSEMBLIES
ITEM
DESCRIPTION
1
Vent
2
Housing
3
Securing nut and washer
4
Vent
5
Electrical connector
6
Turn signal indicator
7
Stop lamp
8
Reflector
9
Securing nut and washer
10
Tail lamp
11
Lens
12
Reflector

Each tail lamp assembly is attached to the rear quarter and the back 
panel of the luggage compartment with three nuts and washers.
FOG/REVERSE LAMPS
A   V6 3.0L SC PETROL VEHICLES (ALL EXCEPT NAS) B   V6 3.0L 
SC PETROL VEHICLES (NAS ONLY) AND V8 SC 5.0L PETROL 
VEHICLES.
ITEM
DESCRIPTION
1
Housing
2
Fog lamp bulb holder
3
Electrical connector
4
Reverse lamp bulb holder
5
Vent
6
Securing screw
7
Lens
Each fog/reverse lamp is attached to the rear valance with three 
screws and contains either bulbs or LEDs, depending on model and 
market specification.

Fog/Reverse lamps that contain bulbs have separate clear bulbs for 
the fog and reverse lamps. The bulbs are installed in bulb holders 
located in separate compartments in the housing, and the lens is split 
into red and clear areas as appropriate for the two lamps.
Fog/Reverse lamps that contain LEDs have different colored LEDs for 
the fog and reverse lamps located in a single compartment, and a 
clear lens.
HIGH MOUNTED STOP LAMP
ITEM
DESCRIPTION
1
Bezel/Cover
2
Lamp assembly
3
Bolt and washer
4
Gasket
5
Electrical connector
6
Bolt and washer
The high mounted stop lamp is located under the trailing edge of the 
deployable spoiler on the luggage compartment lid. The lamp is 
secured to the luggage compartment lid with four bolts and washers 
concealed under a bezel, which clips onto the lamp. A gasket seals 
the interface between the lamp and the luggage compartment lid.

LICENSE PLATE LAMPS
Two license plate lamps are located in the underside of an exterior 
finisher on the luggage compartment lid. Each lamp is secured to the 
finisher with spring clip located at the right end of the lamp.
The license plate lamps are illuminated at all times when the side 
lamps are active.
SIDE REPEATER LAMPS
A side repeater lamp for the turn signal indicators is located in each 
exterior mirror, and can be accessed by removing the mirror cap.
HEADLAMP LEVELING CONTROL MODULE (HLCM)
NOTE:
The HLCM contains software for controlling xenon headlamp 
levelling and also Adaptove Front lighting system(AFS) when 
fitted.

The HLCM is located on the bulkhead panel, adjacent to the right A 
pillar. The HLCM controls headlamp leveling and, where fitted, the 
AFS headlamps and the static bending lamps. The HLCM is connected 
to the HS CAN bus and receives inputs from other vehicle systems on 
the status of the following parameters:
Height sensors
Steering angle
Vehicle speed
Headlamp status
Engine running
Reverse gear selected.
The HLCM is connected to each AFS motor on a private Local 
Interconnect Network (LIN) bus.
HEIGHT SENSORS
NOTE:
Rear height sensor shown front height sensor similar.

The height sensors used by headlamp leveling are both located on 
the right side of the vehicle.
The body of the front height sensor is attached to a bracket on the 
front subframe. The sensor link rod is connected to a pin screwed into 
the lower suspension arm.
The body of the rear height sensor is attached to the rear subframe. 
The sensor link rod is connected to a clip attached to the upper 
suspension arm.
Each sensor has three connections with the Integrated Suspension 
Control Module (ISCM) power, ground and signal. The ISCM outputs 
the suspension height data to the HLCM on the HS CAN bus.
AUTO HIGH BEAM CAMERA

Vehicles with the auto high beam feature have an auto high beam 
camera installed in the covers of the rear view mirror support, with 
the lens directed forward through the windshield. The camera is 
connected to the AHBCM, integrated into the body of the rear view 
mirror.
The camera is a low resolution image sensor that detects headlamps 
and tail lamps of preceding vehicles. The AHBCM evaluates the image 
data, checking for light intensity and location. Depending on the 
image data, the control module then sends a high or low beam 
request message to the CJB via MS CAN bus. The CJB then controls 
the shutter in the Xenon projector module accordingly.
BRAKE PEDAL SWITCH

The brake pedal switch is a two pole switch mounted in the brake 
pedal bracket and operated by the brake pedal. The output 
connections of the two poles are hardwired to the CJB. The input 
connection of one pole is a hardwired signal feed from the CJB. The 
input connection of the second pole is hardwired to ground. The CJB 
compares the signals from the two poles to confirm the status of the 
brake pedal switch, which it uses to operate the stop lamps.
NOTE:
LIGHTING CONTROL SWITCH AND LEFT STEERING COLUMN 
MULTIFUNCTION SWITCH
The output connections are also connected to the Engine Control 
Module (ECM)

ITEM
DESCRIPTION
1
Off position
2
Side lamp position
3
High beam position
4
Right turn signal indicator position
5
Headlamp flash/high beam off position
6
Left turn signal indicator position
7
Headlamp position
8
Autolamps position
9
Headlamp timer 120 second delay position
10
Headlamp timer 60 second position
11
Headlamp timer 30 second position

The lighting control switch is located on the left steering column 
multifunction switch. The lighting control switch is a rotary control 
with positions for the following lighting functions:
Off
Side and tail lamps
Headlamps
Autolamps
Headlamp delay timer (3 time period selections).
The left steering column multifunction switch also provides for the 
following functions:
High beam headlamps
Headlamp flash
Turn signal indicators
Trip computer function. 
For additional information, refer to: Information and Message Center
(413-08 Information and Message Center, Description and 
Operation). 
For both the lighting control switch and steering column multifunction 
switch, analogue inputs are used by the CJB. When a switching event 
occurs, the change of input voltage, referenced against the reference 
ground, is assessed in order to determine which switching mechanism 
was activated.
REAR FOG LAMP SWITCH

The rear fog lamp switch is a non-latching momentary switch 
installed on the auxiliary lighting switch in the instrument panel, 
adjacent to the steering column.
HA=ARD WARNING LAMP SWITCH
The hazard warning lamp switch is located on the Integrated Control 
Panel (ICP), and hardwired to the CJB and ground.
WARNING INDICATORS

ITEM
DESCRIPTION
1
Side lamps
2
Headlamp high beam
3
Turn signal indicators
4
Rear fog lamps
5
Auto high beam
6
Adaptive Front lighting System (AFS)
The AFS warning indicator is activated by a HS CAN bus message 
from the HLCM to the IC. The remainder of the exterior lighting 
warning indicators are activated by the CJB using MS CAN bus 
messages to the IC.
CENTRAL JUNCTION BOX
The lighting circuits are protected by conventional fuses and Metal 
Oxide Semiconductor Field Effect Transistors (MOSFET). The control 
circuitry within the CJB for each individual circuit can detect and 
OPERATION

isolate a problem circuit. The exterior lamps are energized by power 
feeds from the CJB, except for the side repeater lamps, which are 
energized by power feeds from the related door module in response 
to MS CAN signals from the CJB.
INPUT SIGNALS FOR LAMP CONTROL
The CJB receives inputs from the following switches:
Lighting control switch and left steering column multifunction switch 
for turn signal indicators, side lamps, headlamps, low/high beam
/headlamp flash and autolamps.
Rear fog lamp switch.
Hazard warning lamp switch.
Brake pedal switch.
Stop/Start switch.
A reverse gear engaged signal is also received on the HS CAN bus 
from the Transmission Control Switch (TCS) to enable the CJB to 
activate the reverse lamps.
The CJB activates the hazard warning indicators if an alarm is 
activated and to signify vehicle locking and unlocking to the driver. 
The CJB also receives requests to activate the hazard warning 
indicators from:
The Restraints Control Module (RCM), via a hardwired connection 
and the HS CAN bus, in the event of a crash.
The Anti-lock Brake System (ABS) control module, via the HS CAN 
bus, if vehicle deceleration exceeds a stored value during 
emergency braking.
On vehicles with auto high beam, the AHBCM outputs signals on the 
MS CAN bus to the CJB to control the high beam headlamps.
If the Electronic Parking Brake (EPB) is applied while the vehicle is 
moving above 2 mph (3 km/h), the Electric Park Brake Control

Module (EPBCM) sends a HS CAN message to the CJB to activate the 
stop lamps.
CIRCUIT PROTECTION
Operation of the lamps is performed using MOSFET
s. The MOSFET
s 
can detect overload, load interruption with the lamps switched on and 
short circuit to positive with the lamps switched off.
The MOSFET
s replace the traditional requirement for fusing by acting 
as a sort of resettable fuse, with associated Diagnostic Trouble Code 
(DTC)
s. However, fuses are still used when relays are implemented 
instead of MOSFET
s.
LAMP MONITORING
Bulb and LED failure monitoring is performed by the CJB. The lamps 
are monitored by the MOSFET
s in order to detect failure.
The CJB processor provides outputs to each MOSFET. The output 
switches the MOSFET to supply the required output to power the 
applicable lighting circuit. The processor evaluates the circuits by 
detecting the returned signals from the controlling MOSFET.
If a turn signal indicator fails, Instrument Cluster (IC) and an audible 
warning will double rate.
Different types MOSFET device are used to control the lighting 
functions. Depending on what type of MOSFET is used, load 
interruption failure detection may or may not be possible. The table 
below shows for what functions load interruption failures are 
detectable. When a bulb or LED failure is detected, a DTC is 
generated, which can be retrieved using Jaguar approved diagnostic 
equipment.
Below is a table showing whether open load detection is available for 
each function:
FUNCTION
OPEN LOAD DETECTION

DISABLED
Right cornering lamp
No
Left cornering lamp
No
Right DRL
Yes
Left DRL
Yes
Right side lamp
Yes
Left side lamp
Yes
Right headlamp high beam shutter
No
Left headlamp high beam shutter
No
Right headlamp low beam
Yes
Left headlamp low beam
Yes
Front right turn signal indicator
No
Front left turn signal indicator
No
Right and left reverse lamps (bulbs)
Fused
Right and left reverse lamps (LEDs)
Fused
Right tail lamp and license plate lamps (Left-Hand 
Drive-(LHD))
Yes
Left tail lamp and license plate lamps (Right Hand 
Drive-(RHD))
Yes
Rear right turn signal indicator
No
Rear left turn signal indicator
No
Right stop lamp
No
Left stop lamp
No
High mounted stop lamp
No
Right rear fog lamp (bulb)
Fused
Right rear fog lamp (LED)
Fused
Left rear fog lamp (bulb)
Fused
Left rear fog lamp (LED)
Fused

In some instances, the MOSFET
s can reach high temperatures 
without a short to ground detection occurring. In these cases, the 
MOSFET
s will react to the heat increase and cut the supply to the 
affected circuit. Once the fault has been rectified or the MOSFET has 
cooled, the MOSFET will automatically reset and operate the circuit 
normally.
INSTRUMENT CLUSTER AND SWITCH ILLUMINATION
The CJB controls the IC backlighting illumination and also illumination 
of all instrument panel switches. IC and switch illumination is 
activated when the lighting control switch is in the side lamp or 
headlamp position.
IC WARNING INDICATOR ILLUMINATION
The warning indicators in the IC for left and right turn signal 
indicator, rear fog lamps, headlamp high beam and side lamps are 
activated by the CJB via messages to the IC on the MS and HS CAN 
buses. The synchronisation of the turn signal warning indicator with 
the turn signal indicator frequency is controlled by a cyclic 
transmission of the light status on the MS CAN bus.
The AFS warning indicator is controlled by a HS CAN signal from the 
HLCM.
DAYTIME RUNNING LAMPS (DRL)
The DRL
s are initially activated when the following parameters are 
met:
The lighting control switch is in the off or autolamps position (when 
autolamps are not requested on).
P (park) is not selected.
The CJB receives an engine running signal.
The ignition state is Power mode 7.
The DRL shall remain off if:

PARK is still selected
or
NEUTRAL is selected AND while the parking brake is applied.
or
The vehicle is not set in motion for the first time after a manually 
activated ignition cycle (not an auto Stop/Start sequence).
If the lighting control switch is moved to the side lamp or headlamp 
positions, DRL are deactivated and normal side lamp and headlamp 
functionality is operational. - Certain markets use DRL¶s in different 
ways and may not be disabled when selecting side lights.
When DRL are active, the headlamp flash function using the left hand 
steering column multifunction switch will operate normally.
In NAS markets, when the parking brake is applied or the TCS is in 
the P position, the DRL are turned off. This is to reduce battery 
discharge during long periods of engine idling in cold climate 
conditions. When the parking brake is released or the TCS is moved 
from the P position, normal DRL functionality is restored.
DRL
s must be switched off during the entire operation cycle of the 
direction indicators, on the same side of the vehicle as the active 
direction indicator lamp or Hazard Warning Signal.
HEADLAMPS
The low beam headlamps are switched on when the ignition is on and 
one of the following occurs:
The lighting control switch is the headlamp position.
The lighting control switch is in the autolamps position and a lights 
on signal is received by the CJB from the rain/light sensor.

The headlamps can be switched on by pressing the headlamp 
switch on the Smartkey. Smartkey signals are relayed to the CJB by 
the KVM (keyless vehicle module) on the MS CAN bus.
The low beam headlamps can also be operated by the headlamp 
delay feature.
The high beam headlamps are switched on when the ignition is on 
and one of the following occurs:
The lighting control switch is in the headlamp position or the 
headlamps are activated by the autolamps feature and the left 
steering column multifunction switch is pushed forward, away from 
the driver.
The auto high beam system is active.
The headlamp flash function operates with the ignition on or off, 
when the left steering column multifunction switch is pulled towards 
the driver.
HEADLAMP DELAY
The CJB controls a headlamp delay function which illuminates the 
headlamps after the ignition is turned off. The headlamp delay will 
operate on low beam headlamps only regardless of the position of the 
left steering column multifunction switch.
To initiate this feature, the lighting control switch must be in one of 
the three headlamp timer positions when the ignition mode is 
changed from on to off. The low beam headlamps will then remain on 
for the selected time period (30, 60 or 120 seconds) after the ignition 
is turned off.
The headlamp delay feature can also be switched off by pressing the 
headlamp switch on the Smartkey. Smartkey signals are relayed to 
the CJB by the KVM on the MS CAN bus.
HEADLAMP LEVELING

When the ignition is on, power is supplied from the extended ignition 
relay in the CJB to the HLCM. When the HLCM receives a power 
supply from the extended ignition relay, it performs an initialization 
procedure to correctly align the vertical aim of the headlamps and to 
determine if the leveling motors are functioning correctly.
The HLCM receives information relating to vehicle attitude from the 
front right and rear right height sensors, relayed from the ISCM on 
the HS CAN bus. The HLCM processes these signals and provides an 
output to the headlamp leveling motors to adjust the headlamp 
vertical aim according to vehicle speed and attitude.
ADAPTIVE FRONT LIGHTING SYSTEM
The AFS will only operate when the HLCM receives an engine running 
signal on the HS CAN bus. When the engine running signal is received 
the HLCM performs an initialization routine.
The AFS will also function when the lighting control switch is in the 
AUTO position and the HLCM receives a lights on signal from the rain
/light sensor and an engine running signal.
The HLCM then monitors the inputs from the other vehicle systems to 
control the AFS functionality according to cornering (steering) angles 
and vehicle speed.
The AFS controls the swiveling angle of each projector module using 
speed and steering angle signals received from the ABS control 
module on the HS CAN bus. The angles of each projector module 
differ to give the correct spread of light, e.g. when turning left, the 
left hand projector module will have a greater swiveling angle than 
the right hand projector module.
INITIALI=ATION PROCEDURE
When the HLCM receives an ignition on signal, it performs the 
initialization procedure which ensures that the headlamps are 
correctly aligned on both their vertical and horizontal axes.

The AFS swivel initialization starts less than 1 second after the 
headlamp leveling initialization is activated to ensure that the 
headlamps are at or below the 0 degree position in the vertical axis, 
thus preventing glare to oncoming vehicles. The AFS swivel 
initialization is completed in less than 2.5 seconds. The left and right 
AFS actuator motors are powered from the 0 degree position to a 
small movement to the inboard position, then another small 
movement to the outboard position and then back to the 0 degree 
position.
FAILURE MODE
In the event of a failure of the AFS system, a warning indicator in the 
IC is illuminated to warn the driver. The AFS warning indicator 
illuminates when the ignition is in on and will flash continuously until 
the fault is rectified. The AFS warning indicator will also be 
illuminated if a failure of the steering angle sensor or the vehicle 
speed signal is detected.
Illumination of the AFS warning indicator does not necessarily mean 
that there is a fault with the AFS system. The fault may be caused by 
a failure of another system preventing the AFS system operating 
correctly.
The HLCM performs a diagnostic routine every time AFS is requested. 
If any fault is found, the HLCM will suspend the operation of the AFS 
function.
If the AFS leveling system has failed with the xenon projector module 
in a position other than the correct straight ahead position, the HLCM 
will attempt to drive the projector module to a position a small 
amount lower than the standard position. If the swivel function has 
failed, the HLCM will lower the projector module using the leveling 
actuator motors to a position much lower than standard to prevent 
excess glare to oncoming vehicles.

The HLCM software can detect an internal failure of the control 
module control circuits. The control module will power the projector 
modules to the zero position and prevent further operation.
Faults can be investigated by interrogating the HLCM using the 
Jaguar approved diagnostic equipment to check for fault codes.
AUTOLAMPS
The CJB uses the rain/light sensor to control the autolamps 
functionality. The wiper system also uses the rain/light sensor for 
automatic wiper operation. 
For additional information, refer to: 
 (501-16 
Wipers and Washers
Wipers and Washers, Description and Operation). 
The driver can override the system operation by selection of side 
lamps or headlamps on if the ambient light conditions require front 
and rear lighting to be active.
The rain/light sensor measures the ambient light around the vehicle 
in a vertical direction and also the angular light level from the front of 
the vehicle.
The rain/light sensor can detect if the vehicle has entered a tunnel or 
similar environment and will activate the headlamps on entry to the 
tunnel when the ambient and forward light levels have fallen quickly. 
When the tunnel is exited, the rain/light sensor detects the sudden 
increase in light levels and requests the lights to be switched off.
Certain light and weather conditions are not detected accurately by 
the rain/light sensor. The driver should override the autolamps 
function if in any doubt about weather conditions and the 
requirement for exterior lights to be active.
The autolamps operation uses ambient light levels which are 
monitored by a photo-diode incorporated in the rain/light sensor. The 
rain/light sensor sends a lights on/off request to the CJB via the LIN 
bus, which responds by switching the low beam headlamps, front side 
lamps and rear tail lamps on/off.

Operation of the autolamps requires the ignition to be in on, the 
lighting control switch to be in the AUTO position and a lights on 
request signal from the rain/light sensor.
If the autolamps function has been selected and the ambient light 
falls below a pre-defined level then the rear fog lamps can be 
manually activated. If the ambient light rises above that level then 
the fog lamps will be deactivated along with the rest of the lamps. If 
the ambient light then falls below this level again the lamps will be 
activated, but the fog lamps which were previously selected will not.
WINDSHIELD WIPER DETECTION
When the lighting control switch is in the AUTO position, if the 
windscreen wipers are switched on for more than 20 seconds, the CJB 
switches on the side lamps and headlamps. When the windscreen 
wipers are switched off, the CJB switches the side lamps and 
headlamps off two minutes later. The side lamps and headlamps will 
also be activated if the number of wipe cycles within the previous 
minute is greater than 12. Following this activation, there is a two 
minute delay and then the lights will be turned off after the number 
of wipe cycles per minute drops below 3.
AUTO HIGH BEAM
WARNING:
The auto high beam system is designed as a driving aid only. 
Should the road conditions require, it is the driver¶s 
responsibility to consider other road users and operate the high 
beam headlamps in a safe manner. In certain circumstances the 
driver will be required to intervene.
Auto high beam operates as part of the autolamps system. When 
driving at night with the lighting control switch in the automatic 
position and the left steering column multifunction switch in the 
central position, with sufficient darkness (approximately 1 lux or less)

and a suitable road speed, auto high beam will automatically operate 
the high beam headlamps when necessary. An auto high beam 
warning indicator in the IC confirms to the driver when the auto high 
beam system is selected and enabled.
NOTE:
ACTIVATION (SYSTEM READY)
Auto high beam will only activate and illuminate the warning 
indicator, to show the system is activated for high beam control, 
when the following conditions are met:
Auto high beam is enabled in the IC 
 menu
Vehicle setup
Lighting control switch is in the autolamps position
Left steering column multifunction switch is in the central position
The ambient light level is below 100 lux
The system has not been overridden or cancelled
The camera (image) sensor view is not blocked.
HIGH BEAM CONTROL
When activated, auto high beam will switch the headlamps to high 
beam when all the following conditions occur:
The function of the blue high beam warning indicator remains 
unchanged and always reflects the actual status of the high 
beam headlamps.
The exterior lighting on threshold for the autolamps system is 
approximately 100 lux which is measured by the rain/light 
sensor. At light levels below this value the low beam headlamps 
and exterior lights will be switched on. The auto high beam will 
not function until the light level has reached approximately
lux. At light levels above 1 lux high beam is not required and 
therefore is not activated.

No relevant oncoming traffic
No relevant preceding traffic
In non-urban environment, i.e. with no street lighting
Ambient light level is below 1 lux
Road speed is suitable.
LOW BEAM CONTROL
When activated, auto high beam will switch the headlamps to low 
beam when any of the following conditions occur:
Relevant oncoming traffic is present
Relevant preceding traffic is present
In urban environment, i.e. with street lighting
Ambient light level is above 1 lux
Road speed is not suitable
Unrecognizable reflective inputs from road signs or markings.
ROAD SPEED
A road speed signal is received by the CJB from the ABS control 
module via the HS CAN bus. When the other activation conditions are 
correct, the CJB will switch the headlamps to high beam when the 
road speed has increased above 40 km/h (25 mph).
When the road speed falls to below 24 km/h (15 mph), the CJB will 
switch the headlamps to low beam. The 10 mph (15 km/h) difference 
between the on and off road speed thresholds prevents the system 
continually switching between high and low beam at low speeds.
OVERRIDE
The driver can manually override the auto high beam system at any 
time. When the auto high beam system is activated, pulling the left 
steering column multifunction switch to the high beam 
flash
 position

or pushing it forward to the high beam position will de-activate the 
system and the auto high beam warning indicator in the IC will 
extinguish.
When the multifunction switch is returned to the central position, 
from a forward high beam position, the system is re-activated and 
the auto high beam warning indicator will illuminate again.
CORRECT PERFORMANCE
In addition, auto high beam will only exhibit best performance if all of 
the following conditions are met:
No false inputs are received by the auto high beam camera, such as 
reflected light from certain static signs
Headlamps are correctly aligned
Auto high beam system has been set for correct hand of drive in 
the 
 menu of the IC
Vehicle set-up
Auto high beam camera has been through a self learning 
auto aim

calibration procedure if any components have been replaced
There are no large reflective items, white papers, etc., sitting on 
top of the instrument panel in near view of the auto high beam 
camera, or stickers placed directly in front of the camera.
Enabling or disabling auto high beam will not affect the hand of drive 
settings once set.
SYSTEM LIMITATIONS
The auto high beam system can occasionally have difficulty 
distinguishing between light from other vehicles or reflected light 
from static highly reflective road signs.
These situations may cause the auto high beam system to 
undesirably operate the high beam headlamps or take no action at 
all. Examples of these situations are as follows:

Dips, hollows or crests in the road
Highly reflective static road signs
Tight bends
Poorly illuminated vehicles e.g. cyclists or small mopeds
Highway central barriers
Extreme weather conditions e.g. fog, heavy snow
Exterior domestic or industrial lighting.
There are situations when a driver is able to judge if a high beam 
deactivation is desirable before the auto high beam system actually 
operates, for example over a crest of a hill. Headlamps from an 
oncoming vehicle can sometimes be seen on the horizon prior to the 
detection sensor receiving an input. It is the driver
s preference to 
determine if early intervention is desired in this and similar situations.
SYSTEM CALIBRATION
To achieve effective operation of the auto high beam system, a 
calibration routine is performed on vehicle build and system 
tolerances are set to an accuracy of +/- 0.2 degrees. This initial 
calibration is a 
one time only
 procedure. Should the auto high beam 
components or the windshield require replacement, an automatic 
calibration routine will be performed. This 
auto aim
 calibration 
procedure is a continual process that takes place during a normal 
drive cycle at night and could take between 10 - 30 minutes 
dependant on the following driving conditions:
If sufficient road markings (lane markings) are visible to the image 
sensor - approximately 10 minutes
If insufficient road markings are visible, the system uses the tail 
lights of preceding vehicles - approximately 30 minutes.
NOTE:

SYSTEM DIAGNOSIS
NOTE:
Auto high beam has a self diagnosis capability by comparing data 
from the rain/light sensor to light levels detected by the auto high 
beam camera. If a deviation is detected it is assumed that the 
ambient light available to the auto high beam camera is being 
restricted by dirt or other blockage and the system will be 
deactivated. DTCs are stored in the AHBCM and can be accessed 
using Jaguar approved diagnostic equipment. Within the diagnostic 
system is a procedure to test the basic operation of the camera 
function.
In the event of a fault, the warning strategy to the driver is as follows:
Image sensor internal fault - auto high beam warning indicator will 
extinguish with no additional message to driver
Until this calibration is complete the system may not react 
correctly during operation. This should be made clear to the 
customer before vehicle handover.
Due to mechanical calibration tolerance the correct mirror 
assembly must be used for the vehicle model types in question 
and it is not exchangeable with other vehicle model types.
After any rectification work and before any calibration drives, 
the headlamps should be checked for correct alignment.
Windshield stickers, stone chips, dirt and general road film will 
affect the successful operation of the auto high beam camera if 
sufficient blocking is present. Avoid placing reflective objects on 
the instrument panel, for example white paper, which can affect 
the image sensor.

CJB has lost all communication with image sensor - auto high beam 
warning indicator will extinguish with no additional message to 
driver
Image sensor blocked - auto high beam warning indicator will 
extinguish with an additional Camera Blocked message within the 
message center.
CORNERING LAMPS
When the ignition is on and the left or right turn signal indicators are 
selected, the CJB operates the cornering lamp on the selected side, 
using a full power Pulse Width Modulation (PWM) voltage, if the 
vehicle is in the following configuration:
The transmission is in D (drive).
Vehicle speed is less than 25 mph (40 Km/h).
The headlamps are on and in low beam.
Only one cornering lamp will illuminate at any one time. When one of 
the required parameters is no longer present, or after three minutes 
of activation, the CJB fades the lamp off by decreasing the PWM 
voltage in a linear manner.
STATIC BENDING LAMPS
The static bending lamps are controlled by the HLCM using HS CAN 
inputs of steering angle and vehicle speed from the ABS control 
module. The HLCM evaluates the inputs and sends static bending 
lamp requests to the CJB, which then operates the lamps as required.
The static bending lamps operate at all speeds. The operating point 
varies with vehicle speed and steering angle. As vehicle speed 
increases, the amount of steering wheel rotation required to activate 
a static bending lamp reduces.
When the operating parameters of the lamp are present, the CJB 
illuminates the static bending lamp on the inside of the corner using a

full power PWM voltage. When one of the required parameters is no 
longer present, the CJB fades the lamp off by decreasing the PWM 
voltage in a linear manner.
Only one static bending lamp will illuminate at any one time.
DYNAMIC BENDING LIGHT SYSTEM (DBL)
DBL is a system designed to improve driver visibility under varying 
driving conditions and shall be achieved by swivelling or rotation of 
the dipped beam module. Any swivelling action shall not impede the 
vertical angular range requirements of headlamp levelling. All swivel 
movement shall be achieved horizontally without any vertical 
deviation (less than 0.2). It is a requirement to be able to achieve 
a maximum of 15 degrees horizontal swivel of the module.
The DBL function is to be controlled by the HLCM, which receives the 
following vehicle input signals:
Steering Angle
Vehicle Speed
Switch inputs (from CJB for dipped beam status)
Engine running
Reverse gear switch
Yaw Rate (optional)
The HLCMmonitors driver steering inputs and vehicle speed to 
produce output signals which in turn activates the lamp dynamic 
bending light module. The DBL modules in each headlamp shall be 
designed to be compatible with the HLCM, refer to the AFS Electronic 
Control Unit Interface Specification.
REAR FOG LAMPS
The rear fog lamps can only be activated if the ignition is on and the 
headlamps or autolamps are on. If the rear fog lamp switch is

pressed when the fog lamps are operating, they will be extinguished. 
If the lighting control switch is moved to the side lamp or off position, 
if autolamps turns off the headlamps, or if the ignition is switched off, 
the rear fog lamps will be extinguished. If the headlamps are 
subsequently turned on the rear fog lamp operation will not be active 
and the rear fog lamp switch must be pressed to activate the lamps.
TURN SIGNAL INDICATORS
The CJB has a turn signal indicator lane change function. If the left 
steering column multifunction switch is gently pushed to either turn 
signal indicator position and then released, the applicable turn signal 
indicators will flash 3 times and then will be automatically cancelled.
If a turn signal indicator LED fails, the green turn signal warning 
indicator in the IC will flash at twice the normal rate and the audible 
ticking from the IC sounder will also be at twice the normal rate. If 
this occurs, the lamp unit must be replaced.
NOTE:
HA=ARD WARNING LAMPS
The hazard warning lamps operate at all times when selected and are 
not dependant on an ignition mode.
The hazard warning lamp switch is a momentary switch that connects 
a ground signal to the CJB. The connection of this ground signal is 
then used to determine whether to activate or deactivate the hazards 
warning lamps, based upon the current operating mode of the 
feature. When the hazard warning lamps are active, they override 
any request for turn signal indicator operation.
CENTRAL DOOR LOCKING AND ALARM INDICATIONS
The hazard warning lamps are also operated by the central door 
locking system when the vehicle is locked or unlocked, and by the 
If a side repeater lamp fails, the flash rate is unchanged.

active anti-theft system if an alarm is triggered. 
For additional information, refer to: Handles, Locks, Latches and 
 (501-14 Handles, Locks, Latches and Entry Systems, 
Entry Systems
Description and Operation). 
If the hazard warning lamps are active when a lock or unlock request 
is made, the hazard warning cycle is interrupted to allow the visual 
indication of the requested lock cycle. When visual indication is 
completed, the hazard warning operation will continue.
CRASH SIGNAL ACTIVATION
The hazard warning lamps are also activated if the vehicle is involved 
in an accident where an airbag is deployed. When the RCM deploys 
an airbag, it also sends hardwired and HS CAN crash signals to the 
CJB, which activates the hazard warning lamps. The hazard warning 
lamps continue to operate until the ignition is in the off or accessory 
mode and then returned to the ignition on mode. Once this condition 
has occurred, the RCM will cease transmission of the crash signal.
EMERGENCY BRAKING ACTIVATION
During emergency braking, if vehicle deceleration exceeds a stored 
value the ABS control module sends a HS CAN message to the CJB, 
which then automatically activates the hazard warning lamps at a 
faster rate than normal (approximately 4 Hz). If the vehicle speed 
reduces below 5 km/h (3 mph), the hazard warning lamps remain 
active but switch to the normal rate of operation. Emergency braking 
activation of the hazard warning lamps is cancelled when one of the 
following occurs:
Vehicle deceleration falls below a second (lower) stored value.
DSC OFF or TracDSC mode is selected.
The left or right turn signal indicators are selected.
LED FAILURE

If one LED in the lamp group fails, then all other LEDs in that group 
are extinguished by the lamp. The affected lamp unit must be 
replaced.
INPUT/OUTPUT DIAGRAM
A   HARDWIRED D   HS CAN BUS N   MEDIUM SPEED CAN BUS 
O   LIN BUS.
ITEM
DESCRIPTION
1
Central Junction Box (CJB)
2
AHBCM
3
Instrument Cluster (IC)
4
Keyless Vehicle Module (KVM)
5
Driver Door Module (DDM)

6
Passenger Door Module (PDM)
7
Right headlamp assembly
8
Right tail lamp assembly
9
Right fog/reverse lamp (V6 3.0L S/C petrol version shown)
10
High Mounted Stop Lamp (HMSL)
11
License plate lamps
12
Left fog/reverse lamp (V6 3.0L S/C petrol version shown)
13
Left tail lamp assembly
14
Left headlamp assembly
15
Ground
16
Power supplies
17
Restraints Control Module (RCM)
18
Brake pedal switch
19
Hazard warning lamp switch
20
Rear fog lamp switch
21
Lighting control switch and steering column multifunction switch
22
Rain/Light sensor
23
Transmission Control Switch (TCS)
24
RCM
25
IC
26
HLCM
27
ABS control module
28
Engine Control Module (ECM)
29
Integrated Suspension Control Module (ISCM)
30
Electric Park Brake Control Module (EPBCM)

2015. 0 F-TYPE (X152), 413-09
WARNING DEVICES
DESCRIPTION AND OPERATION

ITEM
DESCRIPTION
1
Left Door Mirror Warning Lamp
2
Right Door Mirror Warning Lamp
COMPONENT LOCATION

3
Right Blindspot Monitoring Control Module (BMCM)
4
Right radar absorbing pad
5
Left Blindspot Monitoring Control Module (BMCM)
6
Left radar absorbing pad
Eliminating blind spots is a major element in vehicle body design, but 
because of the structural requirements of pillars, blind spots cannot 
be entirely eliminated, so the Blindspot Monitoring System is there to 
help assist the driver safely crossover in moving traffic.
The Blindspot Monitoring System Comprises:
Left BMCM
Right BMCM
Left Side Door Mirror Assembly
Right Side Door Mirror Assembly
Left radar absorbing pad
Right radar absorbing pad
The system uses two radar sensors operating at a frequency of 
24GHz, they are incorporated in each of a Blindspot Monitoring 
Control Module (BMCM), that are located at the rear of the vehicle 
(one module each side) behind each of the rear wheels and are 
connected via a private HS Controller Area Network (CAN) Bus to 
exchange information.
These modules will warn the driver of the presence of vehicles in a 
defined closing vehicle warning zone, or if a vehicle enters the blind 
OVERVIEW
COMPONENT DESCRIPTION

spot warning zone, which poses a threat to the driver if a lane change 
manoeuvre is made.
Each BMCM has an 8 way connector that has power, ground, Medium 
speed CAN bus wires, two private High speed can wires and two hard 
wire connections one to the status light and one for the alert icon in 
the mirror.
The Blindspot Monitoring Control Module carries out an auto-
alignment self-check every time when in use, this procedure can take 
up to an hour in some environments, however the operation of the 
blindspot monitoring system will continue to operate as normal.
Each module will detect a vehicle in the driver¶s Blindspot. Once the 
vehicle is detected the module illuminates an amber warning µalert 
icon¶ Light Emitting Diode (LED) in the relevant exterior door mirror.
If the system displays µblind spot not available¶ and there is a 
misalignment trouble code in the system, the physical sensors must 
be checked for mounting and body work should be checked for 
damage or repair.
When the system initiates, it performs a self-check, during which the 
warning icons in the mirrors illuminate alternately for a short period 
of time. Each module does a left/right determination check when the 
ignition is switched on. Each mirror has a different circuit 
configuration so that the modules can determine which mirror they 
are connected to. If a module detects the wrong mirror it will go into 
a fault condition.
The blind spot monitoring modules receive vehicle speed on the 
Medium Speed CAN and is active from 8mph (13kph) down to 3mph 
(5kph).
CAUTION:

The blind spot monitoring system is designed as a driver aid not 
a safety device. The driver should always exercise due care and 
attention whilst driving.
SYSTEM OPERATION
The Blindspot Monitoring System uses a cross over radar pattern to 
the rear of the vehicle and is used to determine actual moving 
vehicles eliminating any stationary roadside objects which are false 
warnings.
The two radar sensors mounted at the rear of the vehicle will 
continuously scan for and track traffic on the areas to the left-rear 
and right-rear of the vehicle and they can also track vehicles from as 
far as 73 metres.
They will warn the driver of the presence of vehicles in a defined 
closing vehicle warning zone, which poses a threat to the driver if a 
lane change manoeuver is made.
The driver will be notified of the threat by flashing the existing blind 
spot icon in the relevant door mirror.
NOTE:
The blind spot monitoring system lenses are shaped so as to 
minimize the visibility to other drivers. The LED¶s are located towards 
the outside extremity of the mirror face, within the peripheral view of 
the driver but not in any area of the mirror where they could obscure 
or distract from the image.
If an overtaking vehicle is detected on both sides of the vehicle 
simultaneously, the warning alert icons in both mirrors will 
illuminate.

ITEM
DESCRIPTION
1
Warning alert icon
2
System status warning indicator
The LED lighting sequence is as follows
Amber alert LED icon permanently lit - system operational, vehicle 
detected in blind spot area.
No LED
s lit ± system active no vehicle detected in blind spot area.
Amber status LED permanently lit - system not active or faulty.
The system has operating limitations and is automatically turned off 
under certain operating conditions. During these operating conditions 
the amber status LED is permanently lit.
The system operating limitations are as follows
The system is inactive until vehicle speed is greater than 8mph ± 
13kph (amber status LED permanently lit).
The system is inactive if an approved trailer is connected to the 
vehicle (amber status LED permanently lit).

The system is inactive when reverse gear or park is selected 
(amber status LED permanently lit).
If either of the radar signals are blocked or distorted, for example by 
water, the radar face of the module is covered in mud, sleet or snow 
the system may detect this and be disabled with the amber status 
LED permanently lit together with a µblind spot monitoring blocked¶ 
message displayed in the Instrument Cluster (IC) message center. 
The system is disabled until the blockage is cleared.
If there is a fault in the system the amber status LED is permanently 
lit and a µblind spot monitoring not available¶ message displayed in 
the IC message center. The system is disabled until the fault is 
rectified.
System fault and blockage warnings are as follows
The system is disabled when the radar module signal is blocked 
(amber status LED permanently lit and IC message).
The system is disabled by a fault (amber status LED permanently lit 
and IC message).
If there is a failure in the communication network and the warning 
LED cannot be displayed in the mirror, a failure message will be 
displayed in the IC message center.
When any faults are present in the system, Diagnostic Trouble Codes 
(DCS) are stored in both BMCM
s appropriate to each module. 
Replacement of modules requires the right module to be configured 
using the Jaguar approved diagnostic equipment. Due to the fact that 
all modules are supplied as left modules the replacement left modules 
do not require configuring.
Calibration of the modules using the Jaguar approved diagnostic 
equipment enables updates to be downloaded as new technology 
becomes available or any fault concerns require software updates.

ITEM
DESCRIPTION
1
Central Junction Box (CJB)
2
Left Blindspot Monitoring Control Module (BMCM)
3
Passenger door mirror
4
Driver door mirror
5
Right Blindspot Monitoring Control Module (BMCM)
CONTROL DIAGRAM

2015. 0 F-TYPE (X152), 501-09
REAR VIEW MIRRORS
DIAGNOSIS AND TESTING
For a detailed description of the rear view mirrors, refer to the 
relevant description and operation section in the workshop manual. 
REFER to: 
 (501-09 Rear View Mirrors, Description 
Rear View Mirrors
and Operation). 
NOTE:
Visual Inspection
MECHANICAL
ELECTRICAL
Exterior mirror(s)
Fuse(s)
Ambient air temperature sensor resistance check
Relay
PRINCIPLE OF OPERATION
INSPECTION AND VERIFICATION
When performing voltage or resistance tests, always use a 
digital multimeter accurate to three decimal places, and with an 
up-to-date calibration certificate. When testing resistance 
always take the resistance of the digital multimeter leads into 
account.
Verify the customer concern
1.
Visually inspect for obvious signs of damage and system integrity
1.

Electrical connector(s)
Switch
SYMPTOM
POSSIBLE 
CAUSES
ACTION
Ambient air temperature sensor 
intermittent/inoperative/erratic readings 
or a default setting is appearing (ie 
- 40°). Malfunction indicator lamp 
lighting or air conditioning is 
inoperative. (DTC
s that might show 
are: P0070-17, P0071-21, P0071-22, 
P0071-24, P0071-29, P0073-00, P0072-
00, P007B-08, P18A5-14, P1888-15 
may also be flagged for this failure.)
Circuit 
fault: 
high 
resistance
Circuit 
fault: 
short 
circuit to 
ground
Refer to the 
electrical circuit 
diagrams and check 
the ambient air 
temperature sensor 
signal circuit for 
short circuit to 
ground, short 
circuit to power, 
open circuit, high 
resistance. Repair 
circuit as required. 
For ambient air 
temperature 
resistance check - 
see below 
resistance 
specifications
If the resistance 
shows to be within 
the spec stated 
below, the fault is 
NOT with the 
ambient air 
temperature 
sensor, and the 
mirror NOT be 
replaced
If an obvious cause for an observed or reported concern is 
found, correct the cause (if possible) before proceeding to the 
next step
1.
If the cause is not visually evident, Check DDM/PDM for rear 
view mirror related DTCs and refer to the DTC index
1.
SYMPTOM CHART

AMBIENT AIR TEMPERATURE SENSOR SPECIFICATIONS
TEMPERATURE 
(°C)
R 
NOMINAL 
(OHM)
R 
MINIMUM 
(OHM)
R 
MAXIMUM 
(OHM)
RESISTANCE 
TOLERANCE 
( )
TEMPERATURE 
TOLERANCE 
( °C)
-
65319.
62679.
67958.
4.
0.
-
46990.
45205.
48774.
3.
0.
-
34207.
32989.
35425.
3.
0.
-
25182.
24342.
26021.
3.
0.
-
18734.
18151.
19318.
3.
0.
-
14077.
13668.
14486.
2.
0.
-
10678.
10390.
10966.
2.
0.
-
8172.
7968.
8377.
2.
0.
0
6308.
6163.
6454.
2.
0.
5
4909.
4786.
5031.
2.
0.
10
3849.
3746.
3952.
2.
0.
15
3041.
2954.
3127.
2.
0.
20
2419.
2346.
2492.
3.
0.
25
1937.
1875.
1998.
3.
0.
30
1561.
1508.
1613.
3.
0.
35
1265.
1221.
1310.
3.
0.
40
1032.
994.
1069.
3.
0.
45
846.
814.
878.
3.
1.
50
697.
670.
725.
3.
1.
55
578.
554.
601.
4.
1.
60
481.
461.
501.
4.
1.
65
402.
385.
420.
4.
1.
70
338.
323.
353.
4.
1.
75
285.
272.
298.
4.
1.
80
242.
230.
253.
4.
1.

2015. 0 F-TYPE (X152), 100-00
GENERAL INFORMATION
85
206.
196.
216.
4.
1.
For a list of diagnostic trouble codes that could be logged on this 
vehicle, please refer to Section 100-00. 
REFER to: Diagnostic Trouble Code (DTC) Index - DTC: Driver Door 
 (100-00 General 
Module/Passenger Door Module (DDM/PDM)
Information, Description and Operation). 
DTC INDEX
DESCRIPTION AND OPERATION
CAUTION:
Diagnosis by substitution from a donor vehicle is 

NOT
acceptable. Substitution of control modules does not guarantee 
confirmation of a fault, and may also cause additional faults in 
the vehicle being tested and/or the donor vehicle
DRIVER/PASSENGER DOOR MODULE (DDM/PDM)

NOTES:
If the control module or a component is suspect and the 
vehicle remains under manufacturer warranty, refer to the 
warranty policy and procedures manual, or determine if any 
prior approval programme is in operation, prior to the 
installation of a new module/component
Generic scan tools may not read the codes listed, or may read 
only 5-digit codes. Match the 5 digits from the scan tool to the 
first 5 digits of the 7-digit code listed to identify the fault (the 
last 2 digits give extra information read by the manufacturer-
approved diagnostic system)
When performing voltage or resistance tests, always use a 
digital multimeter accurate to three decimal places and with a 
current calibration certificate. When testing resistance, always 
take the resistance of the digital multimeter leads into account
Check and rectify basic faults before beginning diagnostic 
routines involving pinpoint tests
Inspect connectors for signs of water ingress, and pins for 
damage and/or corrosion
If diagnostic trouble codes are recorded and, after performing 
the pinpoint tests, a fault is not present, an intermittent 
concern may be the cause. Always check for loose connections 
and corroded terminals
Where an 
on demand self-test
 is referred to, this can be 
accessed via the 
diagnostic trouble code monitor
 tab on the 
manufacturers approved diagnostic system
Check DDW for open campaigns. Refer to the corresponding 
bulletins and SSMs which may be valid for the specific 
customer complaint and carry out the recommendations as 
required

The table below lists all diagnostic trouble codes (DTCs) that could be 
logged in the Driver/Passenger Door Module (DDM/PDM). For 
additional diagnosis and testing information refer to the relevant 
diagnosis and testing section. For additional information, refer to: 
 (419-10 Multifunction Electronic Modules, 
Driver Door Module (DDM)
Diagnosis and Testing).
DTC
DESCRIPTION
POSSIBLE CAUSES
ACTION
B1087-
87
LIN Bus A - 
Missing 
message
Rear door 
sunblind LIN 
circuit(s) - Short 
circuit to ground, 
short circuit to 
power, open 
circuit, high 
resistance
Refer to the electrical 
circuit diagrams and check 
the door module rear door 
sunblind power and LIN 
circuit(s) for short circuit 
to ground, short circuit to 
power, open circuit, high 
resistance. Repair circuit 
as required. Clear DTC, 
operate sunblind and retest
If fault persists, check and 
install a new sunblind 
module as required
B109C-
11
Front Courtesy 
Light - Circuit 
short to ground
Front courtesy 
light circuit - 
Short circuit to 
ground
Front courtesy 
light - Internal 
failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the front courtesy light 
circuit (pin 3) for short 
circuit to ground. Repair 
circuit as required. Clear 
DTC, repeatedly open and 
close door and retest
If fault persists, check and 
install a new front 
courtesy light as required. 
Clear DTC, repeatedly 
open and close door and 
retest
B109C-
15
Front Courtesy 
Light - Circuit 
Front courtesy 
light - Bulb failure
Disconnect the battery 
prior to performing 
circuit checks

short to 
battery or open
Front courtesy 
light circuit - 
Short circuit to 
power or open 
circuit, high 
resistance
NOTE:
Replace courtesy lamp 
bulb. Clear DTC, 
repeatedly open and close 
door and retest
If fault persists, refer to 
the electrical circuit 
diagrams and check the 
front courtesy light circuit 
(pin 3) for short circuit to 
power or open circuit, high 
resistance. Repair circuit 
as required. Clear DTC and 
retest
B10EB-
11
Driver door 
double locking 
motor - Circuit 
short to ground
Driver door 
double locking 
motor circuit - 
Short circuit to 
ground
Door latch - 
Internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the driver door double 
locking motor circuit (pin 
9) for short circuit to 
ground. Repair circuit as 
required. Clear DTC, 
repeatedly double lock
/unlock the vehicle and 
retest
If fault persists, check and 
install a new door latch as 
required. Clear DTC, 
repeatedly open and close 
door and retest
B10EB-
15
Driver door 
double locking 
motor - Circuit 
short to 
battery or open
Driver door 
double locking 
motor circuit - 
Short circuit to 
power or open 
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

circuit, high 
resistance
Door latch - 
Internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the driver door double 
locking motor circuit (pin 
9) for short circuit to 
power or open circuit, high 
resistance. Clear DTC, 
repeatedly double lock
/unlock the vehicle and 
retest
If fault persists, check and 
install a new door latch as 
required. Clear DTC, 
repeatedly double lock
/unlock the vehicle and 
retest
B10EC-
11
Passenger door 
double locking 
motor - Circuit 
short to ground
Passenger door 
double locking 
motor circuit - 
Short circuit to 
ground
Door latch - 
Internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the passenger door double 
locking motor circuit (pin 
9) for short circuit to 
ground. Repair circuit as 
required. Clear DTC, 
repeatedly double lock
/unlock the vehicle and 
retest
If fault persists, check and 
install a new door latch as 
required. Clear DTC, 
repeatedly open and close 
door and retest
B10EC-
15
Passenger door 
double locking 
Passenger door 
double locking 
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

motor - Circuit 
short to 
battery or open
motor circuit - 
Short circuit to 
power or open 
circuit, high 
resistance
Door latch - 
Internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the passenger door double 
locking motor circuit (pin 
9) for short circuit to 
power or open circuit, high 
resistance. Clear DTC, 
repeatedly double lock
/unlock the vehicle and 
retest
If fault persists, check and 
install a new door latch as 
required. Clear DTC, 
repeatedly double lock
/unlock the vehicle and 
retest
B1108-
11
Driver door 
central locking 
motor - Circuit 
short to ground
Driver door 
central locking 
motor circuit - 
Short circuit to 
ground
Door latch - 
Internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the driver door central 
locking motor circuit (pin 
10) for short circuit to 
ground. Repair circuit as 
required. Clear DTC, 
repeatedly double lock
/unlock the vehicle and 
retest
If fault persists, check and 
install a new door latch as 
required. Clear DTC, 
repeatedly open and close 
door and retest
B1108-
15
Driver door 
central locking 
Driver door 
central locking 
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

motor - Circuit 
short to 
battery or open
motor circuit - 
Short circuit to 
power or open 
circuit, high 
resistance
Door latch - 
Internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the driver door central 
locking motor circuit (pin 
10) for short circuit to 
power or open circuit, high 
resistance. Clear DTC, 
repeatedly double lock
/unlock the vehicle and 
retest
If fault persists, check and 
install a new door latch as 
required. Clear DTC, 
repeatedly double lock
/unlock the vehicle and 
retest
B1109-
11
Passenger door 
central locking 
motor - Circuit 
short to ground
Passenger door 
central locking 
motor circuit - 
Short circuit to 
ground
Door latch - 
Internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the passenger door central 
locking motor circuit (pin 
10) for short circuit to 
ground. Repair circuit as 
required. Clear DTC, 
repeatedly double lock
/unlock the vehicle and 
retest
If fault persists, check and 
install a new door latch as 
required. Clear DTC, 
repeatedly open and close 
door and retest
B1109-
15
Passenger door 
central locking 
Passenger door 
central locking 
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

motor - Circuit 
short to 
battery or open
motor circuit - 
Short circuit to 
power or open 
circuit, high 
resistance
Door latch - 
Internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the passenger door central 
locking motor circuit (pin 
10) for short circuit to 
power or open circuit, high 
resistance. Clear DTC, 
repeatedly double lock
/unlock the vehicle and 
retest
If fault persists, check and 
install a new door latch as 
required. Clear DTC, 
repeatedly double lock
/unlock the vehicle and 
retest
B1163-
11
Left Mirror 
Heater Output 
- Circuit short 
to ground
Left side door 
mirror heater 
output circuit - 
Short circuit to 
ground
Door mirror glass 
- Internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the left side door mirror 
heater output circuit (pin 
10) for short circuit to 
ground. Repair circuit as 
required
Reconnect battery, clear 
DTCs, repeatedly turn 
door mirror heating on 
and off and retest
If fault persists, check and 
install a new door mirror 
glass as required. Clear 
DTC and retest
B1163-
Left Mirror 
NOTE:
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

15
Heater Output 
- Circuit short 
to battery or 
open
Left side door 
mirror heater 
output circuit - 
Short circuit to 
power or open 
circuit, high 
resistance
Door mirror glass 
- Internal failure
Refer to the electrical 
circuit diagrams and check 
the left side door mirror 
heater output circuit (pin 
10) for short circuit to 
power, open circuit, high 
resistance. Repair circuit 
as required
Reconnect battery, clear 
DTCs, repeatedly turn 
door mirror heating on 
and off and retest
If fault persists, check and 
install a new door mirror 
glass as required. Clear 
DTC and retest
B1164-
11
Right Mirror 
Heater Output 
- Circuit short 
to ground
Right side door 
mirror heater 
output circuit - 
Short circuit to 
ground
Door mirror glass 
- Internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the right side door mirror 
heater output circuit (pin 
10) for short circuit to 
ground. Repair circuit as 
required
Reconnect battery, clear 
DTCs, repeatedly turn 
door mirror heating on 
and off and retest
If fault persists, check and 
install a new door mirror 
glass as required. Clear 
DTC and retest
B1164-
15
Right Mirror 
Heater Output 
Right side door 
mirror heater 
NOTE:
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

- Circuit short 
to battery or 
open
output circuit - 
Short circuit to 
power or open 
circuit, high 
resistance
Door mirror glass 
- Internal failure
Refer to the electrical 
circuit diagrams and check 
the right side door mirror 
heater output circuit (pin 
10) for short circuit to 
power, open circuit, high 
resistance. Repair circuit 
as required
Reconnect battery, clear 
DTCs, repeatedly turn 
door mirror heating on 
and off and retest
If fault persists, check and 
install a new door mirror 
glass as required. Clear 
DTC and retest
B1165-
11
Left Front 
Puddle Lamp 
Output - 
Circuit short to 
ground
Left side front 
approach lamp 
output circuit - 
Short circuit to 
ground
Approach lamp - 
Internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the left side front 
approach lamp output 
circuit (pin 12) for short 
circuit to ground. Repair 
circuit as required. Clear 
DTC, repeatedly open and 
close door and retest
If fault persists, check and 
install a new approach 
lamp as required. Clear 
DTC and retest
B1165-
15
Left Front 
Puddle Lamp 
Output - 
Circuit short to 
battery or open
Left side front 
approach lamp - 
Bulb failure
Left side front 
approach lamp 
NOTE:
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

output circuit - 
Short circuit to 
power or open 
circuit, high 
resistance
Approach lamp - 
Internal failure
Replace approach lamp 
bulb. Clear DTC, 
repeatedly lock and unlock 
car using the key fob and 
retest
If fault persists, refer to 
the electrical circuit 
diagrams and check the 
left side front approach 
lamp output circuit (pin 
12) for short circuit to 
power or open circuit, high 
resistance. Repair circuit 
as required. Clear DTC and 
retest
If fault persists, check and 
install a new approach 
lamp as required. Clear 
DTC and retest
B1166-
11
Right Front 
Puddle Lamp 
Output - 
Circuit short to 
ground
Right side front 
approach lamp 
output circuit - 
Short circuit to 
ground
Approach lamp - 
Internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the right side front 
approach lamp output 
circuit (pin 12) for short 
circuit to ground. Repair 
circuit as required. Clear 
DTC, repeatedly open and 
close door and retest
If fault persists, check and 
install a new approach 
lamp as required. Clear 
DTC and retest
B1166-
15
Right Front 
Puddle Lamp 
Output open 
load or short to 
Right side front 
approach lamp - 
Bulb failure
Right side front 
approach lamp 
output circuit - 
NOTE:
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

battery - 
Circuit short to 
battery or open
Short circuit to 
power or open 
circuit, high 
resistance
Approach lamp - 
Internal failure
Replace approach lamp 
bulb. Clear DTC, 
repeatedly lock and unlock 
car using the key fob and 
retest
If fault persists, refer to 
the electrical circuit 
diagrams and check the 
right side front approach 
lamp output circuit (pin 
12) for short circuit to 
power or open circuit, high 
resistance. Repair circuit 
as required. Clear DTC and 
retest
If fault persists, check and 
install a new approach 
lamp as required. Clear 
DTC and retest
B117E-
07
Front Power 
Window Up - 
Mechanical 
Failures
Set when window 
is reversed 
during window 
up due to 
mechanical 
problems, 
window channel 
restriction 
preventing 
window closure
Window 
mechanism fault
Check for mechanical 
problems with the window 
operation. Check door 
window seals are fully 
seated in door, window 
channel seals are correctly 
fitted and window 
movement is not 
obstructed
Manually fully open and 
close windows 5 times 
ensuring window is driven 
fully into fully closed 
position before the window 
up switch is released
Clear DTCs and run Learn 
Window Close Position 
and Window Test 
diagnostic routines using 
the manufacturer 
approved diagnostic tool. 
Clear DTCs and retest
If fault persists, check and 
install new window seals 
as required
B117E-
72
Front Power 
Window Up - 
Door module 
window up
NOTE:

Actuator stuck 
open
/window down 
motor control 
circuits - Short 
circuit to ground, 
short circuit to 
power, open 
circuit, high 
resistance
Door module - 
Internal relay 
sticking open
Refer to the electrical 
circuit diagrams and check 
the door module window 
up/window down motor 
control circuits (pins
1) for short circuit to 
ground, short circuit to 
power, open circuit, high 
resistance. Repair circuit 
as required. Clear DTC and 
retest
Reconnect battery, clear 
DTCs and fully open and 
close windows 5 times 
ensuring window is driven 
fully into fully closed 
position before the window 
up switch is released, then 
retest
If fault persists, check and 
install a new door module 
as required
B117E-
73
Front Power 
Window Up - 
Actuator stuck 
closed
Door module 
window up
/window down 
motor control 
circuits - Short 
circuit to ground, 
short circuit to 
power, open 
circuit, high 
resistance
Door module - 
Internal relay 
sticking closed
NOTE:
Refer to the electrical 
circuit diagrams and check 
the door module window 
up/window down motor 
control circuits (pins
1) for short circuit to 
ground, short circuit to 
power, open circuit, high 
resistance. Repair circuit 
as required. Clear DTC and 
retest
Reconnect battery, clear 
DTCs and fully open and 
close windows 5 times 
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

ensuring window is driven 
fully into fully closed 
position before the window 
up switch is released, then 
retest
If fault persists, check and 
install a new door module 
as required
B117E-
92
Front Power 
Window Up - 
Performance or 
incorrect 
operation
Set when auto 
window up was 
interrupted (e.g. 
by pressing local 
switch)
Check for mechanical 
problems with the window 
operation. Check door 
window seals are fully 
seated in door, window 
channel seals are correctly 
fitted and window 
movement is not 
obstructed
Manually fully open and 
close windows 5 times 
ensuring window is driven 
fully into fully closed 
position before the window 
up switch is released
Clear DTCs and run Learn 
Window Close Position 
and Window Test 
diagnostic routines using 
the manufacturer 
approved diagnostic tool. 
Clear DTCs and retest
If fault persists, check and 
install new window seals 
as required
B117F-
72
Front Power 
Window Down 
- Actuator 
stuck open
Front window 
motor circuit 
open circuit, high 
resistance
Front door 
module internal 
failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the rear window motor 
circuit (pins 12 	 1) for 
open circuit, high 
resistance. Reconnect 
battery, clear DTCs and 
Disconnect the battery 
prior to performing 
circuit checks

retest by moving window 
up and down
If the fault persists, check 
and install a new front 
door module as required
B117F-
73
Front Power 
Window Down 
- Actuator 
stuck closed
Door module 
window up
/window down 
motor control 
circuits - Short 
circuit to ground, 
short circuit to 
power, open 
circuit, high 
resistance
Door module - 
Internal relay 
sticking closed
NOTE:
Refer to the electrical 
circuit diagrams and check 
the door module window 
up/window down motor 
control circuits (pins
1) for short circuit to 
ground, short circuit to 
power, open circuit, high 
resistance. Repair circuit 
as required. Clear DTC and 
retest
Reconnect battery, clear 
DTCs and fully open and 
close windows 5 times 
ensuring window is driven 
fully into fully closed 
position before the window 
up switch is released, then 
retest
If fault persists, check and 
install a new door module 
as required
B1189-
29
Front Window 
Position Sensor 
- Signal signal 
invalid
Missing signal 
from hall sensor 
1 or
Sensor circuit 
fault
Hall sensor - 
Internal Failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the hall sensor circuits pin 
5 (hall 2) and pin 6 (hall 
1) between the door 
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

module and window motor 
for short circuit to ground, 
short circuit to power, 
open circuit, high 
resistance. Repair as 
necessary
Clear DTCs and run Learn 
Window Close Position 
and Window Test 
diagnostic routines using 
the manufacturer 
approved diagnostic tool. 
Clear DTCs and retest
If fault persists, check and 
install a new window 
motor as required
B11D1-
83
LIN Bus C - 
Value of signal 
protection 
calculation 
incorrect
LIN bus 
checksum error 
driver switchpack 
internal fault
Refer to the electrical 
circuit diagrams and check 
the LIN bus circuit 
between the driver door 
window switch and the 
door module. Check the 
connectors for integrity 
and security. Clear the 
DTC and retest
If the fault persists, check 
and install a new driver 
door switchpack as 
required
B11D1-
86
LIN Bus C - 
Signal invalid
LIN bus header 
error driver 
switchpack 
internal fault
Refer to the electrical 
circuit diagrams and check 
the LIN bus circuit 
between the driver door 
window switch and the 
door module. Check the 
connectors for integrity 
and security. Clear the 
DTC and retest
If the fault persists, check 
and install a new driver 
door switchpack as 
required
B11D1-
87
LIN Bus C - 
Missing 
message
NOTE:
Refer to the electrical 
circuit diagrams and check 
the LIN circuit for short 
circuit to ground, short

LIN circuit short 
circuit to ground, 
short circuit to 
power, open 
circuit, high 
resistance
Driver door 
switchpack 
power or ground 
circuit open 
circuit, high 
resistance
Driver door 
switchpack 
internal failure
circuit to power, open 
circuit, high resistance
Refer to the electrical 
circuit diagrams and test 
the driver door switchpack 
power and ground circuits 
for open circuit, high 
resistance
Using the manufacturer 
approved diagnostic 
system, clear the DTCs 
and retest. If the fault 
persists, check and install 
a new driver door 
switchpack as required
B11F6-
11
Driver Folding 
Mirror Motor - 
Circuit short to 
ground
Driver door 
folding mirror 
motor circuit - 
Short circuit to 
ground
Mirror motor 
failure
NOTE:
Clear DTCs, fold/unfold 
the mirrors repeatedly 
from the driver switchpack 
and check if the mirror 
fold function operates 
normally. If a DTC not set 
and the mirror fold 
function operates 
normally, but there is no 
autofold when the car is 
locked, check mirror 
autofold configuration on 
vehicle and reconfigure as 
required
If fault persists, refer to 
the electrical circuit 
diagrams and check the 
mirror fold circuit (pin 17) 
between the driver door 
module and the driver 
door mirror assembly for 
Circuit 
reference LIN
Disconnect the battery 
prior to performing 
circuit checks

short circuit to ground. 
Repair circuit as required. 
Clear DTC and retest
If the fault persists, check 
and install a new door 
mirror as required
B11F6-
15
Driver Folding 
Mirror Motor - 
Circuit short to 
battery or open
Driver door 
folding mirror 
motor circuit - 
Short circuit to 
power, open 
circuit, high 
resistance
Mirror motor 
failure
NOTE:
Clear DTCs, fold/unfold 
the mirrors repeatedly 
from the driver switchpack 
and check if the mirror 
fold function operates 
normally. If a DTC not set 
and the mirror fold 
function operates 
normally, but there is no 
autofold when the car is 
locked, check mirror 
autofold configuration on 
vehicle and reconfigure as 
required
If fault persists, refer to 
the electrical circuit 
diagrams and check the 
mirror fold circuit (pin 17) 
between the driver door 
module and the driver 
door mirror assembly for 
short circuit to power, 
open circuit, high 
resistance. Repair circuit 
as required. Clear DTC and 
retest
If the fault persists, check 
and install a new door 
mirror as required
B11F7-
11
Passenger 
Folding Mirror 
Motor - Circuit 
short to ground
Passenger door 
folding mirror 
motor circuit - 
Short circuit to 
ground
NOTE:
Disconnect the battery 
prior to performing 
circuit checks

Mirror motor 
failure
Clear DTCs, fold/unfold 
the mirrors repeatedly 
from the driver switchpack 
and check if the mirror 
fold function operates 
normally. If a DTC not set 
and the mirror fold 
function operates 
normally, but there is no 
autofold when the car is 
locked, check mirror 
autofold configuration on 
vehicle and reconfigure as 
required
If fault persists, refer to 
the electrical circuit 
diagrams and check the 
mirror fold circuit (pin 17) 
between the passenger 
door module and the 
passenger door mirror 
assembly for short circuit 
to ground. Repair circuit 
as required. Clear DTC and 
retest
If the fault persists, check 
and install a new door 
mirror as required
B11F7-
15
Passenger 
Folding Mirror 
Motor - Circuit 
short to 
battery or open
Passenger door 
folding mirror 
motor circuit - 
Short circuit to 
power, open 
circuit, high 
resistance
Mirror motor 
failure
NOTE:
Clear DTCs, fold/unfold 
the mirrors repeatedly 
from the driver switchpack 
and check if the mirror 
fold function operates 
normally. If a DTC not set 
and the mirror fold 
function operates 
normally, but there is no 
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

autofold when the car is 
locked, check mirror 
autofold configuration on 
vehicle and reconfigure as 
required
If fault persists, refer to 
the electrical circuit 
diagrams and check the 
mirror fold circuit (pin 17) 
between the passenger 
door module and the 
passenger door mirror 
assembly for short circuit 
to power, open circuit, 
high resistance. Repair 
circuit as required. Clear 
DTC and retest
If the fault persists, check 
and install a new door 
mirror as required
B12BA-
11
Lock Status 
LED - Front - 
Circuit short to 
ground
Front door lock
/unlock switch 
status LED circuit 
- Short circuit to 
ground
Lock/unlock 
switch - Internal 
failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the front door lock/unlock 
switch status LED circuit 
(pin 2) for short circuit to 
ground. Repair circuit as 
required. Clear DTC, 
repeatedly lock and unlock 
car using the key fob, wait 
for 60 seconds and retest
If fault persists, check and 
install a new lock/unlock 
switch as required
B12BA-
15
Lock Status 
LED - Front - 
Circuit short to 
battery or open
Front door lock
/unlock switch 
status LED circuit 
- Short circuit to 
power, open 
circuit, high 
resistance
NOTE:
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

Lock/unlock 
switch - Internal 
failure
Refer to the electrical 
circuit diagrams and check 
the front door lock/unlock 
switch status LED circuit 
(pin 2) for short circuit to 
power or open circuit, high 
resistance. Repair circuit 
as required. Clear DTC, 
repeatedly lock and unlock 
car using the key fob, wait 
for 60 seconds and retest
If fault persists, check and 
install a new lock/unlock 
switch as required
B1326-
11
External Door 
Handle LED - 
Circuit short to 
ground
Exterior door 
handle ambience 
lighting LED 
circuit - Short 
circuit to ground
Exterior door 
handle - Internal 
failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the exterior door handle 
circuit (pin 16) for short 
circuit to ground. 
Reconnect battery and 
repeatedly lock and unlock 
door while ignition is in 
the off position and see if 
DTC sets
If fault persists, check and 
install a new deployable 
door handle module as 
required
B1326-
15
External Door 
Handle LED - 
Circuit short to 
battery or open
Exterior door 
handle ambience 
lighting LED 
circuit short 
circuit to power, 
open circuit, high 
resistance
Exterior door 
handle internal 
failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the exterior door handle 
circuit (pin 16) for short 
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

circuit to power, open 
circuit, high resistance. 
Reconnect battery, clear 
DTCs and repeatedly lock 
and unlock door while 
ignition is in the off 
position and see if DTC 
sets
If fault persists check and 
install a new deployable 
door handle module as 
required
B1A98-
83
LIN Bus Circuit 
1 - Value of 
signal 
protection 
calculation 
incorrect
Rear door 
module LIN 
circuit - Value of 
signal protection 
calculation 
incorrect
Refer to the electrical 
circuit diagrams and check 
the LIN bus circuit 
between the rear door 
module and the driver
/passenger door module. 
Check the connectors for 
integrity and security
Clear the DTC, operate the 
rear door switchpack and 
retest. If the fault persists, 
check and install a new 
rear door module as 
required. Clear the DTC, 
operate the rear door 
switchpack and retest
B1A98-
86
LIN Bus Circuit 
1 - Signal 
invalid
Rear door 
module LIN 
circuit - Signal 
invalid
Refer to the electrical 
circuit diagrams and check 
the LIN bus circuit 
between the rear door 
module and the driver
/passenger door module. 
Check the connectors for 
integrity and security
Clear the DTC, operate the 
rear door switchpack and 
retest. If the fault persists, 
check and install a new 
rear door module as 
required. Clear the DTC, 
operate the rear door 
switchpack and retest
B1A98-
87
LIN Bus Circuit 
1 - Missing 
Rear door 
module LIN 
Ensure the battery is fully 
charged. Refer to the

message
circuit - Missing 
message
electrical circuit diagrams 
and check the LIN bus and 
power circuits to the rear 
door module. Repair circuit
(s) as required
Disconnect the harness 
from the rear door 
module, wait 30 seconds 
and reconnect. Clear 
DTCs, start engine and 
leave running for at least 
30 seconds, then retest. If 
fault persists, repeat the 
above procedure and retest
If the fault continues to 
persist, check and install a 
new rear door module as 
required. Clear the DTC, 
operate the rear door 
switchpack and retest
B1C09-
11
Driver Left
/Right Mirror 
Motor Circuit - 
Circuit short to 
ground
Driver mirror 
adjustment 
motor circuit - 
Short circuit to 
ground
Mirror motor 
failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the mirror adjustment 
motor circuit (pin 8) 
between the drivers door 
module and the door 
mirror assembly for short 
circuit to ground. Repair 
circuit as required. 
Reconnect battery, clear 
DTCs and attempt to move 
the door mirror left and 
right, then retest
If the fault persists, check 
and install a new door 
mirror as required
B1C09-
15
Driver Left
/Right Mirror 
NOTE:
NOTE:
Disconnect the battery 
prior to performing 
circuit checks

Motor Circuit - 
Circuit short to 
battery or open
Driver door 
mirror left/right 
adjust circuit 
short circuit to 
power, open 
circuit, high 
resistance
Driver door 
mirror motor 
internal failure
Refer to the electrical 
circuit diagrams and check 
the driver door mirror left
/right adjust circuit (pin 8) 
for short circuit to power, 
open circuit, high 
resistance. Reconnect 
battery, clear DTCs and 
attempt to move the 
mirror left and right
If DTC sets again check 
and install a new driver 
door mirror as required
B1C10-
11
Driver Up
/Down Mirror 
Motor Circuit - 
Circuit short to 
ground
Driver mirror 
adjustment 
motor circuit - 
Short circuit to 
ground
Mirror motor 
failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the mirror adjustment 
motor circuit (pin 24) 
between the drivers door 
module and the door 
mirror assembly for short 
circuit to ground. Repair 
circuit as required. 
Reconnect battery, clear 
DTCs and attempt to move 
the door mirror up and 
down, then retest
If the fault persists, check 
and install a new door 
mirror as required
B1C10-
15
Driver Up
/Down Mirror 
Motor Circuit - 
Circuit short to 
battery or open
Driver mirror 
adjustment 
motor circuit - 
Short circuit to 
NOTE:
Circuit 
reference 
MIRRORBX / 
MIRRORBXY
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

power, open 
circuit, high 
resistance
Mirror motor 
failure
Refer to the electrical 
circuit diagrams and check 
the mirror adjustment 
motor circuit (pin 24) 
between the drivers door 
module and the door 
mirror assembly for short 
circuit to power, open 
circuit, high resistance. 
Repair circuit as required. 
Reconnect battery, clear 
DTCs and attempt to move 
the door mirror up and 
down, then retest
If the fault persists, check 
and install a new door 
mirror as required
B1C11-
11
Passenger Left
/Right Mirror 
Motor Circuit - 
Circuit short to 
ground
Passenger mirror 
adjustment 
motor circuit - 
Short circuit to 
ground
Mirror motor 
failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the mirror adjustment 
motor circuit (pin 8) 
between the passenger 
door module and the door 
mirror assembly for short 
circuit to ground. Repair 
circuit as required. 
Reconnect battery, clear 
DTCs and attempt to move 
the door mirror left and 
right, then retest
If the fault persists, check 
and install a new door 
mirror as required
B1C11-
15
Passenger Left
/Right Mirror 
Motor Circuit - 
Circuit short to 
battery or open
Passenger mirror 
adjustment 
motor circuit - 
Short circuit to 
power, open 
circuit, high 
resistance
NOTE:
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

Mirror motor 
failure
Refer to the electrical 
circuit diagrams and check 
the mirror adjustment 
motor circuit (pin 8) 
between the passenger 
door module and the door 
mirror assembly for short 
circuit to power, open 
circuit, high resistance. 
Repair circuit as required. 
Reconnect battery, clear 
DTCs and attempt to move 
the door mirror left and 
right, then retest
If the fault persists, check 
and install a new door 
mirror as required
B1C12-
11
Passenger Up
/Down Mirror 
Motor Circuit - 
Circuit short to 
ground
Passenger mirror 
adjustment 
motor circuit - 
Short circuit to 
ground
Mirror motor 
failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the mirror adjustment 
motor circuit (pin 24) 
between the passenger 
door module and the door 
mirror assembly for short 
circuit to ground. Repair 
circuit as required. 
Reconnect battery, clear 
DTCs and attempt to move 
the door mirror up and 
down, then retest
If the fault persists, check 
and install a new door 
mirror as required
B1C12-
15
Passenger Up
/Down Mirror 
Motor Circuit - 
Circuit short to 
battery or open
Passenger mirror 
adjustment 
motor circuit - 
Short circuit to 
power, open 
circuit, high 
resistance
NOTE:
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

Mirror motor 
failure
Refer to the electrical 
circuit diagrams and check 
the mirror adjustment 
motor circuit (pin 24) 
between the passenger 
door module and the door 
mirror assembly for short 
circuit to power, open 
circuit, high resistance. 
Repair circuit as required. 
Reconnect battery, clear 
DTCs and attempt to move 
the door mirror up and 
down, then retest
If the fault persists, check 
and install a new door 
mirror as required
B1C13-
11
Driver Up
/Down Mirror 
Motor 
Feedback 
Circuit - Circuit 
short to ground
Driver mirror 
adjustment 
motor sensor Y 
circuit - Short 
circuit to ground
Mirror motor 
sensor failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the mirror adjustment 
motor sensor Y circuit (pin 
18) between the driver 
door module and the door 
mirror assembly for short 
circuit to ground. Repair 
circuit as required. 
Reconnect battery, clear 
DTCs and attempt to move 
the door mirror up and 
down, then retest
If the fault persists, check 
and install a new door 
mirror as required
B1C13-
15
Driver Up
/Down Mirror 
Motor 
Feedback 
Circuit - Circuit 
short to 
battery or open
Driver mirror 
adjustment 
motor sensor Y 
circuit - Short 
circuit to power, 
open circuit, high 
resistance
NOTE:
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

Mirror motor 
sensor failure
Refer to the electrical 
circuit diagrams and check 
the mirror adjustment 
motor sensor Y circuit (pin 
18) between the driver 
door module and the door 
mirror assembly for short 
circuit to power, open 
circuit, high resistance. 
Repair circuit as required. 
Reconnect battery, clear 
DTCs and attempt to move 
the door mirror up and 
down, then retest
If the fault persists, check 
and install a new door 
mirror as required
B1C14-
11
Driver Left
/Right Mirror 
Motor 
Feedback 
Circuit - Circuit 
short to ground
Driver mirror 
adjustment 
motor sensor X 
circuit - Short 
circuit to ground
Mirror motor 
sensor failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the mirror adjustment 
motor sensor X circuit (pin 
19) between the driver 
door module and the door 
mirror assembly for short 
circuit to ground. Repair 
circuit as required. 
Reconnect battery, clear 
DTCs and attempt to move 
the door mirror left and 
right, then retest
If the fault persists, check 
and install a new door 
mirror as required
B1C14-
15
Driver Left
/Right Mirror 
Motor 
Feedback 
Circuit - Circuit 
short to 
battery or open
Driver mirror 
adjustment 
motor sensor X 
circuit - Short 
circuit to power, 
open circuit, high 
resistance
NOTE:
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

Mirror motor 
sensor failure
Refer to the electrical 
circuit diagrams and check 
the mirror adjustment 
motor sensor X circuit (pin 
19) between the driver 
door module and the door 
mirror assembly for short 
circuit to power, open 
circuit, high resistance. 
Repair circuit as required. 
Reconnect battery, clear 
DTCs and attempt to move 
the door mirror left and 
right, then retest
If the fault persists, check 
and install a new door 
mirror as required
B1C15-
11
Passenger Up
/Down Mirror 
Motor 
Feedback 
Circuit - Circuit 
short to ground
Passenger mirror 
adjustment 
motor sensor Y 
circuit - Short 
circuit to ground
Mirror motor 
sensor failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the mirror adjustment 
motor sensor Y circuit (pin 
18) between the 
passenger door module 
and the door mirror 
assembly for short circuit 
to ground. Repair circuit 
as required. Reconnect 
battery, clear DTCs and 
attempt to move the door 
mirror up and down, then 
retest
If the fault persists, check 
and install a new door 
mirror as required
B1C15-
15
Passenger Up
/Down Mirror 
Motor 
Feedback 
Passenger mirror 
adjustment 
motor sensor Y 
circuit - Short 
NOTE:
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

Circuit - Circuit 
short to 
battery or open
circuit to power, 
open circuit, high 
resistance
Mirror motor 
sensor failure
Refer to the electrical 
circuit diagrams and check 
the mirror adjustment 
motor sensor Y circuit (pin 
18) between the 
passenger door module 
and the door mirror 
assembly for short circuit 
to power, open circuit, 
high resistance. Repair 
circuit as required. 
Reconnect battery, clear 
DTCs and attempt to move 
the door mirror up and 
down, then retest
If the fault persists, check 
and install a new door 
mirror as required
B1C16-
11
Passenger Left
/Right Mirror 
Motor 
Feedback 
Circuit - Circuit 
short to ground
Passenger mirror 
adjustment 
motor sensor X 
circuit - Short 
circuit to ground
Mirror motor 
sensor failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the mirror adjustment 
motor sensor X circuit (pin 
19) between the 
passenger door module 
and the door mirror 
assembly for short circuit 
to ground. Repair circuit 
as required. Reconnect 
battery, clear DTCs and 
attempt to move the door 
mirror left and right, then 
retest
If the fault persists, check 
and install a new door 
mirror as required
B1C16-
15
Passenger Left
/Right Mirror 
Motor 
Feedback 
Passenger mirror 
adjustment 
motor sensor X 
circuit - Short 
NOTE:
Disconnect the battery 
prior to performing 
circuit checks

Circuit - Circuit 
short to 
battery or open
circuit to power, 
open circuit, high 
resistance
Mirror motor 
sensor failure
Refer to the electrical 
circuit diagrams and check 
the mirror adjustment 
motor sensor X circuit (pin 
19) between the 
passenger door module 
and the door mirror 
assembly for short circuit 
to power, open circuit, 
high resistance. Repair 
circuit as required. 
Reconnect battery, clear 
DTCs and attempt to move 
the door mirror left and 
right, then retest
If the fault persists, check 
and install a new door 
mirror as required
B1D06-
11
Left Turn 
Indicator - 
Circuit short to 
ground
Left turn side 
repeater circuit - 
Short circuit to 
ground
Bulb/LED failure
Side repeater 
lamp assembly - 
Internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the left turn side repeater 
circuit (pin 11) for short 
circuit to ground. Repair 
circuit as required. Clear 
DTC and retest
If the fault persists, check 
and install a new side 
repeater bulb/LED as 
required. Clear DTC and 
retest
If the fault persists, check 
and install a new side 
repeater assembly as 
required. Clear DTC and 
retest
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

B1D06-
15
Left Turn 
Indicator - 
Circuit short to 
battery or open
Bulb/LED failure
Left turn side 
repeater circuit - 
Short circuit to 
power, open 
circuit, high 
resistance
Side repeater 
lamp assembly - 
Internal failure
NOTE:
Check and install a new 
side repeater bulb/LED as 
required. Clear DTC and 
retest
If the fault persists, refer 
to the electrical circuit 
diagrams and check the 
left turn side repeater 
circuit (pin 11) for short 
circuit to power, open 
circuit, high resistance. 
Repair circuit as required. 
Clear DTC and retest
If the fault persists, check 
and install a new side 
repeater assembly as 
required. Clear DTC and 
retest
B1D07-
11
Right Turn 
Indicator - 
Circuit short to 
ground
Right turn side 
repeater circuit - 
Short circuit to 
ground
Bulb/LED failure
Side repeater 
lamp assembly - 
Internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the right turn side 
repeater circuit (pin 11) 
for short circuit to ground. 
Repair circuit as required. 
Clear DTC and retest
If the fault persists, check 
and install a new side 
repeater bulb/LED as 
required. Clear DTC and 
retest
If the fault persists, check 
and install a new side 
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

repeater assembly as 
required. Clear DTC and 
retest
B1D07-
15
Right Turn 
Indicator - 
Circuit short to 
battery or open
Bulb/LED failure
Right turn side 
repeater circuit - 
Short circuit to 
power, open 
circuit, high 
resistance
Side repeater 
lamp assembly - 
Internal failure
NOTE:
Check and install a new 
side repeater bulb/LED as 
required. Clear DTC and 
retest
If the fault persists, refer 
to the electrical circuit 
diagrams and check the 
right turn side repeater 
circuit (pin 11) for short 
circuit to power, open 
circuit, high resistance. 
Repair circuit as required. 
Clear DTC and retest
If the fault persists, check 
and install a new side 
repeater assembly as 
required. Clear DTC and 
retest
C1B14-
11
Sensor Supply 
Voltage A - 
Circuit short to 
ground
Front door 
window hall 
sensor supply 
circuit - Short 
circuit to ground
Front door 
window motor - 
Internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the window hall sensor 
supply circuit (pin 17) for 
short circuit to ground. 
Repair circuit as required. 
Reconnect battery, clear 
DTCs and operate window, 
then retest
If the fault persists, check 
and install a new front 
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

door window motor as 
required. Clear DTC and 
retest
C1B14-
15
Sensor Supply 
Voltage A - 
Circuit short to 
battery or open
Front door 
window hall 
sensor supply 
circuit - Short 
circuit to power, 
open circuit, high 
resistance
Front door 
window motor - 
Internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the window hall sensor 
supply circuit (pin 17) for 
short circuit to power, 
open circuit, high 
resistance. Repair circuit 
as required. Reconnect 
battery, clear DTCs and 
operate window, then 
retest
If the fault persists, check 
and install a new front 
door window motor as 
required. Clear DTC and 
retest
U0010-
00
Medium Speed 
CAN 
Communication 
Bus - No sub 
type 
information
Medium speed 
CAN 
communication 
bus fault
Door module - 
Internal failure
Refer to the electrical 
circuit diagrams and check 
the power and ground 
connections to the 
module. Repair circuit as 
required
Using the manufacturer 
approved diagnostic 
system, complete a CAN 
network integrity test. 
Refer to the electrical 
circuit diagrams and check 
the CAN network. Repair 
circuit as required. Clear 
DTC and retest
If the fault persists, check 
and install a new door 
module as required
U0208-
Lost 
Disconnect the battery 
prior to performing 
circuit checks

00
Communication 
With Seat 
Control Module 
A - No sub 
type 
information
Loss of CAN 
communication 
with driver seat 
module
Refer to the electrical 
circuit diagrams and check 
the power and ground 
connections to the module
Using the manufacturer 
approved diagnostic 
system, complete a CAN 
network integrity test. 
Refer to the electrical 
circuit diagrams and check 
the CAN network between 
the driver seat module 
and the driver door module
Check the driver seat 
module for related DTCs 
and refer to the relevant 
DTC index
U0300-
00
Internal 
Control Module 
Software 
Incompatibility 
- No sub type 
information
Invalid 
configuration 
message is 
received
Door module(s) 
ID does not 
match stored car 
configuration 
details
Check door module part 
numbers are correct for 
vehicle type
If correct modules are 
installed, reflash the car 
configuration file using the 
manufacturer approved 
diagnostic system. Clear 
DTC and retest
If incorrect modules are 
installed, check and install 
a new door module as 
required
U2010-
11
Switch 
Illumination - 
Circuit short to 
ground
Switch 
illumination 
circuit - Short 
circuit to ground
NOTE:
Refer to electrical circuit 
diagrams and check the 
switch illumination circuit 
for short circuit to ground. 
Repair circuit as required. 
Clear DTC and retest
U2011-
11
Motor - Circuit 
short to ground
Exterior door 
handle motor 
NOTE:
Disconnect the battery 
prior to performing 
circuit checks

circuit short 
circuit to ground
Exterior door 
handle module 
internal failure
Refer to the electrical 
circuit diagrams and check 
the deployable door 
handle circuit (pins
19) for short circuit to 
ground. Reconnect 
battery, clear the DTCs 
and repeatedly lock and 
unlock the vehicle
If the fault persists, check 
and install a new door 
handle module as required
U2011-
12
Motor - Circuit 
short to battery
Exterior door 
handle motor 
circuit short 
circuit to power
Exterior door 
handle module 
internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the deployable door 
handle circuit (pins
19) for short circuit to 
power. Reconnect battery, 
clear DTCs, repeatedly 
lock and unlock vehicle
If the fault persists, check 
and install a new door 
handle module as required
U2011-
13
Motor - Circuit 
open
Exterior door 
handle motor 
circuit open 
circuit, high 
resistance
Exterior door 
handle module 
and harness 
internal failure
NOTE:
Refer to the electrical 
circuit diagrams and check 
the deployable door 
handle circuit (pins
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks
Disconnect the battery 
prior to performing 
circuit checks

2015. 0 F-TYPE (X152), 501-09
REAR VIEW MIRRORS
19) for open circuit, high 
resistance. Reconnect 
battery, clear DTCs, and 
repeatedly lock and unlock 
the vehicle
If the fault persists, check 
and install a new harness 
and door handle module 
as required
U2014-
44
Control module 
hardware - 
Data memory 
failure
Control module - 
Data memory 
failure
Clear DTC and retest. If 
fault persists, reconfigure 
the door module using the 
manufacturer approved 
diagnostic system. Clear 
DTC and retest
If fault persists, check and 
install a new driver door
/passenger door module 
as required
U2100-
00
Initial 
configuration 
not complete - 
No sub type 
information
Control module 
incorrectly 
configured
Check that all parameters 
associated with the door 
module are set correctly in 
the car configuration
Reconfigure the driver door
/passenger door modules 
using the manufacturer 
approved diagnostic 
system. Clear DTC and 
retest
DESCRIPTION AND OPERATION

NOTE:
ITEM
DESCRIPTION
1
Passenger door mirror
2
Passenger Door Module (PDM)
3
Interior mirror
4
Driver door mirror
COMPONENT LOCATION
 shown, 
 mirror 
RHD (right-hand drive)
LHD (left-hand drive)
image.

5
Driver Door Module (DDM)
6
Driver door switchpack
AUTOMATIC DIMMING INTERIOR MIRROR
The automatic dimming function is permanently active when the 
ignition is in power mode 4 (Accessory) and power mode 6 (Ignition). 
The forward facing light sensor monitors the ambient light level at the 
front of the vehicle the rearward facing light sensor monitors the 
light level coming from the rear of the vehicle. When light from the 
rear of the vehicle exceeds the ambient light level from the front of 
the vehicle, the automatic dimming circuit darkens the interior mirror 
surface.
Automatic dimming is inhibited when reverse gear is selected to 
provide the driver with maximum vision. On vehicles with automatic 
transmission, the reverse gear signal is provided by the Transmission 
Control Module (TCM) via the high speed CAN bus to the CJB. The 
CJB then provides a power feed to the mirror. On vehicles with 
manual transmission, the reverse gear signal is provided by a 
transmission switch that is hardwired to the CJB.
Automatic dimming interior mirrors are connected to the vehicle 
wiring by an electrical connector in the mounting stem. The 
electrochromic mirror circuits and, where fitted, the universal 
transmitter, are powered by a feed from the central junction box 
(CJB) when the ignition is in power mode 6.
HOMELINK® UNIVERSAL TRANSMITTER
WARNING:
Before programming HomeLink® to a garage door opener or 
gate operator, make sure that people and objects are out of the 
way of the device to prevent potential harm or damage.
SYSTEM OPERATION

NOTES:
The HomeLink® wireless control system provides a convenient way 
to replace up to three hand-held Radio Frequency (RF) transmitters 
used to activate devices such as gate operators, garage door 
openers, entry door locks, security systems, even home lighting.
PROGRAMMING HOMELINK® UNIVERSAL TRANSMITTER
NOTE:
Garage door openers manufactured after 1996 may be 
equipped with rolling code protection feature. If this is the 
case, you may need a stepladder or other sturdy, safe device 
to reach the 
Learn
 or 
Smart
 button on the garage door 
opener.
When programming a garage door opener, it is advised to 
park outside of the garage.
Additional HomeLink® information can be found at www.
HomeLink.com. If additional programming support is needed, 
please call the toll-free HomeLink Hotline at 1-800-355-3515.
Please note that the instructions below apply to the majority of 
HomeLink® use cases. However, there are some HomeLink® 
applications or HomeLink® compatible systems that require 
slightly different instructions. For more information and for 
custom training instructions specific to your device, visit 
http://www.HomeLink.com.
HomeLink® is a registered trademark owned by GENTEX 
CORPORATION.

Step
Turn the ignition On.
Step
Press and hold the outer two switches of the HomeLink® universal 
transmitter until the status indicator begins to flash.
Step
Release the swiches.
This initializes the HomeLink® universal transmitter and erases 
previous settings from all three channels.
Step
It is recommended that a new battery be placed in the hand-
held transmitter of the device being programmed to HomeLink® 
for quicker training and accurate transmission of the Radio 
Frequency (RF) signal.

Place the signal emitting end of the hand held transmitter 2 - 8 cm (1 
- 3 inches) away against the underside of the rear view mirror. Keep 
the status indicator in view.
Simultaneously press and hold the activation switch on the hand held 
transmitter and the chosen switch of the HomeLink® universal 
transmitter. The status indicator begins to flash slowly.
NOTE:
Step
The status indicator begins to flash rapidly. This can take up to
seconds.
Step
Release both switches.
Do not release the buttons until the following step has been 
completed.

Step
Press the programmed HomeLink® universal transmitter switch. The 
solid status indicator light indicates the successful programming.
To program another channel on the HomeLink® universal 
transmitter, repeat Steps 4 to 7.
Step
Turn the ignition Off.
To operate the previously programmed device, press and hold the 
chosen switch of the HomeLink® universal transmitter. Release the 
switch when the device begins to operate.
PROGRAMMING HOMELINK® UNIVERSAL TRANSMITTER - DEVICES 
WITH CODE PROTECTION FEATURE
The Radio Frequency (RF) signals used to operate some home/office 
systems incorporate a code protection feature. After a channel has 
been programmed from the hand held transmitter, these systems will 
need to be trained to accept the signal from the HomeLink® universal 
transmitter. To check if a system is code protected, operate the 
appropriate HomeLink® universal transmitter switch. If the status 
indicator flashes rapidly for 1 to 2 seconds before illuminating 
permanently, the system has a code protection feature.

Locate the 
Learn
 or 
Smart
 button at the garage door opener 
receiver (motor-head unit) in the garage before performing the 
following steps. This can usually be found directly on the motor-head 
unit (see the Garage Door Opener manual to identify the 
Learn 
Button
).
Step
Turn the ignition On.
Step
Press and hold the outer two switches of the HomeLink® universal 
transmitter until the status indicator begins to flash.
Step
Release the swiches.
This initializes the HomeLink® universal transmitter and erases 
previous settings from all three channels.
Step

Place the signal emitting end of the hand held transmitter 2 - 8 cm (1 
- 3 inches) away against the underside of the rear view mirror. Keep 
the status indicator in view.
Simultaneously press and hold the activation switch on the hand held 
transmitter and the chosen switch of the HomeLink® universal 
transmitter. The status indicator begins to flash slowly.
NOTE:
Step
The status indicator begins to flash rapidly. This can take up to
seconds.
Step
Release both switches.
DO NOT release the buttons until the following step has been 
completed.

Step
Press and release the 
Learn
 or 
Smart
 switch at the garage door 
opener receiver. The name and color of the switch may vary by 
manufacturer.
After the 
Learn
 or 
Smart
 switch has been released, a status 
indicator on the garage door opener receiver will continously lit.
Step
NOTE:
Perform the following step within 30 seconds.

Return to the vehicle and press and hold the chosen switch of the 
universal transmitter for 3 seconds to activate the device. Repeat this 
step up to three times to complete the training.
If the device activates, programming is complete.
Step
Turn the ignition Off.
To operate the previously programmed device, press and hold the 
chosen switch of the universal transmitter. Release the switch when 
the device begins to operate.
HIGH BEAM ASSIST

The high beam assist system is controlled by a high beam assist 
control module which is located in the interior rear view mirror body. 
The module and the CJB are connected via the medium speed CAN 
bus.
The high beam assist control module receives a power supply from 
the CJB when the ignition is in power mode 6 (ignition on). The rear 
view mirror also includes a low resolution camera (image) sensor 
which detects headlamps and tail lamps of preceding vehicles. The 
sensor is connected to the control module which evaluates the image 
data, checking for light intensity and location.
If conditions are correct and auto high beam assist has been 
activated, the control module will activate the high beam assist by 
sending a high or low beam request message to the CJB via the 
medium speed CAN bus. The CJB then controls the shutter in the 
Xenon projector module together with the high beam fill-in lamp. 
For additional information, refer to: 
 (417-01 Exterior 
Exterior Lighting
Lighting, Description and Operation). 
Interior Mirrors
COMPONENT DESCRIPTION

ITEM
DESCRIPTION
1
Rear light sensor
2
Front light sensor
3
Universal Transmitter Light Emitting Diode (LED) (market dependent
4
Universal Transmitter channel switch

The interior rear view mirror is provided as a electrically operated 
automatic dimming type.
The automatic dimming mirror comprises an electro-chromatic glass 
housed within a surrounding case that is attached with a ball joint 
connector to the mirror stem.
Light sensors are mounted on the front and rear of the mirror 
surround case. The sensors control the automatic dimming feature to 
reduce glare from the headlights of following vehicles.
Heating
Heating of the exterior mirrors is controlled by the CJB and the 
respective door modules, and is active while the ignition is in power 
mode 6 or 7.
The CJB receives the ambient air temperature value from the 
instrument cluster via the CAN (controller area network) bus. The CJB 
converts the ambient air temperature value to an on-time percentage 
and transmits it on the medium speed CAN bus to the two door 
modules, which then energize the exterior mirror heating elements 
accordingly. The on-time percentage is increased while the windshield 
wipers are on.
Exterior Mirror Heating Times
Ambient Air 
Temperature in °
C (°F)

-
(14)
- 10 to
(14 to 
32)
0 to
(32 to 
59)
15 to
(59 to 
77)
25 to
(77 to 
95)
!
(!95)
On-time 
Percentage
100
75
50
25
0
0
On-time 
Percentage With 
Wipers On
100
100
75
50
25
0
On vehicles with the parked heating function, exterior mirror heating 
may also operate when the parked heating function is active, 
depending on the ambient air temperature.

For additional information, refer to: 
 (412-01 Climate 
Air Conditioning
Control, Description and Operation). 
Dimming
Exterior mirrors with automatic dimming are slaved to the interior 
mirror. The interior mirror determines the amount of dimming 
required and energizes the electrochromic elements in the exterior 
mirrors accordingly. Feed and ground wires from the interior mirror, 
for the electrochromic elements in the exterior mirrors, bypass the 
door modules and connect directly to the exterior mirrors.
Mirror Memory
The seat, exterior mirrors and steering column memory functions are 
integrated into the CJB.
The driver and front passenger door modules control the mirror 
memory while the driver seat module controls the seat and the CJB 
controls the steering column memory.
Located on the outboard side of the driver seat plinth, the memory 
switch and memory pre-set switches can be used to store 3 different 
mirror positions. When a position is stored or recalled, the 
information is transmitted to the CJB via the medium speed CAN. It is 
then relayed to the door modules. Each door module evaluates the 
recalling and storage commands transmitted via the medium 
speedCAN for positions 1 to 3 and performs the necessary 
adjustments.
If a manual adjustment is selected while the mirror memory is 
operating, it will over-ride the memory recall function.
For mirror memory to operate, the mirror adjustment potentiometers 
must deliver a voltage value in the range of 80mV - 4.8V. Should a 
voltage applied be outside of this range the mirror will not operate 
when memory is selected.
Reverse Dipping

If the customer has activated reverse dipping when reverse gear is 
selected and the vehicle is in power mode 6 or 7, the driver and 
passenger exterior mirrors dip to provide a better view of the kerb. 
The mirrors return to their original position immediately upon reverse 
gear being disengaged.
The kerb view mirror position can be adjusted using the mirror 
adjustment multi-directional switch while reverse gear is selected and 
the vehicle in power mode 6 or 7.
Blind Spot Monitoring
NOTE:
ITEM
DESCRIPTION
1
Warning alert icon
2
System status warning indicator
Blind spot monitoring function alerts the driver to a vehicle located in 
the vehicle blind spot. A warning indicator is located in each exterior 
mirror towards the outer edge. 
Some variation in the illustrations may occur, but the essential 
information is always correct.

For additional information, refer to: 

Blindspot Monitoring System
(413-09 Warning Devices, Description and Operation). 
Electrochromic Mirror
The electrochromic mirrors automatically dim to reduce glare from 
the headlights of following vehicles in dark or low light conditions. In 
addition to dimming the interior mirror, the electrochromic mirror 
circuits also control the dimming of the two exterior mirrors, via 
power feed and ground connections with the 2 exterior mirrors.
A light sensor on the front of the interior mirror monitors ambient 
light at the front of the vehicle and a light sensor in the interior 
mirror glass monitors the light coming from behind the vehicle. When 
the light from behind the vehicle exceeds the ambient light level, the 
electrochromic circuits simultaneously dim the interior and exterior 
mirrors. Dimming is inhibited when reverse gear is selected. The 
interior mirror is provided with a reverse gear signal by the Lighting 
Control Module (LCM).
NOTE:
CONTROL DIAGRAM
   Hardwired    Medium Speed 
A
N
CAN (controller area 
 bus    
 bus
network)
O
LIN (local interconnect network)

ITEM
DESCRIPTION
1
Central Junction Box (CJB)
2
Driver door switchpack
3
Interior rear view mirror

4
Driver door mirror
5
Passenger door mirror
6
Passenger Door Module (PDM)
7
Driver Door Module (DDM)

2015. 0 F-TYPE (X152), 501-09
REAR VIEW MIRRORS
AUTO-DIMMING INTERIOR MIRROR - COUPE 
(G1716713)
REMOVAL AND INSTALLATION
76. 10.56
AUTO DIM 
INTERIOR 
MIRROR - 
RENEW
CABRIOLET
0.
USED 
WITHINS
76. 10.56
AUTO DIM 
INTERIOR 
MIRROR - 
RENEW
COUPE
0.
USED 
WITHINS
NOTES:
REMOVAL
Some variation in the illustrations may occur, but the essential 
information is always correct.
Removal steps in this procedure may contain installation 
details.
1.

CAUTIONS:
Take extra care not to damage the clips.
Protect the surrounding trim to avoid damage.
CAUTIONS:
Take extra care not to damage the clips.
Protect the surrounding trim to avoid damage.
2.

3.

4.

CAUTION:
To avoid damage to the mirror glass, make sure force is 
only applied at the mirror base.
INSTALLATION
CAUTION:
Make sure that the component is correctly located on the 
locating pegs.
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-09
REAR VIEW MIRRORS
AUTO-DIMMING INTERIOR MIRROR - 
FOLDING TOP (G1580262)
REMOVAL AND INSTALLATION
76. 10.56
AUTO DIM 
INTERIOR 
MIRROR - 
RENEW
CABRIOLET
0.
USED 
WITHINS
76. 10.56
AUTO DIM 
INTERIOR 
MIRROR - 
RENEW
COUPE
0.
USED 
WITHINS
NOTES:
REMOVAL
Some variation in the illustrations may occur, but the essential 
information is always correct.
Removal steps in this procedure may contain installation 
details.
1.

CAUTIONS:
Take extra care not to damage the clips.
Protect the surrounding trim to avoid damage.
2.
3.

INSTALLATION
CAUTION:
Make sure that the component is correctly located.
1.

To install, reverse the removal procedure.

2015. 0 F-TYPE (X152), 501-09
REAR VIEW MIRRORS
EXTERIOR MIRROR COVER (G1580264)
REMOVAL AND INSTALLATION
76. 11.26
EXTERIOR 
MIRROR 
CAP - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
CAUTION:
Take extra care not to damage the component.
NOTES:
REMOVAL
Removal steps in this procedure may contain installation 
details.
LH illustration shown, RH is similar.
Refer to: 
 (501-09 Rear View Mirrors, 
Exterior Mirror Motor
Removal and Installation).
1.
2.

3.
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-09
REAR VIEW MIRRORS
EXTERIOR MIRROR MOTOR (G1580266)
REMOVAL AND INSTALLATION
76. 10.57
EXTERIOR 
MIRROR 
MOTOR 
ASSEMBLY 
- RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (501-09 Rear View Mirrors, 
Exterior Mirror Glass
Removal and Installation).
1.
2.

3.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-09
REAR VIEW MIRRORS
EXTERIOR MIRROR GLASS (G1580265)
REMOVAL AND INSTALLATION
76. 10.53
EXTERIOR 
MIRROR 
GLASS - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
CAUTIONS:
Do not use tools during this operation, removal of 
the component(s) must be carried out by hand.
Take extra care not to damage the component.
1.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-09
REAR VIEW MIRRORS
EXTERIOR MIRROR MOTOR (G1580266)
REMOVAL AND INSTALLATION
76. 10.57
EXTERIOR 
MIRROR 
MOTOR 
ASSEMBLY 
- RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (501-09 Rear View Mirrors, 
Exterior Mirror Glass
Removal and Installation).
1.
2.

3.

2015. 0 F-TYPE (X152), 501-09
REAR VIEW MIRRORS
EXTERIOR MIRROR GLASS (G1580265)
INSTALLATION
To install, reverse the removal procedure.
1.
REMOVAL AND INSTALLATION
76. 10.53
EXTERIOR 
MIRROR 
GLASS - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS

NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
CAUTIONS:
Do not use tools during this operation, removal of 
the component(s) must be carried out by hand.
Take extra care not to damage the component.
1.
INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-09
REAR VIEW MIRRORS
EXTERIOR MIRROR (G1580263)
REMOVAL AND INSTALLATION
76. 10.52
EXTERIOR 
MIRROR - 
RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
Refer to: 
 (501-05 Interior Trim and 
Front Door Trim Panel
Ornamentation, Removal and Installation).
1.
2.

3.

2015. 0 F-TYPE (X152), 501-05
INTERIOR TRIM AND ORNAMENTATION

Torque: 9 Nm
INSTALLATION
To install, reverse the removal procedure.
1.

FRONT DOOR TRIM PANEL (G1584209)
REMOVAL AND INSTALLATION
76. 34.01
FRONT 
DOOR 
TRIM PAD 
- RENEW
ALL 
DERIVATIVES
0.
USED 
WITHINS
76. 34.01
FRONT 
DOOR 
TRIM PAD 
- RENEW
COUPE
0.
USED 
WITHINS
NOTE:
REMOVAL
Removal steps in this procedure may contain installation details.
1.
2.

3.
4.

5.
6.

NOTE:
Do not disassemble further if the component is removed 
for access only.
7.
8.

9.
10.

11.
12.

13.
14.

15.
16.

INSTALLATION
To install, reverse the removal procedure.
1.

2015. 0 F-TYPE (X152), 501-10
SEATING
SPECIFICATIONS
Torque Specifications
ITEM
NM
LB-FT
LB-IN
Front seat track to vehicle floor - bolt
48
35
-
Front seat height adjustment motor retaining bolts
22
16
-
Front seat backrest frame to seat base bolts
50
37
-
Front seat module retaining bolts
9
6
-
Front seat side air bag retaining bolts
7
5
-
NOTE:

New nut/bolt must be installed.

2015. 0 F-TYPE (X152), 501-10
SEATING
DESCRIPTION AND OPERATION

ITEM
DESCRIPTION
1
Sport seats
2
Performance seats
COMPONENT LOCATION - SHEET 1 OF

ITEM
DESCRIPTION
1
Right seat switchpack
2
Left seat switchpack
3
Seat modules
COMPONENT LOCATION - SHEET 2 OF

ITEM
DESCRIPTION
1
Cushion heater element
2
Backrest heater element
3
Seat heater control module
LEATHER SEAT COVERS
Leather is a natural product, therefore it bears natural characteristics, 
such as grain variations, growth 	 bush marks. These non-weakening 
COMPONENT LOCATION - SHEET 3 OF
OVERVIEW

marks show the true nature of the hide and are the hallmarks of 
Leather. In order to maintain the beauty of the vehicles natural 
Leather upholstery it requires regular cleaning, which if neglected, 
may cause deterioration. Where dust and dirt are allowed to 
accumulate and become ingrained in the surface of the Leather, the 
upholstery may become permanently damaged.
Light coloured upholstery can be particularly susceptible to soiling 
and staining and care should be taken to ensure that where there is 
evidence of any soiling or staining on the upholstery then this should 
be cleaned immediately using the Jaguar/Land Rover approved 
products, failure to do this could lead to the stain becoming 
permanent, this applies to all leather upholstery and is not colour 
specific.
Leather trimmed seats will naturally exhibit areas of creasing and 
wrinkling over a period of time and is a normal characteristic as the 
Leather ages.
Particular care should be taken where there is evidence of soiling or 
staining on the leather, this should be cleaned immediately. Failure to 
do this could lead to the stain becoming permanent.
Particular care should be taken to prevent damage from studs, zips 
and buckles.
NOTES:
Please refer to Leather care label attached to seats for more 
information.
Creasing and wrinkling does not represent a manufacturing 
defect.
Damage from studs, zips and buckles do not represent 
manufacturing defects.
Use only Jaguar/Land Rover approved products in accordance 
with the instructions for use.

The vehicle is fitted with either sport seats or performance seats. The 
two types of seat incorporate either 6-way or 14-way adjustment and 
may also incorporate seat heating (option or market dependent).
Seats with 6-way adjustment have manual forward/rearward 
adjustment, and electric adjustment for:
Seat height
Backrest recline.
Seats with 14-way adjustment have all electric adjustment for:
Seat forward/rearward
Seat height
Backrest recline
Cushion tilt
4-way lumbar
Side bolsters.
Seat adjustment is controlled by a seat switchpack and a seat module 
for each seat. Seats with 14-way adjustment have a position memory 
feature incorporated into their control system.
On vehicles with seat heating, heater elements are incorporated into 
the cushions and the backrests. Power to the heater elements for 
each seat is controlled by a seat heater control module incorporated 
into the seat harness.
Seat heating is selected on the ICP (integrated control panel) and 
relayed to the seat heater control modules by the ATCM (automatic 
temperature control module). 
For additional information, refer to: 
 (412-01 
Control Components
Climate Control, Description and Operation).

A side airbag is installed in the backrest of each seat. 
For additional information, refer to: Supplemental Restraint System 
 (100-00 General Information, 
(SRS) Health and Safety Precautions
Description and Operation). 
The driver and passenger front seats, although almost identical, have 
some unique components. The front driver seat has a seat position 
sensor and the front passenger seat has an occupancy sensing 
system. In both instances the components form an integral part of 
the air bag 
 . 
SRS (supplemental restraint system)
For additional information, refer to: Air Bag Supplemental Restraint 
 (501-20B Supplemental Restraint System, Description 
System (SRS)
and Operation). 
SEATS
Seat Adjustment - 6-way Adjustable Seats
ITEM
DESCRIPTION
DESCRIPTION

1
Seat height motor
2
Seat forward/rearward release handle
3
Seat backrest recline motor
Seat Adjustment - 14-way Adjustable Seats
ITEM
DESCRIPTION
1
Seat lumbar assembly
2
Seat bolster
3
Seat backrest recline motor
4
Lumbar solenoid
5
Seat bolster solenoid
6
Seat cushion tilt motor
7
Seat forward/rearward motor
8
Seat height motor
9
Lumbar air pump
10
Seat bolster

Seat position is monitored by the related seat module using inputs 
from Hall sensors in the seat adjustment motors. This prevents the 
seat from being adjusted to a position that will contact the 
surrounding interior trim (clash avoidance).
Seat memory is standard on seats with 14-way adjustment. Each 
seat memory can be configured for three positions, which are set 
using the seat memory switches and stored in the individual seat 
module.
Selections on the seat adjustment and memory switches are 
transmitted on a 
 bus to the related 
LIN (local interconnect network)
seat control module.
SEAT HARNESS CONNECTORS
SEAT HEATERS
The heater elements are installed under the cushion and backrest 
covers of the seat. The heater elements are connected in parallel to 
the seat heater control module, which is provided with an ignition 
feed from the comfort relay in the 
 and a 
AJB (auxiliary junction box)
 bus connection from the ATCM.
LIN
SEAT SWITCHPACKS
6-way Adjustable Seats

ITEM
DESCRIPTION
1
Seat backrest recline switch
2
Seat height switch
14-way Adjustable Seats
ITEM
DESCRIPTION
1
Memory LED indicator
2
Seat position memory store switch
3
Stored memory position switch
4
Stored memory position switch
5
Stored memory position switch

6
Seat backrest recline switch
7
Seat bolster switch
8
Seat forward/rearward, height and tilt switch
9
Lumbar switch
The seat switchpacks are installed in the driver and passenger door 
casings.
SEAT MODULES
ITEM
DESCRIPTION
1
Seat module ± 6-way adjustable seats
2
Seat module ± 14-way adjustable seats
The seat modules, located under the driver and front passenger 
seats, rely upon a number of inputs to control various outputs. As 
with all electronic control modules, the unit needs information 
regarding the current operating conditions of the engine and other 
related systems before it can make calculations, which determine the 
appropriate outputs.
AUDIBLE AND VISUAL CONFIRMATIONS
A single chime audible confirmation is generated by the instrument 
cluster to provide confirmation to the driver that the memory store 
operation has been successfully completed.

In addition to audible confirmation there is also a visual confirmation 
via the instrument cluster message center.
IMMEDIATE ADJUSTMENT
Pressing one of the manual adjustment switches will initiate the 
corresponding motor for that axis until the switch is released.
Only 2 seat motors can be driven at any one time.
STALL DETECTION
Seat, steering column and mirror motors are deemed to have stalled 
if there is no change in the inputs that are received from the 
corresponding feedback sensors for more than approximately 0.5 
seconds (times differ slightly for each motor).
If a stall condition is detected then the drive to that axis is cancelled 
for the remainder of that memory operation (memory recall) or until 
the switch is re-selected (manual movement).
If the motor movement has stopped due to loss of sensor feedback, 
either stall or sensor failure, then that axis may be activated again, to 
move past the stall position, by re-selecting the appropriate switch 
and pressing for longer than 2 seconds. This allows control of the 
motor to be maintained if sensor feedback is lost.
Upon re-selection of movement, if sensor pulses are detected then 
the motor will continue to be driven until the switch is released or 
another stall condition is detected. If sensor feedback is not detected 
then the motor is only driven for 0.5 second and then stops until the 
switch is released and then pressed again, when a further 0.5 second 
of activation is permitted, and so on, this is known as inch mode.
For all seat motor manual movements, whenever a motor is driven 
and a stall occurs, the seat control module records the position at 
OPERATION

which the stall occurred. If movement occurs beyond a stall position, 
then that position is erased from the control modules memory. This 
will always allow movement past a previously recorded stall position 
once movement has been registered beyond that position. This is the 
case for both manual and memory movement.
INITIALI=ATION
When a replacement seat control module is fitted to a seat it should 
be calibrated using Jaguar approved diagnostic equipment so that the 
control module can learn the absolute position of the seat.
BATTERY MONITOR
If the battery voltage drops below 10.5 Volts, then the seat control 
module ignores all requests for a memory recall until the battery 
voltage has reached 11.5 Volts. This will conserve as much power in 
the vehicle battery as possible to enable engine cranking.
STAND-BY MODE
The seat control module supports a stand-by mode to keep power 
consumption to a minimum.
If the control module is being prevented from entering stand-by 
mode due to motor movement, memory recall or switch operation, 
then it will enter stand-by mode when the current function has 
terminated.
NOTE:
The control module will exit stand-by mode if there is any CAN 
 bus activity.
(controller area network)
The exchange of information between the diagnostic unit and the seat 
control module is via the medium-speed 
 bus. There is a non-
CAN
In the case of a memory recall, all memory recall operations 
should be carried out before entering stand-by mode, not just 
the current motor movement.

volatile Electronic Erasable Programmable Read Only Memory 
(EEPROM) for saving detected errors. Its contents are not lost when 
the power supply is disconnected. Only Jaguar approved diagnostic 
equipment can erase the error memory.
SEAT MEMORY
The seat control module can store up to 3 different driver seating, 
mirror and steering column positions. The numbered memory and 
single memory store switches control memory storage and recall 
operations. Each switch is a momentary action push switch.
The seat control module broadcasts memory switch selections on the 
medium speed 
 bus, for storage and recall of the door mirror and 
CAN
steering column positions by the door modules and instrument cluster 
respectively.
MEMORY STORE - DRIVER SEAT
Once the driver seat, steering column and exterior mirrors have been 
adjusted, the vehicle is able to memorize these settings for future use 
by using the following procedure:
The LED will extinguish, and a chime will sound to confirm that the 
settings have been memorized. If the ignition is ON, the message 
center will display a confirmation message.
MEMORY STORE - PASSENGER SEAT
The procedure to memorize a passenger seat position is the same as 
that for the driver seat with two exceptions. There will be no chime or 
message to confirm the settings.
MEMORY RECALL
Push the memory button M, the red Light Emitting Diode (LED) 
will illuminate for five seconds.
1
While the LED is illuminated, press button 1, 2 or 3 to memorize 
the current settings.


Memory recall has 3 memory positions stored for the seats, steering 
column and exterior mirrors. The switches for this function are 
located on driver and passenger door side trim panel. Pressing the 
appropriate numbered memory switch allows the seat to start moving 
to the position appropriate to that memory. When the switch is 
released the system will operate in manual mode. This means that 
when the switch is released, the seat will stop moving. In order to 
reach the intended memory position, the switch must not be released 
until all movement has stopped.
When a memory recall is initiated, to limit the overall current 
consumption, only 2 seat axis will move towards their intended 
position at any one time.
Both mirrors move simultaneously about the vertical axis first (left
/right), and then, once all vertical axis movements are complete, 
about the horizontal axis (up/down). To minimize the number of 
mirror drives required, a method of sharing is implemented, which 
dictates that all movement about 1 axis is complete before movement 
about the other axis commences.
SEAT HEATING
Seat heating selections on the ICP are transmitted to the ATCM on 
the medium speed 
 bus. The ATCM then sends a message on the 
CAN
 bus to the seat heater control module, which provides a feed to 
LIN
the cushion and backrest elements.
INPUT/OUTPUT DIAGRAM - 6-WAY ADJUSTABLE SEATS

A   HARDWIRED CONNECTION N   MEDIUM SPEED 
 BUS O   
CAN
 BUS.
LIN
ITEM
DESCRIPTION
1
Driver seat module
2
Instrument cluster
3
Seat backrest recline motor
4
Seat height motor
5
Ground
6
Power feed

7
Seat height motor (position signal)
8
Seat backrest recline motor (position signal)
9
Seat switchpack
INPUT/OUTPUT DIAGRAM - 14-WAY ADJUSTABLE SEATS
A   HARDWIRED CONNECTION N   MEDIUM SPEED 
 BUS O   
CAN
 BUS.
LIN
ITEM
DESCRIPTION
1
Driver seat module
2
Instrument cluster
3
Central junction box
4
Driver door module

5
Passenger door module
6
Seat backrest recline motor
7
Seat forward/rearward motor
8
Seat height motor
9
Seat cushion tilt motor
10
Lumbar air pump
11
Seat bolster solenoid
12
Lumbar solenoid
13
Ground
14
Power feed
15
Seat cushion tilt motor (position signal)
16
Seat height motor (position signal)
17
Seat forward/rearward motor (position signal)
18
Seat backrest recline motor (position signal)
19
Seat switchpack
INPUT/OUTPUT DIAGRAM - SEAT HEATING

2015. 0 F-TYPE (X152), 412-01
CLIMATE CONTROL
A   HARDWIRED CONNECTION O   
 BUS.
LIN
ITEM
DESCRIPTION
1
Seat heater control module
2
Backrest heater element
3
Cushion heater element
4
Ground
5
Power feed
6
Automatic temperature control module
DESCRIPTION AND OPERATION

ITEM
DESCRIPTION
1
Refrigerant pressure sensor
2
Humidity sensor
3
Ambient air temperature sensor
4
Pollution sensor (where fitted)
NOTE:
COMPONENT LOCATION - SHEET 1 OF
COMPONENT LOCATION - SHEET 2 OF

ITEM
DESCRIPTION
1
Sunload sensor
2
In-vehicle temperature sensor
3
Evaporator temperature sensor
4
Automatic temperature control module
5
Integrated control panel
6