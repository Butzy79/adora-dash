# PLUGIN CONFIGURATION
- [Plugin Tab](#adora-v-tab)
- [Racing Platforms Tab](#racing-platforms-tab)
- [Game Settings Tab](#game-settings-tab)
- [Pit Settings Tab](#pit-settings-tab)
- [Tracks List Tab](#track-list-tab)

## Adora v Tab
![Main Tab](/src/images/docs/plugin.jpg)

This is the main section of the Adora Plugin where you can set various parameters.
### Driver Info
In the first section, you can set your name, number, and color (by clicking on the color itself) to set up a customized idle screen.
It is only a cosmetic setting to make AdoraDash look nicer and more personalized.

### Settings
- Map Zoom: Value (smaller = bigger) of the map in the MFD display.
- New Lap Overlay: Each time you cross the finish line, an overlay layer appears over your MFD showing specific information. Here you can set for how many seconds this overlay will be shown.
- Electronics Change Overlay: Each time you change ABS, brake bias, TC, map, and so on in the top-left section of the dashboard, this information will flash to show the change.  You can set for how many seconds you want this info flashing (0 = not appear).
### MFD
The MFDs are the sections on the dashboard where, by setting a button or using the touch screen, you can scroll through various screens.
In this section, you can completely disable a screen (by clicking on the main checkbox), or disable it only for the race and/or qualifying by unchecking the respective option.

For example, if I do not want the screen that shows the track in any session, I can uncheck the value 'MFD Track.'
However, if I want it in practice and not in qualifying but yes in the race, I can uncheck 'Qualify.'
It will be visible only in practice and the race.
- MFD Tyres: It shows tire pressure and temperature, and brake temperature.
- MFD Last Lap: It shows tire pressure and temperature, and brake temperature of the previous lap (average values).
- MFD Standings: It shows session standings.
- MFD Nearby: It shows who is in front and behind us.
- MFD Hammer Time: It shows how to catch the car in front, and how to push the one back.
- MFD Delta: A delta time and a small track view.
- MFD Track: It shows the track and all the cars.
- MFD Damage: It shows car damage status.


## Racing Platforms Tab
![Racing Platforms](/src/images/docs/racing_platform.jpg)

If you enable LFM and enter your LFM ID, once a race you have subscribed to on LFM is approaching, an information pop-up containing all the server information will appear on the dashboard.

To retrieve your LFM ID, connect to the Low Fuel Motorsport website. Click on your user in the top right corner, and then go to the profile page.

In the URL, you will find the ID, which is the number at the end of the URL.


![LFM ID](/src/images/docs/plugin/lfm_id.jpg)


If this is set up correctly, once you launch the dashboard, the next race will pop up on the screen.

![DASHBOARD LFM](/src/images/docs/dashboard/lfm_next_race.jpg)

## Game Settings Tab
![Game Settings Tab](/src/images/docs/plugin/game_settings.jpg)

Here you can update specific values for each game.
In detail, you can set the target PSI for a specific game.
In Generic, you can set a generic value for sims not listed.

Target temperature (dry/wet) is displayed on the dashboard as a target value, and all the tires are aimed at this target, showing the delta in specific MFD displays.

## Pit Settings Tab
![Pit Settings Tab](/src/images/docs/plugin/pit_settings.jpg)

Set up your pit strategy and generic pit calculations.
#### Generic Settings
- Pit Strategy Calculation: When you are in the pit lane, with the engine and ignition off, you have an extra MFD showing information about tires and, in the fuel position, details about the fuel strategy relative to a race length set using this slider.
- Stint Time for Race: This value calculates the fuel to add at the next pit based on stint time and not the full remaining time of the race. In any case, if you set a stint longer than the tank capacity, the tank capacity will be shown as the fuel value to add at the next pit. (0 = full remaining time or maximum tank size of the car.)
#### Pit Generic Calculation
This section, combined with the Tracks List tabs, provides you with the timing to calculate pit stops during the race and estimate your final position.
- Pit Lane Length: If a specific pit lane length in seconds is not set in the Tracks List for your sim, this is the default value used.
- Fuel added in one second: Please specify how much fuel (liters/gallons) is loaded into your car per second.
- Extra fixed time to refuel: This parameter adds some extra seconds for refueling.
- Pit time for changing tires: If you want the estimation of your pit stop to include changing tires, please set the amount of time it requires in seconds.

## Tracks List Tab
![Tracks List Tab](/src/images/docs/plugin/tracks.jpg)

Here you can see all the tracks mapped in AdoraDash. If you want to add more tracks, please join our [AdoraDash Discord Server](https://discord.gg/2yNzuRc62S) and help us fill in the missing data.

## Other Steps
1. Step into [Action Buttons and Triggers](triggers.md) to seamlessly control AdoraDash.
2. A last step to know AdoraDash in all its functionality: [Walkthrough AdoraDash](walkthrough.md) to seamlessly control AdoraDash.

## Discord Community
Join the vibrant AdoraDash community on Discord!

👉 [AdoraDash Discord Server](https://discord.gg/2yNzuRc62S) 👈
