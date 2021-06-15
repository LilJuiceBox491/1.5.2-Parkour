# 1.5.2-Parkour

## DESCRIPTION
A work-in-progress parkour map for Minecraft 1.5.2. Insipred by the UltraCraft island.

## HOW TO USE
1. Download the entire `Parkour/` folder to your computer
2. Navigate to your computer AppData. On Windows, type `%appdata%` in your File Manager bar. On Mac, open spotlight (Command + Space), and enter `~/Library/Application Support/minecraft`
3. Navigate into the `.minecraft/` folder. Inside there, go to the `saves/` folder.
4. Move the `Parkour/` folder into said saves folder.
5. Boot up Minecraft 1.5.2 or higher (patch). Any version above 1.5 **WILL NOT WORK** due to a JSON format change.
6. The world will be in your Singleplayer section, saved as "Parkour".

## 1.5.2 NOT LOADING PROPERLY?
In Minecraft 1.6, Mojang changed the structure of a specific file, `options.txt`. Due to this, loading up older versions (like 1.5.2) in the same directory **WILL NOT WORK**. Thankfully, there is a simple fix. All we need to do is allow the older version to write it's own `options.txt` file.
1. Copy your entire `.minecraft/` folder (see above) and paste it into another place on your computer. It could be your `Downloads/`, `Desktop/`, or even another folder in your `AppData/`. 
2. Next, go inside your new Minecraft folder copy. Find `options.txt` and delete it.
3. Now, open your Minecraft launcher. If you already have a 1.5.2 installation, skip the next step.
4. If you don't have a 1.5.2 installation, create one by simply going to the installations tab in the launcher. Click the New installation button. Choose any name and icon. For version, scroll down to 1.5.2 and select it. Click create.
5. To apply our new Minecraft directory to this version, click the three dots next to the installation in the installations tab. Click edit in the dropdown.
6. Look at the Game Directory section. Click browse, and select your new Minecraft directory.
When you boot up the game, Minecraft will automatically write the options.txt file, and you are good to go!

# Enjoy!
