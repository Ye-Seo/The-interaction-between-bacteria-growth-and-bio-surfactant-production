# The-interaction-between-bacteria-growth-and-bio-surfactant-production

#Overiview#

My research about PhD is about bacterial studies in Niepa's group of UPitt and my previous thinking about bacteria was negative before doing research.
Most bacteria affect negatively like biofilm in the drain or pipe, infection to the human organs or contamination of environments.
But I have found that bacteria can be utilized for myriads purposes by deriving their bioproducts and applying them to the desired things effectively.
Bacteria can produce biosurfactant, gas, or organic solvents and among them, biosurfactant can enhance oil recovery by reducing the interfacial tension of oil and water.
It was very interesting to me that bacteria can be also useful and I chose this topic about interaction with bacteria growth and biosurfactants production.

#Research#
This research is about investigating microbial enhanced oil recovery from biosurfactant of Clostidium sp.
Biosurfactant producing Bacteria Growth (BBG) model was adressed to minimize the parameters and relating to the interfacial tension models.
The experimental data of which bacteria growth and biosurfactant production veresus time could be fitted to the BBG models.
And they set the parameters of bacteria dependent on time and optimize the equation by finding out SRSS error and could minimize the parametersn resulting the most reduced errors from the therotical models. 
Additionally, they linked it to the interfacial tension model to see how biosurfactants can recover oil with reduced interfacial tension.


BBG models can be expressed like this;
   1) Bacteria Growth:  dP/dt = 𝜇1*P −  𝜇1/𝐾0*P^2  − 𝛾*P*S
   2) Surfactant Production:  dS/dt = 𝜇2*P− 𝛿*P*S


#Results#
Fisrt of all, I choose the parameter K0 which is carrying capacity and this is in the denomination of the coeffcient in the second term.
The second term means the inter bacteria competition so when K0 goes infintie which means the active competiton of bacteria for nutrients.
And the interaction between bacteria will be zero, and there will be no disturbtion of bacteria growth.
But when K0 goes zero, there will be negative infinity in bacteria growth which can be problematic.

But there was no 𝐾0 in the surfactant production equation, I choose another parameter on the surfactant production equation.
When analyzing bifurcation about bacteria growth P assuming other biosurfactant production S is 1, 
unstable steady state with (0,0) at 𝐾0= 0.5 is found but stable steady state was additionally found at 𝐾0=5.
And it can be seen that the steady state at K0=5 got more stable steady state.


And I choose the predation factor which bacteria consume biosurfacnt which can be seen in the bacteria and surfactant interaction term.
But when the values of predation factor, 𝛿 were alterted, it was same in the stable steady state at (0,0).

From Flow on a line, the moderate carrying capacity for bacteria growth and the small predation factor had more stable steady state.
It can be explained that carrying capaciy should be not too small or big to save the interbacteria interaction and the predation of bacteria should be small to produce the biosurfactant.

From 2d phase portrait, the data was limited with small size.
The steady state can be seen at (0,0) but biosurfactant production rate seemed most steady state.
The vectors are repelled from the steady state, which can be seen unsteady state.
Considering the eigenvalue and eigenvector, thery are all positive real part without imaginary part, resulting in unstable steady state.

When analyzing the parameter sensitivity for bacteria growth, 𝜇1>𝐾0>𝛿 was most sensitive when measured at 0.15 pertubation.
and for biosurfactant production, 𝜇2>𝐾0>𝜇1 was most sensitive when measured at 0.15 pertubation.
It could be justified that 𝜇1 was bacteria growth rate, and 𝜇2 is biosurfactant production rate so they are most sensitive.
𝐾0 was interbacteria interaction, so resulting that there is much highly affect to bacteria growth and biosurfactant production.

In initial parameter sensitivity, they were same but predator factor which bacteria consume biosurfactat is also essential.
There was some deviation in distribution of paramters with several random parmeters, and also there was different predicted bacteria growth and biosurfactant production when normalizing 𝐾0.

#Conclusion#
Interaction of bacteria growth and biosurfactant production was unsteady state.
Bacteria Growth had most sensitivity to 𝜇1 (bacteria growth rate) followed by 𝐾0 (carrying capacity).
Surfactant Production had most sensitivity to 𝜇2 which is biosurfactant production rate.
My expectation that 𝐾0 would be most sensitive to both bacteria and surfactant could be justified by estimation.
We can expect that bacteria growth rate can interact the oil recovery without calculating surfactant rate for simplication in the next step.

