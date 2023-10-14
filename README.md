# RPI-Seismic-Monitor-Code

Stable well-tested code suitable for long-term recording of seismic data. This be easily adapted to record a range of input signals periodically producing plots for uploading to the web. Data are saved timestamped .mseed format for ease of analysis by standard seismic software.

This code evolved out of Raspberry PI projects to monitor solar wind, solar flares and infrasound. It runs successfully on RPi 3b and 4 and can be left unattended for months. A simple separate crontab script periodically (e.g. hourly) uploads the plots to a website. Should further analysis be required data-files from the Rpi are downloaded for detailed examination with standard seismic software such as ObsPy on a PC. An example of this ObsPy analysis code is also included.

The RPi code is written in python3 and invokes the ObsPy seismic data handling library. 


Key Features
    • OpenSource.
    • Easily configurable to store data from a variety of sensor inputs.
    • Running unattended on multiple devices 24/7 for over 3 years with zero crashes.
    • Produces regular data-plots for automatic uploading to a webpage.
    • Creates subdirectories for plots and data
    • Data is stored in miniSEED format permitting reading and analysis by standard seismic analysis software such as ObsPy.
    • Hourly timestamps for accuracy.
    • Recovers from power outages



Ian Robinson     www.starfishprime.co.uk
