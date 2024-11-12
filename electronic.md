# Electronics part 1: Set up


Wiring:

- Bpod flex i/o lick sensor channel 1 and ground via wire to bnc adapter in analog output of amplifier of lick detection, 
if pieso lick sensor

- Motor just connected with arduino shield, motor connection Bnc (needs 4 times bnc to wire)

const int Spinpib = 13;  // Define the digital output pin 			        rotating upper motor pin 
const int latpib = 11;										right left movement
const int dirpib = 8;									          	right left movement


Pin for buzzer: 
const int cue1pib = 6;								   		 for buzzer







usb mini in computer


This step guides you the connection of the electronic devices.

{{BOM}}

## Connect electronic components {pagestep}

The [Bpod](electronic.yml#bpod){Qty:1} is the central component where everything is connected to.

### Arduino

- Attach the [Bpod shield](electronic.yml#bpod_shield){Qty:1} to the [Arduino Board Due Core](electronic.yml#Arduino_Due){Qty:1}. There is only one possibility to combine them based on the labeling of pins.

- Connect the [Bpod shield](electronic.yml#bpod_shield) via an [ethernet cable](electronic.yml#ethernet){Qty:1} to the [Bpod](electronic.yml#bpod).

### Solenoid pinch valve

- Attach the two wires of the [solenoid pinch valve](electronic.yml#pv){Qty:1} to the valve connections of the [port interface board](electronic.yml#pib){Qty:1}. 

- Connect the [port interface board](electronic.yml#pib) via an [ethernet cable](electronic.yml#ethernet){Qty:1} to the [Bpod](electronic.yml#bpod).

### Motor to Arduino

- The power supply of the motor needs to be in a plug socket.

- The four other cables of the motor need to go via a [BNC to wire connector](electronic.yml#bnc_wire){Qty:4} in the [Bpod shield](electronic.yml#bpod_shield).

#### How to connect

One wire of each [BNC to wire connector](electronic.yml#bnc_wire) needs to go to a grounding. Use a [circuit board](electronic.yml#circuit_board){Qty:1} and [jumper wires](electronic.yml#jumper_wires){Qty:Some} as the Arduino has not enough groundings.


- The spin connection needs to go in pin 13
- The lateral connection needs to go in pin 11
- The direction connection needs to go in pin 8
- The go connection needs to go in pin 4


>! **Caution** 
>!
>! Adjust connection names




### Buzzer

The [buzzer](electronic.yml#buzzer){Qty:1} needs to go to the ground and into pin 6.



>! **Caution** 
>!
>! Which buzzer





## 





![](images/ardu_shield.png)

[bpod](electronic.yml#bpod){Qty:1}

[ethernet cable](electronic.yml#ethernet_cable){Qty:1}

[port interface board](electronic.yml#port_interface_board){Qty:1}

[bpod shield](electronic.yml#bpod_shield){Qty:1}

[solenoid pinch valve](electronic.yml#pv){Qty:1}

[tube](electronic.yml#pv_tube){Qty:1}

[circuit board](electronic.yml#circuit_board){Qty:some}. 

[jumper wires](electronic.yml#jumper_wires){Qty:many}


[cable ties](connectors.yml#cable_tie){Qty:many} 

[Arduino Board Due Core](electronic.yml#Arduino_Due0lp-ö){Qty:1}

#### Wiring configuration
