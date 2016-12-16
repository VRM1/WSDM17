## **CityName**_venue_cat.json 

This file has the category and tag for all the POIs/venues.
The format is json, where key is the POI id and the value is another dictionary.
The sub dictionary has 2 keys.
1. cats: has vlaue as a list of category ids
2. tags: has value as a list of tag ids

The following python code will create a dictonary dict_venue_cat with the structure described above.
```python
import json
dict_venue_cat = json.loads(open('**CityName**_venue_cat.json').read())
```


-------------------------------------------------------------------------------------------------------------------
##**CityName**_venues.csv

1. Venue ID
2. Venue name
3. Latitude
4. Longitude
5. Category
6. Number of Tips for the venue
7. Average rating given by users
8. Number of check-ins
9. Number of users checked in
10. Number of likes
11. Number of lists the venue belongs to
12. Number of photos uploaded
13. Price category
14. Time of profile creation on foursquare
15. URL
