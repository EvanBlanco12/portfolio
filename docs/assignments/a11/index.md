# A11 – Motor Selection
Evan Blanco, Grady Stallings, Jake Umebayashi 

## Introduction 
<img width="506" height="428" alt="image" src="https://github.com/user-attachments/assets/4c77d08e-f0c3-4d3e-b124-096ee5094bc2" />

## Motor Selection and Attachments (Evan)
<img width="463" height="622" alt="image" src="https://github.com/user-attachments/assets/6067bce4-1af1-4168-96f3-88874bab40f9" />


<img width="460" height="610" alt="image" src="https://github.com/user-attachments/assets/735a23c7-2b30-4862-866f-c6e7c6a877cc" />

<img width="461" height="614" alt="image" src="https://github.com/user-attachments/assets/0cf3af48-6d82-4143-a31f-24ddf37f0732" />

<img width="461" height="610" alt="image" src="https://github.com/user-attachments/assets/925a8b0e-98bf-4cf6-a260-28d88b175fdb" />

## Motor Mount Design (Jake)
https://www.mcmaster.com/91280A246/
M5 bolt
<img width="469" height="431" alt="image" src="https://github.com/user-attachments/assets/35df264e-3ebb-4b14-8cf2-1810b5a7e0ff" />

MMP D22-490D-24V Midwest Motion Products | Motors - AC, DC | DigiKey Marketplace 

## Analyze and design a Frame (Jake)
<img width="463" height="338" alt="image" src="https://github.com/user-attachments/assets/c53e8d3e-be53-46f9-8b83-76c3ffac0838" />
<img width="260" height="400" alt="image" src="https://github.com/user-attachments/assets/ef7a57a5-5a83-4984-acfc-c403a0371e8f" />
<img width="448" height="668" alt="image" src="https://github.com/user-attachments/assets/a6f4475b-3a9f-41fe-a417-362cf9727f4e" />
<img width="311" height="536" alt="image" src="https://github.com/user-attachments/assets/0c5d3abb-87c5-4967-b901-6da89e6e197a" />


These are photos from the FEA I tried. I’m not sure why this FEA kept failing, but I tried for a decent amount of time before giving up. I truly don’t understand why this analysis wouldn’t converge and give a result unfortunately. 


<img width="328" height="413" alt="image" src="https://github.com/user-attachments/assets/c00ed852-0775-448c-a7ee-d66dcbd1da2a" />
To prevent twisting and joint slip at the vertical standoffs, we used two 4-hole gusseted corner brackets (McMaster-Carr #6812N831) per corner (one on the inner/underside corner and one on the side/back face, providing 4 M8 bolts per rail connection, spaced 40 mm apart


##  Constraints Boundary Conditions: (Grady)

Standoff Interfaces: x=0 and x=400mm. Apply Fixed Geometry on the bottom and side T-slot bearing faces where the McMaster-Carr #6812N831 corner gusset brackets clamp the top rail to the vertical standoffs spanning 0 to 400mm from each end.
Motor Bracket Interface: x=100mm and x=300mm. Rigid / Bonded Contact between the 6061-T6 motor mounting brackets and the top/front T-slot faces of the rail, with bolt connectors at the four M6 mounting holes per bracket.
Applied Loads: at  x=100mm and x=300mm
Lead Screw Axial Tension Path: Apply Fy at -1000N (downward) at each of the two thrust-bearing / lead screw centerline locations offset e=60mm from the rail neutral axis, transmitted Remote Load / Rigid Coupling to the motor/thrust bracket mounting pads.

## Meshing & Mesh Convergence Verification
<img width="459" height="89" alt="image" src="https://github.com/user-attachments/assets/6763343f-e985-4904-b5a4-848a6d2f3eb3" />

<img width="298" height="170" alt="image" src="https://github.com/user-attachments/assets/420b8279-062f-4b53-9d86-4da235868a1c" />



Motor Reaction Moments: Apply two moments of Tm = 5.39N.

## 5d. Optimization Pass (Grady)
Proposed Targeted Design Changes:
Top Cross-Rail = Heavy 40×80 Extrusion (McMaster-Carr #5537T103 / 80/20 #40-4080) oriented vertically(80mm height): Increases vertical area moment of inertia and torsional rigidity by 3.4x while using the exact same 40 Series connectors.
Add T-Slot Backing Plates (Drop-In Flat Bar T-Nuts) & Increase Motor Bracket Base Pad: Replace individual M6 T-nuts with a continuous 6mm thick steel T-slot backing strip inside the slot and widen the motor bracket base flange corner fillets to distribute clamping pressure across both T-slots of the 40×80 profile.
Pocket Non-Critical Web Material on Motor Bracket: Adds a weight-reduction pocket in the low-stress central gusset region of the 8 mm motor bracket to offset the added mass of the taller 40×80 top rail.
Shift in Critical Stress Locations & Improved Metrics:
Stress Reduction & Location Shift: Maximum von Mises stress drops The peak stress location shifts away from the open T-slot lip fillet (eliminating slot lip flaring) to the root of the corner gusset bracket bolt flange. which is a much safer, ductile bearing zone.
Deflection Reduction: Maximum vertical deflection at the grip line drops by 78%,virtually eliminating angular misalignment on the lead screws.

<img width="458" height="611" alt="image" src="https://github.com/user-attachments/assets/50965b9b-df92-4e21-81b6-ca27f7940aae" />

<img width="458" height="595" alt="image" src="https://github.com/user-attachments/assets/6b03ebf8-88d6-49e2-ab0e-ffe90bd0ab72" />

## Design Floating Bearing Mount (Jake)
<img width="344" height="467" alt="image" src="https://github.com/user-attachments/assets/87609ce2-f5eb-48bf-afdf-d854602dfaa0" />
<img width="262" height="329" alt="image" src="https://github.com/user-attachments/assets/c403f163-8db3-4354-b397-5e6fbf89d834" />


## Bill of Materials and Labor Costs (Grady)
<img width="482" height="261" alt="image" src="https://github.com/user-attachments/assets/5f694fb7-5d4d-4929-aef5-13ac9c89d880" />

3 Hours Each Student = 10*35=$350
Total cost = $423.53
Total Cost A10= $345.42

Total Cost All = $768.95

##  Lessons Learned 

This project taught me the importance of being accurate and taking my time when working with different parts. I learned that proper planning can prevent mistakes and make the assembly process easier. Overall, I gained more experience with design and solving problems that came up along the way. 

Time spent on this assignment: 10

Appendix

Assembly Link: https://drive.google.com/file/d/1YFY-PD2WgQZkguM8FMqARV9GhuWzAYsH/view?usp=sharing

Bearing: https://drive.google.com/file/d/17EzgKZkyo69Kd_8aF3KUpcEzWTA8MABL/view?usp=sharing

Motor Mount: https://drive.google.com/file/d/1d6m_rzQQj5zF8i9rKwGXnT2ZVXiw65Nv/view?usp=sharing





