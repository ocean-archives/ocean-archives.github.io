<img src="https://repository-images.githubusercontent.com/657862402/5af48b86-b724-4ed3-b4d6-9656bed5eb0f" style="width: 100%; max-width:1000px; height: auto;">
Last update: 17:57 PT 29 July, 2023

## Background
### Why make this?
This little repository of information is put together in the interest of helping retrospective analysis of the 2023 OceanGate Titan incident. The scope of information here is intended to only extend to mechanical, logistical, and operational points of data. I will do my best to include only the information that is confirmed, and any unconfirmed or rumour-basis information will be tagged as "Unconfirmed" to the best of my ability.

## Disclaimer

__I am not affiliated with OceanGate or any of its partners, nor am I an expert in submersibles! I greatly appreciate the corrections sent my way or volunteer help in maintaining the information in this page. The contents of this page are accurate to the best of my knowledge, but there may be inaccuracies. The Titan was a frequently changing submersible. Some equipment or methods listed may have been in use at one time but may not have been not in use at the time of the incident.__

## Image Gallery (Work in Progress)
<table>
  <tr>
  <td><a href="https://ocean-archives.github.io/gallery-cad.html">CAD (OnShape, SolidWorks) Files</a></td>
  <td><a href="https://ocean-archives.github.io/gallery-internal-computers.html">Internal Computers</a></td>
  <td><a href="https://ocean-archives.github.io/gallery-iron-sub.html">Iron Sub</a></td>
  <td><a href="https://ocean-archives.github.io/gallery-nav-comms.html">Nav & Comms</a></td>
 </tr>
 <tr>
  <td><a href="https://ocean-archives.github.io/gallery-dome-ring.html">Titanium Dome, Ring, Acrylic Viewport</a></td>
  <td>Fairing</td>
  <td><a href="https://ocean-archives.github.io/gallery-cf-hull.html">Carbon Fiber Hull</a></td>
  <td><a href="https://ocean-archives.github.io/gallery-thrusters.html">Thrusters</a></td>
 </tr>
 <tr>
  <td><a href="https://ocean-archives.github.io/gallery-life-support.html">Oxygen & Scrubber Systems</a></td>
  <td>Displays & Monitors</td>
  <td><a href="https://ocean-archives.github.io/gallery-hmi.html">SCADA/HMI Control Panel</a></td>
  <td>Hull Insert</td>
 </tr>
 <tr>
  <td><a href="https://ocean-archives.github.io/gallery-j-box.html">Birns Junction Box (J-Box)</a></td>
  <td><a href="https://ocean-archives.github.io/gallery-control-pods.html">Spherical Control Pods</a></td>
  <td><a href="https://ocean-archives.github.io/gallery-penetrator.html">Hull Penetrators</a></td>
  <td><a href="https://ocean-archives.github.io/gallery-battery.html">Batteries & Power</a></td>
 </tr>
 <tr>
  <td><a href="https://ocean-archives.github.io/gallery-frame-foam.html">Frame & Syntactic Foam</a></td>
  <td><a href="https://ocean-archives.github.io/gallery-ballast.html">Ballast</a></td>
  <td><a href="https://ocean-archives.github.io/gallery-camera-systems.html">Camera Systems</a></td>
  <td><a href="https://ocean-archives.github.io/gallery-real-time-monitoring.html">Real Time Monitoring System</a></td>
 </tr>
</table>


## OceanGate Titan Construction

### Hull

#### Version 1
* Carbon fiber wound cylinder hull built by Spencer Composites in 2017
* 6000lb, 56” diameter, 100” long
* "Alternating placement of prepreg carbon fiber/epoxy unidirectional fabrics in the axial direction, with wet winding of carbon fiber/epoxy in the hoop direction, for a total of 480 plies." ... "Manufacturing in a generous safety margin. The carbon fiber/epoxy hull of the Cyclops 2 features alternating layers of UD prepreg in the axial direction, and wet-wound carbon fiber filaments in the hoop direction. The hull is 127 mm thick (5 inches vs. the 6 inches planned for Fossett’s earlier craft) and has tested to 2.5 times the 6,500-psi service pressure." [Article](https://www.compositesworld.com/articles/composite-submersibles-under-pressure-in-deep-deep-waters)
* Carbon fiber is standard-modulus Grafil 37-800 (30K tow), supplied by Mitsubishi Chemical Carbon Fiber & Composites Inc. (Irvine, CA, US). 
* Prepreg was supplied by Irvine-based Newport Composites, now part of Mitsubishi Chemical Carbon Fiber & Composites Inc. The wet-winding epoxy is Epon Resin 682 from Hexion Inc. (Columbus, OH, US). 
* The curing agent is Lindride LS-81K frLindau Chemicals Inc.cals (Columbia, SC, US).
* Modeling was done in SolidWorks and analysis was done with COSMOS/M, supplied by Dassault Systèmes subsidiary Structural Research and Analysis Corp. [Thesis](https://dspace.lib.ntua.gr/xmlui/bitstream/handle/123456789/57640/ZERVOU_THESIS.pdf?sequence=1)
* The CF hull was "sandblasted and coated with a 5mm layer of polyurethane to prevent saltwater intrusion when the hull is subjected to water pressures at her maximum depth of 4,000 meters." (From Facebook, now removed).
* Hull later redone due to cyclic fatigue on original Spencer Composites hull
* Hull insert
  * Designed to prevent condensation from dripping inside and isolates electronics from the hull
  * Also used for ambient lighting and aesthetic [Instagram](https://www.instagram.com/p/Bb0VVcRlggI/)
  * Material is unknown

#### Version 2
* 2020 Upgrades are made to the carbon fiber hull for Titanic Survey expedition in 2021
  * Carbon Fiber composite by ElectroImpact
    * [LinkedIn Post (Archived)](https://web.archive.org/web/20230624152949/https://www.linkedin.com/feed/update/urn:li:activity:7006648654967029761/)
    * 667 plies [CBS Interview with Stockton Rush](https://www.cbsnews.com/news/titanic-submersible-interview-transcript-with-oceangate-ceo-stockton-rush/)
  * Manufactured using ElectroImpact's "AFP 4.0" process
    * [Whitepaper: "AFP 4.0" (Archived)](https://archive.is/UWOwf)
  * Prepreg CF by Toray Composite Materials America Inc
    * [Facebook post](https://www.facebook.com/jeccomposites/photos/a.353532834730096/2799682173448471/?type=3&paipv=0&eav=AfZ1k8CuEfwFfFNOA36okdSyPXodyhNefYtZFHzsuve_1gygIDJu0o1CJ-7B0-_JfF8&_rdr)
  * Machining done by Janicki Industries.
  * In a 2022 expedition video, it's claimed to be coated with Rhino Liner.
  * Structural analysis by Collier Aerospace. ([Facebook Post](https://www.facebook.com/collieraerospace/posts/pfbid02ae7jxE1aaoY9gEEgJ1A3D6jybVxrDtTctWnbnUbMpFCxDLWSgoJfudBMUjUVCcEgl))
    * "In July, 2021, OceanGate descended to the sunken remains of the #Titanic in its revolutionary carbon fiber and titanium submersible, Titan. Collier Aerospace had the opportunity to be a part of this groundbreaking expedition during the development of Titan's carbon fiber hull, which was designed with the help of our structural analysis and design software." 

#### Titanium hemispheres (x2)
* Made by Titanium Fabrication Corp
* Hatch
  * Entrance at surface depth, with hatch sealed with 17 bolts

#### Titanium rings (x2)
* Made by Titanium Fabrication Corp
* Affixed to the carbon fiber hull with a glue
* Assembly: [Video](https://www.youtube.com/watch?v=WK99kBS1AfE)
* Titanium rings had at least 2 hull penetrators
  * Penetrators fitted by ports for MacArtney SubConn ethernet and (unconfirmed) coaxial cabling
    * At least one penetrator is fitted with the SubConn DBH13F Power Ethernet 13-pin circular connector  

#### Viewport
* Original
  * 380-mm-diameter (21”) acrylic viewport
  * Fabricated by Hydrospace Group, though listed as 23" dome. Possibly indicator that two domes have been used. [Facebook post](https://www.facebook.com/OceanGateInc/posts/pfbid031t4h6E88fjU3NP5DLq7mZM3RG6Y7RPPnsp12kGHhacuSakTUicHzgNKtYGUckEv5l?__cft__[0]=AZXEPHTiC6StJRnuULAi0qr3uQj0MS0JeFwcdexD-o5FzEzrpXQUPDbwJK_tCJ6_ITDu_14CRsAHhAjHRNKj2m6I9qHGg6EBd1DHc-6RQNnwJny84_km24GjCT5A8wRjEZw&__tn__=%2CO%2CP-R)
  * Manufactured and fitted in 2017, making this viewport likely the same viewport reviewed by David Lochridge in 2018.
  * The original viewport may have been replaced at the time of the 2020 hull upgrade.
* Revised Viewport? (Unconfirmed)
  * Around 2020, the viewport's bolts seem to have undergone a slight visual change.
  * (Hearsay) It is claimed by at least one person affiliated with OceanGate that the original viewport was replaced.
  * Manufacturer of an alleged new viewport is unknown, but could possibly be Heinz Fritz, which supplied the new acrylic dome of the Cyclops I in 2020. [Archived Tweet](https://web.archive.org/web/20230620034837/https://twitter.com/OceanGateExped/status/1286405823695138819)
* ~~(Unconfirmed) In a review of the 2021 Titanic expedition, Stockton claims that the viewport is concave so a viewer could put their head inside it. This seems to conflict with pictures of the Hydrospace viewport which has a flat inner surface?~~
  * [~~Video~~](https://youtu.be/nIQxssTuWCw?t=810)

#### Ballast System
* Ballast control include pneumatic and hand-pump failsafes.
* Ballast also releases if occupants rock the ship, or, a pneumatic pump can be activated to knock the weights free.
* Lines securing the ballasts are designed to fall apart after 24 hours to automatically surface the sub.
* Drop weight controller
  * Upgraded in 2021. [Instagram post (Removed)](https://www.instagram.com/p/CWYo5FhsS2Q/)
    * This upgrade may coincide with the addition of steel shot bags as drop weights and moving the steel pipes out of the drop tray to the Titan's sides instead. 
  * Weight dropped by actuator.
* Variable Ballast Tanks
  * Designed to be used if the actuator fails.
  * Buoyancy bag located at the top of the Titan, straddling the pressure hull. [Instagram](https://www.instagram.com/p/B--ds_tls29/)
  * The bag is inflated by a black high pressure tank located in the tail. [Explanation on Youtube](https://youtu.be/uD5SUDFE6CA?t=1249)
* Valves for drop cylinder weight and HPA tank are made by Autoclave Engineers.

#### Fairing
* Glass fiber shell composite pieces for free-flooding outer shell.
* Probably manufactured by Sunbacker. [Company portfolio](https://sunbacker.com/oceanographic/) [Archived](https://archive.is/yP5Bw)
* Bolted to titanium rings.
* Empty space is filled with blocks of syntactic foam.

## Systems at the time of the incident
### Power
* Ictineu Pressure-tolerant Li-Po Battery
  * [Instagram post](https://www.instagram.com/p/Bgo79HIFCWn/)

### Propulsion
* Innerspace Model 1002 series electric thrusters
  * 2 vertical, 2 horizontal
  * [Innerspace product page](https://innerspacethrusters.com/products/electric/model-1002-series/)

### Life Support 
* 96 hours for a crew of 5
* Equipment unknown
* Oxygen Supply
  * At least 4 cylinders of what appear to be oxygen (green tanks) running parallel to the hull under the floor platform. This may or may not be part of the life support system. [Instagram post](https://www.instagram.com/p/Bdimnn-lwVl/)
* CO2 Scrubber
  * Utilizes soda lime, and/or SodaSorb.
  * "One of the many essential life support systems on a dive is a CO2 (carbon dioxide) scrubber. Our scrubbing system for Cyclops 1 and Titan contains soda lime. Soda lime are white granules that contain a mixture of calcium hydroxide (~75%) and sodium hydroxide (3%) with a precise amount of water moisture and binding agents. They absorb CO2 from the air via an exothermic, water facilitated, base catalyzed chemical reaction. The fans in our subs circulate air throughout the interior so all breathing air is consistently brought to the scrubber unit and cleaned of CO2." [Facebook post (Removed)](https://www.facebook.com/OceanGateInc/videos/245982903111389) [(Archived Copy)](https://i.imgur.com/pTIbvpS.png)
    * A tupperware tub containing loose sodasorb with fan mounted to a lid can be seen when the aft panel is opened, and is also seen in the main sitting area of the vessel during an [interview](https://youtu.be/y9DuM_gzaOQ?t=30).
  * "So we have two systems. One is a thing called Sodasorb, which is calcium hydroxide. [...] If that system fails—'cause it does require a battery—we have lithium-hydroxide blankets, which are used in the mine industry mostly, and also in submersibles. And you just hang 'em, and they scrub the carbon dioxide just from ambient flow." [CBS Interview with Stockton Rush](https://www.cbsnews.com/news/titanic-submersible-interview-transcript-with-oceangate-ceo-stockton-rush/)
    * Curtains are likely [ExtendAir® Curtains](https://www.microporeusa.com/mine-safety/) or similar model. The metal container (OM-0910K model) is seen in some photos, and what appears to be the metallic bag without metal container is seen in others (OM-0610K model).
* Air Sensors
  * Exact model or implementation unknown. A previous OceanGate engineer has said that there are sensors for O2, CO2, pressure, temperature, and humidity. 
* Water Sensors
  * Exact model or implementation unknown.

### External component controls
* The "Birns Junction Box" (aka J-Box)
* Birns 77-pin connectors used to connect signals throughout the hull.
  * [Instagram post](https://www.instagram.com/p/CAqPDrKJGCW/)
  * "This Birns Junction Box (or J-Box for short) has been designs by our Engineering team to connect the brain of Titan to the external electrical components on the submersible. The J-box is named after the Birns 77-pin connector which is utilized to connect all the signals through the hull; the connector itself we named after the company who created it (BIRNS, Inc.). The unit acts like a mission control center, sending out necessary information for each party involved to opera..." (Facebook. [Archived](https://i.imgur.com/8IwK8Yf.png)).

### Fire Safety
* Pocket Smoke Mask by HKMASK Safety Ltd.

### Internal Computer Systems
* Inside the aft dome
  * Three Nuvo-5000LP or very similar fanless PCs by Neousys Tech. [Neousys Product page](https://www.neousys-tech.com/en/product/product-lines/industrial-computers/fanless-industrial-pc/nuvo-5000lp)
    * Controls media, cameras, and hull monitoring system
    * Main SCADA control panel likely created with Generic Logic GLG Toolkit for monitoring battery, power systems, etc.
      * OceanGate is listed as a customer on the [Generic Logic website](https://www.genlogic.com/generic_logic.html).
      * The GLG Toolkit avianics widget exactly matches the widget seen in [YouTube video](https://www.youtube.com/watch?v=BL2aCMONLws) and various other footage from inside the Titan.
  * Netgear ProSafe 16-Port Gigabit Switch GS116xx series.
* Two [MageDok screens](http://www.magedok.com/) - exact type unclear - one on the left and one on the right side inside (the small ones)
 
### "Control Pod" [sic]
#### Glass Sphere
* Two deep sea glass instrument spheres with orange shells contain motor controllers, switches and relays. Positioned in the aft, outside of the pressure vessel hull.
* Filled with oil [YouTube video](https://www.youtube.com/watch?v=uD5SUDFE6CA&t=1132s)
* Responsible for controlling the movement of the Titan.
* A spare is also kept on hand.
* The control pod units had been in use for 3 years as of the 2023 expedition.

#### Pod Contents
* Small size 5-port RJ45 ethernet switch module. May be similar to this model. [AliExpress Product page](https://www.aliexpress.com/item/32918204913.html)

### Interior Lighting
* IllumaGrip Lighted Assist Handle
  * [Campingworld product page](https://www.campingworld.com/illumagrip-lighted-assist-handle---20-inch-65915.html)

### Structural Monitoring
* "Real time health monitoring" system, though exact implementation is not confirmed.
  * [Patent](https://patents.google.com/patent/US11119071B1/en?q=(%22stockton+rush%22)&oq=%22stockton+rush%22)
  * "This system is based on nine separate acoustic sensors and 18 strain gauges to measure all mechanical loading of the hull using both passive and active measurements to compare with historical performance at depth." ([Marine Technology Society Journal](https://mtsociety.memberclicks.net/assets/docs/Journals/MTS52-5-WEB.pdf))

### Navigation & Communication

#### CB Radio
* Uniden Bearcat 9xx or 8xx series CB radio. Seen in footage of components hidden behind panel in aft side dome.
  * Used for communications when near surface
  * Attached to Uniden BC9xx model Wireless Microphone

#### (Unconfirmed) Tracking transducer
* Kongsberg mentioned in [https://youtu.be/RAncVNaw5N0?t=407](https://youtu.be/RAncVNaw5N0?t=407)
  * Also pictured in a 2019 dive of the Titan in the Bahamas. [Angari Expedition page](https://angari.org/expedition-24/)
  * Not sure if also included on the dive of the 2023 incident.

#### USBL
* Removed at time of incident
  * Previously used systems by Sonardyne (Sonardyne Gyro Ranger 2 USBL and AvTrak 6) are removed, most likely replaced with equipment from ixBlue or Teledyne.
    * "We can confirm no Sonardyne equipment was in use or is fitted for the current mission." [Sonardyne article](https://www.sonardyne.com/case-studies/surveying-the-titanic-with-ranger-2-and-avtrak-6/)
* Most in use at time of incident
  * iXBlue Posidonia USBL position system
    * [iXBlue product page](https://www.ixblue.com/store/posidonia/)
    * Posidonia uses advanced acoustic modulation, as well as digital signal processing technology and operates in the low frequency band for deep sea tracking operations. To communicate with Posidonia during each dive, Titan is equipped with iXblue’s MT8 compact low-frequency transponder.
    * Unsure whether this or the Benthos gear was used in 2023 expedition
  * iXBlue MT8 compact low-frequency transponder
    * [Manual](https://www.manualslib.com/products/Ixblue-Gaps-Mt8-11014294.html)
    * Unsure whether this or the Benthos gear was used in 2023 expedition
  * Teledyne Benthos USBL DAT (Directional Acoustic Transponder)
    * Probably rehoused
    * [EcoMagazine article](https://www.ecomagazine.com/news/industry/teledyne-marine-technology-utilized-extensively-onboard-oceangate-s-titan-manned-submersible)
     
#### INS
* iXBlue PHINS 6000 Inertial Navigation System (INS)
  * Phins Subsea is a subsea inertial navigation system providing position, true heading, attitude, speed, depth, and heave. Its high-accuracy inertial measurement unit is coupled with an embedded digital signal processor that runs an advanced Kalman filter. Phins Subsea can be pre-assembled and pre-calibrated with a doppler velocity log version, making the system easy to install and ready to use for more precise navigation.

#### SONAR
* Teledyne BlueView M900 Mk2 2D collision avoidance SONAR (rehoused)
  * [Product page/](http://www.teledynemarine.com/blueview/)
  * Likely with titanium housing rated to 6000m
* Teledyne BlueView BV5000 3D imaging SONAR
  *  [YouTube video](https://www.youtube.com/watch?app=desktop&v=RCa3qhnF9yQ)

#### DVL
* Teledyne 6000m RDI phased array Pioneer DVL, with XRT extended tracking
  * For underwater vehicles, the bottom tracking feature can be used as an important component in the navigation systems. In this case the velocity of the vehicle is combined with an initial position fix, compass or gyro heading, and data from the acceleration sensor. The sensor suite is combined (typically by use of a Kalman filter) to estimate the position of the vehicle. This may help to navigate submarines, autonomous, and remotely operated underwater vehicles.
  * [EcoMagazine article](https://www.ecomagazine.com/news/industry/teledyne-marine-technology-utilized-extensively-onboard-oceangate-s-titan-manned-submersible)
  * [Teledyne press release](http://www.teledynemarine.com/press-releases/OceanGate)
  * [Teledyne product page](http://www.teledynemarine.com/pioneer-doppler-velocity-logs?ProductLineID=34)

#### Other Electronics
* Teledyne Benthos ATM-90x Series acoustic modem
  * Possibly an ATM-903
  * Modified to by Teledyne to send/receive custom text strings as well as beacon position [https://www.youtube.com/watch?app=desktop&v=RCa3qhnF9yQ](https://www.youtube.com/watch?app=desktop&v=RCa3qhnF9yQ)
  * Provides real time text communication 6km range of surface. [Instagram post](https://www.instagram.com/p/BxEYwIOhH8G/)
   
* CTD / Sound Velocity
  * Valeport Midas SVX2
  * [LinkedIn post](https://www.linkedin.com/posts/phill-harvey-financedirector-oceanographic-watermonitoring-manufacturing_titan-activity-6821356543955496960-jmkv/)

* Axis Communications F34 Network Camera System
  * Seen in https://www.youtube.com/watch?v=uD5SUDFE6CA&t=1417s

* Misc Cabling
  * MacArtney SubConn connectors and cables. [Facebook Post](https://www.facebook.com/permalink.php?story_fbid=4291543250961322&id=151180704997618&paipv=0&eav=AfbPK7dWSq2pW-IFw-phZOUN5rjtMTCrWxBreinduXqrhGJctyUOunuNDi1TfL9WUtw&_rdr)  

* Power
  * Jameco Dual Channel power supply. Model similar to [Jameco Product Page](https://www.jameco.com/z/HY3003D-2-R-Jameco-BenchPro-180W-Dual-Output-Benchtop-Power-Supply-30-Volt-3-Amps-per-Channel_211693.html)
    * Unsure if this was ever on board the ship. It's seen a few times when the Titan is on land. May have just been used for testing.

### Mobility/Thruster Control
* Logitech F710 Wireless Game Pad

### External Lighting
* 6 Deep Sea Power & Lights LED Sealites, 60,000 lumens total output
  * SubC Imaging Aquorea LEDs

### External Cameras
* SubC Imaging iCam Rayfin 4K camera
  * Includes built-in depth, tilt and roll sensors, and can store NMEA sensor data.
* 3 AXIS cameras [AXIS F34 Network Camera](https://www.axis.com/products/axis-f34-surveillance-system/support) - one on IP 192.168.0.90

### Scanner
* 2G Robotics Dynamic Underwater Laser Scanner (ULS-500 PRO)
  * Now called the "Insight Pro".
  * "The Insight Pro is a long-range laser scanner designed for 3D modelling over large areas from dynamic and static platforms. Its proven design has been deployed since 2013 and has modelled over 10,000 km of subsea pipelines, seabed and subsea structures. Insight Pro has been integrated into countless AUVs and ROVs, including a control interface compatible with most standard vehicle navigation systems. Real-time data processing allows for the development of machine learning applications such as fault detection and pipeline tracking"
  * [Product page](https://www.subsea-tech.com/2g-robotics/)
 
### Sampling
* General Oceanics Water Sampler
  * Unsure of exact model, but similar to these: [Product Page](https://www.generaloceanics.com/rov-niskin-bottles/)
  * May not have been deployed at time of incident, but has seen mounted to the starboard side of the Titan before.
  
## OceanGate Launch and Recovery System (LARS) Construction
* Aluminum platform manufactured by Everest Marine. [Article](https://www.geekwire.com/2018/oceangate-everest-marine-finish-construction-titanic-subs-launch-pad/)


## Development and Release Process
* Onshape for product data management
  * [Engineering.com article](https://www.engineering.com/story/is-pdm-the-unnecessary-evil)

## Past Dives & Tests
This section has been moved to [a new page](https://ocean-archives.github.io/timeline.html)

## Other Documents
* [Release of liability agreement](https://dam.tmz.com/document/b1/o/2023/06/22/b106a285e72448c3a7aef771402ffff0.pdf)
* [OceanGate Inc v. Lochridge (2:18-cv-01083)](https://www.courtlistener.com/docket/7506826/oceangate-inc-v-lochridge/)
* [Marine transportation safety investigation M23A0169](https://www.tsb.gc.ca/eng/enquetes-investigations/marine/2023/m23a0169/m23a0169.html)

------------------

## Author

Repository is created and maintained by A. Walraven, ayalan@gmail.com. 

### Other Contributors
* Nayuki
* 299WF
* [tricoos](https://github.com/tricoos)

## Page Change Log
* [Change Log](https://github.com/ocean-archives/ocean-archives.github.io/commits/main/README.md)

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-W5PZZJPTKX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-W5PZZJPTKX');
</script>

