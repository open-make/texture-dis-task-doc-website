# Construct your texture discrimination task setup!


This website will guide you through the whole process of building an texture discrimination task setup.


The experimental setup was first published in 2018, with a paper titled [Behavioral Strategy Determines Frontal or Posterior
Location of Short-Term Memory in Neocortex](https://doi.org/10.1016/j.neuron.2018.07.029).
It was designed by the authors of the paper and rebuilt within Larkum Lab. 
This documentation website was created by Fabio Reeh and reviewed by XXXX, based on the existing documentation and an own replica.

Gilad A, Gallero-Salas Y, Groos D, Helmchen F. Behavioral Strategy Determines Frontal or Posterior Location of Short-Term Memory in Neocortex. Neuron. 2018 Aug 22;99(4):814-828.e7. doi: 10.1016/j.neuron.2018.07.029. Epub 2018 Aug 9. PMID: 30100254.


>!! **Warning** 
>!!
>!! picture here


This guide is part of the output from the [open.make project](https://www.openmake.de/) (see website for more information, including funding information). This project aims to further establish open hardware in academic research, and support
 scientist in the creation of FAIR research hardware.


## Table of contents


#### [Construction of the elevated platform](platform.md){step}

#### [Precut of aluminium profile strut](platform_base.md){step}

#### [Print the mouse tube](mouse_tube.md){step}

####  [Head fixation](head_fixation.md){step}

#### [Lick detection](lick_detection.md){step}


#### [Construction of the peripherals](peripherals.md){step}

#### [Construction of horizontal motor](horizontal_motor.md){step}

#### [Construction of rotating motor](rotational_motor.md){step}


#### [Setup of the electronics](setup_electronic.md){step}

#### [Setup of the wiring](electronic.md){step}

#### [Installation of scripts](script_setup.md){step}

#### [Configuration of PixyCam](PixyCamConfig.md){step}



#### [Arduino code guide](code_usage.md){step}

#### [Training and experiment](training.md){step}









#### [List of all necessary components]{BOM}







## About the texture discrimination task

To investigate the neuronal activities in ordinary behaviour, it's eligible to implement modern brain recording equipment.
These modern technics frequently require head fixation.






## Overview of the setup

The texture discrimination task system consists out of a elevated table with the mouse placement and headfixation and two motors which present different textures to the mouse.



### Download STEP file of hole Airtrack


The STL file above and the CAD files of the ZIP folder contain partly different components. The main changes:




>i **Download** 
>i
>i Download all available CAD files and extra documents:
>i
>i Contains: STL file, CAD Parasolid file, CAD for SolidWorks viewer, STEP file, PDF with some technical aspects
>i
>i
>i [ZIP file](airtable_480x366.zip)
>i
>i **Note** 
>i
>i The STL and STEP files vary in the used components at some places to this guide



### Disclaimer: Construction complexity

Some parts are more difficult to construct than others. Mainly the combined motors are to difficult to build with an improvised work place. 

We have access to a workshop, we recommend you to get the motors constructed there. In general, it's better to have a large fraction of the setup manufactured professionally. 


### Disclaimer: Arduino/ BPod code complexity

I order to fully use the texture discrimination task setup, you need to debug and write code for the Arduino and Bpod. The provided code works but you need to adjust it at some places to adapt it to your circumstances. 

### Disclaimer: No different sounds

In the version designed for the paper [Behavioral Strategy Determines Frontal or Posterior Location of Short-Term Memory in Neocortex](https://doi.org/10.1016/j.neuron.2018.07.029) multiple frequencies are used. This version can only create one frequency but changes in the amount of sounds. Forward movements of the horizontal motor happen along two short sounds and backwards movements with four sounds. The sound one can send with the code "9" is one longer sound (check documentation about how to use the program).


### Advice: Further development

If you want to use the base hardware of the texture discrimination task setup and want to use it for other research questions, we recommend you to have a good understanding of the Bpod, Arduino and possible peripherals. 

 

References: [Gilad A, Gallero-Salas Y, Groos D, Helmchen F.: Behavioral Strategy Determines Frontal or Posterior Location of Short-Term Memory in Neocortex](https://doi.org/10.1016/j.neuron.2018.07.029)




#### Latest change: XX.XX.202X