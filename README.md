A 1D pouch cell method was implemented to optimize diffusion and electrochemical reactions to enhance Solid Electrolyte Interface (SEI) process for Li-ion batteries. This is done by coding the aforementioned model and dynamically varying the input paramaters to derive substantial output results such as substrate concentration on the electrodes, flux of the electric field and ion migration kinetics. The mechanical side effects such as concentration overpotential, activation overpotential and ohmic overpotential aren't considered as they adversely affect the saturation and inhibition constants. 


The idea of a gradual decrease in the porosity of the negatively charged electrode due to the formation of a passivation layer of the ions present in the electrolyte is considered by taking the Bruggeman coefficient so as to correlate the volume fractions with the capacity-defade mechanism.


Mohtat2020, Ai2020 and SPM are used in tandem wherein the test configuration of the degradation mode decides the implication of one of these chemistry parameters for 'electrochemical reaction limited SEI process', 'side reactions limited SEI process', 'solvent diffusion limited SEI process', 'electron-migration limited SEI process' or 'interstitial-diffusion limited SEI process'.


Discretizing a 1D pouch cell model involves dividing the spatial domain into discrete elements or nodes and discretizing the differential equations governing the system. In PyBaMM, this involves creating a mesh, defining spatial methods, and discretizing the model equations. This can be done by initializing boundary limits as shown in 'Test 1'.


The data used for iterating the model performance are referred from the citations mentioned.
