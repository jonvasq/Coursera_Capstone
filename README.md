# Coursera_Capstone
# ----------------------------------------------------------------
Clearly define a problem or an idea of your choice, where you would need to leverage the Foursquare location data to solve or execute. Remember that data science problems always target an audience and are meant to help a group of stakeholders solve a problem, so make sure that you explicitly describe your audience and why they would care about your problem.

# ----------------------------------------------------------------
I would like to find the optimal zip code in Charlotte, NC based on certain criteria. I will be moving to Chalotte and would like to move to an area that has things that are important to me. There are base requirements as well at other considerations that will be considered only in the event that there is a tie.

The base criteria are as follows:

1. Has a Hospital 
2. Has a Police Station
3. Has a Fire Station

If there is only one zip code in Chalotte that has all 3 it will be considered the winner and will be selected to be moved to.

In the event that there is no single zip that has all three criteria. Zip codes that have two out of three will be considered with no consideration to which base criteria is missing.

In the event that there are multiple zip codes that meet the above criteria, secondary criteria will be considered to be used as a tie breaker.

The secondary criteria are as follows:

1. Has a Mexican Restaurant
2. Has a Italian Restaurant
3. Has a Public Park


# ---------------------------------------------------------------- 

# Describe the data that you will be using to solve the problem or execute your idea. Remember that you will need to use the Foursquare location data to solve the problem or execute your idea. You can absolutely use other datasets in combination with the Foursquare location data. So make sure that you provide adequate explanation and discussion, with examples, of the data that you will be using, even if it is only Foursquare location data.

# ----------------------------------------------------------------

The data I will be using is a csv of zip codes with location data for the center of the zip code. The csv contains all 77 zip codes for Charlotte, NC.

Here is the web address where I accessed the csv:

https://public.opendatasoft.com/explore/dataset/us-zip-code-latitude-and-longitude/export/?q=charlotte&refine.state=NC

The data contains:

Zip  ,  City  ,    State\n Timezone , Daylight savings time flag , Latitude,  Longitude

28214 , Charlotte NC  ,  -5     ,   1                          , 35.276639 ,-80.96111
