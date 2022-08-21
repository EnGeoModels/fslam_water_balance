# fslam_water_balance
Hydrological water balance model to compute effective recharge

# Three-layers hydrological model
The hydrological model that will be described here is a continuous model (long-term) at daily time step but is not designed to simulate detailed single-event flood routing. Originally, it was developed by UPC and called ‘Easy Bal’ model (https://h2ogeo.upc.edu/es/software-hidrologia-subterrania/11-software-hidrologia subterrania/43-easy-bal). Original hydrological model only included two layers to represent the catchment soil: the root zone and the saturated zone (aquifer). This document will introduce a modified version of the model which includes three layers (see Figure 1). The new model is designed to evaluate water balance per unit of soil area as a function of precipitation, the potential evapotranspiration (or ETP), temperature and irrigation. It represents physically the root zone (Layer 1), unsaturated soil (Layer 2) and saturated soil (Layer 3). 
