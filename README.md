# Thesis
**Please note that all provided commands are suitable for a Windows system and may need modification if ran on a Linux or Mac OS system.

## Downloading Data
In order to get the data using the given scripts, you must have Chrome and ChromeDriver installed. Make sure the versions match up. 
Download the files into a directory and run the following command from that directory in your command prompt.

```
python link_scraper.py
```

This will generate a csv file of 2000 URLs you can use to download the PDF and MIDI files. This csv file is also available in the data folder if you run into any issues with the link scraping file. Using this csv file, you can then run the musescore_scraper.py file in order to download the metadata, PDF, and MIDI files of all the links you just obtained. 

```
python musescore_scraper.py
```
