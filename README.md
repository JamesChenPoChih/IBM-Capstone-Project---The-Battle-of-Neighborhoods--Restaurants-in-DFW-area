# IBM-Capstone-Project---The-Battle-of-Neighborhoods--Restaurants-in-DFW-area
### Use map to explore the restaurants in DFW area

# ReadMe
## A. Introduction/Business Understanding
### A.1 Description of the problem

The Dallas–Fort Worth metroplex, officially designated Dallas–Fort Worth–Arlington , is a conurbated metropolitan statistical area in the U.S. state of Texas encompassing 11 counties. It is the economic and cultural hub of North Texas. Residents of the area also refer to it as DFW (airport code), or the Metroplex. The Dallas–Fort Worth–Arlington metropolitan statistical area's population was 7,573,136 according to the U.S. Census Bureau's 2019 population estimates.

DFW have great people and make it the most populous metropolitan area in both Texas and the Southern United States, the fourth-largest in the U.S. In 2016, the Dallas–Fort Worth metroplex had the highest annual population growth in the United States. Since DFW area is metroplex with a high population and population density, there are great amount of shops, cafeteria and restaurants in the metroplex where the population is dense. The restaurants will grow quickly as well. This research wants to explore what kind of restaurant is DFW area and what numbers of restaurant in different district. Then the investors can choose to the potential area to start up their entrepreneur. 

The investor can see the type of restaurants and numbers to decide where to build their restaurants and distinct from others.

### A.2 Data Description

To consider the problem we can list the data as below:
- The sources of zip, city and population are from the public: Opendatasoft, GitHub and demographics of Texas gov. The .json file has coordinates of the all city of Texas.
- I used Forsquare API to get the most common venues of given district of DFW area.
- For convenience, I deleted the city showed in the public data but not showed in the Foursquare search.
- The result data is the final data I merged, and I will put it in the file.
- You can to to the open data to find the Postal code, Latitude, Longitude and Population.
    1. http://zipatlas.com/us/tx/zip-code-comparison/population-density.htm
    2. https://demographics.texas.gov/Data/TPEPP/Estimates/
    3. https://github.com/OpenDataDE/State-zip-code-GeoJSON
    4. https://public.opendatasoft.com/explore/dataset/us-zip-code-latitude-and-longitude/table/

## B. Methodology
## C. Result
## D. Discussion
### 1. Interpret the Maps
1. Maps 1: The cites in DFW area. One city stands for one zip code.
2. Maps 2: The restaurants in DFW area. The bigger the bubble stands for the more restaurants and vice versa. The different color shows the different groups.
3. Maps 3: The restaurants in DFW area, which is showed in district. Therefore, we can see which district has the most restaurants.
4. Maps 4: The restaurants in DFW area, which is shown in clear map.
### 2. Name for Clustering
#### According to the clustering, we got 7 groups.
1. Great Dallas area metro.
2. Fast Food lover: Between cities and border area: Sachse, Hutchins and Terrel.
3. The border area:  Prosper and Ponder.
4. Frisco area.
5. Mexican Food lover: Lavon, Alvarado, Euless.
6. Great Fort Worth area.
7. Sanger: Chinese Food Lover.

#### Explanation for the clustering.
1. Great Dallas area metro: Since Great Dallas area is the largest city in DFW area, they got a lot of choices. Most of them choose Mexican food because Mexican restaurant are the most in DFW area because these two types of restaurants are more than other restaurants.
2. Fast Food lover: The area between cities and border area: Sachse, Hutchins and Terrel. Basically the restaurants are below 20, so they had few choices.
3. The border area: Prosper and Ponder. The top three restaurants are American food, French food, and Italian food.
4. Frisco area: Frisco had the a lot of Japanese food and people like to eat.
5. Mexican Food lover: Lavon, Alvarado, Euless area.
6. Great Fort Worth area: People got top 2 choices: Fast food and Mexican food.
7. Sanger: Chinese Food Lover. Sanger has more Chinese restaurant than others. 6. Great Fort Worth area: People got top 2 choices: Fast food and Mexican food.
7. Sanger: Chinese Food Lover. Sanger has more Chinese restaurant than others.

### 3. Investors View

1. Investors can see the size of bubble and decide where to start up their new restaurants.
2. Investors can use the most popular restaurants in different district table and find the potential chance. For example, although the most restaurants in Plano and Allen are Mexican restaurants, Chinese restaurants are the third place in Plano. However, Chinese restaurants stand only 10th in Allen.
## E. Conclusion
1. Investors can open their restaurants according to the final file--result. In this file, we will know the most popular restaurants, the population and numbers of restaurants in specific area.
2. The bubble in map shows the first and second metroplex in DFW area, which are Great Dallas and Fort Worth area. Investors can choose their ideal location to start up.

## G. References:
   - [1] DFW Wiki, https://en.wikipedia.org/wiki/DFW
   - [2] The demographics Texas of government, https://demographics.texas.gov/
   - [3] Forsquare API, https://foursquare.com/
   - [4] Opendatasoft, https://public.opendatasoft.com/    
