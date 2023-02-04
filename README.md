# FTC-matches

#### ALPHA v0.5.0

Welcome to FTC Matches, a little project designed to see how your team is doing and when your next match is at a glance.

If you do find any bugs (and it's not listed in the limitations category), please do create an issue.

### Links

[Installation Guide](#how-2-install)

[Limitations/Known Issues](#limitations--known-issues)

[FAQ](#faq)

## FAQ

soonTM

## How 2 Install

##### Step 1: 
Download/clone all of the files from this repository into a single folder. 

##### Step 2: 
Go to chrome://extensions. Make sure "Developer Mode" is turned on.

![image](https://user-images.githubusercontent.com/42128680/210491200-22616cae-c719-494d-874d-30132315a9da.png)

##### Step 3: 
Click "Load unpacked." Locate the folder in the file browser that appears, and select the folder. 

![image](https://user-images.githubusercontent.com/42128680/210491208-cae547da-10c1-4402-bf1f-fb8763884008.png)

Once the extension is loaded, this should appear in the extensions screen:

![image](https://user-images.githubusercontent.com/42128680/210491254-89b19870-4ad6-417a-8b60-b4a72565fb24.png)

##### Step 4: 
Select the extension in the extensions tab (the puzzle piece).

![image](https://user-images.githubusercontent.com/42128680/210491346-9845819e-1603-4c0d-bc48-d3b67897e339.png)

##### Step 5:
Input a team number and event code to be displayed and click Open.

![image](https://user-images.githubusercontent.com/42128680/210491730-bceaf6fe-7910-49eb-8b68-a8f726ba23cf.png)

> Note: Currently an event MUST be from the 2022 season.

Event codes can be found at (https://ftc-events.firstinspires.org). You can type your team number in the search bar at the top and select an event you want (again, currently only from the 2022 season).

## Limitations / Known Issues

Known limitations/issues, either because I haven't had the time to code them or it just can't be changed.

- A match displaying "In Progress" well before it starts

  This is due to limitation with the FTC events API. It is impossible to tell whether a match has actually started, thus the program just assumes the next match has started when the previous one has finished.
  
- Matches with 3 teams per alliance either don't show up or otherwise don't display the right teams in the right places

  Support for this hasn't been added yet. It will be added soon, for now, the program will probably be unsuable if your match has 3 teams per alliance.
  
- The program looks squished or the content doesn't fit on small / 4:3 screens.

  The display is designed to fit on either a normal sized laptop (It works fine on a 13.3" laptop I use) or something bigger. 4:3 screens aren't designed to be supported. This could be added in the future, but that would require a lot of changes to the HTML.

- Older events (previous seasons) don't work

  This will be fixed eventually, but for now, due to the way the API makes you request the data, it's currently limited to matches from the 2022 season (Power Play).
