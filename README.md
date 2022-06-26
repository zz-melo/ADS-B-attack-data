# ADS-B-attack-data
Here is the anomaly data set based on ADS-B historical data, which mainly contains six attacks: abnormal altitude, abnormal speed, abnormal track, time replay, fake injection and jamming attack. 
# Real ADS-B data
The data in the ADS-b_data.TXT file is the real data of ADS-B.ADS-B data format is shown as example 1. 
example 1:
2017-02-10 10:43:06: 780AE7,CDG4652,118.4102173,38.9137604,22600,421.93,257.545,0,64
Time: 2017-02-10 10:43:06:
Flight ID:CDG4652
Longtitude:118.4102173
Latitude：38.9137604
Altitude:22600
Speed:421.93
Heading:257.545
# Attack
We randomly select time periods in multiple flights for abnormal data processing, the specific explanation is as follows:
# Abnormal altitude
Flight ID       Time
CCA1458    11:47:00-11:48:00
CCA1590    10:50:00-10:51:00
CCA9615    10:50:00-10:51:00
CDC8866    11:44:00-11:45:00
CDG8701    11:10:00-11:11:00
CES2078     11:10:00-11:11:00
CES5713     11:13:00-11:14:00
CQH8555    10:50:00-10:51:00
CSC8729     11:00:00-11:01:00
CSN3601     10:50:00-10:51:00
CSN6214     11:10:00-11:11:00
DKH1174     11:00:00-11:01:00
MU2949      11:10:00-11:11:00
# Abnormal speed
Flight ID       Time
CCA1458    11:47:00-11:48:00
CCA1590    10:50:00-10:51:00
CCA9615    10:50:00-10:51:00
CDC8866    11:44:00-11:45:00
CDG8701    11:10:00-11:11:00
CES2078     11:10:00-11:11:00
CES5713     11:13:00-11:14:00
CQH8555    10:50:00-10:51:00
CSC8729     11:00:00-11:01:00
CSN3601     10:50:00-10:51:00
CSN6214     11:10:00-11:11:00
DKH1174     11:00:00-11:01:00
MU2949      11:10:00-11:11:00
# Abnormal track
Flight ID       Time
CCA1458     11:45:50-11:48:50
CCA1590     10:49:00-10:50:00
CCA4189    10:49:00-10:50:00
CCA9615     10:49:00-10:50:00
CDC8866    11:45:00-11:46:15
CDG8701    11:14:00-11:14:15
CES2078     11:14:00-11:14:15
CES5694     11:00:00-11:01:00
CQH8555    10:49:00-10:50:00
CSC8729     11:00:00-11:01:00
CSN3601    11:00:00-11:01:00
CSN6214    11:14:00-11:14:15
DKH1174    11:00:00-11:01:00
MU2949      11:14:00-11:14:15
# Time replay
Flight ID       Time
CCA1458   11:49:00-11:50:00
CCA1590   11:50:00-11:53:00
CCA9615    11:51:00-11:53:00
CDC8866    11:46:00-11:48:00
CDG8701    11:11:00-11:13:00
CES2078      11:13:00-11:15:00
CES5713      11:14:00-11:16:00
CQH8555    11:46:00-11:48:00
CSC8729      11:03:00-11:05:00
CSN3601      10:52:00-10:56:00
CSN6214       10:10:00-11:12:00
DKH1174       10:59:00-11:02:00
MU2949         11:12:00-11:14:00
# Fake injection 
Flight ID       Time
CCA1458     11:45:00-11:50:00
CCA4189     11:45:00-11:50:00
CCA1590     11:45:00-11:50:00
CCA9615     11:00:00-11:04:00
CDC8866     11:45:00-11:50:00
CDG8701     11:11:00-11:15:00
CES2078      11:11:00-11:15:00
CES5693      11:18:00-11:21:00
CES5713      11:13:00-11:15:00
CQH8555    10:44:00-10:51:00
CSC8729      11:00:00-11:02:00
CSN3601     11:00:00-11:02:00
CSN6214     11:10:30-11:14:30
DKH1174     10:56:00-11:00:00
MU2949       11:13:00-11:15:30
# Jamming attack
Flight ID       Time
CCA1458     11:45:00-11:48:00
CCA1590     10:48:00-10:50:00
CCA9615     10:48:00-10:50:00
CDC8866     11:45:00-10:48:00
CDG8701    11:12:00-11:14:00
CES2078     11:12:00-11:14:00
CES5713     11:12:00-11:14:00
CQH8555   10:46:00-10:48:00
CSC8729     11:00:00-11:05:00
CSN3601    10:48:00-10:50:00
CSN6214    11:12:00-11:14:00
DKH1174    11:00:00-11:05:00
MU2949     11:12:00-11:14:00
