# WG_API_HW
06-Python-API-HW

WeatherPy

Use Function WeatherDataPull to quickly and easliy pull up to date weather statisitcs from OpenWeatherMap.org [https://openweathermap.org/]
    
    -Ensure your OpenWeatherMap API Key is saved into the designated Config file within the WeatherPy folder

    -Input desired count of unique cities
        -The Function begins randomly selecting cities from across the world based off random latitude and longitudes
        -Duplicate cities will be skipped, and cities that fail to retrieve data will be skipped and replaced

    -Automaticly puts data into a Pandas DataFrame for easy use and control of generated data



VacationPy

    -Ensure your Google API Key is saved into the designated Config file within the VacationPy Folder

    -Automaticaly create a heat map based on WeatherPy's humidity data

    -Input desired or ideal weather
        -Input a maximun temp you would like on vacation in Farenheit
        -Input a minimum temp you would like on vacation in Farenheit

        -Input a maximum humidity level you would like on vacation 
            - 0 to 100 scale, do not put a percent icon (%) or decimal into the input field
        
        -Input a maximum cloud coverage percentage you would like on vacation
            - 0 to 100 scale, do not put a type of cloud covereage
            -Do not add a percent (%) icon or decimal into the input field

        -Input a maximum wind speed you like on vacation
            - Please input a valid windspeed, do not add mph to the input field
        
        -Should there be an error, run function again and insert valid fields
    
    -Generate a list and interactive map of the nearest hotel to the city center of all cities that fit your ideal vacation weather!

































































































the function formerly known as, MegaFunction()