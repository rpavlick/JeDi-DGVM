JeDi
====

Input files

paw.srv
- unit plant available water (mm water per mm soil)
- calculated following Kleidon and Heimann 2000, Batjes 1996

landsea.srv
- land mask (1=land/0=ocean/glacier)

tas.srv
- 2m air temperature
- Kelvin

rlns.srv
- net longwave radiation at the surface
- W/m^2
 
rsds.srv
- downward shortwave radiation at the surface
- W/m^2

pr.srv
- daily total precipitation
- kg/m^2/s

jedi_specparm.txt
- pseudorandom trait values generated by create_jedi_specparm


Postprocessing

jedi_partab
landsea.nc
landfraction.nc
