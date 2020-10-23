# Weather-Forecast

1. What you need is to get your API Key address at https://home.openweathermap.org/api_keys.
   Get your own API Key by sign up first.
  
2. Open your command prompt and create a file name node-weather: 
   mkdir node-wheather
   
3. Then once the file created, open it using Visual Studio Code.

4. Install packages:
   npm install request
   
5. Go to the Open Weather Map website and click:
   API
   Current weather data
   `http://api.openweathermap.org/data/2.5/weather?q=${address}&units=metric&appid=${process.env.API_KEY}`
   As u can see in the url, I put units=metric because in can automatically convert it to Celsius.
   
6. Create a new file nama .env in your node-weather folder.

7. The .env is to encrypt your API key so that your API key will be secured.
   API_KEY= Your API Key
   
 8. Open your command prompt and start searching for places you want to know about current weather.
    Must include in your command :
    
    Example - node app.js Kuala Lumpur,MY
    
 9. Then you will obtain the current weather data from the city you search for.
 
 Thank you :)
    
    
