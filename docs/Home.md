The _Arduino solar meter_ is a program that runs on an [Arduino](www.Arduino.cc) controller.

This program started in 2009 when I got my first set of solar panels and wanted to log the production of the set. In the last 3 years, several additions and improvements were made. Because many people that also use this program ask for more documentation, I have created this project page.

The program can read information from various devices in your meter cabinet at home.
It will store this information on the onboard SD card and can send it to different websites to make nice graphics.

The most simple form of the _Arduino solar meter_ (V8.x) can read pulse information from 3 kWh meters via the S0 interface and send this information to 3 different systems on [pvoutput.org](www.pvoutput.org)

Additionally, (V9) a ferraris meter can be monitored in two directions to measure consumption and generation and a sensor can be connected to a gasmeter or a watermeter.

Version 10 now supports the Smart-Meter P1 port!
Discussions on the soft- and hardware can be found on the forum of  [url:Wijhebbenzon.nl|
http://www.wijhebbenzon.nl/forum/19-monitoren-loggen-en-meten]

Version 11 adds the support for uploading of gas-usage to [mindergas.nl](http://www.mindergas.nl)
The minor releases (11.1 to 11.31 are stability updates and bugfixes.

In Version 11.4 all sensors have an absolute counter. This can be set via the webpage and is updated automatically.

Version 11.41 has some minor bugfixes, mostly related to the ntp time updating and pvoutput error reporting.

Version 11.42 is updated to use the latest Arduino releases (with library manager). Also a fix is done on the DST calculation so that the time is corrected on the right moment.

Unfortunately, the memory in the Arduino is not large enough to hold all the options so a choice has to be made.

Look in the [documentation](documentation) page to see how to connect the sensors and how the software works.

If you like this software, please consider a [donation](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=TGJJ6NCG4GMGU&lc=NL&item_name=Solarmeter&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donate_LG%2egif%3aNonHosted) so I can keep building and testing new functions.

If you use this software, please add your system to the [Pvoutput team](http://pvoutput.org/listteam.jsp?tid=564)

Also consider reviewing the software 


