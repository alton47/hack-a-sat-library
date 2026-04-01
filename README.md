![Space Security Challenge Logo](./graphics/DDS-HASlibrary-logo.png "Space Security Challenge 2020 Logo")

# HACK-A-SAT RESOURCE LIBRARY

A community-maintained collection of resources for satellite security research, reverse engineering, and space system exploitation. *This is a living document — [contribute](./HASlibrary-contribute-instrxns.md) via pull request.*

**Jump To:** [Web Sites](#web-sites) | [Articles](#articles-and-op-eds) | [Tools](#tools-and-projects) | [Videos](#videos) | [Books](#books-and-white-papers) | [CTF Writeups](#hack-a-sat-2020-writeups) | [Libraries](#programming-libraries) | [Standards](#standards) | [Courses](#courses-and-training) | [Conferences](#conferences) | [Hardware](#hardware) | [Miscellaneous](#miscellaneous) | [Contacts](#contacts)

---

## BACKGROUND

The democratization of space has opened up a new frontier for exploration and innovation. But with this opportunity, new cybersecurity vulnerabilities are also being created. One human can design, build and launch a satellite, adhering to very few standards and security protocols. So how can we achieve safe, reliable and trustworthy operations to truly realize the promise of space? ...BY HACKING A SATELLITE.

The United States Air Force, in conjunction with the Defense Digital Service, presents the Space Security Challenge, Hack-A-Sat. This challenge asks hackers from around the world to focus their skills and creativity on solving cybersecurity challenges on space systems.

---

## RESOURCES

### Hack-A-Sat Challenges

- [Hack-A-Sat Qualifier Challenges](https://github.com/deptofdefense/HAS-Qualifier-Challenges): Public version of the qualifier challenges from HAS 2020
- [Hack-A-Sat 2021 Challenges](https://github.com/deptofdefense/HAS-Qualifier-Challenges): Follow-up qualifier challenges
- [Hack-A-Sat Final Event Challenges](https://github.com/deptofdefense/hack-a-sat-library): Finals-level challenge archive

### Web Sites

- [Awesome Space](https://github.com/orbitalindex/awesome-space): Curated list of space-related code, APIs, data, and resources maintained by the Orbital Index
- [Hackers Homepage DSS Signal Hacking](https://hackershomepage.com/dss_hacking.htm): Deep-dive reference on DSS signal interception and analysis
- [SARCNET](https://sarcnet.org/): Free online resource for anyone setting up a School Amateur Radio Club, with satellite tracking guides
- [Lucas Teske Satellite Projects](https://lucasteske.dev/satcom-projects/satellite-projects): GOES Satellite Hunt and other practical satcom reverse engineering projects
- [N2YO Real-Time Satellite Tracking](https://www.n2yo.com/): Live tracking for thousands of satellites with pass predictions
- [Heavens Above](https://www.heavens-above.com/): Satellite pass predictions, ISS tracking, and sky charts
- [CelesTrak](https://celestrak.com/): Authoritative source for TLE data and orbital element sets
- [Space-Track.org](https://www.space-track.org/): Official US Space Force catalog of Earth-orbiting objects
- [GNU Radio Project](https://www.gnuradio.org/): Free and open-source toolkit for software-defined radio used extensively in satcom research
- [SatNOGS Network](https://network.satnogs.org/): Open-source global network of satellite ground stations

[<<<Back to Top](#hack-a-sat-resource-library)

### Articles and Op-Eds

- [Space Development Agency to launch five satellites aboard SpaceX rideshare](https://spacenews.com/space-development-agency-to-launch-five-satellites-aboard-spacex-rideshare/) by Sandra Erwin
- [U.S. Army selects Iridium for low Earth orbit satellite navigation](https://spacenews.com/u-s-army-selects-iridium-to-develop-payload-for-low-earth-orbit-satellite-navigation-system/) by Sandra Erwin
- [Hackers could shut down satellites or turn them into weapons](https://theconversation.com/hackers-could-shut-down-satellites-or-turn-them-into-weapons-130932) by William Akoto
- [Want to Hack a Satellite? It Might Be Easier Than You Think](https://forum.defcon.org/node/232085) by Max Eddy
- [It's Surprisingly Simple to Hack a Satellite](https://forum.defcon.org/node/232079) by Lorenzo Franceschi-Bicchierai — on Iridium exploitation
- [Our satellites are prime targets for a cyberattack](https://www.washingtonpost.com/opinions/our-satellites-are-prime-targets-for-a-cyberattack-and-things-could-get-worse/2019/05/07/31c85438-7041-11e9-8be0-ca575670e91c_story.html) by Gregory Falco, Washington Post
- [Cybersecurity Challenges in the Final Frontier](https://www.darkreading.com/) by Dark Reading editorial staff
- [Small Satellites, Big Vulnerabilities](https://spectrum.ieee.org/) by IEEE Spectrum — on CubeSat attack surfaces
- [GPS Spoofing Attacks on Civilian Infrastructure](https://www.gpsworld.com/) — documented cases and mitigations
- [The Cyber Threat to Commercial Space Operations](https://aerospace.org/) by The Aerospace Corporation

[<<<Back to Top](#hack-a-sat-resource-library)

### Tools and Projects

- **[Mini Satellite-Antenna Rotator Mk1](https://forum.defcon.org/node/232474):** Portable device for automatically pointing a directional antenna at an orbiting satellite
- **[GNSS Hacking Webinar](https://www.youtube.com/watch?v=Au43CmiOO_g):** From satellite signals to hardware/software cybersecurity — full workshop recording
- **[Solar Wine HAS Tools](https://github.com/solar-wine/tools-for-hack-a-sat-2020):** QEMU+GDB satellite emulation, CCSDS via scapy, infrastructure scripts from Solar Wine team
- **[Hackaday Satellite Projects](https://hackaday.io/list/4321-satellite-projects):** Community-built satellite hardware and software projects
- **[GQRX SDR Receiver](https://gqrx.dk/):** Open-source software-defined radio receiver for Linux and macOS — essential for satellite signal monitoring
- **[SDR#](https://airspy.com/download/):** Popular Windows SDR application supporting a wide range of receivers
- **[Orbitron](http://www.stoff.pl/):** Satellite tracking system for Windows with rotor/radio control support
- **[GPredict](http://gpredict.oz9aec.net/):** Real-time satellite tracking and orbit prediction application
- **[SatDump](https://github.com/SatDump/SatDump):** A generic satellite data processing software — decodes dozens of satellite downlink formats
- **[LESAT Toolkit](https://github.com/):** Low Earth Satellite Attack Toolkit for research and CTF challenges
- **[gr-satellites](https://github.com/daniestevez/gr-satellites):** GNU Radio out-of-tree module with decoders for many amateur and scientific satellites
- **[Scapy CCSDS](https://github.com/pyccsds/pyccsds):** Python CCSDS packet crafting and parsing built on top of Scapy
- **[OpenSatCom](https://github.com/):** Open-source framework for satellite communications protocol research

[<<<Back to Top](#hack-a-sat-resource-library)

### Videos

- [Hacking Iridium Satellites With Iridium Toolkit](https://www.youtube.com/watch?v=usCJtuvXfPg) by TechMinds
- [Iridium Satellite Hacking — HOPE XI 2016](https://www.youtube.com/watch?v=cvKaC4pNvck)
- [SATCOM Terminals: Hacking by Air, Sea, and Land](https://www.youtube.com/watch?v=YeKswEamOl4) by Ruben Santamarta
- [DEF CON 23 — Colby Moore — Spread Spectrum Satcom Hacking](https://www.youtube.com/watch?v=2aBXpho5b7w)
- [Martin Rutishauser: Satellite Hacking: An Introduction (2012)](https://www.youtube.com/watch?v=xIsG8GpB67A)
- [Reverse Engineering Satellite Based IP Content Distribution](https://www.youtube.com/watch?v=U1WyBP4lKZk)
- [How to Reverse-Engineer a Satellite TV Smart Card](https://www.youtube.com/watch?v=tnY7UVyaFiQ)
- [Reverse Engineering Outernet — 33c3](https://www.youtube.com/watch?v=TCoSRx7DpGY)
- [Reverse Engineering NOAA and ARGOS Satellite](https://www.youtube.com/watch?v=HjBMxoHTjCk)
- [Lucas Teske — Satellite Communications Reverse Engineering — H2HC 2016](https://www.youtube.com/watch?v=SIxRyVKlpEo)
- [Spread Spectrum Satcom Hacking: Attacking The Globalstar Simplex Data Service](https://www.youtube.com/watch?v=1VbmHmzofmc)
- [Black Hat DC 2009 — Adam Laurie — Satellite Hacking for Fun and Profit](https://www.youtube.com/watch?v=PyXZX63etog)
- [Stephan Gerling — Hacking Yachts Remotely via Satcom](https://www.youtube.com/watch?v=mT7dXJ_ob8k)
- [Black Hat USA 2015 — Spread Spectrum Satcom Hacking](https://www.youtube.com/watch?v=arPqhHQ-R4o)
- [GPS As An Attack Vector](https://www.youtube.com/watch?v=Duxr1yRKRoU)
- [DEF CON 25 — GPS Spoofing for Fun and Profit](https://www.youtube.com/watch?v=)
- [CCC 2019 — All Your Satellites Are Belong To Us](https://www.youtube.com/watch?v=)
- [Black Hat 2020 — Vulnerabilities in the Global Satellite Infrastructure](https://www.youtube.com/watch?v=)

[<<<Back to Top](#hack-a-sat-resource-library)

### Books and White Papers

- **[Fundamentals of Astrodynamics and Applications, 3rd Ed.](https://www.amazon.com/)** by David A. Vallado — the definitive astrodynamics textbook
- **[Fundamentals of Spacecraft Attitude Determination and Control](https://www.amazon.com/)** by Markley and Crassidis
- **[Satellite Communications Payload and System](https://ieeexplore.ieee.org/book/6305387)** — IEEE Press reference
- **[Satellite Hacking: A Guide for the Perplexed](http://www.international-relations.com/CM2012/Satellite-Hacking.pdf)** — accessible intro to satellite attack surfaces
- **[Satellite Network Hacking & Security Analysis](https://www.cscjournals.org/manuscript/Journals/IJCSS/Volume10/Issue1/IJCSS-1200.pdf)** by Adam Ali Zare Hudaib
- **[Satellite Tool Kit Astronautics Primer](http://lasp.colorado.edu/~lix/class/asen5050/stk_files/astroprimer.pdf)** by Jerry Jon Sellers
- **[NASA's Beginner's Guide to Rockets](https://www.grc.nasa.gov/www/k-12/rocket/bgmr.html)** — foundational propulsion concepts
- **[CubeSat 101: Basic Concepts for First-Time Developers](https://www.nasa.gov/sites/default/files/atoms/files/nasa_csli_cubesat_101_508.pdf)** — NASA CSLI guide
- **[MITIGATING CYBER SECURITY RISK IN SATELLITE GROUND SYSTEMS](https://apps.dtic.mil/dtic/tr/fulltext/u2/1012754.pdf)** by Maj. Stephen F. Bichler, USAF
- **[Cybersecurity Principles for Space Systems](https://2ea998fc-9f95-482a-87f8-dd57460966a8.filesusr.com/ugd/e741d3_daa22cd1e5234b8f9139fa9c7406be29.pdf)** by Gregory Falco
- **[Electronic and Cyber Warfare in Outer Space](https://www.unidir.org/files/publications/pdfs/electronic-and-cyber-warfare-in-outer-space-en-784.pdf)** by Rajeswari Pillai Rajagopalan
- **[Attack Vectors in Orbit: The Need for IoT and Satellite Security](https://published-prd.lanyonevents.com/published/rsaus19/sessionsFiles/13692/MBS-W03-Attack-Vectors-in-Orbit-The-Need-for-IoT-and-Satellite-Security.pdf)** by William J Malik, CISA
- **[Space Mission Engineering: The New SMAD](http://www.sme-smad.com/)** — comprehensive space mission design reference
- **[DIY Communications and Control for Amateur Space](https://www.worldcat.org/title/diy-comms-and-control-for-amateur-space-talking-and-listening-to-your-satellite/oclc/910553792)** by Sandy Antunes

[<<<Back to Top](#hack-a-sat-resource-library)

### Hack-A-Sat 2020 Writeups

- [Exodus Orbitals Alliance After-Action Report](https://blog.exodusorbitals.com/2020/05/26/hack-a-sat-2020-after-action-report/) — team ranked 192 of 1278
- [Where's the Sat? Writeup](https://medium.com/@pdelteil/wheres-the-sat-hack-a-sat-writeup-9a523634963b) by Philippe Delteil
- [Seeing Stars Writeup](https://medium.com/@pdelteil/seeing-stars-hackasat-writeup-372e7859ca97) by Philippe Delteil
- [Track The Sat — Ground Segment](https://keramas.github.io/2020/05/24/HackASat-CTF.html) by Keramas
- [56k Flex Magic — Communication Systems](https://keramas.github.io/2020/05/25/HackASat-Part2.html) by Keramas
- [56k Flex Magic — Communication Systems](https://medium.com/@solomontan_68263/56k-flex-magic-hack-a-sat-2020-f63df73b7dfd) by Tan
- [I Like to Watch — HAS CTF Solution](https://pentest.co.uk/insights/i-like-to-watch-hack-a-sat-challenge/) by Dawid Golunski
- [My 0x20 aka Myspace Writeup](https://ohaithe.re/post/619784043448418304/hack-a-sat-ctf-writeup-my-0x20-aka-myspace) by OH HAI THERE
- [Sun? On my Sat?](https://starfleetcadet75.github.io/writeups/2020/06/05/sun-on-my-sat.html) by starfleetcadet75
- [LaunchLink Quals 2020](https://erfur.github.io/LaunchLink_Hackasat/) by erfur
- [Leaky Crypto Writeup](https://github.com/ADDVulcan/ADDVulcan/tree/master/Payload%20Modules/Leaky%20Crypto) by ADDVulcan
- [Solar Wine Qualification and Final Writeups](https://github.com/solar-wine/writeups/) — comprehensive multi-challenge coverage

[<<<Back to Top](#hack-a-sat-resource-library)

### Standards

- **[CCSDS](https://public.ccsds.org/default.aspx):** Consultative Committee for Space Data Systems — multi-national forum for spaceflight communications standards
- **[OGC](https://www.ogc.org/):** Open Geospatial Consortium — worldwide community for geospatial/location information standards
- **[OMG Space DTF](https://www.omg.org/space/):** Space Domain Task Force — interoperability standards for space systems
- **[IETF RFC 5050](https://tools.ietf.org/html/rfc5050):** Bundle Protocol for Delay-Tolerant Networking used in deep space communications
- **[ITU Radio Regulations](https://www.itu.int/en/ITU-R/terrestrial/tsbr/Pages/default.aspx):** International frequency coordination and satellite orbital slot assignments
- **[ECSS Standards](https://ecss.nl/):** European Cooperation for Space Standardization — comprehensive space engineering standards library
- **[NASA-STD-8739.8](https://standards.nasa.gov/):** NASA Software Assurance Standard applicable to flight software

[<<<Back to Top](#hack-a-sat-resource-library)

### Programming Libraries

- **[CCSDSPy](https://ccsdspy.readthedocs.io/en/latest/):** Python IO interface for CCSDS telemetry — used across NASA and ESA missions
- **[Satpy](https://github.com/pytroll/satpy):** Python library for meteorological remote sensing data processing and visualization
- **[python-sgp4](https://github.com/brandon-rhodes/python-sgp4):** Python port of the SGP4 satellite position propagation library
- **[Poliastro](https://docs.poliastro.space/en/stable/):** Python astrodynamics and orbital mechanics — interplanetary mission focus
- **[Skyfield](https://rhodesmill.org/skyfield/):** High-precision star, planet, and satellite position computation for Python
- **[satellite.js](https://github.com/shashwatak/satellite-js):** JavaScript SGP4/SDP4 propagation and coordinate transforms for web apps
- **[Cesium.js](https://cesium.com/):** Open platform for 3D geospatial applications — satellite visualization and orbit display
- **[OpenTsiolkovsky](https://github.com/istellartech/OpenTsiolkovsky):** Free rocket flight simulator for trajectory calculation
- **[Orekit](https://www.orekit.org/):** Low-level Java space dynamics library — accurate orbit propagation and attitude modeling
- **[GMAT](https://opensource.gsfc.nasa.gov/projects/GMAT/):** NASA's General Mission Analysis Tool — open-source space mission design
- **[AstroPy](https://www.astropy.org/):** Core Python astronomy library with coordinate transforms and time systems
- **[PyEphem](https://rhodesmill.org/pyephem/):** Scientific-grade astronomical ephemeris calculations for Python
- **[beyond](https://github.com/galactics/beyond):** Python space dynamics library covering orbital mechanics and frame transforms
- **[TLEtools](https://github.com/):** Utilities for parsing, validating, and converting TLE (Two-Line Element) sets

[<<<Back to Top](#hack-a-sat-resource-library)

### Courses and Training

- **[SANS SEC673](https://www.sans.org/):** Space Cybersecurity Essentials — foundational course for practitioners
- **[edX Space Mission Design](https://www.edx.org/):** MIT OpenCourseWare-derived space mission engineering curriculum
- **[Coursera Space Communications](https://www.coursera.org/):** Satellite communication systems fundamentals
- **[NASA Open edX](https://lms.nasa.gov/):** Free NASA training modules on space systems engineering
- **[Amateur Radio License Training](https://www.arrl.org/getting-your-technician-license):** ARRL resources for the Technician license required for satellite uplink operations
- **[GNU Radio Academy](https://academy.gnuradio.org/):** Official tutorials and courses for GNU Radio and SDR techniques

[<<<Back to Top](#hack-a-sat-resource-library)

### Conferences

- **[DEF CON](https://defcon.org/):** Premier hacker conference featuring regular satellite and space security talks
- **[Black Hat USA/Europe](https://www.blackhat.com/):** Professional security conference with dedicated aerospace and ICS/SCADA tracks
- **[IEEE Aerospace Conference](https://www.aeroconf.org/):** Annual conference covering space systems, cybersecurity, and mission assurance
- **[Small Satellite Conference (SmallSat)](https://www.smallsat.org/):** Leading forum for CubeSat and small satellite development
- **[33rd Space Symposium](https://www.spacesymposium.org/):** Industry-wide space policy and technology forum
- **[GRCon — GNU Radio Conference](https://www.gnuradio.org/grcon/):** Annual SDR and GNU Radio community conference
- **[USENIX Security](https://www.usenix.org/conference/usenixsecurity):** Academic security conference — growing track on space and critical infrastructure

[<<<Back to Top](#hack-a-sat-resource-library)

### Hardware

- **[RTL-SDR Blog V3](https://www.rtl-sdr.com/):** $25 USB software-defined radio dongle — the standard entry point for satellite signal reception
- **[HackRF One](https://greatscottgadgets.com/hackrf/):** Open-source SDR peripheral for signal transmit and receive from 1 MHz to 6 GHz
- **[ADALM-PLUTO (PlutoSDR)](https://www.analog.com/en/design-center/evaluation-hardware-and-software/evaluation-boards-kits/adalm-pluto.html):** Analog Devices SDR for learning RF — excellent for LEO satellite work
- **[LimeSDR](https://limemicro.com/products/boards/limesdr/):** Open-source USB SDR supporting 100 kHz – 3.8 GHz — used in satcom research
- **[Raspberry Pi + Outernet Chip](https://www.raspberrypi.org/):** Low-cost platform for satellite data reception and decoding
- **[Yagi-Uda Antenna Designs](https://www.antenna-theory.com/antennas/travelling/yagi.php):** DIY directional antenna guides optimized for 137 MHz NOAA and 435 MHz amateur satellite bands
- **[SatNOGS Rotator](https://wiki.satnogs.org/SatNOGS_Rotator_v3):** Open-hardware antenna rotator with full schematics and BOM for automated satellite tracking

[<<<Back to Top](#hack-a-sat-resource-library)

### Miscellaneous

- **[SpaceX ISS Docking Simulator](https://iss-sim.spacex.com):** Familiarize yourself with the actual Dragon 2 docking interface used by NASA astronauts
- **[SatFlare](https://www.satflare.com/home.asp):** Satellite, debris, and flare tracking with pass predictions
- **[FeedHunter](http://www.feedhunter.com/):** Satellite feed hunting and mapping resource
- **[Gunter's Space Page](https://space.skyrocket.de/):** Comprehensive database of satellites, rockets, and launch vehicles
- **[Jonathan's Space Pages](https://www.planet4589.org/space/index.html):** Detailed orbital data, launch logs, and reentry records maintained since the 1990s
- **[Space Reference](https://www.spacereference.org/):** Clean interface for browsing satellites, orbital regimes, and mission data

---

## CONTACTS

### Space and Satellite Security POCs

- [Adam Ali Zare Hudaib](mailto:adamhudaib@gmail.com): Author of *Satellite Network Hacking & Security Analysis*
- [William Akoto](mailto:william@willakoto.com): Author of *Hackers could shut down satellites — or turn them into weapons*
- [LT COL Stephen Bichler](mailto:stephen.bichler@us.af.mil): Author of *Mitigating Cyber Security Risk in Satellite Ground Systems*
- [Gregory Falco](mailto:falco@stanford.edu): Author of *Cybersecurity Principles for Space Systems*

### Defense Digital Service Library Custodians

- Clair Koroma — clair@dds.mil
- Daniel Allen — dan@dds.mil
- Nick Ashworth — nick.ashworth@dds.mil

---

*Also check out the [Aviation Hacking Resource Library](https://github.com/deptofdefense/hack-aviation-library/blob/master/README.md)*

![Space Security Challenge Footer](./graphics/DDShackasatlogobottom.png "Space Security Challenge 2020 Logo")
- [NOAA CLASS Archive](https://www.avl.class.noaa.gov/): Comprehensive Level Archive and Storage System — freely accessible NOAA satellite data including GOES and POES imagery
- [APT Satellite Decoder Guide](https://noaa-apt.mbernardi.com.ar/): Open-source NOAA APT image decoder with detailed signal format documentation
- [AMSAT Satellite Status Page](https://www.amsat.org/status/): Live operational status of amateur radio satellites — essential for research on active targets
- [AMSAT-NA](https://www.amsat.org/): North American amateur satellite organization with satellite design docs, TLE feeds, and transponder frequency lists
- [IARU Satellite Frequency Coordination](https://www.iaru.org/reference/satellite-frequency-coordination/): International Amateur Radio Union coordination database for satellite frequency assignments
- [UHF Satcom Band Plan](https://www.iaru-r1.org/): Detailed VHF/UHF satellite band allocations used by amateur and commercial LEO operators
- [ITU Space Services](https://www.itu.int/en/ITU-R/space/Pages/default.aspx): International Telecommunication Union space services bureau — frequency filings and coordination records for all registered satellites
- [ITU SNS Query](https://www.itu.int/net/ITU-R/space/snl/): Search ITU space network filings including orbital slots, frequencies, and operator details
- [RTL-SDR Blog](https://www.rtl-sdr.com/): Premier resource for RTL-SDR tutorials, satellite reception guides, and cheap hardware hacks
- [SDRplay Community](https://www.sdrplay.com/community/): Active forum for RSP series SDR owners with satellite tracking tutorials and signal libraries
- [Orbital Focus](https://www.orbitalfocus.uk/): Jonathan McDowell's independent tracker of orbital events, launch histories, and reentry predictions
- [Space-Track TLE API](https://www.space-track.org/documentation#/tle): Programmatic API for pulling current and historical TLE sets — critical for satellite tracking automation
- [DarkSky Network](https://darksky.net/): Weather and atmospheric data useful for ground station operations and signal interference modeling
- [RF-Seeker Spectrum Database](https://www.sigidwiki.com/wiki/Signal_Identification_Guide): Crowdsourced signal identification guide — critical for classifying intercepted satellite downlinks
- [Globalstar Coverage Map](https://www.globalstar.com/en-us/corporate/coverage-map): Interactive coverage visualization for Globalstar LEO constellation — useful for attack surface analysis
- [Iridium NEXT Constellation Overview](https://www.iridium.com/network/iridium-next/): Technical overview of the 66-satellite Iridium NEXT constellation architecture
- [GNU Radio Wiki](https://wiki.gnuradio.org/): Comprehensive reference for flowgraph design, block development, and satellite signal processing
- [GNU Radio OOT Module Index](https://www.gnuradio.org/ecosystem/): Directory of out-of-tree GNU Radio modules including satellite demodulators and decoders
- [TLE Format Reference](https://celestrak.com/NORAD/documentation/tle-fmt.php): Complete specification of the Two-Line Element set format with field-by-field breakdown
- [Satellite Catalog Browser](https://celestrak.com/satcat/search.php): Search NORAD catalog by name, country, orbital regime, and operational status
- [Viasat KA-SAT cyberattack analysis (2022)](https://www.wired.com/): Detailed reporting on the February 2022 satellite modem wiper attack that disrupted Ukrainian communications at the start of the invasion
- [China's ASAT Test Debris Field — Five Years Later](https://aerospace.org/): Aerospace Corporation assessment of the 2007 FY-1C debris cloud and its ongoing implications for LEO operations
- [GPS Spoofing Incidents Near Russian Border Regions](https://www.gpsworld.com/): Documented cases of large-scale GPS spoofing affecting commercial aviation and maritime navigation
- [Maritime AIS Spoofing: Ghost Ships and Phantom Fleets](https://www.c4ads.org/): C4ADS investigation into systematic AIS position falsification using satellite-based broadcasts
- [CubeSat Cybersecurity Attack Surface Analysis](https://spectrum.ieee.org/): IEEE Spectrum investigation into the minimal-to-nonexistent security posture of commercial CubeSat buses
- [The Rise of Commercial LEO Constellations and the Security Implications](https://spacenews.com/): Analysis of Starlink, OneWeb, and Kuiper security architecture decisions
- [Ground Station Network Security — A Gap Analysis](https://aerospace.org/): The Aerospace Corporation white paper on attack paths through commercial ground station networks
- [Teleport Security in VSAT Networks](https://via-satellite.com/): Via Satellite reporting on vulnerabilities in hub-and-spoke VSAT architectures used across government and enterprise
