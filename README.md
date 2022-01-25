![Ursarion](https://github.com/GemYearInteractive/Ursarion/blob/main/Images/base_github.png?raw=true)

# VERSION 0.1 PRE-ALPHA COMING SOON!

## What is Ur-Sar-E-On?
Ursarion is a terminal text RPG and Sandbox taking place in the Land of Ursarion. Carve your own path in the land and/or follow the storyline to legend in Ursarion. Ursarion is akin to a digital "choose your own adventure book" with RPG elements and near-infinite possibilies. No need to turn to page x. 


### Controls
Controls in Ursarion are simple. Numbers in green indicate that it will perform an action. Simply press the number corresponding to the action you want to do, then press ENTER to confirm your selection.

![Ursarion main menu demo-ing controls](https://github.com/GemYearInteractive/Ursarion/blob/main/Images/image_2022-01-25_142300.png?raw=true)

## Code Side of Ursarion

Ursarion is a very light software, the game file is currenltly 50 Kilobytes. Meaning even an MP3 of a game sound is way larger than the game file. However, future versions will be likely to get into the Megabytes. This is the size of the .py file and not the end-user .exe file. The size of the .exe file is unknown as an exe build has not yet been made. One will be made once 0.1 goes gold and will be the way and end-user will play.

Ursarion is programmed natively in Python 3.9, with the help of 10 Python Modules. 
Big thanks to Python and the devs of these modules for making Ursarion possbile.

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
