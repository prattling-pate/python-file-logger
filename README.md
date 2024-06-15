# Python File Logger

This was created to aid in my project so I am putting it in a repo here for my (and possibly others') future use.

This repo hosts a logger.py file which contains a logger which can output to a seperate file (helpful when debugging terminal apps), 
simplify clone and copy the files into your project and then create a logger file specifying a logfile you want to use:

```
# import the logger class
from utility.logger import Logger

path_to_log = "log.txt"

# create the logger object
logger = Logger(path_to_log)

#.log saves the given string in the log file
logger.log("I am logging this")

# saves log to the given file
logger.write_log()
```

Simple as that!
