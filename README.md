# SPIKE Prime Hub 2 Hub Communication
How can one SPIKE Prime Hub communicate with another one 

There are many ways how one SPIKE Hub can communicate to another. This list will be updated regularly.
Thanks a lot to the FB Community for the feedback and support, especially the Robotmak3rs :)
Special Credits and Authors are listed by the different solutions


## OpenWorld: 
- Communiction: wireless (use of opensource 3rd-party software on an other device)
- Prog-Language: block, python
- Complexity: low (classroom-proof)
- Files:
  - [Sender Code] (https://github.com/PhoBricks/hub2hub/blob/main/h2h_openworld_sender.llsp)
  - [Reicever Code] (https://github.com/PhoBricks/hub2hub/blob/main/h2h_openworld_receiver.llsp)
  - [instruction-Files] (https://github.com/PhoBricks/hub2hub/blob/main/h2h_OpenWorld.pdf)
- Video: [SPIKE Hub2Hub OpenWorld Example] (https://youtu.be/x4KoTypLORc)
- Credits: Dimi


## BLE: 
- Communication: wireless (direct)
- Prog-Language: python
- Complexity: medium
- Files: 
  - Sender Code (gets updated to the new library)
  - Receiver Code (gets updated to the new library)
  - instruction/library from Nard Strijbosch (https://hubmodule.readthedocs.io/en/latest/hub2hub/)
- Video: [SPIKE Hub2Hub BLE Example] (https://youtu.be/ASUmDYYeX6E)
- Credits: Nard Strijbosch, Dimi



## UART:
- Communication: wired (use of customized powerup-cable)
- Prog-Language: python
- Complexity: high

## PyLights(beta):
- Communication: PowerUP LED to LightSensor
- Prog-Language: sender(pybricks), recv(block, python, pybricks)
- Complexity: low
- Credits: pybricks

## Gestures:
- Communication: Motor to Hub 
- Prog-Language: block, python
- Complexity: low

## KnockKnock:
- Communication: Motor to Hub
- Prog-Language: block, python
- Complexity: medium

## Color:
- Communication: Colored Brick to ColorSensor
- Prog-Language: block, python, pybricks
- Complexity: low (classroom proof)

## Distance:
- Communication: Distance to DistanceSensor
- Prog-Language: block, python, pybricks
- Complexity: low (classroom proof)

## Distance2Color:
- Communication: Distance to ColorSensor
- Prog-Language: block, python, pybricks
- Complexity: low (classroom proof)

## Color2Color:
- Communication: ColorSensor to ColorSensor
- Prog-Language: python
- Complexity: medium

## Turn:
- Communication: Motor to Hub 
- Prog-Language: block, python
- Complexity: low











