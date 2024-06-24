# Setting Up and Recording with Mark IV and Faceware Studio

## Introduction
This guide will help you set up the necessary hardware and software to record a video using the Mark IV camera and Faceware Studio, then use the recorded data to animate a character.

## Hardware Setup

1. [Click on this link to initiate the setup process for the necessary hardware for recording.](https://www.youtube.com/watch?v=kcALXTq6QIU)
2. Use the following image as a reference to get an overview of connections and components involved in the setup:
   <p align="center">
     <img src="images/setup_overview.png" width="600" height="400" alt="Hardware Setup Overview"></p>

## Steps to Record a Video Using Mark IV

1. *Activate the Camera*:
   - Once all connections are established, power on the camera.
2. *Power Up the Teradek Bolt*:
   - Turn on the Teradek Bolt device.
3. *Check Battery and Connections*:
   - If neither the camera nor the transmitter powers up, check the battery's charge. Recharge if needed.
4. *Begin Recording*:
   - If the Teradek Bolt displays "sending video" or if Faceware Shepherd shows "status ready" without error messages, you're set to record. If not, follow these tips to troubleshoot.

## Importing and Processing Video in Faceware Studio

1. *Importing Video*:
   - Import the recorded video into Faceware Studio by following these steps.
2. *Tracking and Calibration*:
   - Initiate tracking and calibration within Faceware Studio to track the actor's movements.
3. *Animation Streaming*:
   - To stream animation data from Faceware Studio to your character, follow the specified actions within the Studio.
4. *Live Link Plugin*:
   - Faceware provides a live link plugin to seamlessly stream data from Faceware Studio into Unreal Engine.
5. *Using MetaHuman*:
   - If you opt to use MetaHuman instead of a custom character, skip to the "Epic MetaHuman Setup" section on this page.

## Troubleshooting Data Streaming Issues

If the data streaming seems unreliable:

1. Ensure the "Streaming to Client" toggle is activated in Faceware Studio.
2. Verify that the Live Link setup is operational under Window > Virtual Production > Live Link in Unreal Engine.

Faceware also offers live client plugins for Unity and MotionBuilder.

## Additional Information

- *Live Streaming*:
  - If you intend to live stream, ensure that AJA U-TAP is correctly configured and connected.
- *Faceware Software*:
  - Faceware provides four different software applications, each serving a unique purpose:

### Analyzer
- A facial tracking software that analyzes video recordings to capture facial movements.

### Retargeter
- A facial animation plugin compatible with Maya, 3ds Max, and MotionBuilder, used to apply captured facial data to digital characters.

### Faceware Studio
- Offers real-time tracking and calibration, allowing for capture review and application of facial movements.

### Shepherd
- An application built to help you easily sync, configure, and manage multiple recording decks at the same time.

## Next Steps
- For further instructions, please proceed to the [Git Bash setup](Gitbash.md).
