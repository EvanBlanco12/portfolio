
# A3 – Parametric and FEA

## Objective
This assignment is about designing a bar that is strong and stiff enough to handle an axial load. Parametric modeling and finite element analysis (FEA) are used to see how the force, size, and material of the bar affect how much it bends or stretches. The results are then used to create and test a suitable bar design.

## Analyze
Creo Parameters

I created parameters for the force, Young’s Modulus, maximum deflection, and diameter. These values control the dimensions of the bar.

Creo Relations

I used relations in Creo to connect the parameters together using the axial deflection equation. This allows Creo to automatically calculate the required length of the bar.

Final CAD Model

After applying the parameters and relations, Creo generated the final bar with a 0.25 in diameter and a length of approximately 11.04 in.

<img width="1577" height="635" alt="assignment 3#3" src="https://github.com/user-attachments/assets/06e5f2c9-3326-495f-99c7-30c30a2729cf" />
<img width="1600" height="637" alt="assignment 3#2" src="https://github.com/user-attachments/assets/a6faea81-2a42-40ae-9cd1-70a6d988ef06" />
<img width="1263" height="204" alt="assignment 3" src="https://github.com/user-attachments/assets/036303a0-49c5-4ac2-b49a-b34920912cad" />


## Calculations
<img width="592" height="761" alt="assignment 3#4" src="https://github.com/user-attachments/assets/8d45a97a-ebcb-4573-b004-ff95ee84c072" />


## Design Reflection/Pin-hole stress concentration
<img width="588" height="742" alt="assignment 3#5" src="https://github.com/user-attachments/assets/bd2f14db-fc4c-4291-a424-c244c59ba844" />

The estimated peak stress at the pinhole is still below the aluminum yield strength of 40 ksi. Therefore, the bar with the pinhole would still pass the required safety requirement.

## FEA
<img width="2048" height="1115" alt="c670c2fd-7260-4de9-a74d-cbcb474ea4c8" src="https://github.com/user-attachments/assets/1f4717af-5b3b-4e69-9d2b-96f2aa7914ba" />
The bar was analyzed using a 400 lbf axial load. The maximum stress was approximately 8.15 ksi, which is below the aluminum yield strength of 40 ksi, giving a safety factor of approximately 4.91; therefore, the bar passes the strength requirement.

## FEA Deflection Map
<img width="1916" height="733" alt="image" src="https://github.com/user-attachments/assets/a9ffec63-8886-437c-bc7b-04aea6b60ca4" />


he deflection map shows the displacement of the bar under the applied load. The maximum deflection occurs near the free end of the bar, while the minimum deflection occurs at the fixed end.

## Communicate
Final reflect
This project took approximately 4 hours to complete

## Lesson Learn
This assignment helped me better understand how hand calculations and FEA can be used together to analyze a part. I learned how to generate and interpret both a Von Mises stress map and a deflection map in Creo. I also learned that even when the nominal stress of a part is low, features such as holes can create stress concentrations that increase the maximum stress in that area. Comparing my hand calculations with the FEA results also showed me how assumptions, boundary conditions, and the way loads are applied can affect the final results.

Creo links
Model 1:
[Assignment A3 - Copy.pdf](https://github.com/user-attachments/files/31937338/Assignment.A3.-.Copy.pdf)





