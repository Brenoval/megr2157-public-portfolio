# A3 – [Topic]

## Objective

In this assignment, students are tasked to design a bar with a circular cross-section made out of aluminum of arbitrary area which will undergo an arbitrary force. During the creation of this beam, the length will be determined by Hooke's Law both parametrically and through FEA analysis on a CAD software. After the solution has been determined and the models created, both the parametric and simulation results are to be compared and a conclusion drawn.

## Analyze

For the design of the beam with a circular cross-section, the constraints are as follow: elongation is limited to .009in, force is to be between 300 and 500 lbf, and the material will be aluminum with a modulus of elasticity between 8.5 to 11.5 x 10^6 psi. The area for the beam will be decided by the student and, as a result, will complete the equation to determine a parametric length for the beam. 

## Decide

For my design, I started by inputting the delta value as .009, followed by determining the force as the maximum allowed value of 500 lbf as a way of solving for the maximum expected force that could be applied on the beam. I then determined the radius of my cross-section to measure 0.5in to create an area equal to pi(r^2) = 0.25pi in. The aluminum alloy I chose to use has a modulus of elasticity equal to about 10 x 10^6 psi. After determining all the parameters, I input the equation L = (A*E*delta)/F to parametrically determine the length of my beam and model it in the software. Below will be images showing the parameters and equations in the software as well as the original model in 3d form with the material selected.

After parametrically determining the length of the beam and assigning a material, I created a study of my design to use FEA analysis built into the software to generate simulated values for deflection, strain, and to generate a Von Mises stress map. This was accomplished by fixing one end of the beam in Solidworks and then creating a mesh along the entire length of the beam. After the software was able to generate the mesh, I assigned an outward force along the longitudinal axis of the beam equal to the 500lbf determined earlier in the project. Images of the following will be pictured below.

After all the constraints and forces had been applied to the meshed beam, I ran the simulation in Solidworks to generate displacement, stress, and strain graphs, all which will be pictured as follows:

The graphs pictured above were all modeled with the aluminum's Young modulus that Solidworks has on file for that specific alloy of aluminum. 

## Communicate

