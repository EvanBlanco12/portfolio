# A7 – [FEA on Bracket]

## Objective
For this assignment, we used FEA to test and optimize the bracket we created in Assignments 5 and 6. We wanted to make sure our mesh was accurate by achieving a 7% convergence for maximum stress, maximum deflection, and minimum factor of safety. We compared the results from different mesh sizes to check for consistency. I also created an Excel spreadsheet to calculate the percentage differences, which will be shown and linked at the end of the assignment.

## Design #1
To begin the FEA analysis, I first determined the loading conditions and chose the mesh settings for the bracket. Once everything was set up, I completed three simulations using different mesh sizes to compare the results. Each test provided information on the highest stress, greatest displacement, and lowest factor of safety. This helped me see how changing the mesh affected the accuracy and consistency of the results. The table below shows the data collected from the original bracket, along with the percentage differences between the simulations.

FEA Inner Loop	FEA 1 (Coarse)	FEA 2 (Default)	FEA 3 (Fine)	% Error
Max stress (psi)	14720	20950	22700	34.93131483
Location	OGcoarsestress-2.png	OGdefaultstress.png	OGfinestress.png	
Max deflection (in)	0.09	0.11	0.11	20
Location	OGcoarsedef.png	OGdefaultdef.png	OGfinedef.png	
Min. safety factor	0.73	0.51	0.47	35.48387097
Location	OGcoarseFOS.png	OGdefaultFOS.png	OGfineFOS.png	
Mass (lb)	0.34	0.34	0.34	
Mesh Elements	1655	9160	35000	






## Design #2







## Design #3






## Lesson Learned
I spent around 5 hours completing this assignment, with most of my time going toward the written portion and making my design changes more complicated than they needed to be. Through this project, I gained a better understanding of how FEA and different mesh settings can help improve a part under various loading conditions. I also saw how changing the mesh density can impact the time needed to run a simulation. Although this wasn't a major issue for my project, I can see how larger and more detailed models could take much longer to analyze. Below, I included a screenshot of my Excel sheet showing the results from each simulation and design. I also provided links to the spreadsheet and all three CAD models.

## Communicate


