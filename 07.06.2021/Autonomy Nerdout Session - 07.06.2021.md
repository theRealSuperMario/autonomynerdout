# Autonomy Nerdout Session - 07.06.2021

[TOC]


# Radar

## Questions to be answered

* which types of Radar are actually being used and why

* strenghs & weaknesses
    * Things only radar can detect (vs camera & lidar)
    * Things radar can't detect
    * robustness to changes in weather conditions
* Under which assumptions is Radar robust enough to:
    * Detect vehicles
    * Detect pedestrians
* Key technical performance metrics
    * SNR
    * range
    * field of view
    * cost / unit
* Key Companies

## Sources
https://archer-soft.com/blog/lidar-vs-radar-pros-and-cons-autonomous-driving

https://archer-soft.com/blog/lidar-vs-radar-pros-and-cons-autonomous-driving

https://www.fierceelectronics.com/components/why-hi-resolution-radar-a-game-changer

https://en.wikipedia.org/wiki/Imaging_radar#4D_imaging_radar

https://patentimages.storage.googleapis.com/36/a8/95/85c09f4777f85b/WO2021037454A1.pdf

[Continental 4D Imaging Radar](https://www.all-electronics.de/markt/continental-und-xilinx-entwickeln-4d-imaging-radarsystem-fuers-autonome-fahren.html)



## Strenghts / Advantages
* Comparatively cheap
* Long range detection
* Allows for velocity measurements
* Bouncing possible (look underneath other vehicles)


## Weakness / Dissadvantages
* Deceivable with jamming noise
* Low resolution
    * Often not good engough for classification by shape
    * [SOTA: 36° production, 12° research](https://www.tudelft.nl/en/stories/articles/increased-road-safety-with-high-resolution-automotive-radar)
        * [vs LIDAR: 0.1° production](https://cdn.www.ibeo-as.com/6929eac354f4a0dbda29ee49bd5580fc044ac758/Specsheet_ibeoNEXT_Generic_Module.pdf)


![](upload_e4856a786bf3619f8268618ca48bc307.png)




## Types of Radar
* [Short range Radar by Continental](https://www.continental-automotive.com/DE/Passenger-Cars/Autonomous-Mobility/Enablers/Radars/SRR600)
* [Surround Radar by Continental](https://www.continental-automotive.com/DE/Passenger-Cars/Autonomous-Mobility/Enablers/Radars/SRR600)


## Radar ICs

* [NXP 2011](https://www.nxp.com/docs/en/fact-sheet/AUTORADARFS.pdf)


## Research on Radar

* [Research by TU Delft](https://www.tudelft.nl/en/stories/articles/increased-road-safety-with-high-resolution-automotive-radar)
* http://microelectronics.tudelft.nl/People/bio.php?id=484

## Ongoing Developments

![](upload_182404d1814e76b0342768e3e4551b1d.png)





## Specs

[Example](https://www.continental-automotive.com/DE/Passenger-Cars/Autonomous-Mobility/Enablers/Radars/SRR600)

* Dimensionen: 60 x 50 x 15 mm (w/o con.)
* Reichweite: >100 m, >160 m @ LCA direction (Motorrad)
* Sichtfeld: ± 90° Erkennung / ± 75° Messung
* Update Rate: 50 ms
* Genauigkeit der Geschwindigkeitsmessung: ± 0.07 kph
* Temp. Bereich: -40° to +85°
* Versorgungsspannung: 12V
* Betriebsfrequenz: 76…77 GHz

![](upload_f4c9230bc77ec8f4fcc06af3082b5bae.png)


* [Source - ITU R](https://www.itu.int/dms_pubrec/itu-r/rec/m/R-REC-M.2057-1-201801-I!!PDF-E.pdf)
