# JavaQuest - Parse a JSON with Jackson
SEA8 - Quest: Parse a JSON with Jackson

Challenge: Share a JSON weather data file

Opens the fileweather.json in order to understand its structure, and then complete the classParse.

    1. Retrieving the document root
    2. Retrieve the value of the "name" property
    3. Retrieve the values of the "lat" and "lon" properties of the "coord" node
    4. Convert the "wind" node to an objectWind (class already exists)
    5. Convert the "weather" node to a table ofWeather (class already exists)
    6. Compile and execute the code in order to get the expected result displayed.
    7. Send changes to your remote repository and share the link of the_fork_ in solution

Expected outcome :

    City name: London
    City latitude: 51.51
    City longitude: -0.13
    Wind infos: src.main.Wind{speed=4.1, deg=80.0}
    Weather infos: src.main.Weather{id=300, main='Drizzle', description='light intensity drizzle', icon='09d'}
    Weather infos: src.main.Weather{id=800, main='Clear', description='clear sky', icon='01n'}

You can compile and execute your code with the following command:

    ./tester.sh