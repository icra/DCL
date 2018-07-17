# DCL

Results of DCL (diclofenac) concentrations calculated using a Contaminant Fate Model. 
The results are in raster (.tif) format and cover the world.
Rasters use geographic coordinate system WGS84 with resolution of 1/16 deg (δ); the extreme positions x_0=-180 (western cell position) and y_0=-56 (southern cell position); the extension nr=2240 (number of rows) and nc=5760 (number of columns).

For any question, please contact vacuna@icra.cat or rmarce@icra.cat. Please refer our article: <br />
Acuña V., Bregoli F., Font C., Barceló D., Corominas L., Ginebreda A., Petrovic M., Rodríguez-Roda I., Sabater S., Marcé R. *Mitigating pharmaceuticals impact on global freshwaters: upstream or end-of-pipe solutions?* (in course)

- Actual:<br />
contaminant_C_actual_mask.tif<br />
Simulated mean annual diclofenac accumulated concentration under actual conditions.

- BAU:<br />
contaminant_C_BAU_mask.tif<br />
Simulated mean annual diclofenac accumulated concentration under future (2030) conditions.<br />
Using: estimated populatio; Runoff under Climate Change conditions; predicted sanitation treatments (under business as usual tendency).

- SDG6:<br />
contaminant_C_SDG6_mask.tif<br />
Simulated mean annual diclofenac accumulated concentration under future (2030) conditions, using sanitation improvement with the implementation of the United Nations Sustainable Development Goal 6 (SDG6).<br />

- SDG6_BAU:<br />
contaminant_C_SDG6_BAU_mask.tif<br />
Simulated mean annual diclofenac accumulated concentration under future (2030) conditions, taking sanitation improvement as the maximum between business as usual and SDG6 for each country.<br />

- Swiss:<br />
contaminant_C_swiss_mask.tif<br />
Simulated mean annual diclofenac accumulated concentration under future (2030) conditions, using WWTP efficiency in DCL removal from the Swiss national strategy at global scale.<br />

- Consum:<br />
contaminant_C_consum_mask.tif<br />
Simulated mean annual diclofenac accumulated concentration under future (2030) conditions, considering a 10% reduction of the per capita consumption for each country.<br />

- All:<br />
contaminant_C_consum_swiss_SDG6_BAU_mask.tif<br />
Simulated mean annual diclofenac accumulated concentration under future (2030) conditions, using all the above mentioned mitigation strategies (SDG6 sanitation, Swiss standard treatment and consumption reduction). <br />



