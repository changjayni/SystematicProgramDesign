# SystematicProgramDesign
Final Project for "Introduction to Systematic Program Design" course

This program reads:
- Time (ISO 8601 format, e.g. 0:00:00)
- Measured fluorescence values for each experimental condition
  (WCS365-mTq bacteria grown with WCS365 or N2C3 bacteria)
    
Does not read:
- Temperature values
- The first header, which indicates the bacteria's nutrient source (LB media)
- The second header, which indicates the experimental condition for each measured fluorescence value
- The third header, which describes the values in each column (e.g. time, temperature)

Produces line charts for each condition (2 in total) with:
- Measured fluorescence of WCS365-mTq on the y axis versus time on the x axis.
- Optical density of WCS365-mTq on the y axis versus time on the x axis.
- Optical density of WCS365-mTq (log) on the y axis versus time on the x axis (growth curve)
