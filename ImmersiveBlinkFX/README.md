# 👀 Immersive Blink FX - V1.3.0 👀

## 🙎🏼‍♀️ Overview

This script adds subtle visual effects to your screen in Grand Theft Auto V (GTA V) that mimic the blinking effect seen when closing and opening your eyes. This enhances immersion and creates a more natural experience when playing..

## 🚀 Features

- **Realistic Blinking:** The script simulates blinking when in first-person view, enhancing the immersion.
- **Configurable Durations:** Customize how long the screen fades out and fades back in during a blink.
- **Randomized Blinking:** Enable or disable random blink intervals to simulate more natural eye behavior.

## 🛠️ Requirements (Singleplayer)
- **ScriptHookV:** [Download ScriptHookV](http://www.dev-c.com/gtav/scripthookv/)
- **ScriptHookVDotNet-nightly:** [Download ScriptHookVDotNet](https://github.com/scripthookvdotnet/scripthookvdotnet-nightly/releases/latest)

## 🔧 Installation (Singleplayer)
1. Copy the `ImmersiveBlinkFX.dll` file to your GTA V `scripts` folder.
2. Configure blink settings via the `scripts\\Code-Master\\Configs\\ImmersiveBlinkFX.ini` file.
3. Done! The script will activate automatically in-game.

## 🔧 Installation (FiveM)
1. Copy the entire `ImmersiveBlinkFX` folder to your server’s `resources` directory.
2. Add `ensure ImmersiveBlinkFX` or `start ImmersiveBlinkFX` to your `server.cfg`.
3. Configure blink settings via the `config.lua` file.
4. Done! The script is now live on your FiveM server.

## ⚙️ Configuration
### FiveM 
Inside `config.lua`, you can modify the following settings:
```lua
config = {
    BlinkDurationIn = 150,    -- Duration for fade out (in milliseconds)
    BlinkDurationOut = 150,   -- Duration for fade in (in milliseconds)
    BlinkInterval = 10000,    -- Default time between blinks (in milliseconds)
    EnableRandomBlinks = false, -- Enable or disable random blink intervals
    RandomBlinkMin = 1000,    -- Minimum random blink interval (in milliseconds)
    RandomBlinkMax = 5000,    -- Maximum random blink interval (in milliseconds)
}
```

### Singleplayer
Inside `ImmersiveBlinkFX.ini`, you can modify the following settings:
```ini
[IBFX_SETTINGS]

; Fade-out duration (entering black screen)
BlinkDurationIn = 150

; Fade-in duration (exiting black screen)
BlinkDurationOut = 150

; Time between blinks in milliseconds
BlinkInterval = 10000

[IBFX_RANDOM_BLINKS]

; Enable random blinks
EnableRandomBlinks = false

; Range for random blink interval MIN
RandomBlinkMin = 1000

; Range for random blink interval MAX
RandomBlinkMax = 10000

; ©2024 CodeMaster.
```

## ⚙️ How to Use
Once installed, the blink effect will automatically activate during gameplay in first person camera ONLY.

## 📋 Changelog

> #### ✔️ V1.3.0 | Enhancements & Bug Fixes
```diff
+ Customizable Random Blinks: Introduced a configurable boolean setting in the INI file to toggle the 'EnableRandomBlinks' feature, allowing users to customize the interval between blinks. This feature generates a random duration within the range defined by RandomBlinkMin (in milliseconds) and RandomBlinkMax (up to 10,000 milliseconds).

+ Removed redundant code: Streamlined the codebase by removing redundant segments, addressing minor stuttering issues encountered during gameplay.

+ FiveM Version: The FiveM version has been completely rewritten in LUA, enhancing clarity and reliability. Initially crafted in C#, the script transitioned to LUA due to persistent errors and a stronger familiarity with the latter language.

- NOTE: If updating to V1.2.0 we recommend deleting previous version files.
```
---

> #### ✔️ V1.2.0 | Enhancements (Requested by JoyLucien on GTA5Mods)
```diff
+ Customizable Random Blinks: Introduced a configurable boolean setting in the INI file to toggle the 'EnableRandomBlinks' feature, allowing users to customize the interval between blinks. This feature generates a random duration within the range defined by RandomBlinkMin (in milliseconds) and RandomBlinkMax (up to 10,000 milliseconds).

+ Removed redundant code: Streamlined the codebase by removing redundant segments, addressing minor stuttering issues encountered during gameplay.

+ FiveM Version: The FiveM version has been completely rewritten in LUA, enhancing clarity and reliability. Initially crafted in C#, the script transitioned to LUA due to persistent errors and a stronger familiarity with the latter language.

- NOTE: If updating to V1.2.0 we recommend deleting previous version files.
```
---
> #### ✔️ V1.1.0 | Enhancements & Realism (Requested by JoyLucien on GTA5Mods)
```diff
+ Customizable Blink Duration:** You can now customize the time it takes for the screen to fade out and fade in (blink duration) by editing the ImmersiveBlinkFX.ini file in the script directory.

+ Periphery-to-Center Effect: I've added a new periphery-to-center effect when blinking, which simulates the screen going black from the edges towards the center during the blink.

+ Renamed DLL FiveM: Renamed FiveM dll from ImmersiveBlinkFX.net.dll to ImmersiveBlinkFX.Client.dll.
```
---
> #### ✔️ V1.0.0 | Initial Release
```diff
+ Blink Effect: Adds a realistic blinking effect to the player's perspective.

+ Beta Release: First beta version of the script. User feedback is appreciated to help refine the feature set.
```
---

## 🛣️ Future Updates
We are continuously working on improving Immersive Blink FX. Future updates may include:

- **Event-Triggered Blinking:** Blinking triggered by specific actions or events in-game.
- **Fatigue Effects:** Dynamic blinking speed based on player exhaustion or other conditions.
- **Visual Enhancements:** Additional effects such as eye strain, blurred vision, and more.

## ⚠️ License & Usage
- **No Copying, Reselling, or Claiming:** This script is the property of ***Code Master***. Do not copy, sell, or claim this script as your own. Unauthorized use or distribution is prohibited.

## 📈 Feedback & Support
Your feedback is valuable! If you have suggestions or encounter issues, feel free to reach out through any of the following:

- [Discord](https://discord.com/invite/XcEHvPR9qA)
- [UnionMods](https://unionmods.com/viewauthor?author=592)
- [GTA5Mods](https://www.gta5-mods.com/users/BerkshireMods)
- [LCDPFR](https://www.lcpdfr.com/profile/465231-code-master/)
- [GitHub](https://github.com/CodeMasterLtd)
- [Youtube](https://www.youtube.com/@CodeMaster2024)

#### © Code Master 2024 | [CodeMaster.Ltd](https://codemaster.ltd/)
