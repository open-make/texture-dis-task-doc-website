# Electronics part 3: Program explanation



>!! **todo** 
>!!
>!! add programm screenshots
>! specify times and how to change
>!
>!
>!
>!


## General information

All following informations assume that you have done the wiring exactly as indicated. This is necessary as the ports are specified in the scripts and will only work in that configuration.  

## How to start {pagestep}

Start by typing "Bpod()" in the Matlab console.

This will open a window to control the Bpod where you can open another window by clicking the play button.
This new window allows you to choose the script where you can start the preset experimental procedure.

## Experimental procedure {pagestep}

With the script starts one of four random cases is chosen for 100 iterations. Each case consists of a movement of the rotational motor to place the texture in the right position. Then the horizontal motor moves to present the texture to the mouse for 2 seconds. Afterwards the motor moves back and the next iterations starts.

During the procedure an extra window is open which displays the sequence of cases and wether the mouse did a lick or not and if it was correct or false. The window has four lanes with circles. Each lane represents a case.

Information of circles:

- Full green circle: Correctly licked
- Empty green circle: Wrongly not licked
- Full red circle: Wrongly licked
- Empty red circle: Correctly not licked


## Manual controlling {pagestep}

In the Bpod window, which opens after typing "Bpod()" in the console, are several possibilities to control the setup by typing in specific codes.

### Movement control

The movement information is forwarded by numbers to the Arduino Bpod shield. Use the following numbers to do the desired movements. These movements are specified in the Arduino code file.

#### Movement codes

Code "1":

- Front rotation by 90°
- Horizontal motor movement to texture present position

Code "2":

- Front rotation by 180°
- Horizontal motor movement to texture present position

Code "3":

- Front rotation by 270°
- Horizontal motor movement to texture present position

Code "4":

- Front rotation by 360°
- Horizontal motor movement to texture present position

Code "5": 

- Back rotation by 270°
- Horizontal motor movement to default/ no texture present position

Code "6": 

- Back rotation by 180°
- Horizontal motor movement to default/ no texture present position

Code "7": 

- Back rotation by 90°
- Horizontal motor movement to default/ no texture present position

Code "8": 

- No rotation
- Horizontal motor movement to default/ no texture present position

Code "9":

- Make sound with buzzer.

Code "10":

- Make a quarter turn.

Code "11":

- Make a 1/200 turn.





### Reward control

You can manually provide rewards to the mouse by clicking "vlv1". 

The first click opens it and the second closes it.



 



### Additional informations {pagestep}

- In the Bpod window are all s.gui variables changeable
    - These are changeable during a run

- "flexthreshold" needs to be adjusted depending on the lick strength

- "S.GUI.Reward" specifies the amount of rewards by the opening time

- TrialTypes = randsrc(1,MaxTrials,[1 2 3 4; 0.25 0.25 0.25 0.25]); // List of cases and their probability, maybe only use two cases because of  wearing
    - This specifies the cases and their probabilities 

- Rotation speed defined by "for i in range 3000". 
- Lateral speed also defines as delay




rotain speed defined by 3000 variables down definiert als delay
latspeed für lateralen geschw auch definiert als delay


derzeot nur töne unterschiedlicher länge impleementiete
als alternative arduino uno hinten dran und damit vers freqsaf



### Training mode {pagestep}

Follow the [instruction](training.md) to use the training mode.



