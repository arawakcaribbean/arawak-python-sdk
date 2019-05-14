# Python SDK for Arawak Platform


[arawak_python_sdk](https://dev.azure.com/caribbean-tour-platform/_git/arawaks-sdks) is a library for access to API REST  for Arawaks Platform for python 2.7.15 +.  Basically provide the features and flexibility to get the job done and make those features really easy to use.

Features

 - Support to module Booking and Bookable Resource
 - Support to module Resource (Attraction,Accommodation, Event and TransportationOperators types)
 - Support to module Claim a Resource
 - Support to module to manager Country
 - Support to module Location (Georeference and maps points)
 - Support to module Reviews (state and evaluation a Resource)


#### Install dependencies
`$pip install requests`

# Examples
location = Location()
countries = location.getCountries()
print countries