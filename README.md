# 2023-Powdery-Mildew-Fungicide-Programs-Project

The data and codes available here accompany the paper:
Hwang et al. 2024. What explains hop growers’ fungicide use intensity and management costs in response to powdery mildew? Phytopathology  https://doi.org/10.1094/PHYTO-04-24-0127-R

The data files provided include the following variables.

### Clean Data_Random Forest_V1.csv

Year: Classification variable for year of observation, 2014 to 2017

Field_ID: A unique identifier for each hop yard within each year. 

Quadrant: A classification variable denoting which quadrant in the landscape each hop yard (Field_ID) was located within relative to the centroid of all yards. Values are SE, SW, NE, NW based

Mildew_Apr: Incidence of plants with powdery mildew in April

Mildew_May: Incidence of plants with powdery mildew in May

Mildew_Jun: Incidence of plants with powdery mildew in June

Mildew_Jul: Incidence of plants with powdery mildew in July

Mildew_Apr_Dummy: A binary variable coded as 1 or 0 to represent the presence or absence of Mildew_Apr variable

Mildew_May_Dummy: A binary variable coded as 1 or 0 to represent the presence or absence of Mildew_May variable

Mildew_Jun_Dummy: A binary variable coded as 1 or 0 to represent the presence or absence of Mildew_Jun variable

Mildew_Jul_Dummy: A binary variable coded as 1 or 0 to represent the presence or absence of Mildew_Jul variable

Mildew_Incidence: Seasonal mean incidence of plants with powdery mildew

Mildew_Incidence_Dummy: A binary variable coded as 1 or 0 to represent the presence or absence of Mildew_Incidence variable

Susceptibility_to_R6_Strains: Each cultivar an ordinal score for its susceptibility to pathogenic races of P. macularis: Vb,V3,V4,V5,V6. 

Susceptibility_to_nonR6_Strains: Each cultivar an ordinal score for its non-susceptibility to pathogenic races of P. macularis: Vb,V3,V5. 

Initial_Strain: Each hop yard was determined as being virulent or not on cultivars possessing R6. we coded the initial strain as ‘1’ if the pathogen was non-V6-virulent and ‘2’ if the pathogen was V6-virulent. If we could not obtain isolates or virulence data or when powdery mildew did not occur at any level, we coded the initial strain as ‘0’.

Pruning: Thoroughness of spring pruning rated using a 1 to 5 ordinal scale. In this ordinal scale, ‘1’ represents the most thorough pruning which removed all green leaves and stems from every plant. Each subsequent point represents an approximation of the incidence of plants with green foliage remaining such that a ‘5’ indicates that >80% of plants had green leaves and shoots remaining after pruning.

FlagShoot_Incidence: Seasonal mean incidence of bud infection which might cause shoots emerging from winter dormancy colonized by P. macularis.

FlagShoot_Incidence_Dummy: A binary variable coded as 1 or 0 to represent the presence or absence of FlagShoot_Incidence variable

Mildew Incidence_Dummy: A binary variable coded as Detected or Not Detected to represent the presence or absence of Mildew_Incidence variable for generalized propensity score
