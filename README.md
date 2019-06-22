# -Los-Angeles-Traffic-Collision-Data
This dataset reflects traffic collision incidents in the City of Los Angeles dating back to 2010. This data is transcribed from original traffic reports that are typed on paper and therefore there may be some inaccuracies within the data. Some location fields with missing data are noted as (0°, 0°). Address fields are only provided to the nearest hundred block in order to maintain privacy. This data is as accurate as the data in the database.

Kaggle :https://www.kaggle.com/cityofLA/los-angeles-traffic-collision-data
- DR NumberDivision of Records Number: Official file number made up of a 2 digit year, area ID, and 5 digits.
- Date ReportedMM/DD/YYYY
- Date OccurredMM/DD/YYYY
- Time OccurredIn 24 hour military time.
- Area IDThe LAPD has 21 Community Police Stations referred to as Geographic Areas within the department. These Geographic Areas are sequentially numbered from 1-21.
Area NameThe 21 Geographic Areas or Patrol Divisions are also given a name designation that references a landmark or the surrounding community that it is responsible for. For example 77th Street Division is located at the intersection of South Broadway and 77th Street, serving neighborhoods in South Los Angeles.
Reporting DistrictA code used in producing reports to group data into geographic sub-areas within an area. 
- Crime Code : Indicates the crime committed. For this dataset - all Crime Code 997.
Crime Code DescriptionDefines the Crime Code provided. For this dataset - all Traffic Collision.
- MO CodesModus Operandi: Activities associated with the suspect in commission of the crime. See attached PDF for list of MO Codes in numerical order. https://data.lacity.org/api/views/y8tr-7khq/files/3a967fbd-f210-4857-bc52-60230efe256c?download=true&filename=MO%20CODES%20(numerical%20order).pdf
- Victim Age :Two character numeric.
- Victim Sex : F - Female,M - Male,X - Unknown
- Victim Descent :Descent Code: A - Other Asian B - Black C - Chinese D - Cambodian F - Filipino G - Guamanian H - Hispanic/Latin/Mexican I - American Indian/Alaskan Native J - Japanese K - Korean L - Laotian O - Other P - Pacific Islander S - Samoan U - Hawaiian V - Vietnamese W - White X - Unknown Z - Asian Indian
- Premise CodeThe type of structure or location where the incident took place.
- Premise Description : Defines the Premise Code provided.
- AddressStreet address of crime incident rounded to the nearest hundred block to maintain anonymity.
Cross StreetCross Street of rounded Address.
LocationThe location where the crime incident occurred. Actual address is omitted for confidentiality. XY coordinates reflect the nearest 100 block.
- Zip Codes
- Census Tracts
- Precinct Boundaries
- LA Specific Plans
- Council Districts
- Neighborhood Councils (Certified)

Findings :
- Time at which Traffic Accidents Occurs most is between 6:00pm to 7:00 pm
- Mean Time at which accident occurs is 1:54pm i.e between 1:00 pm to 2:00 pm. 
- Top 3 Area ID in which accident occurs most is 12,3,7.
- Top 3 Premise Code in which accident occurs most is 101,108,102.
- Reporting District - 645 has Maximum Reporting having count 2260.
- Most victim were male and then females.
- Top Victim Descent which more effected are Hispanic/Latin/Mexican,White,Other,Black,Unknown.
- Top Zip Codes in which there were maximum Traffic accidents are 23675,23668,23446,22352 
- Top Premises were accident occurs most are Street,Parking Lot,Sidewalk,Alley and in Driveway
- In the year 2017 and 2018 there where maximum accidents
- March,May,April are the month in which accident occure most
- Victim Descent - H have mean age pf 39, W has mean age of 43,O has mean age of 44
