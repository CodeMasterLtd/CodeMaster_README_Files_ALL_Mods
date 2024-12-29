The **Nuke & Radiation System** is a comprehensive script designed for GTA V servers running on FiveM. This script introduces a realistic and immersive experience by simulating nuclear radiation zones and alerting players when they are in danger. Here's what the script does:
#

# Features:
### 1. Radiation Zones:

- Defines multiple radiation zones with specific coordinates and radius.
- Players entering these zones will receive visual and audio alerts.

### 2. Nuclear Alert System:

- Automatically triggers a nuke alarm when players spawn into the server.
- Displays a warning message and plays a nuke alarm sound to alert players of the imminent danger.


### 3. Health Impact:

- Players inside the radiation zones will take damage based on their proximity to the center of the zone.
- The closer a player is to the center, the more damage they receive.

### 4. Visual and Audio Effects:

- Applies visual effects to simulate the impact of radiation.
- Plays specific sounds to enhance the immersive experience.

### 5. HUD Integration:

- Displays a radiation bar and icon on the player's HUD, indicating their radiation exposure.
##

# How It Works:

**Configuration (`config.lua`):**

- Defines the radiation zones and alert messages.

**Client-Side Script (`client/client.lua`):**
- Processes NUI messages to update the HUD.
- Manages the radiation zones and player health.
- Sends notifications and triggers sounds.
- Handles player spawning events to automatically trigger the nuke alarm.
#

# Usage:
### When a player enters a radiation zone:

- They receive a warning message.
- The radiation bar and icon appear on their HUD, updating in real-time to show their exposure level.
- They start taking damage based on their proximity to the zone's center.
- Radiation visual effects are applied to simulate the impact.
- Radiation sounds are played to enhance the immersive experience.

### When a player spawns:

- They are automatically alerted with a nuke alarm sound and a warning message.

# Installation:
- Place the **Nuke & Radiation System** folder in your server's resources directory.
- Add ensure **Nuke & Radiation System** to your server.cfg file.
- Configure the radiation zones and alert messages in config.lua.
 >### Enjoy
