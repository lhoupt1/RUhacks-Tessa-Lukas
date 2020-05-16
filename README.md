# RUhacks-Tessa-Lukas

# API Workshop
Tessa- read this really quickly and then download the "simple-python-get-example" and "simple-python-post-example" files and run them

-GET request: for retrieving info
-POST request: for submitting info (ex a sign-in to a website)
-API use: to make your data accessible for developers
  -Examples:
    -https://openweathermap.org/api weather data
    -https://api.ratesapi.io/api/latest exchange rates
-Making a request:
  -Click https://api.ratesapi.io/api/latest
    -Returns json data (common API format, key-value pairs similar to python dictionaries)
    -Notice that base = Euro
    -We can change base with a “Parameter”
-Parameters:
  -For GET requests, just modify the url:
    -http://mywebsite.com/api?a_parameter=a_value
      -Add ?a_parameter=a_value
    -For rates api, use https://api.ratesapi.io/api/latest?base=USD
      -Now the base currency is USD
  -For POST requests, modify the “body” of the request:
    -After the headers, not in the url
