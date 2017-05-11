## Application Infrastructure Team Overview:

The Application Infrastucture Team will help define the under the hood elements of the Track-a-Cat application.  This group will work together to decide what the framework will look like for the backend of an application that may start small with a responsive map showing trolley stops and current trolley locations, but will one day scale to be able to support a number of features that have yet to be defined potentially including native mobile applications, sms interaction, multiple routes and bus types.  Cat would like to one day be able to use the data collected from the onboard location devices to determine things like actual stop time, expected stop time, average time between stops, etc.  

## Issues to Discuss:

* Initial Hosting Location
* Language and Framework for the Server/Application
* Database for collecting location data over time
* Potential Mapping Solutions
* API for receiving Trolley Location
* Other API Interactions i.e. Google Transit or MapZen for current traffic details 
* Long term environment RoadMap considerations

## Reference Materials:

* OneBusAway is open source project in use in many cities already and could be a good starting place 
https://github.com/OneBusAway/onebusaway/wiki
* Code for Greenville's Track the Troley Application was created for just such a purpose!  They have a simple map and API for recording trolley location and native apps for Iphone and Android for riders. See the different associated repos on their Git Hub 
https://github.com/codeforgreenville
* Google spearheaded the creation of the GTFS protocol for recording transit routes (GTFS Static) and live location (GTFS Real Time Feed) we should use these standards if possible to make it easier to use the data from other services, like Goolge Maps
    GTFS Static: https://developers.google.com/transit/gtfs/
    GTFS Real Time: https://developers.google.com/transit/gtfs-realtime/
* The OpenSavannah Brigade gets a number of benefits from being a local brigate of Code for America, including hosting!  Check out the free benefits we get here: http://brigade.codeforamerica.org/brigade/tools/ 




