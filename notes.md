# NOTES

## TO-DO
- process ndep using Danica's script
- enable FSDS_diffuse vs. FSDS_direct
- inspect Danica's simulations
- practice pft-regridding

### August 17, 2021
combined all of the downloaded ndep into a single CLM-compatible file
  - copy the four dry/wet nhx/noy arrays
  - add them together and multiply by 1000 (kg->g) for the three other fields 
  - copy date/datesec from Danica's file
    - though I made all the datesecs 0
    - hers had datesec=-2147483647, from 2017 onwards?
  - created gw via cos(lat)
    - normalized to sum to 2
