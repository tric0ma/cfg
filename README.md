# cfg
Config file for cs2 that could help to improve FPS and gamplay.

Make shure that you habe the console enabled in game configuration > key binding

First of all, we have to add the following commands to the interpreter in our cs2 at Steam library:
  Open Steam > go to library > second click on Counter Strike 2 > click on properties > scroll down until you see an input box called "launch parameters" at the end.
  Copy and paste the following commands:

    -allow_third_party_software -novid -nojoy -high -threads 16 -cl_forcepreloads 1 -tickrate 128 +exec autoexec.cfg

  The most important command is "+exec autoexec.cfg" which allows us to run the configuration file every time we start the game.

The second step is to download the config file from the repository. You can download the ZIP or use the following command to download the file in your actual directory:
  git clone https://github.com/tric0ma/cfg.git

Finally you only have to copy the config file called "autoexec.cfg" and paste in the cfg folder in cs2, by default, it uses the following direction:
  C:/Program Files (x86)/Steam/steamapps/common/cs2 or csgo folder/game/core/cfg 

Close all the windows and launch the game like always. If you enter a game you can probably see the changes in the hub. You can press the button, by default, 'º' to open a console and then type:
  exec autoexec.cfg

  You can read the log that says the config file was loaded successfully.
  
