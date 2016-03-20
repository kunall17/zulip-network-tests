# Network Tests for Various Libraries for Zulip Organization

This comprises of measuring the amount of time taken to fetch a JSON file from a server (custom header if needed) using 4 libraries which are 
* Retrofit
* HTTPURLConnection
* Volley
* Apache Client.

I built these to test which of the these libraries will be best suited for the Zulip Android Project. 

###Usage- 
In each MainActivity file there are these constants

```    
String ANDROID_APP_KEY = "";
String APP_AUTH_KEY="";
String JSON_URL="";
```

In which you need to specify from where you want to fetch the JSON from.
And add any header's (if needed, remove it if you don't want) 
Run the Application. And it basically logs two things the json itself and the time taken. 
Search "timeinms" to find the time in MilliSeconds or "json-" to find the JSON in the logcat.
