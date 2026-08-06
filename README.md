# Clash AutoLoot

## Summary
Automated farming bot for Clash of Clans on PC (Google Play Games). Farms Gold/Elixir hands-free in **Home Village** using Valkyries, Sneaky Goblins, Super Minions, or Electro Dragons — or farms **Builder Base** with Baby Dragons. Includes multi-account support, star bonus tracking, auto wall upgrades, and automatic elixir cart collection in Builder Base.

<img width="1265" height="755" alt="exmapleautoloot" src="https://github.com/user-attachments/assets/8b31faab-8971-4e2c-8d00-4859a91438a8" />

## Highlights
- Uses Google Play PC - Virtually undetectable "official" way to play Clash of Clans on PC (Unmodifiable emulator, unlike Bluestacks/Ldplayer)
- Works with the game window behind others (no cursor hooks)
- **Home Village** and **Builder Base** farming from the same app
- Multi-account rotation with name matching from the in-game list
- Upgrades walls automatically when storages are full (Home Village)
- **Builder Base** — Baby Dragon raids, loot prioritisation (Gold / Both / Elixir), and full elixir cart collection after each attack
- **180M+ Loot per hour** (Gold + Elixir at TH18)
- Smart, random, and humanlike placement, clicks, and drags.
- Multiple accounts stress tested for several hours everyday for months, survived 4+ ban waves

## HOW TO USE

### Prerequisites
- **Windows 10/11**.
- Google Play PC - **Clash of Clans**
- Aspect ratio of 16:10 or 16:9

### Install

1. Open **[Releases](https://github.com/clashautoloot/Clash-AutoLoot/releases)** for this project.
2. Download the latest **`ClashAutoLoot.exe`** (or the main Windows build attached there).
3. Save it somewhere you’re happy to run it from (Desktop or a folder is fine). You can run it as-is; no Python install needed.

### Before you run it

- **Make sure to fullscreen your game and it should be running on your primary monitor if you have multiple.**
- If the game window isn’t open yet, the app can still start—just open Clash before you press **Start** on the bot.
- At the top of the Run page, choose **Home Village** or **Builder Base**. The bot will switch villages automatically if you’re on the wrong one when you start.

#### Home Village setup
- Make sure you're in the **Home Village** (or select **Home Village** in the app and let the bot switch you there).
- Make sure your deployment bar icons are set to default (2 rows work)
- **Make sure you have an army of all valkyries, earthquakes, and log launcher at the top of your saved recipe armies.** 
<img width="1142" height="275" alt="image" src="https://github.com/user-attachments/assets/f37362f6-8e2b-4b8c-9185-0f3f5d0cfc0f" />

*Example of a Valk setup*

- Other army strategies require you to manually select troops in your current army because some are super troops and need to be boosted.

<img width="1127" height="577" alt="image" src="https://github.com/user-attachments/assets/a82f6de6-e461-461e-b9aa-6349448dff55" />

*Example of a Super Minion setup*

#### Builder Base setup
- Manually fill the same type troop in your builder base armies (future update you won't)

### Using the app

1. Open Clash of Clans and leave the window open or in the background, but don't minimize it.
2. Double-click **`ClashAutoLoot`** to open it.
3. Enter and activate your **license key** (see below).
4. At the top, choose **Home Village** or **Builder Base**.
5. Pick your **attack strategy** (options change depending on which village you selected).
6. Toggle on and off **Multi-run**, **Star Bonus**, or **Ranked attack fill** (Home Village only — more info below).
7. Type **how many minutes** to farm (or use the quick **5m / 10m / 20m** buttons), or turn on **Star Bonus**.
8. Click **Start** when you’re ready. Use **Stop** anytime — it should stop within a few seconds. You may also see **Start/Stop** on the **taskbar preview** when you hover the app.
9. **Clicking or refocusing the window may disturb the bot occasionally while it's running** — simply stop and start on your home village (or Builder Base) to fix it.

### Home Village

**Attack strategies:** **Valkyries**, **Sneaky Goblins**, **Super Minions**, or **Electro Dragons**

**Modes:**
- **Star Bonus** — keeps going until you have no star bonus to collect, then stops on its own.
- **Multi-run** — uses your player list; enter Supercell IDs, case sensitive. Order matters: that’s the order it visits accounts. After each account’s Home Village session, the bot can also boat to Builder Base to collect resources and use the clock boost before returning home.
- **Ranked attack fill** — uses **ranked** battles instead of regular farming. Only enable it if you’re okay using up ranked attacks during your run.
- **Upgrade walls** — auto upgrades your walls once your storages are full. Spare builder required. Use it if you're running it for longer than 20 minutes!

### Builder Base

**Attack strategy:** **Baby Dragon** (Night Witches is shown but still under development)

**How a raid works:** Attack → Find Now → deploy Baby Dragons (and Battle Machine / Flying Machine if on your bar) → end battle or surrender based on your prioritise setting → Return Home → collect a full elixir cart if one is visible.

**Prioritise** (click the **?** for details):
- **Gold** — waits until **2 stars**, then ends the battle.
- **Both** — waits until **1 star**, then ends the battle.
- **Elixir** — **surrenders immediately** after deploying troops (you’ll get a warning first — this will deplete trophies).

**Star Bonus** works in Builder Base too — the bot stops when the Builder Base star bonus is finished.

**Under development for Builder Base:** Upgrade walls and Multi-run toggles are visible but not active yet.

### License key

A free trial of 1 hour runtime is given, which after a valid license key is required to use the bot.

1. Head over to the license page where you can choose to buy a subscription or lifetime license.
2. After purchasing, you will receive an email with a key in the format `CLASH-XXXX-XXXX-XXXX-XXXX`. If you're extending, just reuse the same license key.
3. Open the bot and paste the key into the **License Key** field at the top.
4. Click **Activate**. The indicator dot turns **green** when the key is valid.
   - **Green** = valid and ready to use.
   - **Yellow** = checking (or temporarily unable to reach the server — retrying).
   - **Red** = key is empty, invalid, revoked, or the server has been unreachable for more than 15 minutes.
5. The key is **bound to this machine** on first activation. To transfer to a new machine, Click the **Unpair** button in the license key menu.

> **Internet connection required.** The bot validates your license on startup and periodically while running. There is no offline mode. 

### CONTACT ME
Have any questions, concerns, or feedback? Feel free to reach out to me at **clashautoloot@gmail.com**

Disclaimer: This tool automates gameplay which is against Clash of Clans' ToS — use it at your own risk. I'm not responsible if your account gets banned.
