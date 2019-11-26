# ETL_project
Proposal Plan

1. Data Source = AirBnb Data for Seattle - Reviews CSV and Listings CSV (kaggle)

2. Create dataset with the most popular Seattle neighborhood rentals based on review score and frequency of repeat visitors. 
	A. Are people who give a "10" rating score more likely to stay again?  
	B. Do certain listing title words "Downtown"-"Views" make a difference? 
	C. Differences in the property type/location. Analyze the location of the most popular areas
	D. Is the review count statistically different between locations?

3. Store in SQL Table

4. Determine Count of reviews, Count of reviewers that stayed at same listing, pull out words in listing title "Downtown"/"View"

5. Real estate market price of property effects price of the stay(?)

Primary key = listing ID

Listing CSV = Review score 
Listing CSV = Neighborhood Cleansed
Listing CSV = property_type
Listing CSV= room_type
Listing CSV = Price
Listing CSV = Name
Review CSV = Reviewer ID, Listing ID, Count (# of reviews)
