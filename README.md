# KingMC Minecraft Bot Auto Order



---

## Requirements

Before running the bot, make sure you have:

- **Node.js v18 or newer**  
  Download: https://nodejs.org  
- A stable internet connection

Check your Node version:

```bash
node -v
Installation
Open the project folder in Terminal or Command Prompt and run:

npm install
This installs all required dependencies.

Configuration
Create a file named .env in the project folder and add:

MC_HOST=kingmc.vn
MC_PORT=25565
MC_USERNAME=your_bot_name
MC_PASSWORD=your_password
MC_VERSION=1.20.4

TARGET_PLAYER=player_order_bone

BONE_X=your_coord
BONE_Y=your_coord
BONE_Z=your_coord

BLAZE_X=your_coord
BLAZE_Y=your_coord
BLAZE_Z=your_coord
Run Bot
Start the bot with:

node final.js
