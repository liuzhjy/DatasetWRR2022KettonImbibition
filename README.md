# DatasetWRR2022KettonImbibition
Two-phase fluid distribution data for the imbibition in Ketton rock at different injection flow rates.

## Description
Forced imbibition in porous media under a fully wetting condition has complex interfacial dynamics due to the influence of additional meniscus such as corner flow. These data, i.e., the phase field distribution obtained by using a color lattice Boltzmann model, demonstrate the fluid distribution within the pore space of Ketton rock at different injection flow rates. Through the visual presentation of these data, pore filling dynamics and displacement patterns under different injection and exploitation conditions can be examined visually.

## Datasets
These data are the results of pore-scale simulations of forced imbibition under different flow conditions based on the Ketton digital rock model. In the simulation, the color lattice Boltzmann model is used and numerical calculations are carried out by the open-source LBPM software package (https://github.com/OPM/LBPM). The different injection conditions are characterized by the capillary number Ca calculated based on the pore-scale average flow rate. 
These data can be visualized and dynamically displayed through ParaView software (https://www.paraview.org) and can be further post-processed for analysis. The ".vtk" file in the zip data contains a total of three phases, 0 for the solid phase, -1 for the non-wetting fluid, and 1 for the wetting fluid. Detailed parameters, imbibition simulation settings and the results analysis for these data can be found in “Systematic investigation of corner flow impact in forced imbibition”.

