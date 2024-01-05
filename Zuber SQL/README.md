# Zuber Database
The purpose of this project was to use SQL to find patterns in the available information from competitors to understand passenger preferences and the impact of external factors on rides.

Video Capture of the SQL code and results: https://drive.google.com/file/d/1Azcob44DlMPgUuVa9XEol6WM3TXD47dM/view?usp=sharing

# Data
* 'neighborhoods' table: data on city neighborhoods
  * 'name': name of the neighborhood
  * 'neighborhood_id': neighborhood code
* 'cabs' table: data on taxis
  * 'cab_id': vehicle code
  * 'vehicle_id': the vehicle's technical ID
  * 'company_name': the company that owns the vehicle
* 'trips' table: data on rides
  * 'trip_id': ride code
  * 'cab_id': code of the vehicle operating the ride
  * 'start_ts': date and time of the beginning of the ride (time rounded to the hour)
  * 'end_ts': date and time of the end of the ride (time rounded to the hour)
  * 'duration_seconds': ride duration in seconds
  * 'distance_miles': ride distance in miles
  * 'pickup_location_id': pickup neighborhood code
  * 'dropoff_location_id': dropoff neighborhood code
* 'weather_records' table: data on weather
  * 'record_id': weather record code
  * 'ts': record date and time (time rounded to the hour)
  * 'temperature': temperature when the record was taken
  * 'description': brief description of weather conditions, e.g. "light rain" or "scattered clouds"
 
# Description
This project is a six step SQL query that includes exploratory data analysis and investigation into the duration of rides from the Loop to O'Hare International Airport.

# Assumptions
* There isn't a direct connection between the trips table and weather_records table in the database
* neighborhood_id is the Primary Key for the neighborhoods table
* cab_id is the Primary Key for the cabs table
* trip_id is the Primary Key for the trips table
* record_id is the Primary Key for the weather_records table

# Process
1. Analyzed taxi rides by company for specific dates, sorting by trip count
2. Analyzed rides for companies containing specific keywords, grouping by company name
3. Retrieved neighborhood IDs for O'Hare and Loop
4. Categorized weather conditions by hour
5. Retrieved Saturday rides from Loop to O'Hare, including weather and duration

# Findings
* Flash Cab had the most number of rides for November 15-16
* For rides completed on November 1-7 there were two taxi companies that had blue in their name and two that had yellow in there name
* For November 1-7: Flash Cab completed 64,084 rides, Taxi Affiliation Services completed 37,583 rides, and all other taxi companies completed 335,771 rides
* The neighborhood_id for Loop is 50
* The neighborhood_id for O'Hare is 63
