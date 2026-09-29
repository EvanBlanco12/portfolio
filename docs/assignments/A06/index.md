# A6 – [Bracket Drawing]

## Objective
The goal of this assignment was to create a CAD model and engineering drawing based on the bracket designed in A5. Since all dimensions needed to be parametric, I began by setting up the equations that would control the model. Below are sketches I made that show the bracket design and its dimensions used for the stiffness and stress analyses.
<img width="565" height="767" alt="image" src="https://github.com/user-attachments/assets/06467250-ba93-4539-abf1-09504b96aaf4" />


## Parametric Design 
<img width="515" height="382" alt="image" src="https://github.com/user-attachments/assets/ff0a9a4e-9778-41c0-9e78-81f4e6f20a67" />
The motor mount was modeled parametrically in Creo using the dimensions determined from the previous strength and stiffness calculations. Each important dimension was added as its own parameter so that the model can be easily changed without manually rebuilding the geometry. Parameters were created for the feature lengths, widths, and thicknesses, as well as the motor shaft hole, wall mounting holes, and hole spacing. For example, Feature 1 used a thickness of 9 mm and Feature 2 used a thickness of 10 mm based on the previous design calculations. By connecting these values to the CAD dimensions, any change made to a parameter will automatically update the corresponding feature in the model.

<img width="581" height="523" alt="image" src="https://github.com/user-attachments/assets/df791061-3fe6-4972-9153-04a0003ac2f8" />
<img width="618" height="561" alt="image" src="https://github.com/user-attachments/assets/7eae0965-b922-4c0c-937a-fa3dd6160e32" />
<img width="647" height="537" alt="image" src="https://github.com/user-attachments/assets/8fd47d16-d32c-455b-9a9f-4babbe595c39" />
<img width="562" height="517" alt="image" src="https://github.com/user-attachments/assets/11330430-62e5-4610-87c7-0c0c6c962bff" />



## Drawing 


## Reflection 
A.
One lesson I learned from this assignment was how to connect engineering calculations to a parametric CAD model. For Feature 2, I used the cantilever beam deflection equation, (\delta = \frac(PL^3)(3EI)), to determine the required thickness. The calculation gave about 9.55 mm, so I used a final thickness of 10 mm. In Creo, I created the parameter FEATURE2_THICKNESS and tied it to that feature so the model could update when the parameter changed.

B.
I also learned that tolerances should depend on the function of each feature. For a functional feature like the motor shaft hole, I used a tighter tolerance such as X.XXX ± 0.005 in because the fit and alignment are important. For a non-critical feature like the overall plate length, I used a looser tolerance such as X.X ± 0.02 in because small changes would not affect the design. Using very tight tolerances on every feature would increase manufacturing cost and make the part harder to produce.


## Communicate/Lesson Learned
This assignment helped me relearn the difference between first and third angle projections and how to properly set up an engineering drawing. I also learned more about using parameters and equations in Creo to make a model easier to modify. Creating the drawing helped me improve at placing dimensions, setting tolerances, creating different views, and editing the title block. I also learned how important it is to keep parameter names and dimensions organized throughout the modeling process. Overall, this assignment helped me become more comfortable with Creo and improved my CAD and engineering drawing skills.

This assignment took me 5 hours
