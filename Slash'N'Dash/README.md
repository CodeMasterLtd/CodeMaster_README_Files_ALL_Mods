# <span style="color:darkorange; text-shadow: 0 0 20px black;">Slash'N'Dash</span> - <span style="color:green; font-weight:bold;">V1.0.1</span> / <span style="color:grey; font-weight:bold; font-size: 15px;">Singleplayer Only</span>

  <img src="https://img.gta5-mods.com/q95/images/slash-n-dash/7516e7-image1.jpg" style="box-shadow: 0 0 10px rgba(150, 30, 180, 255); border-radius: 40px; width: auto; height: auto;" alt="Description of the photo">

#
# 🙎🏼‍♀️ Overview

The <span style="color:darkorange; text-shadow: 0 0 20px black; font-size: 15px;">**Slash'N'Dash**</span> script is a GTA V mod that adds dynamic gameplay by allowing players to slash vehicle tyres using melee weapons. It features adjustable detection distances for vehicles, tyres, and police, as well as a configurable key for triggering the tyre slashing action. The script also includes a police alert system, where the player’s wanted level is increased if police are nearby. Additionally, the script supports a customizable config file for personalized settings, providing an immersive and customizable gameplay experience.

# 🚀 Features

- **(1.) Tyre Slashing:**
  - Slash vehicle tyres with melee weapons (e.g., knives, switchblades).
  - Instant tyre burst upon slashing, configurable range for detection.

- **(2.) Police Alert:**
  - Automatically notifies police when a tyre is slashed, raising your wanted level.
  - Customizable detection range for police response.
  - Crime report "Attack on a Vehicle" before being wanted.

- **(3.) Vehicle Alarm:**
  - When a tyre is slashed, there is a configurable `5%` chance that the vehicle's alarm will be triggered.
  - The alarm will start if the vehicle is locked and the tyre has been slashed.
  - If the alarm is triggered, the player’s wanted level may increase if law enforcement is nearby.

- **(4.) Vehicle Detection:**
  - Identifies nearby vehicles within a set distance for tyre slashing.
  - Detection range is configurable in the ini file.

- **(5.) Whitelisted Weapons:**
  - Only specific melee weapons are allowed for tyre slashing, with customizable options.

- **(6.) Keybinding:**
  - Customizable keybinding for tyre slashing actions.

- **(7.) Realistic Tyre Damage:**
  - Tyres burst upon slashing with a realistic effect, preventing re-slashing of burst tyres.

- **(8.) Interactive Feedback:**
  - On-screen message when in range of a tyre, with customizable text.  
___
# ⚡️ Performance Advisory

Slash'N'Dash is optimized for performance, but if any issues arise, please report them for support and troubleshooting.

# 🛠️ Requirements
- **ScriptHookV:** [Download ScriptHookV](http://www.dev-c.com/gtav/scripthookv/)
- **ScriptHookVDotNet-nightly:** [Download ScriptHookVDotNet](https://github.com/scripthookvdotnet/scripthookvdotnet-nightly/releases/latest) - Any version from and above **|> ᴠ3.7.0.6 <|**

# 🔧 Installation
1. Simply drag and drop the `scripts` folder into the root directory of your Grand Theft Auto V installation.

# ⚙️ How to Use
The script will activate automatically in-game. However, you also have the option to customize the settings via the INI file in GTAV/scripts/Code-Master-Configs, which appears once you run the mod for the first time.

# 📋 Versions & Changelog

> ## <span style="color:white; display: block; text-align: center; font-size: 25px; font-weight: bold;">V1.0.1 | Enhancements, New Features & Fixes <span style="color:green; display: block; text-align: right; font-size: 12px; font-weight: bold;">Current Version<span style="color:white; font-size: 14px; text-shadow: 0 0 10px white; text-align: right;"> /</span><span style="color:green; font-size: 14px; text-shadow: 0 0 10px green; text-align: right;"> 🟢</span></span>
>
>- <span style="color:green">🚗 <span style="font-weight: bold; color: white;">More Wheel Support:</span> Enhanced functionality now supports a broader range of wheels. In V1.0.0, certain HGV wheels were not properly detected, but this issue has been resolved.</span>
>- <span style="color:green">🔪 <span style="font-weight: bold; color: white;">More Weapon Support:</span> Now compatible with additional melee weapons for tire-slashing (e.g., machetes, knives, glass bottle and crowbar). <b style="color: lightblue;">Configurable in the ini</b></span>
>- <span style="color:green">🕒 <span style="font-weight: bold; color: white;">Cooldown System:</span> Implemented a cooldown to prevent spamming the tire-slashing feature. Players must now wait for a short period before slashing another tire.</span>
>- <span style="color:green"> 🚶‍♂️ <span style="font-weight: bold; color: white;">Animation Fix:</span> Resolved an issue where <b style="color: lightblue;">Wait()</b> was missing from the script, ensuring smoother and more consistent animation.</span>
>- <span style="color:green"> 🔔 <span style="font-weight: bold; color: white;">Tyre Text Enhancements:</span> Improved the visual presentation of the <b style="color: lightblue;">"Press 'E' to - Slash'N'Dash"</b> prompt for better clarity and user experience.</span>
>- <span style="color:green">🚨 <span style="font-weight: bold; color: white;">Police Detection System:</span> Enhanced detection logic. If cops are nearby while a player slashes a tire (Police will now be alerted more realistically, A wanted level will be issued if within their field of view).</span>
>- <span style="color:green">📂 <span style="font-weight: bold; color: white;">Dynamic Directory Handling:</span> Introduced `AppDomain.CurrentDomain.BaseDirectory` to dynamically detect the game's installation directory, ensuring compatibility across all drives (e.g., C, D, E). This improves INI file handling and guarantees seamless operation regardless of the game's installation path.</span>
>- <span style="color:green;">🚘 <span style="font-weight: bold; color: white;">Tyre Status Feedback:</span> Tyres now provide feedback when slashed. Players will be informed if a tyre is <b style="color: lightblue;">"burst"</b>.</span>
>>- <span style="color:green">🤖 <span style="font-weight: bold; color: white; ">AI Response to Tyre Slashing:</span> Added randomized AI behavior when a vehicle's tires are slashed. NPC drivers may now:
>>- <span style="color:lightblue; font-weight: bold;">Swerve unpredictably.</span>
>>- <span style="color:lightblue; font-weight: bold;">Pull over and stop the vehicle.</span>
>>- <span style="color:lightblue; font-weight: bold;">Attempt to evade aggressively.</span></span>
> ### <span style="color:orange; display: block; text-align: left; font-size: 15px; font-weight: bold;">INI Changes in This Version
> - <p>This update introduces changes to the INI file. These changes will be applied automatically while preserving your existing settings, ensuring a seamless update experience.</p>
>---

> ## <span style="color:white; display: block; text-align: center; font-size: 25px; font-weight: bold;">V1.0.0 | Initial Release <span style="color:darkorange; display: block; text-align: right; font-size: 12px; font-weight: bold;">Previous Version<span style="color:white; font-size: 14px; text-shadow: 0 0 10px white; text-align: right;"> /</span><span style="color:darkorange; font-size: 14px; text-shadow: 0 0 10px darkorange; text-align: right;"> 🟠</span></span>
>
>- <span style="color:green"> 🆕 <span style="font-weight: bold; color: white;">Initial Release:</span> This script is now available for download.</span>
>---

# 🔮 Future Updates
### We are continuously working on improving Slash'N'Dash. Future updates may include:

- **AI Response to Tyre Slashing:** AI drivers react dynamically to their tyres being slashed, such as swerving, pulling over, or attempting to evade the player.
- **Localized Impact Effects:** Visual effects showing smoke, sparks, or fluids when tyres are slashed, enhancing realism.
- **Vehicle Type Detection:** Slashing effects change depending on vehicle type (e.g., motorcycles have different slashing effects than cars).
- **Tyre Deflation:** We initially introduced this feature in version 1.0.1; however, due to performance concerns, we decided to temporarily remove it. This will allow us to optimize the functionality for a smoother experience in the next version.

# 🛡️ Security & Code Protection
To safeguard against unauthorized duplication, Slash'N'Dash now includes encrypted DLL files.


# 📈 Feedback & Support
Your feedback is appreciated! For suggestions, support, or bug reports, reach out via:

<a href="https://discord.gg/3MKyscCXkk" target="_blank">
  <img src="https://avatarfiles.alphacoders.com/367/thumb-1920-367017.png" style="width: 50px; height: auto;" alt="Description of the photo">
</a>

#### [© Code Master 2024](https://codemaster.ltd/)
