# Data management Plan
##### 1. We need to store the information about the visitor which includes
- Visitor Id
- Name
- Contact Number
- Email Address
- Feedback
##### 2.	We need to store the information about an event that includes
-	Event_id
-	Name
-   Location
-	Date 
-	Time
-	Duration
##### 3. 	We also need a location table to store the information about the location that includes
-	Location_id
-	Name
-	Latitude
-	Longitude
##### 4.	We need a map routes table that includes
-	Location_id
-	Event location
-	Route name
-	Route distance
######        As of now, we divided the data into four entities. The visitor entity is to maintain the information about the visitor where it also stores the feedback messages given by the visitor based on the place he visited. The event entity contains the complete information about the event that also include the duration of the event. This entity is used to convey the information about the event to the visitors. The location entity is to get the exact latitude and longitude of the event or the position of a visitor. The map routes entity is used to calculate the distance between the event and the user location. There may be another entities to be added further.


