# User Weather with a database

Your goal is to only hit the Weather API once a day (per user or per zip code).

1. Single page app with Browserify and Grunt
1. Utilizes json server and OpenWeather(get an API key)
1. Have a user login with Username and password.
1. If user does not exist in json server, add them to user collection with a default zipcode.
1. If user exists, use details in json server.
1. User details will contain today's weather.
1. If today's weather exists, use it.
1. If today's weather does not exist (NA or yesterday), get today's weather and save to json server.
