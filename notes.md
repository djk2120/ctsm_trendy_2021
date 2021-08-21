# NOTES

## TO-DO
- process ndep using Danica's script
- enable FSDS_diffuse vs. FSDS_direct
- inspect Danica's simulations
- practice pft-regridding


### August 21, 2021
set up AD spin from coldstart
  - Erik provided the fsurdat and landuse timeseries
  - Sean provided the forcing data
  - res = hcru_hcru
  - 

Danica's simulations
  - /glade/u/home/dll/TRENDY2020Simulations
  - /glade/u/home/dll/TRENDY2019Simulations

Actual commands:




### August 17, 2021
combined all of the downloaded ndep into a single CLM-compatible file, via trendy_2021.ipynb
  - copy the four dry/wet nhx/noy arrays
  - add them together and multiply by 1000 (kg->g) for the three other fields 
  - copy date/datesec from Danica's file
    - though I made all the datesecs 0
    - hers had datesec=-2147483647, from 2017 onwards?
  - created gw via cos(lat)
    - normalized to sum to 2
