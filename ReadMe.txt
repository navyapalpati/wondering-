Final Project (Software Engineering):
Can you help patrick find spongebob?

Development Environment:
    Editor: Pycharm
    link: https://www.jetbrains.com/pycharm/

Pre-requirement:
  pygame: type in "pip3 install pygame" in terminal
  install instructions reference: https://www.pygame.org/wiki/GettingStarted
  
Game Mode Available:
  EASY: 300*300
  MEDIUM: 500*500
  HARD: 1280*800
  VERY HARD: 2560*1600
  Build your map: limited size as 999*999
  
  
How to control:
  Patrick(user 1):    is able to press keyboard "w", "s", "a", "d" to move up, down, left, right
  Spongebob(user 2):  is able to press keyboard up, down, left, right to move up, down, left, right
  Sandy(user 3):      is able to press keyboard "1", "2", "3", "4" to move up, down, left, right
  Squid(user 4):      is able to press keyboard "6", "7", "8", "9" to move up, down, left, right
  
Game Finish Requirement:
    dual player mode:   When Patrick sees spongebob, game is over and a celebration screen will be displayed with the celebration sound
    3 player mode:      When Patrick meets both spongebob and sandy, game is over and a celebration screen will be displayed with the celebration sound
    4 player mode:      When Patrick meets both spongebob, squid and sandy, game is over and a celebration screen will be displayed with the celebration sound
  
Bump into the wall:
  Patrick/Spongebob/Sandy/Squid don't have superpower so if they hit the wall they will be forced to go back to recent position with a collision sound
  

K2   -> refer as basic game mode. The map size is fixed
K3-5 -> refer as build your map mode. The map size is changeable
        multiple player mode

k6-8 -> There is two panel, 1 is for player manual input and 2 is for stimulation purpose.
        player manual input mode is the k6-8 mode

Data storage:
    For user manual input mode data(contains map size and step counter) are stored in "data.txt"
    For random stimulation mode data(contains map size and step counter) are stored in "random.txt"
