# WRO_Future_Engineers-2025
<p align="center">
<img width="782" height="733" alt="wrofe" src="https://github.com/user-attachments/assets/158750e4-8d29-4889-935d-e1269878ad6a" />
</p>

The World Robot Olympiad (WRO) is a prestigious international robotics competition that ignites the imaginations of students worldwide. It challenges participants to showcase their creativity, problem-solving skills, and technical prowess in designing and programming robots for a variety of tasks and challenges.

One of the most dynamic categories within WRO is the Future Engineers category. Here, participants are tasked with developing innovative solutions to real-world problems using robotics and automation. This category serves as a breeding ground for future innovators, encouraging students to think critically and creatively, laying the groundwork for a new generation of engineers and technologists.

This year, the Future Engineers category presents an exciting challenge: creating a self-driving car. This challenge pushes participants to explore the cutting edge of robotics, adding layers of complexity and innovation to an already thrilling competition.

It contains the full repository of Team Vai-Vai Electronics to compete in World Robot Olympiad 2025 (Category: Future Engineers).

## Content

- `t-photos`: Contains photo of the team with all team members.
- `v-photos`: Contains 6 photos of the vehicle, showcasing it from every side as well as from the top and bottom.
- `video`: Contains a `video.md` file with a link to a video demonstrating the vehicle's driving capabilities.
- `schemes`: Contains one or several schematic diagrams (JPEG, PNG, or PDF) illustrating all electromechanical components used in the vehicle, including electronic components and motors, and how they connect to each other.
- `src`: Contains the control software code for all components programmed to participate in the competition.
- `models` (optional): Contains files for models used by 3D printers, laser cutting machines, and CNC machines to produce the vehicle elements. If not needed, this directory can be removed.
- `other` (optional): Contains additional files that can help understand how to prepare the vehicle for the competition, such as documentation on connecting to a SBC/SBM, uploading files, datasets, hardware specifications, and communication protocols descriptions. If not needed, this directory can be removed.

OUR ROBOT
====
## OUR ROBOT
<p align="center">
<img width="1024" height="1024" alt="picwish_8823215301_image2" src="https://github.com/user-attachments/assets/b8ac6324-e319-4ae8-9df6-97a83a150d45" />
<br>
  <strong>OUR ROBOT</strong>
</p>

Our robot is an impressive assembly of diverse electronic components, thoughtfully integrated to deliver optimal performance. It comprises five essential subsystems, each playing a vital role in its operation. The steering module enables accurate directional control, while the gearbox facilitates seamless mechanical transitions. Environmental sensors enhance situational awareness, allowing the robot to respond intelligently to external stimuli. Finally, the propulsion system drives the robot forward with both speed and finesse.

## ROBOT AIM and OBJECTIVES
The aim of the robot is to swiftly maneuver its environment or parkour.
This involves

**Objectives**

1. Detect obstacles in the environment.
2. Avoid obstacles in the environment.
3. Perform (1) and (2) while self driving.
4. Detect state and auto-correct when crashed or in error.

## RESEARCH and BRAINSTORMING
Practical Functions of the Robot: 
Using a rear-wheel drive system the bot will be able to perform the follow (the following list is in order of priority)

### PRACTICAL FUNCTIONS OF ROBOT
● Moving in all directions
  
● Lane following
  
● Acceleration and deceleration
  
● Braking
  
● Color Detection
  
● Turning
  
● Crash handling
  
● Obstacle detection
  
● Obstacle avoidance
  
● Light adjustment

### ELABORATION OF PRACTICAL FUNCTIONS DETAILS
**COLOR DETECTION BY THE ROBOT:**  
With the OpenCV library, the robot will be programmed to detect color using the following.

**The HSV format**:

1. The video frame is read correctly.
2. Each frame is converted from BGR to HSV.
3. A mask is created using the inRange() method on the image with the image and the color to be detected as the arguments.
4. After doing the above, a threshold image is created by the mask. This blacks out every other item in the image leaving only the pixels that match the mask. This creates a black background with a white range of detection.
5. This shows that the color has been detected.

## Energy Source for the Robot

The robot uses a power bank that has an output of 5V/2.5A or less.

## Bill of materials

| Quantity | Status                             | Description                                                                                                                                             |
| ---------| ---------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1        | Raspberry Pi 4 Model B             | ![Raspberry-Pi4](https://github.com/DexterTaha/WRO-2024-FUTURE-ENGINEERS/assets/130682580/29ab19c0-aab2-42f6-a3a3-ed79587e58bc)                         |
| 1        | Raspberry Pi Camera Module V1.3    | <img width="701" height="686" alt="picam (1)" src="https://github.com/user-attachments/assets/4f09dcce-4395-4877-919d-f3444324d50a" />                  |
| 1        | 5V power bank                      | ![5v power bank](https://github.com/DexterTaha/WRO-2024-FUTURE-ENGINEERS/assets/130682580/4259c9a3-a346-4806-9d60-ad36e5115942)                         |
| 3        | 18650 Lithium-ion battery (with casing)         |<img width="634" height="577" alt="battery (2)" src="https://github.com/user-attachments/assets/4261f1c6-33a5-4fd2-aac2-f326e78b0566"  />   |
| 3        | Ultrasonic Sonar Sensor HC-SR04    |      <img width="702" height="702" alt="sonar (1)" src="https://github.com/user-attachments/assets/2435b370-180a-41d3-a2de-4b57223c832e" />             |
| 5        | High Torque Gear Motor 12V 300RPM  | <img width="702" height="703" alt="motor (1)" src="https://github.com/user-attachments/assets/4f9ad0bd-93da-43d9-ab16-166273b93a6a" />                  |
| 2        | L298N Motor Driver                 |   <img width="634" height="577" alt="driver (1)" src="https://github.com/user-attachments/assets/d7f3ebab-f937-4992-8749-feecf9789d80" />               |
| 3        | MG996R Servo Motor                 |    <img width="937" height="701" alt="servo (1)" src="https://github.com/user-attachments/assets/9a1a193a-4572-4500-813d-b1486879f261" />               |
| 4        | Wheel                              |  <img width="806" height="703" alt="wheel (1)" src="https://github.com/user-attachments/assets/c736eb16-e9f8-48ec-a8c5-5042ca222978" />                 |
| -        | Chassis & Frame                    |    <img width="441" height="444" alt="chassis (1)" src="https://github.com/user-attachments/assets/a787c292-1231-48c7-baef-4517d9035389" />             |
| -        | Accessories                        |   <img width="840" height="701" alt="ac (1)" src="https://github.com/user-attachments/assets/ad59e822-d77c-46df-a5cf-d1c246a00b61" />                   |                               
