# flood-precautionary-bot
Every monsoon, many cities in the world effectively get paralyzed due to heavy rains. Although the Meteorological Department provide blanket warnings, they have limited resources. To help understand flooding at a street level more data is needed on the streams, canals and sewers. The Flood Precautionary Bot project aims to show how to prevent loss of life and property locally by the Internet of Things using embedded systems with sensors. When a condition of flood occurs, the device will: send out a tweet(Twython), make an FB post, send an email (SSMTP). Also a WhatsApp autoreply bot (Yowsup2) is made that tells the distance of water and status of flood in real time.
This project contains 3 files and two of them are run together. One of the files if twitter.py. This file contains the code for reading the distance between water and the sesnor at an interval of 5 seconds and sending alerts when the distance becomes less than the critical distance. 
The other two files are part of the same program that run the real time monitoring on WhatsApp. Yowsup2 is used in both the files.
