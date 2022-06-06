# UFOs

## Purpose
The purpose of this analysis was to create a website that can be used to quickly look through a large data set containing reported UFO sightings. We also added the ability to filter through the data by date, city, state, country, and shape - or using a combination of the filters. This allows the user to customize their search to quickly find the information they are looking for.

## Results
### Welcome to UFO Sightings!

![header](https://user-images.githubusercontent.com/100883212/172081431-cc5a293f-7985-4594-87ed-d42c20f7c95a.png)

We are thrilled you are interested in discovering more about the many UFO sightings across the US in recent years! We have created our webpage with you in mind, allowing users to search through our database using multiple criteria.

### Instructions for Use

![filters](https://user-images.githubusercontent.com/100883212/172081449-dbb7a321-e420-4f86-b882-3cfd61eb5a1e.png)

We have set up our database to allow users to filter based on five criteria which can be used alone or in combination. In each box are examples to guide you through your search. To begin your search, simply type in the criteria you would like to search on and press "Enter" on your keyboard to initiate the filter. Your results will appear in the table to the left.

For example, below we have set the filters to search for all sightings of triangular UFOs in California. This search returned 7 results.

![results](https://user-images.githubusercontent.com/100883212/172081472-f61561a3-eeb7-4a34-884a-7e89eafedb0a.png)

To reset the filter, simply click the "UFO Sightings" text in the top left corner of the webpage. By default, all entries in our database will appear if no filters are entered.

## Summary

### Design Limitations
Although the site will absolutely make research easier for users, the filters are limited. All criteria must be entered in the exact format as is in the database. For instance, entering "CA" instead of "ca" for the state will return no results. Searches can only be conducted for one day at a time, so if a user wants to view all reported sightings in January 2010, they will have to search each day individually rather than entering "01/2010" in the filter.

### Recommendations
Based on these limitations, I have two recommendations for improving user experience:
1. Allow for searching based on a date range instead of one date at a time - for example, searching either "01/2010" should return all results for January 2010.
2. Upgrade the filters to recognize entries formatted in ways similar to but not exactly as the database entries are formatted - for example, "roswell", "Roswell", "ROSWELL", or "Roswell " should all return results for Roswell, CA. 
