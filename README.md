# Modeling of the Hudson basin, New York, USA.
Catchment model for the course ENVM1502


##### to do: change this image 
![map_satelite_imaging](GIS/map_satelite_imaging.jpeg)

##### Work overview:
| Unit        | What                | To dos                                 | Who   | Done?  |  Result                 |
| :----:      | ----                | ----                                   |:----: | :----: | ----                    |
| 0.1         | P data (& T)        | Precip data, likely also temp          | Anne  | Yes    | loaded in               |
| 0.1.3       | P data reweighing   | use theissen polygon rather than mean  | David | Yes    | completed, reruning with|  
| 0.2         | Q data              | From UGSG                              | David | Yes    | loaded in               |  
| 0.3         | EP data             | from satelite product?                 | David | Yes    | era5 loaded in          | 
| 0.4         | Combining all data  | take the mentioned data & load in      | David | Yes    | era5 loaded in          |  
| ----        | ----                | ----                                   | ----  | ----   | ----                    |
| 1.1         | Budyko curve        | Plotting Ea/P vs EP/p &  desribing     | Anne  | Yes    | Done, needs comments    |  
| 1.2         | EVA                 | Creating MEV & GEV                     | David | Yes    | Done, needs comments    |
| 1.3         | Vegetation          | Estimate rootzone storage              | Anne  | Yes    | Done, needs comments    |
| 1.4         | snow                | Estimate snow storage & melt           | David | Yes    | Done, some commments    |  
| 1.5         | Muskingum           | Flood routing                          | Anne  | Yes    | Done, some commments    |
| 1.6         | Mositure recycle    | Local mositure                         | David | Yes    | Done, commented         |
| ----        | ----                | ----                                   | ----  | ----   | ----                    |
| 2.1         | map reservoirs      | Use landsat to select surface water    | David | Yes    | Done, commented         |
| 2.2         | remote P measure    | analyse P with satilites/microwave obs | Anne  | NA     | write up why not needed |
| 2.3         | moisture            | map soil moisture                      | David | Yes    | Done, some comments     |
| 2.4         | DEMS & gravity      | Use dem & estimate S using grace       | Anne  | Yes    | Done,needs some comments|
| 2.5         | Evaporation         | extract evaporation from rs            | David | Yes    | loaded from era 5, see 0.3|
| 2.6 & 7     | Data assimilation   | tweak data to close waterbalance       | Both  | Yes    | Now use Gleam instead of era5 |
| 2.8         | Climate predictions | Look at monthly precipitation predict  | David | Yes    | Done, needs comments    |
| ----        | ----                | ----                                   | ----  | ----   | ----                    |
| 3.1         | Linear reservoir    | K & alpha values                       | Anne  | Yes    | Done, some commments    |
| 3.2         | lumped model        | Insert values into model               | Anne  |        |                         |
| 3.3         | callibration        | callibrate values in model             | Anne  |        |                         |
| 3.4         | distributed model   | Use landscape and divide into gridcells| Anne  |        |                         |
| ----        | ----                | ----                                   | ----  | ----   | ----                    |
| 4.0         | overview nb         | Combine everything                     | David |        |                         |
