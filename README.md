# gary_for_canary
gary solution for canary

this guy should be able to click a square area on your screen and fill a GOTE.

was developed and tested on `Python 3.9`

should work on every platform that can install python and the requirements

can't really be used while playing other games

## Installation
If you've got python3.9 on windows, you should be able to install the requirements by openining a terminal in the project folder and then running

`$ pip install -r requirements.txt`

if you dont know how to open a terminal on your computer, just google `how to open terminal on windows`

if you dont know how to open a terminal on your computer, then you probably also haven't installed python which is needed to run this project.
 
On MAC/unix based operating systems, you'll probably have to define that we're using `pip3` as most of them can have python2 and pip2 installed. Like above, navigate to the project folder, open a terminal there and then run

`$ pip3 install -r requirements.txt`

## running
call python to run the projects main file by inserting `$ python3 gary.py` to your terminal

### 1. Setting up your clicking areas
use your right-click to create a square shapeed area on screen which will not cause your character to move if clicked in. The square isn't visible on screen because I couldnt find an easy solution on how to draw on screen and didnt really want to put too much time into this.

use your middle-click to create a square shaped area around your GOTE, all of the pixels within this area should activate the GOTE-dropdown menu if right-clicked in.

after both squares (4 coordinates each) have been created, you can continue by using right-click or middle-click once.


### 2. Setting up your GOTE charging height
the program will then ask you to charge your GOTE once, its going to recurd the height between the right-click to activate GOTE dropdown menu and left-click to "charge all porters". After you've charged this once, the programs main loop will start and you can go to bed.
