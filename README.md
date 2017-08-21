## EU4-Player-Map-Creator ##

# What is it for?
  This was created to generate player maps, to help visualize the distribution of players, for the game EU4 on the Discord server "Paradox+".
  
# What does it do?
  player_map_creator.py takes a screenshot map from Europa Universalis 4 and removes countries not listed as player nations. (see example.png for example)
  
# How does it work?
  The program takes a list of countries (player_countries_list.txt) and finds their map color from the EU game files. It then scans an input screenshot map (F10 in-game screenshot) and removes pixels that are not included in the country list.
  
# What programming language?
  player_map_creator.py is written in Python 2.7.13 and uses the Image module. (which must be downloaded seperately)
 
# What are all these other files?
 -README.md is this one, explaining everything.
 -player_map_creator.py is the python program that does all the things
 -player_country_list.txt is a text file containing the list of countries 
 -image_names.txt

# How do I run it?
  You need to have python version 2.7 installed first (https://www.python.org/download/releases/2.7/). Then, in the command shell, enter "pip install Image" to get the Image module. Navigate to whatever directory your program is saved in (using "cd something\something\something") and run it with the command ("python player_map_creator.py").
  
