Zomato Data manipulation and reporting using Power BI
Constructing a consolidated and interactive PowerBI report that will allow Zomato to quickly assess the required data.

Steps performed:
Data transformation steps:

Imported data from all the available Excel files (mentioned below) into Power BI. a. Africa b. Asia c. Europe d. NAM e. SAM f. Oceania g. Fact Table h. Country-Code
Appended the Continent wise data files into a single file (i.e. from 'a' through 'f' from above list).
Split the column Restaurant Name, Address to have 2 separate columns respectively.
Replaces all the City names to have correct values.
Removed unwanted columns like Locality, Locality Verbose, etc.
For Country-Code data removed null or duplicates.
Created Measures for – Restaurant Count, Average Rating, Average cost, Cuisine count.

Created following visuals for the report:
World Wide Analysis Page:

Created Cards for: a. Restaurant Count b. Average Rating c. Average Cost
Map using the Continent -> Country -> City hierarchy, with bubble size indicating the restaurant count.
Infographic designer -> custom column chart with martini image as custom columns indicating the average rating for restaurant name.
Interaction between Map & Infographic designer charts to view data for selected region.
Restaurant Analysis Page:

Slicers created for a. Rating color – which follows below logic for assigning colors: Aggregate rating Rating color Above 4.5 Dark Green 4 to 4.4 Green 3.5 to 3.9 Yellow 2.5 to 3.4 Orange 1.8 to 2.4 Red 0 to 1.7 White b. Country c. City d. Has Online delivery e. Has Table Booking
Tree Map – Shows the Restaurant Names & Cuisine Count.
Gauge – Created 2 gauge as follows: a. Average Cost for 2 b. Average Rating
Cards – Created 2 cards a. Shows the Restaurant Address for selected Restaurant. b. Shows the available cuisines for the selected Restaurant.
Interactions are enabled across the page using slicers & between tree map & other visuals.
Report:
