# Pitch

## Intro (David)
For our project we looked at the northern hudson basin. This is located in the state of New York, in the United States. The southern hudson basin is influenced by the sea as the tide moves up the estuary river and thus has nog discharge data availible. For this reason we only considered the nothern section. 

We chose this region as it has a snow, reservoirs as interesting processes and a lot of data availible. 

## Data (David)
We used the data assimilation technique to verify which evaporation technique to use. This lead us to use the GLEAM data set which plotted nicely on the budyko curve, in contrast to ERA 5 which underestimated the evaporation in the region. For precipitation we used station data, which was very close to ERA5. For discharge we used station data.

## HBV vs distributed (Anne)
We then modeled the region with a HBV model and a distributed model. To do so, we added the snow bucket to the model, because the area has snowfall in winter. 
The distributed model underestimated the peaks, and with 21 parameters couldn't fit well to the data. We modeled the region in sets of 8 years. 4 years of callibration followed by 4 years of testing the model to the data. This was repeated 5 times between 1980 and 2020. The first one and half year of the calibration is used as spinoff and not taken into account when calculating the NSE.

## conclusion (Anne)
The Earlier models achieved higher NSE values whilst the later years were less better fits. 
One of the main issues are the high amount of reservoirs in the area, which flattens out peak flows in the summer, which the model fails to replicate. Adding a parameter which modifies the fast reservoir in summer could help to improve this. 
More parameters however also adds uncertainty, thus multi-objective calibration should be needed. 
