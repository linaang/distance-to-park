Estimation of distance (in meters) from HDBs to the nearest parks (Singapore)
================
Lina Ang
2025-05-30

## About
<div style="text-align: justify;">
This repository contains datasets in GeoPackage (.gpkg) and CSV (.csv) formats, detailing the estimated distances (in meters) from public residential buildings to the nearest nature parks or nature reserves in Singapore. All data in this public repository is free to use and download, as they are generated using open-source datasets.
</div>

## Data sources used 
1) HDB Property Information [Data.gov.sg](https://data.gov.sg/datasets?query=hdb&resultId=d_17f5382f26140b1fdae0ba2ef6239d2f&page=1)
2) NParks Parks and Nature Reserves [Data.gov.sg](https://data.gov.sg/datasets?query=nature+parks&page=1&resultId=d_77d7ec97be83d44f61b85454f844382f)
3) OneMap API [OneMap API](https://www.onemap.gov.sg/apidocs/maps)

## Variables
 [1] "blk_no"                "street"                "postal"                "max_floor_lvl"        
 [5] "year_completed"        "residential"           "commercial"            "market_hawker"        
 [9] "miscellaneous"         "multistorey_carpark"   "precinct_pavilion"     "bldg_contract_town"   
[13] "total_dwelling_units"  "X1room_sold"           "X2room_sold"           "X3room_sold"          
[17] "X4room_sold"           "X5room_sold"           "exec_sold"             "multigen_sold"        
[21] "studio_apartment_sold" "X1room_rental"         "X2room_rental"         "X3room_rental"        
[25] "other_room_rental"     "address"               "dist_to_park_m"        "park_area"            
[29] "park_length"           "park_name"             "SVY21_X"               "SVY21_Y"              
[33] "Longitude"             "Latitude"    

### Variables of interest
1) dist_to_park_m: estimation of residential building to the nearest park in meters
2) park_name: nearest park name to residential building

## HDB mapped
![HDB mapped by latitude and longitude](figures/HDBs.jpg)

## Nature parks/reserves mapped
![Nature parks and nature reserves](figures/Parks.jpg)

## Contact
<div style="text-align: justify;">
For more information, please email me at <ephanli@nus.edu.sg>.
</div>

