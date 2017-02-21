## Shadowverse Tracker

This was created to allow users to track and and view statistics of their **Shadowverse** games.

You can filter the games by:

* Craft played (player and opponent).
* Deck played (player and opponent).
* Whether you went first or second.

Also included is an Icon Changer in case you don't like the current icon.

Feature/improvement suggestions are welcome and I will add them when I have time.

If you like the tracker, feel free to donate:

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.me/sleeplessghost)

Bitcoin address: *1Q2Z6A7un9dSX37JAs29Bhiu7CFMCNN7VA*

Contact me: sleeplessghost@live.com

## Installation

#### Simple

Download the ```dist``` folder and open either ```ShadowverseTracker.exe``` or ```IconChanger.exe``` to run them.

#### Complicated

If you want to modify these programs, you can clone this repository and change them then recompile as needed.

```
https://github.com/sleeplessghost/ShadowverseTracker.git
```

It was created in Visual Studio 2008 using C#. You can run ```build.bat``` to build the solution and copy files to dist folder.

**Note:** ```build.bat``` requires .NET Framework v4.*

## Usage

#### Shadowverse Tracker

![Screenshot of Shadowverse Tracker](https://cloud.githubusercontent.com/assets/25903992/23140087/9135a1b2-f7ff-11e6-80fe-d469e27da28a.jpg)

You will first want to add some decks (```Add Deck``` panel).

Add games as you play in the ```Add Game``` panel. Hopefully this will be able to automatically do this for you at some point in the future.

Click on  ```Wins``` or ```Decks``` or ```Matchups``` in the Data panel to view statistics for your current filtered selection. You can click on the column headers in the Decks/Matchups tables to sort by each column.

Click on Export to export the game data to a ```.csv``` file (in the same directory as ```ShadowverseTracker.exe```).

Filtering options:

* Craft played by you using the buttons on the left.
* Opponent craft/deck using the dropdown lists in ```Filter``` panel.
* Specific deck played by you using the dropdown list in ```Filter``` panel.
* Game mode (ranked/unranked/take two) using the dropdown list in ```Filter``` panel.
* Turn (first/second) using the dropdown list in ```Filter``` panel.

To clear the saved games, delete ```storeddata.xml``` file then relaunch ```ShadowverseTracker.exe```.

#### Icon Changer

![Screenshot of Icon Changer](https://cloud.githubusercontent.com/assets/25903992/23140089/956e1962-f7ff-11e6-979d-5c0e45676c7d.jpg)

First, browse for ```ShadowverseTracker.exe```. If it is in the same directory as ```IconChanger.exe``` it should be automatically selected. This can also be used for other ```.exe``` files but I'm not sure if it will cause issues - backup first.

Click on the icon you want to use then click the ```Set Icon``` button at the very bottom.

Alternatively, if you want to use your own icon you can browse for one and set it using the ```Custom Icon``` panel. It will need to be a ```.ico```.

If you want to change the icon of Icon Changer, just copy it and use the copy to change the original's icon.

**Note:** It cannot change the icon of a currently running ```.exe```. Close ShadowverseTracker before changing the icon.