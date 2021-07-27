# Information on forcing data

## Data as downloaded
All of these data are available in /glade/u/home/djk2120/ctsm_trendy_2021/data
1. CO2
   - global_co2_ann_1700_2020.txt, annual CO2
   - global_co2_mon_GCP2021.txt, monthly CO2
   - seems like we can use whichever is easier to implement
2. Meteorological forcing, 0.5 degree CRU-JRA55 6-hourly historical forcing over 1901-2020
   - dlwrf
   - pre
       - note that precip is in units of mm/6h
   - pres
   - spfh
   - tmax
       - do we need this?
   - tmin
       - do we need this?
   - tmp
   - ugrd
   - vgrd
   - fd
       - note that they would like us to use their diffuse fraction
   - tswrf
3. LULCC
   - states.nc
   - transitions.nc
   - management.nc
4. ndep, using ours instead
5. population density, using ours instead