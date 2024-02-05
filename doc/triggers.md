# ACTION BUTTONS AND TRIGGERS

## General
You can set up your controller to interact with some actions of Adora Plugins Controllers. 
Some of those actions require a valid license for the Adora Plugin. 
To do that, in SimHub, go to the left menu, select Controls and Events. 
Under the Controls section, click on New mapping, and on the left, select your input controller (you can push a button on your controller to directly select it).
n the left list, select the action to set with this control. Choose the input mode as "Short and Long press" or your preferred option.

## Set Actions Button (A and D) and Next Screen
In SimHub, navigate to DashStudio -> Controls and assign triggers to the A and D buttons, and also for the next screen.
If you are using a DDU, please set up those controls in your DDU interface: Devices -> Control (on your selected device).

- **Action A:** Controls the MFD display, allowing you to scroll between different screens such as Tyres, Map, Damages, and others that will be developed in the coming days.

- **Action D:** Scrolls through Fuel values.

![Maim](/src/images/docs/triggers/action_ad.jpg)
![Track](/src/images/docs/triggers/track_pn.jpg)
![Standing](/src/images/docs/triggers/standing_pn.jpg)

All the controls are also touch screen-enabled if your display supports it.

## Qualifyng delta 
<sup>[___free___]</sup>
You can set up your controller to interact with the delta time in your central top console.
There is an action named Delta.PolePositionDelta.
Assign it to your controller to interact during your session with this section.

This feature allows you to display the delta time between:
-Your best lap time
-The current pole position
-The best time in your category

The time for each of these selections will be shown in this box.

***This option is valid only in qualifying sessions.***

![Pole](/src/images/docs/triggers/pole.jpg) ![Your Best](/src/images/docs/triggers/yourbest.jpg) ![Category](/src/images/docs/triggers/category.jpg)

## Standing scrolling standings 
<sup>[___free___]</sup>
You can set up your controller to interact with the standings in the MFD display.
There are three actions: Standing.ScrollUpStandings, Standing.ScrollDownStandings, and Standing.IsPlayerCenter.

These actions give you the opportunity to interact with the standings, scrolling up or down, or centering on the player's position. 

Assign them to your controller to interact with this section during your session.

## Change Standing Type
<sup>[___free___]</sup>
You can set up your controller to interact with standings type in MFD display.
There is an action named Standing.StandingCup.
This option gives you the opportunity to see your overall position or that of your category.
Assign it to your controller to interact during your session with this section.

## Set Your Target Temperature (Only licensed)
<sup>[___licensed___]</sup>
You can set up your controller to interact with the target temperature of your tires. There are two actions: Tyre.Decrement_TargetTemp and Tyre.Increment_TargetTemp. Assign both to your controller to interact during your session with those values.

## Strategy Time
<sup>[___licensed___]</sup>
You can increment and decrement the strategy time in minutes. There are two actions: Strategy.Decrement_TimeInMinutes and Strategy.Increment_TimeInMinutes. Assign both to your controller to interact during your session with those values.
