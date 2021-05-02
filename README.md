# AJAX-Calls
Open Air Quality Description You have been provided with a public API by
Open Air Quality Org, which gathers data about the quality of air through
various data nodes, such as private and government agencies.
Following is the common URL to get the cities: https://api.openaq.org/v1/cities 
However, one can also look for the cities belonging to a given country by appending the
following string at the end of the common URL: "?country=nameOfCountry"  Thus, the URL will be updated to the following
in case of getting cities for a given country: https://api.openaq.org/v1/cities?country=IN  Here, IN represents the country India.
You've been provided with a form in your stub code. The submit button, when clicked, invokes the click handler named getCities
while passing in the argument as the id of the input text box which is used for getting the country code.  You are required
to complete the function getCities that makes a GET request to the above URL for getting all cities for a given country, 
the code for which is provided in the input box.  You can see the output in the Console tab in your browser's Developer Tools. 
The output will be in the following format:  The output you'll get if you've made the current 
call is:  {   "meta": {     "name": "openaq-api",     "license": "CC BY 4.0",     "website": "https://docs.openaq.org/",     "page": 1,     "limit": 100,     "found": 110   }, 
"results": [     {       "city": "Bengaluru",       "country": "IN",       "locations": 18,       "count": 688991     },     {       "city": "Delhi",       "country": "IN",   
"locations": 79,       "count": 2044924     },     ...     {       "city": "Jaipur",       "country": "IN",       "locations": 9,       "count": 288917     }   ] }

