# Clash-AutoLoot
## HOW TO USE

### Install

1. Open **[Releases](https://github.com/Clash-AutoLoot/releases)** for this project.
2. Download the latest **`ClashAutoLoot.exe`** (or the main Windows build attached there).
3. Save it somewhere you’re happy to run it from (Desktop or a folder is fine). You can run it as-is; no Python install needed.

### Before you run it

- Use **Windows**.
- Play **Clash of Clans on PC** (for example Google Play Games).
- Run the game in a **normal widescreen window**—either a standard 16:9 shape or a slightly taller 16:10-style layout. Don’t use a random or extreme crop; if the shape isn’t supported, the app may close right after opening with a short message.
- If the game window isn’t open yet, the app can still start—just open Clash before you press **Start** on the bot.

### License key

A valid license key is required to use the bot.

1. After purchasing, you will receive an email with a key in the format `CLASH-XXXX-XXXX-XXXX-XXXX`.
2. Open the bot and paste the key into the **License Key** field at the top.
3. Click **Activate**. The indicator dot turns **green** when the key is valid.
   - **Green** = valid and ready to use.
   - **Yellow** = checking (or temporarily unable to reach the server — retrying).
   - **Red** = key is empty, invalid, revoked, or the server has been unreachable for more than 15 minutes.
4. The key is **bound to this machine** on first activation. To transfer to a new machine, contact support at [clashautoloot@gmail.com](mailto:clashautoloot@gmail.com).

The bot re-validates the key every 3 hours in the background. If your key is revoked while the bot is running, it will stop automatically.

> **Internet connection required.** The bot validates your license on startup and periodically while running. There is no offline mode.

### Using the app

1. Open **Clash of Clans** and leave the window visible.
2. Double-click **`ClashAutoLoot`** to open it.
3. Enter and activate your **license key** (see above).
4. Pick how you want to attack: **Valkyries**, **Sneaky Goblins**, or **Super Minions**.
4. **Multi-run** (optional): turn it on, then **Player list…** to add the account names you see in-game, choose who runs and who is skipped, and put them in the order you want. At least one account must be set to run.
5. **Ranked attack fill** (optional): only turn this on if you **want** to spend ranked attacks; you’ll get a confirmation screen first.
6. Either type **how many minutes** to farm (or use the quick **5m / 10m / 20m** buttons), or turn on **Star Bonus** to farm until your daily star bonus is done (the timer is turned off in that mode).
7. Click **Start** when you’re ready. Use **Stop** anytime—it should stop within a few seconds. You may also see **Start/Stop** on the **taskbar preview** when you hover the app.

### Star Bonus

With **Star Bonus** on, the bot keeps going until it no longer sees the “you still have a bonus to earn” stars on your home screen, then it stops on its own.

### Multi-run

The app saves your player list as **`player_list.json`** in the **same folder** as **`ClashAutoLoot.exe`**. Order matters: that’s the order it visits accounts. **Skip** means it won’t farm that account this round.

### Ranked attack fill

This uses **ranked** battles instead of regular farming. Only enable it if you’re okay using up ranked attacks during your run.
