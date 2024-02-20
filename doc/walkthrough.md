# WALKTHROUGH OF ADORADASH
- [Main Screen](#general-main-screen)
- [Track Screen](#track-screen)
- [Standing Screen](#standing-screen)

## General Main Screen
AdoraDash has three main differences based on the type of session you are conducting. Here, we will delve into the specific screens and information common to all sessions, as well as the unique features of each session.

***PLEASE READ [Action Buttons and Triggers](triggers.md) SECTION to understand how to interact with AdoraDashboard***

### Common screens
- [Electronics Box](#electronics-box)
- [Last Lap Box](#last-lap-box)
- [Timing Box](#timing-box)
- [Functions and Map Box - Clock Time](#functions-and-map-box---clock-time)
- [Pit Box](#pit-box)
- [Fuel Box](#fuel-box)
- [MFDs Box](#mfds-box)

![Common View](/src/images/docs/walkthrough/common.jpg)

#### Electronics Box
![Electronics](/src/images/docs/walkthrough/electronics.jpg)

Information about Brake Bias, ABS, and Traction Control will be provided.

If ABS or TC is engaged, the background will blink. Additionally, if there is a change in electronic values, an overlay will display the change.
![Electronics Change](/src/images/docs/walkthrough/electronics_change.jpg)

#### Last Lap Box
![Last Lap](/src/images/docs/walkthrough/lastlap.jpg)

Information about your last lap will be displayed here. 

The color of the lap is as follows: Purple indicates your best lap for this session, green means you are lapping at your pace time, and yellow indicates that you are slower than expected.

If there is a change in track grip, it will be displayed here for a few seconds.
The values may vary based on the sim.

![Last Lap Change](/src/images/docs/walkthrough/lastlap_change.jpg)

#### Timing Box
![Timing Box](/src/images/docs/walkthrough/timing.jpg)

This is the main box to track your time and position. You can see:

- Estimated lap
- Laps: the number of completed laps
- Time Left: This section can display the time remaining to complete a session or the number of laps left in a race.
- Pos: Your current overall position
- Stint time: This section shows you the time you have been on track since the start of the session. In endurance races, the missing time before a driver swap (if available) will be displayed in green. In qualifying sessions, this box will contain the value of Delta Times. Please refer to the following section to understand them: [Qualifyng Delta](https://github.com/Butzy79/adora-dash/blob/dev/doc/triggers.md#qualifyng-delta) 
- D.Cut/Cup/CLS: This section in blue hosts your category position. Details about that are in the [Plugin](plugin.md#standing-style) section and [Triggers](triggers.md#change-standing-type) section 
#### Functions and Map Box - Clock Time
![Functions ana map](/src/images/docs/walkthrough/functions.jpg)

Here, information about the lights, rain lights, wiper speed, and blinker of your car is displayed. Next to it, you will see the engine map value of your car.

By using the touchscreen or Trigger Action B on your controller, you can switch between viewing functions and real clock time.
Assetto Corsa and other simulators display only this screen, as the other screen is not compatible with the simulator.
![Clock Time](/src/images/docs/walkthrough/clock_time.jpg)

If a flag is waved on the track, this display will show the corresponding flag.
![Flags](/src/images/docs/walkthrough/functions_change.jpg)

#### Pit Box
![Pit Box](/src/images/docs/walkthrough/pit.jpg)
Three values are displayed here:

- Mandatory Pit Stops: These are the mandatory pit stops you still need to make.
- MFD Value: If the simulation permits displaying this value, you will see the amount of fuel you need to load for your next pit stop here.

  If the fuel needed for the next pit stop is sufficient to complete the session, a large white number or a dash (if no pit stop is planned) will be displayed.
  If the fuel needed is insufficient or no pit stops are planned but there isn't enough fuel to finish the session, a second number will appear indicating the additional fuel needed to complete the session. The large number in this case will be shown in red.
  ![Fuel Missing](/src/images/docs/walkthrough/pit_missing.jpg)
- Fuel Surplus: This indicates the surplus fuel available to complete the session. If a dash is displayed ("-"), it means you will not have enough fuel to complete the session. ***Remember that the Surplus counts the current fuel in the tank along with the fuel you plan to add at your next pit stop.***

![Pit End Race Box](/src/images/docs/walkthrough/pit_finish.jpg)

This second screen, accessible using Action C (please refer to the [Action Buttons and Triggers](triggers.md) section), shows you:

- The amount of fuel you need to refill to complete the race.
- The total pit stop time, including entering and exiting the pit lane and the time allocated for changing tires.
- The predicted position at the end of the pit stop.

Please remember that the refill value includes the amount of fuel currently in your tank.

![Pit Stint Box](/src/images/docs/walkthrough/pit_stint.jpg)

This third screen is similar to the one above, but the amount of fuel shown is for completing a stint of the time set in the plugin or with the right triggers.
It displays the length of the stint in yellow.

In this case, the amount of fuel shown is ***NOT*** including of or evaluating the current fuel level in your tank.

This feature is more oriented toward endurance races.

#### Fuel Box
![Fuel status](/src/images/docs/walkthrough/fuel.jpg)

This section shows you:
- How many laps you can complete with your current fuel level. If the fuel is sufficient to finish the session, this value will be displayed in green; if the fuel is enough for only two or fewer laps, it will be displayed in red.- The average consumption of your car based on your driving style.
- The amount of fuel in your tank.

![Fuel time](/src/images/docs/walkthrough/fuel_finish.jpg)

This second screen, accessible using Action D (please refer to the [Action Buttons and Triggers](triggers.md) section), shows you:

- Remaining time with the fuel you have onboard. If the fuel is enough to finish the session, the white bar will be colored green; however, if the remaining laps are less than two, it will be red.
- The total fuel you need to finish the race at this moment. ***Please remember that this value does not consider your current fuel level!***

#### MFDs box
Those screens, accessible using Action A (please refer to the [Action Buttons and Triggers](triggers.md) section), are the core value of AdoraDash.

You can activate/deactivate them in the [Plugin](plugin.md#MFD) section.
Each screen provides unique information about the session in which you are driving.

![MFD Tyres](/src/images/docs/walkthrough/mfd_tyre.jpg) It shows real-time values for tire temperature and PSI, as well as brake temperature. For sims that support it, tire wear is also displayed. Additionally, it shows the number of tire sets you are using and indicates whether you have wet or dry tires mounted. The target temperature set in the plugin is displayed at the bottom of the screen. Tire pressure changes color according to targets: green indicates ideal, blue indicates lower than ideal, and red indicates higher than ideal. Different gradients are shown for these colors.


![MFD Last Lap](/src/images/docs/walkthrough/mfd_lastlap.jpg)

![MFD Standings](/src/images/docs/walkthrough/mfd_standing.jpg)

![MFD Nearby](/src/images/docs/walkthrough/mfd_nearby.jpg)

![MFD Hammer Time](/src/images/docs/walkthrough/mfd_hammer.jpg)

![MFD Delta](/src/images/docs/walkthrough/mfd_delta.jpg)

![MFD Track](/src/images/docs/walkthrough/mfd_track.jpg)

![MFD Damages](/src/images/docs/walkthrough/mfd_damage.jpg)
## Track Screen
***PLEASE READ [Action Buttons and Triggers](triggers.md) SECTION to understand how to interact with AdoraDashboard and reach this screen***

![Track View](/src/images/docs/walkthrough/track_screen.jpg)

## Standing Screen
***PLEASE READ [Action Buttons and Triggers](triggers.md) SECTION to understand how to interact with AdoraDashboard and reach this screen***

![Standing View](/src/images/docs/walkthrough/standing_screen.jpg)

## Other Steps
1. Step into [Adora Plugin](plugin.md) to experience AdoraDash.
2. Step into [Action Buttons and Triggers](triggers.md) to seamlessly control AdoraDash.
3. A last step to know AdoraDash in all its functionality: [Walkthrough AdoraDash](walkthrough.md) to seamlessly control AdoraDash.


## Discord Community
Join the vibrant AdoraDash community on Discord!

👉 [AdoraDash Discord Server](https://discord.gg/2yNzuRc62S) 👈
