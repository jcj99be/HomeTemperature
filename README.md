# HomeTemperature
Transmit Home Temperature to public storage to read on Android Phone

The ultimate goal of this project is to pick up some experience on using public cloud storage and accessing it from an Android device
- Programming with Python
- Using Goole Drive services store and retrieve information
- Develop an android application to retrieve and display information from Google Drive

The use case is to send temperature and humidity information collected from my weather station to Google Drive, then retrieve and display the info on an Android smartphone connected to the internet.

Actual Setup:
- Oregon Scientific WMR88 weather station with various probes
- WMR88 connected (via USB) to a Raspberry Pi running Linux Raspberry 3.18.7
- WeeWX 3.8.2 to retrieve information from the WMR88, consolidate and correlate the information and generate reports.
- Synology DS211 with Web Server connected to my home network with Web Server installed. 
- WeeWX generates HTML reports which are FTPed to the DS211. The page can be viewed via browser from any device connected to the home network. Not open to the public internet
