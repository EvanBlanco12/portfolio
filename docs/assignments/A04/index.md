# A4 – [Motor Mount]

## Objective
For this project, a motor mount will be designed to support a Brushed 24V DC gear motor with a 99.5:1 planetary gearbox and a rating of 3.6 kg·cm/46 RPM. One edge of the mount will be secured to a rigid wall. The mount must be designed in two stages while meeting the required maximum deflection of about 0.3 mm and preventing the stress in either feature from exceeding the selected material's yield strength. The first figure contains the dimensions needed to model the motor, and the second figure illustrates the location and direction of the applied load of P = 300 N. These figures provide the main information needed to complete the motor mount design.

<img width="532" height="220" alt="image" src="https://github.com/user-attachments/assets/70438722-44eb-4470-be15-fff252e64a2c" />

## Feature 1:
<img width="432" height="581" alt="image" src="https://github.com/user-attachments/assets/85c0ea01-6a6e-4e9d-953a-8446821a819f" />
<img width="461" height="545" alt="image" src="https://github.com/user-attachments/assets/27dc37ec-413a-4919-945e-e3f61d419031" />

For Feature 1, I treated the motor mount as a cantilever beam and analyzed it using both bending stress and deflection equations. I used the applied 300 N load along with the dimensions and material properties of aluminum to determine the required cross-sectional geometry. After solving for the minimum thickness based on both requirements, I found that deflection controlled the design. The calculated minimum thickness was 8.34 mm, so I rounded up and selected a 9 mm thickness to ensure the feature meets both the stress and deflection requirements.


## Feature 2
<img width="446" height="598" alt="image" src="https://github.com/user-attachments/assets/4d25523b-11c7-4b69-9174-1280a662ed14" />
<img width="407" height="606" alt="image" src="https://github.com/user-attachments/assets/8bceed25-4574-4540-92db-2db3c79c01a6" />

For the second feature, I analyzed the vertical section that connects the motor mount to the rigid wall. The load from Feature 1 transfers a 30,000 N·mm moment into this section. I used the bending stress and beam deflection equations with the properties of aluminum to find the required thickness. The minimum thickness was 3.61 mm based on stress and 9.55 mm based on deflection. Therefore, I rounded up and used a 10 mm thickness for the final design.

## Part 3- Isometric View of Motor Mount
<img width="469" height="574" alt="image" src="https://github.com/user-attachments/assets/883d285c-1a82-4335-ac0b-076fb1b9662a" />

The image shows the final isometric design of the motor mount using the dimensions determined from the previous calculations. Feature 1 is the horizontal plate where the motor will be mounted and has a thickness of 9 mm. Feature 2 is the vertical plate that attaches the mount to the rigid wall and has a thickness of 10 mm. Both features are 100 mm wide and use 6061-T6 aluminum. The sketch also shows the motor mounting area, shaft opening, and four bolt holes used to secure the mount to the wall.

## CAD Model
Isometric View of my Motor Mount
<img width="808" height="755" alt="image" src="https://github.com/user-attachments/assets/77cf0ee5-7bd6-411e-8d8a-f0621b7022cb" />

Here are the steps of me making the Motor Mount in CAD:

<img width="245" height="274" alt="image" src="https://github.com/user-attachments/assets/dce34f2a-9c34-4f64-880f-90139f3d34c0" />

## Lessons Learned
This assignment taught me more about the process of designing a component to withstand a specific load. I learned how the size and shape of the motor mount influence both the stress and the amount of deflection. I also gained a better understanding of why checking the results against the material's yield strength is important for creating a safe design.

## Communicate
This assignment took me 6 hours
CAD Files:
https://drive.google.com/file/d/1v5PITs8Axd559LbcoZLZKvV0E4jeKU80/view?usp=sharing

