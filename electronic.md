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

## Combine Arduinos {pagestep}

![](images/ardu_shield.png)

[bpod](electronic.yml#bpod){Qty:1}


[bpod shield](electronic.yml#bpod_shield){Qty:1}

[circuit board](electronic.yml#circuit_board){Qty:some}. 

[jumper wires](electronic.yml#jumper_wires){Qty:many}


[cable ties](connectors.yml#cable_tie){Qty:many} 

[Arduino Board Due Core](electronic.yml#Arduino_Due0lp-ö){Qty:1}

#### Wiring configuration
