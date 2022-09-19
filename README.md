# SVR-to-predict-percentage-favourability-of-materials
The code is a subpart of my academic project "AI for Accelerated Discovery of fuel cell materials". 
The objective of the project was to develop a ML code to obtain a new electrocatalyst for the anode in Proton Exchange Membrane fuel cell from a set of 
potential electrocatalysts. 
The project involves a dataset of materials manually prepared from OQMD, materialsproject.org and some other open-source databses. The key idea based based on the limited 
data of the novel materials was with the assumption that the material with highest electrical conductivity should have the highest pecentage favourability. 
The materials are ranked on the basis of their Eg, Kl and volumetric density values, and their dependence on electrical conductivity. 
The model was trained with support vector regression (SVR) model.
