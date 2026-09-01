# Kacperczyk Discography Manual APWorld for Archipelago

## What is Archipelago?
Archipelago is a multiworld multi-game randomizer (See: [Archipelago Website](https://archipelago.gg/))

## What is a manual APWorld?
A manual is system created initially to allow games, which do not allow modding to be played in an Archipelago setting. In order to achive that, a player must manually (hence the name "Manual") track everything they have done in a game. However, tracking everything by hand would be extremely tedious, the team behind manuals also made "Manual Client", which lets a player check off locations similarly to a To-Do list.

## How do you play a discography?
Every singular song (except starting three) must be "unlocked" by getting a check from the multiworld. After that you can mark (via the Manual client) that you have listened through the song, sending a location to the multiworld.

Because of this specific implementation (1 unlocked song = 1 location), this APWorld is meant to be played alongside other games with more balanced out distribution of locations.

# Setup guide

## Requirements
- Latest Archipelago launcher version ([Setup guide](https://archipelago.gg/tutorial/Archipelago/setup_en))
- Latest APWorld version from [release page](https://github.com/life8853/Manual_Kacperczyk_Discography/releases)
- Latest version of the [Universal Tracker](https://github.com/FarisTheAncient/Archipelago/releases) APWorld

## Generating a multiworld game
1. Install Archipelago Launcher (link to the setup guide above)
2. Install both the Universal Tracker APWorld and this APWorld by double clicking (or manually placing them in the `custom_worlds` folder in Archipelago's install directory)
3. Open Archipelago Launcher
4. Inside the Archipelago Launcher open the Options Creator
5. Use the Options Creator to configure your playthrough
6. Export the player options file into the `players` folder
7. Open the Generate program inside of Archipelago Launcher. The output file is automatically put in the `output` folder after generation.
8. Using the zip file host your own game (e.g by using [archipelago.gg](https://archipelago.gg/uploads))

## Connecting to the game
1. Open Archipelago Launcher and launch the Manual Client
2. Use the dropdown labeled `Manual Game ID` to choose what manual are you using. For this APWorld should be set to "manual_kacperczykdiscography_life8853"manual_kacperczykdiscography_life8853"manual_kacperczykdiscography_life8853
3. Use the input box on the top to input the connection info. The format is IP_ADDRESS:Port. For example: "archipelago.gg:65111"
4. Click the connect button
5. Use the command line box to input your player/slot name (the same name you have put in the Options Creator)
6. Switch over to the Manual tab to start playing.