# neopixel-display-project*
## After planning, became two projects, a basic one and an advanced one

#Project I: Binary Clock

## Hardware

### Feature I: Navigation
- [ ] Design Must be easy to use

### Constraint I: Battery
- [ ] Battery Life of 1 year (we are jumping the gun here)
- [ ] Must show indication of low battery when battery is below 10%

### Constraint II: Electronics
-  Must use an ESP8266 (its what i have 😭)
-  Must use the one 8x8 neopixel display 

### Constraint III: Organization
- Must be as neat as possible for final product
- Must be easy to troubleshoot for problems


## Software

### Feature I: Clock
1. Test i: Grab time using Public NTP
3. Test iii: Show Binary Clock indication in HH:MM:SS[^2]
[^2]:See https://en.wikipedia.org/wiki/Binary_clock#/media/File:Binary_clock_Swiss_railway_station.jpg for funny example if neo pixels 

### Feature II: WIFI

1. Test i: Connect to an outside Wifi network
2. Test ii: Encrypt Wifi Details <sup>help</sup>

### Feature III: Alarm
1. Set up alarms through http
2. have them reoccur in minutes, days, weeks, months etc
3. automatic shutoff


### Feature IV: Spotify 
## Unknowns
- Power Consumption
- BOM
- if its feasible on the esp8266 without 💥 or smoking
- Design
- Whether to add weather or not

#Project II: Dot Matrix Smart Display


