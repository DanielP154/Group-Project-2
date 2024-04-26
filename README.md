Group Project 2

Jack Burke https://github.com/jgburke1

Daniel Palomino https://github.com/DanielP154

Shaan Patel https://github.com/shaan101patel

Zack Kendrick https://github.com/gzk07762

John Bell https://github.com/jcb10308![](Aspose.Words.f759409a-af8f-41f3-9bed-546c3e12ce9c.001.png)

The dataset titled "Motor Vehicle Collisions - Crashes" is a collection of data on traffic collisions reported by the police in New York City. It was last updated on April 19, 2024, and includes information derived from the “MV-104AN” forms filled out by police officers for each collision event. These forms are mandatory for officers to fill out if there is an incident that results in injury, death, or at least $1,000 in damages.

- Total Entries and Features: The dataset contains 1,048,576 rows, with each row representing a unique crash event, and has 30 columns detailing various aspects of each collision.
- Temporal Data: The 'CRASH DATE' and 'CRASH TIME' columns indicate the date and time when each collision occurred.
- Location Data: Information about the location of each collision includes the 'BOROUGH', 'ZIP CODE', 'LATITUDE', 'LONGITUDE', 'LOCATION', 'ON STREET NAME', 'CROSS STREET NAME', and 'OFF STREET NAME'. Not all entries have complete location data.
- Injury and Fatality Counts: There are separate columns for 'NUMBER OF PERSONS INJURED', 'NUMBER OF PERSONS KILLED', and further breakdowns for pedestrians, cyclists, and motorists.
- Collision Details: The dataset captures factors contributing to the collision (up to five factors), and types of vehicles involved (up to five types).
- Identifiers: Each collision is uniquely identified using a 'COLLISION\_ID' as well as vehicle identifier from: ‘VEHICLE TYPE CODE 1-5’

***Data Types:***

- The columns range from date-time and string (object) types for categorical data to integers and floats for numerical counts and geographical coordinates.
- Not all columns are fully populated; some, like 'OFF STREET NAME' or 'CONTRIBUTING FACTOR VEHICLE 5', have a significant number of missing values.

This dataset is intended for public access and use, as specified under its access terms. The data is stored and managed through the Finest Online Records Management System (FORMS), which helps traffic safety.

**LINK:** <https://catalog.data.gov/dataset/motor-vehicle-collisions-crashes>

**Geospatial Analysis**

What are the spatial distribution and hotspots of motor collisions within the region covered by the dataset?

![heatmap 2](https://github.com/DanielP154/Motor-Vehicle-Collisions-Data/assets/166060597/fda4e687-48fe-4da9-9366-504fc98e8ff4)


- To create the geospatial analysis, we utilized the map function along with the zip codes of New York and count of collisions in those specified zip codes. This allowed us to find the zip codes where motor vehicle collisions were most prevalent. Our map is highlighted from colors blue to orange based on the amount of collisions occurring in a given zip code. The more orange an area is, the more collisions that occur in that area.
- The heat map reveals Brooklyn as a major hotspot for motor collisions, likely due to its dense population and complex road network. Factors like pedestrian traffic, intersections, and diverse driving could be likely contributors to this risk. Targeted interventions, such as improved enforcement and infrastructure, can enhance road safety in Brooklyn.

**Temporal Trend Analysis**

What is the trend in the frequency of motor vehicle accidents over the past decade in dense and busy areas of New York? How does this trend compare to the other regions?

<img width="937" alt="thth" src="https://github.com/DanielP154/Motor-Vehicle-Collisions-Data/assets/166060597/80df9caa-c218-461b-8cb9-e25ab8cc8e59">

- For the temporal trend analysis, we manipulated the data by using the crash date by year, the sum of person(s) killed and the sum of person(s) injured per year. Our graph is then filtered by boroughs to depict the rate of collisions in more dense and busy areas. We used these manipulations to find the severity and frequency of collisions each year based on the location and year.
- Based on the visualization of severity/frequency by time, it can be drawn that the number of persons injured in motor vehicle accidents encounters high levels of variation. This causes the lines for each year to move closer towards the same values. However, the fatality data is more polarizing, illustrating high numbers of death in the earlier years of the data and lower numbers as the years grow on. This can most likely be attributed to stricter driving regulations and increased vehicular safety.

***Tableau Packaged Workbook Save or Export your project as a Tableau packaged workbook file and provide it as part of the github repository.***
