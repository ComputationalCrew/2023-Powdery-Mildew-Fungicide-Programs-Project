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

Mildew_Apr_Dummy: A dummy variable coded as 1 or 0 to represent the presence or absence of Mildew_Apr variable

Mildew_May_Dummy: A dummy variable coded as 1 or 0 to represent the presence or absence of Mildew_May variable

Mildew_Jun_Dummy: A dummy variable coded as 1 or 0 to represent the presence or absence of Mildew_Jun variable

Mildew_Jul_Dummy: A dummy variable coded as 1 or 0 to represent the presence or absence of Mildew_Jul variable

Mildew_Incidence: Seasonal mean incidence of plants with powdery mildew

Mildew_Incidence_Dummy: A dummy variable coded as 1 or 0 to represent the presence or absence of Mildew_Incidence variable

Susceptibility_to_R6_Strains: Each cultivar an ordinal score for its susceptibility to pathogenic races of P. macularis: Vb,V3,V4,V5,V6. 

Susceptibility_to_nonR6_Strains: Each cultivar an ordinal score for its non-susceptibility to pathogenic races of P. macularis: Vb,V3,V5. 

Initial_Strain: Each hop yard was determined as being virulent or not on cultivars possessing R6. we coded the initial strain as ‘1’ if the pathogen was non-V6-virulent and ‘2’ if the pathogen was V6-virulent. If we could not obtain isolates or virulence data or when powdery mildew did not occur at any level, we coded the initial strain as ‘0’.

Pruning: Thoroughness of spring pruning rated using a 1 to 5 ordinal scale. In this ordinal scale, ‘1’ represents the most thorough pruning which removed all green leaves and stems from every plant. Each subsequent point represents an approximation of the incidence of plants with green foliage remaining such that a ‘5’ indicates that >80% of plants had green leaves and shoots remaining after pruning.

FlagShoot_Incidence: Seasonal mean incidence of bud infection which might cause shoots emerging from winter dormancy colonized by P. macularis.

FlagShoot_Incidence_Dummy: A dummy variable coded as 1 or 0 to represent the presence or absence of FlagShoot_Incidence variable.

Active_Constituents: Annual number of fungicide active constituents applied by growers in a given year.

Annual_Cost: Annual estimated cost of fungicide active constituents.

degree_centrality_R6_MayJun: Outward degree centrality calculated for monthly time transitions from May to June for each network of yards planted to cultivars that possess R6.

degree_centrality_NonR6_MayJun: Outward degree centrality calculated for monthly time transitions from May to June for each network of yards planted to cultivars that do not possess R6.

degree_centrality_R6_JunJul: Outward degree centrality calculated for monthly time transitions from June to July for each network of yards planted to cultivars that possess R6.

degree_centrality_NonR6_JunJul: Outward degree centrality calculated for monthly time transitions from June to July for each network of yards planted to cultivars that do not possess R6.

Grower_1: A dummy variable coded as 1 or 0 whether Grower 1.

Grower_2: A dummy variable coded as 1 or 0 whether Grower 2.

Grower_3: A dummy variable coded as 1 or 0 whether Grower 3.

Grower_4: A dummy variable coded as 1 or 0 whether Grower 4.

Grower_5: A dummy variable coded as 1 or 0 whether Grower 5.

Grower_6: A dummy variable coded as 1 or 0 whether Grower 6.

Grower_7: A dummy variable coded as 1 or 0 whether Grower 7.

Grower_8: A dummy variable coded as 1 or 0 whether Grower 8.

Grower_9: A dummy variable coded as 1 or 0 whether Grower 9.

YearDummy_2014: A dummy variable coded as 1 or 0 whether year 2014.

YearDummy_2015: A dummy variable coded as 1 or 0 whether year 2015.

YearDummy_2016: A dummy variable coded as 1 or 0 whether year 2016.

YearDummy_2017: A dummy variable coded as 1 or 0 whether year 2017.

NE: A dummy variable coded as 1 or 0 to represent a farm in the northeast region by definition of quadrant.

NW: A dummy variable coded as 1 or 0 to represent a farm in the northwest region by definition of quadrant.

SW: A dummy variable coded as 1 or 0 to represent a farm in the southwest region by definition of quadrant.

SE: A dummy variable coded as 1 or 0 to represent a farm in the southeast region by definition of quadrant.

Grower_Ordinal: Classification variable for grower of observation.

predictions: Predicted value for annual costs from generalized random forests.

predictions1: Predicted value for active constituents from generalized random forests.

GPS: generalized propensity score for a selected variable.

Mildew Incidence_Dummy: A dummy variable coded as Detected or Not Detected to represent the presence or absence of Mildew_Incidence variable for generalized propensity score.

ATE: average treatment effect for annual costs from generalized random forests.

ATE1: average treatment effect for active constituents from generalized random forests.
