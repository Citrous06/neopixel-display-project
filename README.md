# neopixel-display-project
## Funny little display project I have been thinking about for a while
Programming Language(s): iunno 🚶‍♂️

## Hardware
### Feature I: Neopixel Display
- Two ways this can go
   - The one 8x8 Neopixel Display I have
   - get 5-8 more for cheap for a big one
 
### Feature II: Navigation
- [ ] Design Must be easy to use

### ~~Constraint I: Battery~~[^1]
- [ ] ~~Battery Life of 1 year (we are jumping the gun here)~~
- [ ] ~~Must show indication of low battery when battery is below 10%~~

[^1]: This is impossible.

### Constraint II: Electronics
-  Must use an ESP8266 (its what i have 😭)

  
### Constraint III: Organization
- Must be as neat as possible for final product
- Must be easy to troubleshoot for problems


## Software

### Feature I: Clock
1. Test i: Grab time using Public NTP
2. Test ii: Read full-time HH:MM:SS effectively
3. Test iii: Show Binary Clock indication in HH:MM:SS[^2]
[^2]:See https://en.wikipedia.org/wiki/Binary_clock#/media/File:Binary_clock_Swiss_railway_station.jpg for funny example if neo pixels 

### Feature II: WIFI

1. Test i: Connect to an outside Wifi network
2. Test ii: Encrypt Wifi Details <sup>help</sup>

### Feature III: Events/Calendar (contested)
1. Test i: Fetch data from Google Calendar API (or Notion API depends on what sticks for me in the future)
2. Test ii:  Display basic future events
3. Test iii: Show full month view[^3]
[^3]: This can happen only if get enough neopixel displays

## Unknowns
- Power Consumption
- BOM
- if its feasible on the esp8266 without 💥 or smoking
- Design
- Whether to add weather or not

