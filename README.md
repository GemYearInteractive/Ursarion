![Ursarion](https://github.com/GemYearInteractive/Ursarion/blob/main/Images/base_github.png?raw=true)

# VERSION 0.1 PRE-ALPHA COMING SOON! INFO BELOW.

## What is Ur-Sar-Ee-Un?
Ursarion is a terminal text RPG and Sandbox taking place in the Land of Ursarion. Carve your own path in the land and/or follow the storyline to legend in Ursarion. Ursarion is akin to a digital "choose your own adventure book" with detailed RPG elements and near-infinite possibilies. No need to turn to page x. 


### Controls
Controls in Ursarion are simple. Numbers in green indicate that it will perform an action. Simply press the number corresponding to the action you want to do, then press ENTER to confirm your selection.

![](https://github.com/GemYearInteractive/Ursarion/blob/main/Images/image_2022-01-25_142300.png?raw=true)
>Ursarion main menu demo-ing controls.

## Ursarion v0.1
Ursarion v0.1 is the pre-alpha build and will be the first playable version. It is a farcry from the final vision I have for Ursarion, but is still a fun base with a lot more to come. 

0.1 will include:

- 3 player classes
- 3 places (Each including multiple dungeons, shops and other points of interest)
- 5 enemy types (Each including multiple mobs with differing effects)
- 5 detailed status effects (For player and enemies)
- 25% of all audio planned (0.1 will have 3 soundtracks and contextual audio)
- **Save your progress** (Only 1 save for now)

### Ursarion 0.1 will release in early March! (DATE SOON)

## Code Side of Ursarion

### Overview
Ursarion is a very light software, the game file is currenltly 50 Kilobytes. Meaning even an MP3 of a game sound is way larger than the game file. However, future versions will be likely to get into the Megabytes. This is the size of the .py file and not the end-user .exe file. The size of the .exe file is unknown as an exe build has not yet been made. One will be made once 0.1 goes gold and will be the way an end-user will play.

Ursarion is programmed natively in Python 3.9, with the help of 10 Python Modules. 
Big thanks to Python and the devs of these modules for making Ursarion possbile.

### Python Modules Used in Ursarion


Those modules are (not in order appearing in code):

Third Party Modules:
- [Pygame (currently for audio)](https://github.com/pygame/pygame)
- [TQDM (for progress bars)](https://github.com/tqdm/tqdm)
- [Colorama (for coloured text)](https://github.com/tartley/colorama)

Built-in Modules:
- OS Module (for **SAVEFILE** and to clear game screen)
- Pickle (for save/load)
- pathlib Module (for **SAVEFILE** filepath)
- Random Module (for psudo-random operations, RNG)
- Time Module (to add time delays)
- Datetime Module (for Ursarion to know the date,time and year)
- Glob Module (helps **SAVEILE**)
