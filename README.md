# SST_NavTask
Panda3D / PandaEPL-based virtual navigation task

This code underlies the task analyzed in https://github.com/sgagnon/SST

Dependencies include Panda3D v1.8, PandaEPL, sendShock2.ino (for programming Arduino Uno shock delivery box; from github.com/thackerybrown/felix/scripts)

Note that at this time (05/23/2017), the model files on which this code depends are not shared in a remote repository. 

Note that the directory structure in this repository is not functional at this time - the main task scripts (TboyLite_multienv.py) assume they are in the same directory as the config.py file that they reference, and will generate a data directory in their current directory. In this repository, for organizational purposes, the unique config files are placed within randomization subdirectories. This is probably optimal, in the long run, and one coding goal may be to accomodate this cleaner directory structure
