# lstwoMODS

lstwoMODS is a set of mods for different games, originally aiming to recreate Azzamods for Wobbly Life. All mods are FOSS (Free and Open Source Software).

# Installation

## Quickest and Simplest

The README for the mod should contain a `mods.lstwo.net/download.php` link that will give you a `.zip` file after a few seconds. To install it, extract the `.zip` file and drag the game's `.exe` file onto the `.bat` file.

Alternatively you can make the `mods.lstwo.net/download.php` link manually for any mods you can install using the [lstwoMODS Installer](https://github.com/lstwoMODS/lstwoMODSInstaller) using the game id and mod ids. You can find the game id by going to the [lstwoMODS Installer repository](https://github.com/lstwoMODS/lstwoMODSInstaller) and opening the folder `data` and `games`. The folder with the game name is the game id. For any additional mods you need to get their mod ids from the mods folder inside the game folder. Then you can create the url by doing `https://mods.lstwo.net/download.php?game=game id&include=mod id,another mod id` replacing the game and mod ids.

## Installer App

Go to the [lstwoMODS Installer repository](https://github.com/lstwoMODS/lstwoMODSInstaller) and follow the steps in the README.

## Manual

1. Install BepInEx 5.X
   
   You can find a guide [here](https://docs.bepinex.dev/articles/user_guide/installation/index.html)

2. Install lstwoMODS and dependencies

   Download the files for [lstwoMODS Core](https://github.com/lstwoMODS/lstwoMODS-Core) (`lstwoMODS_Core.dll`) and [Cinematic Unity Explorer](https://github.com/originalnicodr/CinematicUnityExplorer/) (`CinematicUnityExplorer.BepInEx5.Mono.zip`).
   Then unzip the `CinematicUnityExplorer.BepInEx5.Mono.zip` file and find the dll files inside.

   Take all files and put them into the `<Game Folder>\BepInEx\plugins\` folder. (If it doesn't exist boot up the game or create it yourself)

3. Install modpacks (and additional mods)

   Get an lstwoMODS modpack (eg. [lstwoMODS Wobbly Life](https://github.com/lstwo/lstwoMODS)), download it and it's requirements and put the files into the `<Game Folder>\BepInEx\plugins\` once more.

5. Boot up your game


# License

All projects fall under the [lstwoSTUDIOS license](https://github.com/lstwo/license/blob/main/LICENSE.md)

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
