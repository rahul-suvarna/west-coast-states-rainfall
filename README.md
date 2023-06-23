# Rainfall in the Indian Western Coastal States

### Description
- The dashboard describes the rainfall distribution amongst various Indian states along its western coast. It provides an interactive way to learn more about rainfall patterns and the changes it has seen in the last century.
- The data was obtained from the India Meteorological Department records hosted on the [Open Government Data Platform India](https://data.gov.in/catalog/rainfall-india?page=1) website.
- An example of what the dashboard looks like:
 
![alt text](west-coast-rainfall.PNG)

- The data in the [Sub_Divison_IMD_2017.csv](Sub_Division_IMD_2017.csv) is the monthly rainfall (in millimetres) recorded within a given sub-division during between 1901 and 2017.
- To get the data in a state-wise format, the data from the sub-divisions that make up the state were added. For example, data for the state of Maharashtra and Goa was obtained by summing up the data from the Konkan & Goa, Madhya Maharashtra, Marathwada and Vidarbha sub-divisions.

### Key Insights
- The states of Maharashtra (including Goa) and Karnataka recieve more than half of the rain in the western coastal region.
- The state of Gujarat receives the lowest amount of rainfall in the western coastal region.
- A clear pattern of high rainfall between the months of June and September is seen in the data; this corresponds to the monsoon season in India.

### Limitations
- A separate data column for the state of Goa does not exist in this dataset because of how sub-division lines were drawn.
- Similarly, no separate data for the Union Territories of Daman & Diu and Dadra & Nagar Haveli exist; instead, they are included in the sub-divisions that form the state of Gujarat.  
