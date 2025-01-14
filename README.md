# <span style="color:purple; text-shadow: 0 0 5px white;">VeloCity</span> - <span style="color:green; font-weight:bold;">V1.1.1</span>

# 🙎🏼‍♀️ Overview

The <span style="color:purple; text-shadow: 0 0 5px white; font-size: 20px;">**VeloCity**</span> mod enhances in-game immersion by dynamically adjusting vehicle and pedestrian densities across specific in-game time frames. The mod replicates real-world traffic patterns, increasing density during rush hours across the map.

# 🚀 Features

- **Increases traffic density during morning and evening rush hours:**
    - **Quiet Morning:** 1:00 AM - 5:00 AM 
    - **Morning Rush:** 7:00 AM - 9:00 AM
    - **Lunch Rush:** 12:00 PM - 1:00 PM 
    - **Evening Rush:** 3:00 PM - 6:00 PM
    - **Quiet Evening:** 9:00 PM - 12:00 AM

- **Weather-Based Density Multipliers:**
    - Reduced densities in rain and snow conditions
    - Increased densities in sunny weather

- **Dynamic Weather Effects:**
    - Introduces vehicle grip adjustments during snowy and rainy conditions to enhance realism.

- **Realistic Police:**
    - <span style="color:red"> REMOVED FOR NOW!!! Enables recognition of previously wanted vehicles: if a player evades the police but remains in the same vehicle, they will become wanted again if spotted within the specified *WantedEscapeRadius* However if you go into a different vehicle you won't be detected.
    </span>
    - Provides an option to disable police blips on the map for added immersion.

- **Enhanced Realism:**
    - Allows real-world PC time synchronization with GTA V, reflecting real-time in-game. Note that enabling this feature will also sync traffic density to real-world time.
___
# ⚡️ Performance Advisory

Please be aware that the performance of the script may be affected by the selected multiplier. If you encounter performance issues, we recommend reducing the multiplier value. This limitation is due to the game capabilities, as an increased number of models can lead to lower fps rates. For users with low to mid-range systems, it is advisable to keep the multiplier at or below 1x.

# 🎚️ Optimized For
- [Immersive Blink Fx](https://www.gta5-mods.com/scripts/immersiveblinkfx-sp-fivem)
- [PoliceAi SHVDN Edition](https://www.lcpdfr.com/downloads/gta5mods/scripts/49024-policeai-shvdn-edition-wip/)
- [Dynamic Weather](https://www.lcpdfr.com/downloads/gta5mods/scripts/48582-dynamicweather/)
- [(RDE) Rebalanced Dispatch Enhanced](https://www.lcpdfr.com/downloads/gta5mods/misc/9266-rebalanced-dispatch-enhanced/)

# 🛠️ Requirements (Singleplayer)
- **GameConfig:** [Download Gameconfig](https://www.gta5-mods.com/misc/kryst4lclr-s-gameconfig-updated-regularly).
- **ScriptHookV:** [Download ScriptHookV](http://www.dev-c.com/gtav/scripthookv/)
- **ScriptHookVDotNet-nightly:** [Download ScriptHookVDotNet](https://github.com/scripthookvdotnet/scripthookvdotnet-nightly/releases/latest)

# 🔧 Installation (Singleplayer)
1. Copy the `VeloCity.dll` file to your GTA V `scripts` folder.
2. Done! The script will activate automatically in-game, and ini file will be created which can be found in `scripts\Code-Master\Configs\VeloCity.ini`.

NOTE: A backup of ini file will be created which can be found in `scripts\Code-Master\Configs\BackUps\VeloCity.bak`.

# ⚙️ How to Use
Once installed, this script will do the rest.

# 📋 Versions & Changelog

> ## ⭐ V1.1.2 | Bug Fixes & Enhancements
> <span style="color:green; font-size: 14px; text-shadow: 0 0 10px green; display: block; text-align: right;">🟢</span>
> <span style="color:green; display: block; text-align: left; font-size: 12px; text-decoration: underline; font-weight: bold;">Current Version</span>
>
>- <span style="color:green">🚨 <span style="font-weight: bold; color: white;">Automatic Hazard Lights Activation on Impact:</span> The hazard lights now engage automatically when a vehicle's health drops below 300 due to a collision. They will flash continuously for 30 seconds to enhance visibility and safety before deactivating ( We will be working on this more in upcoming updates).</span>
>
>- <span style="color:green">🆕 <span style="font-weight: bold; color: white;">Code Optimization and Bug Fixes:</span> Removed redundant and unnecessary code to streamline functionality and resolve issues, ensuring smoother and more reliable performance.</span>
>
>- <span style="color:red">👮 <span style="font-weight: bold; color: white;">Police Mobile Offence:</span> This feature was removed due to the emergence of bugs during extended gameplay sessions. After a 6-hour testing session in GTA V, issues began to surface, prompting the decision to ensure smoother, uninterrupted performance.</span>
>> <span style="font-weight: bold; color: green;">There is no need to delete both INI files located in the Configs and Backups folders in this version</span>
___

> ## ⭐ V1.1.1 | Bug & Version Fixes 
> <span style="color:orange; font-size: 14px; text-shadow: 0 0 10px orange; display: block; text-align: right;">🟠</span>
> <span style="color:orange; display: block; text-align: left; font-size: 12px; text-decoration: underline; font-weight: bold;">Previous Version</span>
>
>- <span style="color:green">⛈️ <span style="font-weight: bold; color: white;">Weather Fixes:</span> Previously, the weather effects would trigger during rain or snow; however, when transitioning to any other weather condition, the effects persisted incorrectly. This issue has been resolved to ensure that weather effects are applied appropriately based on the current conditions.</span>
>
>- <span style="color:green">🆕 <span style="font-weight: bold; color: white;">Code Master Version Checker:</span> While the version checker was accurately reporting the current version, it did not update the files upon the release of a new update. This functionality has been improved to ensure that version files are correctly updated with each new release.</span>
>
>- <span style="color:red">👮 <span style="font-weight: bold; color: white;">Police Wanted Detection:</span> This feature has been temporarily removed to address a recently identified issue. Further testing and refinements are underway to ensure optimal performance before reintroducing it in a future release.</span>
>> <span style="font-weight: bold; color: darkorange;">⚠️ We strongly recommend that all users delete both INI files located in the Configs and Backups folders to avoid potential errors.</span>
___
> ## ⭐ V1.1.0 | Enhancements & User Configuration
> <span style="color:orange; font-size: 14px; text-shadow: 0 0 10px orange; display: block; text-align: right;">🟠</span>
> <span style="color:orange; display: block; text-align: left; font-size: 12px; text-decoration: underline; font-weight: bold;">Previous Version</span>
>
>- <span style="color:green">🌎 <span style="font-weight: bold; color: white;">Enhanced Realism:</span> Integrate real-time synchronization with the in-game clock, providing a true-to-life experience. Players will receive a one-star wanted level if caught using a mobile phone while driving, and police blips can be toggled through `VeloCity.ini` configuration, offering complete control over immersion settings.
>
>- <span style="color:green">⛈️ <span style="font-weight: bold; color: white;">Weather-Based Density:</span> Traffic and pedestrian densities automatically adjust based on weather conditions, with specific multipliers for sunny, rainy, and snowy scenarios to reflect real-life environmental influences and activity patterns.
>
>- <span style="color:green">🕰️ <span style="font-weight: bold; color: white;">Expanded Time Intervals for Density Management:</span> Density adjustments have been made for increased traffic during lunch rush (12:00 PM - 1:00 PM) and quieter hours from 1:00 AM - 5:00 AM, enriching gameplay through realistic time-of-day effects.
>
>- <span style="color:green">❄️ <span style="font-weight: bold; color: white;">Dynamic Weather Effects:</span> Adverse weather conditions, such as rain and snow, now impact vehicle handling, reducing grip and providing an authentic driving experience that adjusts to environmental conditions.
>
>- <span style="color:green">📖 <span style="font-weight: bold; color: white;">User Configuration:</span> Players can easily customize settings through the INI file, enabling a personalized experience. Additionally, a backup of `VeloCity.ini` configuration is now saved in `scripts\Code-Master\Configs\BackUps` for quick recovery of preferences.
>
>- <span style="color:darkorange">🔧 <span style="font-weight: bold; color: white;">Bug Fixes and Performance Enhancements:</span> Enhanced density transitions minimize lag during peak traffic events, optimizing overall performance and ensuring smoother gameplay.
>
>- <span style="color:red">❌ <span style="font-weight: bold; color: white;">Removed:</span> key areas (locations) as this was causing poor performance / lag.
_____

> ## ⭐ V1.0.0 | Initial Release
> <span style="color:red; font-size: 14px; text-shadow: 0 0 10px red; display: block; text-align: right;">🔴</span>
> <span style="color:red; display: block; text-align: left; font-size: 12px; text-decoration: underline; font-weight: bold;">Outdated Version</span>
>
>- <span style="color:green"><span style="font-weight: bold; color: white;">Ped & Traffic Density:</span> Basic functionality for increasing traffic and pedestrian density based on in-game time.
>
>- <span style="color:green"><span style="font-weight: bold; color: white;">Beta Release:</span> First beta version of the script. User feedback is appreciated to help refine the feature set.
_____


We are continuously working on improving VeloCity. Future updates may include:

- **Winter Effects:** Implement a misted windows effect, allowing players to clear mist when the vehicle engine is running.
- **Traffic Control Systems:** Implement dynamic traffic light changes based on real-time traffic density to improve flow and reduce congestion in busy areas.
- **Customizable Traffic Patterns:** Allow users to customize traffic patterns and density based on specific timeframes or events (e.g., holidays, festivals).
- **Performance Optimization**: Improve mod performance and reduce lag during peak density events.
- **FiveM Compatibility:** A fully optimized FiveM version of this script is underway and set for release in the upcoming update.

# 🛡️ Protecting the Security of Our Work
Our code is now fully encrypted, and all future mod updates will include protected DLL files. This step is part of our commitment to safeguarding our work against unauthorized access and duplication. This protection also addresses cases where elements of our original code `such as in version 1.0.0` were found replicated in third-party projects

# 📈 Feedback & Support
Your feedback is valuable! If you have suggestions or encounter issues, feel free to reach out through any of the following:

- [Discord](https://discord.com/invite/XcEHvPR9qA)
- [UnionMods](https://unionmods.com/viewauthor?author=592)
- [GTA5Mods](https://www.gta5-mods.com/users/BerkshireMods)
- [LCDPFR](https://www.lcpdfr.com/profile/465231-code-master/)
- [GitHub](https://github.com/CodeMasterLtd)
- [Youtube](https://www.youtube.com/@CodeMaster2024)

#### <span style="color:green">© Code Master 2024 | [CodeMaster.Ltd](https://codemaster.ltd/)</span>
