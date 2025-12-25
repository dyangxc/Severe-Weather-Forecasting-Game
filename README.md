# Severe-Weather-Forecasting-Game
SOFTWARE AUTHOR: @YangDawsonXC

SOFTWARE VERSION: v1.00 
(LICENSE AGREEMENT & PATCH NOTES AT BOTTOM)

CURRENT DATASET: 2003 - Early Dec. 2025

ABOUT:
Created for the purpose of practicing severe weather foreacsting skills. This program mostly uses archived mesoanalysis data and severe weather event data from the Storm Prediction Center. If there is any data that appears to be broken or missing, it is likely to be a data source issue. This software is provided as is and will be updated when author is willing.

This software is not associated with National Oceanic and Atmospheric Administration, National Weather Service, Storm Prediction Center, or Iowa Environmental Mesonet.

HOW TO PLAY:
1. Select a season (defaults to all seasons if nothing is selected)
2. A random forecast day will be loaded with archived data. 
***ALLOW ALL DATA PRODUCTS TO BE DOWNLOADED FOR BEST PERFORMANCE!!***
3. Review available data products
4. Use the time slider to animate through the day (12Z yesterday through 12Z tomorrow)
5. Issue your forecast using the panel on the right. VALID FORECAST TIMES: 12z-11:59Z
6. OPTIONAL: Use the Create a Forecast Map button to draw your own outlook areas
7. Submit your forecast to see how you did compared to actual SPC outlooks

DATA PRODUCTS:
- SPC Upper Air Charts: 12 hourly analysis at the Surface, 925 mb, 850 mb, 700 mb, 500 mb, 300 mb, and 250mb heights
- Observations: Surface plots, satellite, radar, and other derived products
- Thermodynamics: CAPE, CIN, lapse rates, and moisture parameters
- Wind Shear: Bulk shear, helicity, and storm-relative winds
- Composite Indices: Supercell Composite, STP, VTP, and other severe weather forecasting parameters
- Multi-Parameter Fields: Combination of specific parameters to better visualize the atmosphere
- Other Fields: Misc. products which may be useful

VERIFICATION:
After submitting your forecast, you can view:
- All issued SPC Day 1 outlooks (0100Z, 1300Z, 1630Z, 2000Z, 0100Z)
- Storm reports for the forecast day and yesterday's report also included!
- Your drawn forecast maps compared to actual SPC outlooks

TIPS:
- ***ALLOW ALL DATA PRODUCTS TO BE DOWNLOADED FOR BEST PERFORMANCE!!***
- Use the zoom (mousewheel) and pan (left click) controls to view your selected product
- The "Play" button animates through time automatically
- Green indicators show which data products have loaded successfully
- Use "Refresh Data" if images fail to load
- The Forecast Map button lets you draw your own outlook areas
- You can save the entire day's dataset to your selected folder. You can also save your own drawn forecast maps too!

DATA SOURCES:
- NOAA Historical Data
- Storm Prediction Center Archives
- National Weather Service Archives
- Weather Prediction Center Archives
- Iowa Environmental Mesonet GIS Archives

-------------------------------------------------------------------------------------------------------------------------------------------------------

PATCH NOTES:
Severe Weather Forecasting Game v1.00 [2025-12-25]
- PUBLIC RELEASE

Severe Weather Forecasting Game v0.08 BETA [2025-12-25]
- MAJOR CHANGE; Added event 12z and 00z soundings from SPC Event Archives (Note: Soundings may not be available for all dates!!)
- New change for when loading a new day, all windows will now close

Severe Weather Forecasting Game v0.07 BETA [2025-12-24]
- MAJOR CHANGE: Reduced RAM usage significantly (no longer using over 8GB+ of ram for caching)
- No longer offloads cache to RAM anymore, only use disk as cache reference (disk caching located in TEMP)
- Added security for stats, no more player tampering :)
- Added button on stats page that allows users to reset total forecasts and forecast accuracy (without resetting total playtime)
- Selected product should no longer move around in its category. Happened when user selects a product in search, then clearing search, the selected product moves to the top of its respective category

Severe Weather Forecasting Game v0.06 BETA [2025-12-24]
- MAJOR CHANGE: Added products search
- Fixed softlock bug related to when having drop down menu open then quickly hovering over probability reference, the reference will stay stuck on the screen
- Pressing a new data product resets panning and zoom
- Spacebar now can play and pause the timeslider
- Adjusted error message on no data available page
- Added note at the top of the probability reference image

Severe Weather Forecasting Game v0.05 BETA [2025-12-22]
- MAJOR CHANGE: Changed valid forecast from 00z-12z to 12z-12z
- Added stats! (Hooray!)
	-Includes stats such as how long it took for you to forecast, average forecast time, overall play time hours, and how many forecasts you got correct
- Quality of Life updates involving colors and date indicators
- Fix the center slider to closely line up with the data load display
- Made sure when pressing Random Day to reset EVERYTHING (thanks for going over 100% progress loading bar :D)
- Removed the data link from showing when loading an image and when displaying errors
- Figured out why random lag spikes happened while looking at SPC surface analysis. It was a storage and calling dataset related issue
- Fixed issue when leaving selected dataset time on valid image, changed indicator from partial to success (purple to green)
- Fixed issue where user could actually press the SPC probabilities reference button (top right) instead of hovering over

Severe Weather Forecasting Game v0.04 BETA [2025-12-21]
- Fix saving and displaying forecaster map on view all issued categorical outlooks

Severe Weather Forecasting Game v0.03 BETA [2025-12-20]
- Add display of yesterday's storm reports when clicking on view storm reports
- If date is from a certain time period during SPC, filter categorical options out (no more mrgl, enh options)
- Crop images to hide date and remove full date with only month remaining
- Add ability to select what season (including all season) to select from
- Startup information page, with a checkbox to remember option not to show again
- Fix the progress bar to stop going over 100% (related to reset values when requesting new random day)
- Arrows beside the time slider. Bind to left and right arrows on keyboard.
- Color code the yesterday, today, and tomorrow indicator at the right. Green = Today's forecast and bold the text.

Severe Weather Foreacasting Game v0.02 BETA [2025-12-20]
- Fixed scrolling and performance issues

Severe Weather Forecasting Game v0.01 BETA [2025-12-17]
- Game release to closed testers (thanks everyone!)

-------------------------------------------------------------------------------------------------------------------------------------------------------
LICENSE AGREEMENT:
SEVERE WEATHER FORECASTING GAME END USER LICENSE AGREEMENT
Copyright (C) 2025 YangDawsonXC. All rights reserved.

1. GRANT OF LICENSE
You are granted a free, non-exclusive license to:
- Download and install this software
- Use the software for personal, non-commercial purposes
- Redistribute the original, unmodified software

2. RESTRICTIONS
You may NOT:
- Modify, reverse engineer, decompile, or disassemble the software
- Remove any copyright or proprietary notices
- Use the software commercially without separate permission (means contact me)
- Sell, sublicense, or otherwise monetize the software
- Access or use the source code (will not be released)

3. OWNERSHIP
All rights, title, and interest in the software and source code remain with the copyright holder.

4. NO WARRANTY
THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.
THE AUTHOR SHALL NOT BE LIABLE FOR ANY DAMAGES, INCLUDING LOSS OF DATA, SYSTEM DAMAGE, OR OTHER LOSSES ARISING FROM THE USE OR INABILITY TO USE THIS SOFTWARE.

5. DISTRIBUTION
You may share the complete, unmodified game package freely.
Modified versions may not be distributed.

6. CONTACT
For questions regarding this license or requests for commercial use permission,
contact the author via official social media accounts using the subject
"Severe Weather Forecasting Game".

Permission is only valid if explicitly granted in writing.

Official Contacts:
Bluesky: @yangdawsonxc.bsky.social 
Twitter (X): @YangDawsonXC
