# PiSavar  - [ - PineAP Suite - Analysis, Detect, Kill - ]

<p align="center">
<img src="https://github.com/besimaltnok/pineAPhunter/blob/master/pineapple.png" width="300" height="400">
</p>

<p align="center">
<img src="https://img.shields.io/badge/Python-2-yellow.svg"></a> <img src="https://img.shields.io/badge/license-GPLv3-red.svg">
</p>


### How to work PineAP Suite

* Collect SSID information
* Creates SSID pool with collected SSID information
* Creates fake access points using information in the SSID pool

<img src="images/pineap.png" width="50%"></img>

### Where is the problem?

- ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) `One MAC address, more than one SSID information .... ..- -. - . .-. `


### Features of PiSavar

* Detects PineAP Suite 
* Detects networks opened by PineAP Suite.
* Starts deauthentication attack for PineAP Suite.

### Features to add

* List of clients connected to fake access points
* Record activities - Logging

#### Diagram

<img src="images/info.png" width="50%"></img>

### --------------------------------------------------------------------------------

### Usage

#### Kali Linux:

Download pisavar:

`git clone https://github.com/besimaltnok/PiSavar.git`

Install Python librarie(s):

`pip install termcolor`

It's done!

Run the program with following command: 

```python
(root)
airmon-ng start wlan0
cd PiSavar
python pisavar.py wlan0mon
```


### Screenshots
<img src="images/pisavarnew.png" width="28%"></img>
<img src="images/dosnew.png" width="39%"></img>


### Demo Video

### Authors
This project is written by Besim ALTINOK
