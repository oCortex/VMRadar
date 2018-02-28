# PUBG-Radar ![Imgur](https://i.imgur.com/n3JtN5d.png)

#### By engaging with this repository you explicitly agree with the terms of the Unlicense.

https://github.com/SamuelNZ/VMRadar/releases

![Imgur](https://i.imgur.com/6dZGFen.gif)

This version runs without the spoofing shit in a VM.

'Fixed' the item locations, still working on it.

### Key Kinds
You can't filter level 3 gear (always enabled)

#### Item Filter:
* HOME -> Show / Hide Compass
* NUMPAD_0 -> Filter Throwables
* NUMPAD_1 -> Filter Weapon
* NUMPAD_2 -> Filter Attachments
* NUMPAD_3 -> Filter Level 2
* NUMPAD_4 -> Filter Scopes
* NUMPAD_5 -> Filter Meds
* NUMPAD_6 -> Filter Ammo

#### Zooms:
* NUMPAD_7 -> Scouting
* NUMPAD_8 -> Scout/Loot
* NUMPAD_9 -> Looting

### Online Mode:
`java -jar target\pubg-radar-1.0-SNAPSHOT-jar-with-dependencies.jar "Middle PC IP" PortFilter "Game PC IP"`

### Offline Mode:
You can replay a PCAP file in offline mode:

`java -jar target\pubg-radar-1.0-SNAPSHOT-jar-with-dependencies.jar "Middle PC IP" PortFilter "Game PC IP" Offline`

## Build
Using [maven](https://maven.apache.org/) or [JetBrains](https://www.jetbrains.com/idea/)

## Install and Run

1. Install VMWare Workstation
2. Setup your VM in Bridged Mode, replicate physical.
3. Install [Maven](https://maven.apache.org/install.html) on your VM
4. Add Maven to your environment PATH, screenshot below.
4. Add MAVEN_OPTS environment variable, screenshot below.
4. Install [JDK8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) on your VM and 
5. Add JAVA_HOME to your Environment Path, screenshot below.
5. Install [Wireshark + WinPCap](https://www.wireshark.org/) on your VM
6. Change your IP addresses in the batch file, It will crash if they are wrong.
7. Do the extra step below in the Compatibility tab in the Properties.
8. Run the batch file.

#### MAVEN_OPTS
![Imgur](https://i.imgur.com/aWCdgUX.png)

#### Path (Java and Maven)
![Imgur](https://i.imgur.com/hSCYrCM.png)

#### JAVA_HOME
![Imgur](https://i.imgur.com/4zT1YNR.png)

#### COMPATIBILITY
![Imgur](https://i.imgur.com/Oz6HoDe.png)


#### You can find detailed instructions on how to run a maven project [here](https://maven.apache.org/run.html)


