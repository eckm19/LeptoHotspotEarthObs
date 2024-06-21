Data was used for the study "Unveiling Leptospirosis Hotspots with Earth Observation and AI". 

The study embarks on the spatiotemporal analysis of leptospirosis hotspot areas in Selangor using secondary data from 2011 to 2019.
Point shape files were plotted based on the coordinates of case's possible source of infection.
Cases were aggregated according to respective subdistrict polygon areas. Monthly Hotspot analysis was initially conducted using the Getis Ord Gi* in ArcGIS Pro software.
Satellite data for monthly rainfall and LST was retrieved from the NASA Geovanni EarthData website. Monthly values (2-11-2019) for every subdistrict were extracted using ArcGIS Pro software. 

Data contains monthly data for 55 subdistricts in Selangor (not individually labelled) from 2011 to 2019 - (5 columns and 5940 rows)
1. leptospirosis hotspot (H) (Yes[1] or No[0].
2. Precipitation (P) - monthly values in millimetres
3. Land Surface Temperature (T) - monthly values in degrees Celsius (oC)

The code snippets used for machine learning data analysis are also available. Codes include three algorithms used:
1.  LGBM, 2. Random Forest, and 3. SVM
