
# Platform part 2: Mouse tube




To provide a more common environment the setup includes a tube to place the mouse in during the experiment



{{BOM}}



## 3D print the mouse tube {pagestep}

Use the following STL-file to print the mouse tube in a 3D printer. 

[3D print settings](printsettings.md)

[mouse tube]{output, qty:1, hidden}

![](models/MouseTubeSTL.stl){color: grey}



## Placement on platform {pagestep}



Mouse tube placement constraints:

- It must be placed in one corner of the [base table](fromstep). 
- The tube must be parallel to the short side of the [base table](fromstep).
- The flattened end of the tube must align with the long edge of the [base table](fromstep).

This results in two relevant placement categories. Either comes the texture to the mouse from its right or left.
The flattened end of the tube is also the place of the mouse head.

The following guide will assume that the reward is provided from the left. 

This means:

- If the mouse looks out of the tube, the corner of the [base table](fromstep) should be to the left. 


Use  [M6 screws](screws.yml#m6_screws){Qty: 2} to fixate the mouse tube on the breadboard.

