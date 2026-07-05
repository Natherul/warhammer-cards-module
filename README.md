# Warhammer 3e Cards Compendium

This Foundry VTT module provides a complete, neatly organized compendium of Actions and Talents for the WFRP3e system. It includes over 860 Actions and nearly 200 Talents directly parsed into their proper `conservative` and `reckless` data structures, along with correctly formatted symbols for success, boons, banes, exertion, and more.

## Installation

To install this module in your Foundry VTT instance:

1. Open Foundry VTT and go to the **Add-on Modules** tab.
2. Click **Install Module**.
3. In the Manifest URL field, paste the following link:
   ```
   https://github.com/USERNAME/warhammer-cards-module/releases/latest/download/module.json
   ```
4. Click **Install**.

*(Note: Replace `USERNAME/warhammer-cards-module` with your actual GitHub repository path if you fork or host this yourself.)*

## What's Included

* **Actions Compendium**: `cards-items` pack containing Action and Talent items formatted securely for the WFRP3e system.
* **Fully Configured Mechanics**: 
    * `DifficultyModifiers`, `Check`, and `Requirements` are pre-filled.
    * The WFRP3e font icons (e.g. `{Dsucc}`, `{Dboon}`, `{Dbane}`) are seamlessly integrated into the descriptions so that everything renders flawlessly on the WFRP3e character sheet!
* **Matched Artwork**: Includes image links matching all original card artwork (assuming they were packaged).

## Contributing / Updating

This module automatically bumps its minor version and creates a new release whenever you push a commit to the `main` branch. 

To update the compendium data:
1. Unpack the LevelDB directory `packs/cards-items` using the Foundry CLI: `npx fvtt package unpack cards-items`.
2. Edit the JSON source files in `packs/source/cards-items`.
3. Commit and push! The GitHub Action will automatically pack the module and cut a new release.
