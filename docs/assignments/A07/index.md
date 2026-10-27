# A7 – FEA Bracket Design

## Objective
Students are tasked with using their original bracket design from A5 and A6 to perform a Finite Element Analysis on all the elements of said bracket to test for convergence of the stresses, strain, and displacements, as well as making calculated revisions to their design based on safety factors and concentration of forces. A final revised product is to be achieved with higher strength and stiffness, as well as lower material usage.

## Analyze
Based on my initial A6 design, I decided to run a study in SOLIDWORKS using a relatively coarse mesh to provide a baseline overview of the stresses and strains my bracket would be under. This was achieved by first applying a downward force on the section of the bracket that receives the 1200lbs from a rope and fixing the T-section of the bracket to restrict movement since it will be consistently resting on the protrusion. The results are the following:
<img width="1919" height="1079" alt="Screenshot 2026-10-26 111539" src="https://github.com/user-attachments/assets/31f690a6-aa22-4dc3-a73a-7cad12a6937a" />

I then ran the simulation twice more with a finer mesh both times to create a more accurate analysis of the high stress points on my bracket, as well as the overdesigned features I may have. The results achieved the following:
<img width="1919" height="1079" alt="Screenshot 2026-10-26 111714" src="https://github.com/user-attachments/assets/67731823-433a-4b9b-8308-886d50df38dd" />
<img width="1919" height="1079" alt="Screenshot 2026-10-26 112153" src="https://github.com/user-attachments/assets/9cd2bc32-4932-4d3b-a29c-dfd4ee77c063" />

## Decide
Based on the above analysis, my first step in redesign was to strengthen the cylinder that receives the load to reduce the deflection it would face under the tensile force. This was achieved by adding a second identical support from bracket to cylinder to fix said cylinder at both sides and more evenly distribute the forces it would carry. I then ran a new study that presented the finding as such:
<img width="1919" height="1079" alt="Screenshot 2026-10-26 113355" src="https://github.com/user-attachments/assets/5dcd386a-b26d-419d-a0e0-461b1759d5be" />

After the above analysis, I shifted my focus to reducing the amount of material present in the bracket itself. I achieved this by removing a significant amount of material from the sides of the bracket since they would not see as strong a force and the cylinder below. An analysis of such is presented as follows:
<img width="1919" height="1079" alt="Screenshot 2026-10-26 113726" src="https://github.com/user-attachments/assets/fc5e52e6-5aea-44f7-ac40-0fd3303b9f26" />

Upon reviewing the analysis of my second geometrical change, I realized there were still many sections on the top and bottom of the fixed portions of the bracket that were not under significant stress, so I decided to remove material from their centers as well while maintaining a sizeable edge for structural integrity. This change concluded my outer loop redesign phase and presented the following analysis:
<img width="1919" height="1079" alt="Screenshot 2026-10-26 114346" src="https://github.com/user-attachments/assets/b7c9512d-7130-47f3-b95b-7c8e407da94d" />

## Communicate
During this assignment, I was made aware of how initial designs can be reworked and redesigned in such a way that one can achieve cost effectiveness with the material of choice simply by analyzing the concentration of stresses using FEA analysis. I have also learned how to strengthen and optimize a design using the same analysis of stresses and strains to reduce the possibility of failure in a design of choice for its given application. Furthermore, I have had the doors opened to further applications of FEA that could result to be beneficial in future designs that may result from a career in mechanical engineering, and how the application of such analysis could help any given company reduce costs and increase efficiency before creating or prototyping a design.

The link for the SOLIDWORKS file where all the redesigns and studies were performed will be linked below:
https://drive.google.com/file/d/1U-vsy_4pf8Ck2Z0wWW1bpe1AkSLyHi_S/view?usp=sharing 
