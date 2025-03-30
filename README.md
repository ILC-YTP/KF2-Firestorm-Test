# KF2-Firestorm-Test
Test mod for Killing Floor 2 to see if the Firestorm skill's extra duration on ground fire in working correctly.

Firestorm skill ingame description: "Increase range of the Caulk n' Burn, Flamethrower, and Microwave Gun. Increase fire ground duration a 20%."

Killing Floor 2 wiki actual stats page reports: "Firestorm (ground fire duration, for cnb, ff and mwg) = x1.2

Firestorm should be increasing the ground fire duration by 20%, at least with "thrower" weapons, but when I was testing the skill, it didn't seem to increase the duration at all

This mod was made to see if the skill function even worked at all, increasing the multiplier from 1.2 to 5.2

The mod is very janky, but it does work, the ground fire does last a lot longer. This proves that the skill is working, but it does so little that it makes no noticable impact.

## To try mod
KF2 SDK (might be) needed, can be downloaded under the tools section in your Steam library
Firebug @ level 20 or more

Download mod from releases or in the compiled folder. Place "Dummy.u" in the following directory (Windows Users): ``C:\Users\yourpcusername\Documents\My Games\KillingFloor2\KFGame\Unpublished\BrewedPC\Script``

Go to ``Documents\My Games\KillingFloor2\KFGame\Config`` and open *KFEditor.ini*. Find `[ModPackages]` and add the following line: ``ModPackages=Dummy``

Go to this folder where Killing Floor 2 is installed ``killingfloor2\Binaries\Win64``

Open a command prompt window and insert the following command ``KFGame kf-bioticslab?game=Dummy.dummygameinfo -useunpublished -log``

### Note!
This mod creates a new class that's an almost exact copy of the firebug, it's under the survivalist and you likley need to scroll down to it. Class will keep defaulting to all left side skills when attempting to change skills, but you can select the right ones and it will apply skill changes when clicking OK. Text is corrupted and uses placeholder text.
