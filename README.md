# 📡 Freqman-hacked-files

This repository contains custom and modified frequency list files for the **Freqman** application in the **PortaPack Mayhem** firmware (HackRF + PortaPack H1/H2/H4).

The purpose of this repository is to provide ready-to-use frequency databases for analysis, monitoring, and educational purposes using PortaPack Mayhem.

---

## Repository structure

Freqman-hacked-files  
├── Czech/  
│   └── Czech localized frequency lists and descriptions  
├── DECT_EU.txt  
├── DVB-T_EU_STANDARD.txt  
├── EXPERIMENTAL.txt  
├── GENERAL.TXT  
├── IOT_EU.txt  
├── JAMMER_CAR.txt  
├── JAMMER_WIFI.txt  
├── KEYFOB.txt  
└── WEATHER_SAT.txt  

---

## File descriptions

DECT_EU.txt  
Contains DECT (Digital Enhanced Cordless Telecommunications) frequency bands used in Europe.

DVB-T_EU_STANDARD.txt  
Standard European DVB-T (Digital Video Broadcasting – Terrestrial) channel frequency allocations.

EXPERIMENTAL.txt  
Experimental, uncommon, or test frequency ranges used for research and testing.

GENERAL.TXT  
General-purpose frequency list containing commonly used and miscellaneous radio services.

IOT_EU.txt  
Common Internet of Things (IoT) frequency bands used within the European Union.

JAMMER_CAR.txt  
Reference frequencies associated with automotive signal jammers (receive-only, research purposes).

JAMMER_WIFI.txt  
Reference frequencies related to Wi-Fi jamming and interference bands.

KEYFOB.txt  
Frequencies used by keyfobs, remote controls, and vehicle access systems.

WEATHER_SAT.txt  
Weather satellite downlink frequency allocations.

Czech/  
Contains Czech-language descriptions and localized versions of frequency lists.

---

## Frequency file format

The files are plain text and compatible with the PortaPack Mayhem Freqman format.

Examples:

f=433920000,d=ISM device  
a=88000000,b=108000000,m=WFM,d=FM broadcast band  

f = single frequency in Hz  
a = range start in Hz  
b = range end in Hz  
m = modulation (optional)  
d = description

---

## Installation (PortaPack Mayhem)

1. Power off the PortaPack.
2. Remove the SD card and insert it into your computer.
3. In the SD card root, create a folder named:

   /FREQMAN/

4. Copy all `.txt` files from this repository into the `/FREQMAN/` directory.
5. Optionally copy files from the `Czech/` folder if you want localized lists.
6. Insert the SD card back into the PortaPack.
7. Power on the device.
8. Open **Apps → Freqman** in the Mayhem menu.

Each `.txt` file will appear as a separate category inside Freqman.

---

## Legal notice

These frequency lists are provided for **educational, research, and receive-only purposes**.

You are responsible for complying with local radio regulations.  
Transmitting on restricted or licensed frequencies without authorization is illegal.

---

## Disclaimer

This project is not affiliated with the official PortaPack or HackRF developers.  
Use at your own risk.

---

## Author

Created and maintained by **TheOnlySyntax**

---

## License

No license specified. Add one if required.
