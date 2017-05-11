## On Vehicle Device Team Overview

The On Vehicle Device Team will help define how best to approach the onboard tracking device.  This group will work together to decide what kind of device would work best to provide vehicle location reliably and cost effectively.  Cat would like to be able to report near real time (<15 seconds behind) location of the trollies and one day be able to use same device to collect data to determine things like actual stop time, expected stop time, average time between stops, etc. Some of this can be computed at the server level but the onboard device needs to collect and transmit the right data! 

## Issues to Discuss:

* Initial device type options
* How best to collect location from the device
* Transmitting vehicle location to an API as a JSON object
* Estimated per device cost both initial and monthly service feeds if applicable
* Supportability and Replacement difficulty of on vehicle device
* Configuration Requirements
* Can the device be automated to require no driver interaction?

## Reference Materials:

* Google spearheaded the creation of the GTFS protocol for recording transit routes (GTFS Static) and live location (GTFS Real Time Feed) we should use these standards if possible to make it easier to use the data from other services, like Goolge Maps
   * GTFS Static: https://developers.google.com/transit/gtfs/
   * GTFS Real Time: https://developers.google.com/transit/gtfs-realtime/
* OneBusAway is open source project in use in many cities already and could be a good starting place to see how others are doing mapping
   * https://github.com/OneBusAway/onebusaway/wiki
* On the OneBusAway wiki they've combiled a section on GTFS Realtime Feeds
   * https://github.com/OneBusAway/onebusaway/wiki/GTFS-Realtime-Resources
* Code for Greenville's Track the Troley Application was created for just such a purpose!  They have a simple map and API for recording trolley location and native apps for Iphone and Android for riders. See the different associated repos on their Git Hub 
   * https://github.com/codeforgreenville
* The Code for Greenville project uses an Android application for collecting and transmitting location   
   * https://github.com/codeforgreenville/trolley-tracker-agent
* Code for Miami built and designed an Arduino based solution to communicate with OneBusAway but would be a good reference for any kind of transit platform
   * https://github.com/Code-for-Miami/busTrackingGps
