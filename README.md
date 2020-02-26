# Progressbar
A terminal based countdown with a progressbar

![Progressbar](https://salatfreak.github.io/images/progressbar/progressbar.jpg)

## Usage
`progressbar [-r ROWS] [-c COLS] [-z ZOOM] [-h] [[START] END]`  
 -r, --rows   Set height of the terminal if opening one  
 -c, --cols   Set width of the terminal if opening one  
 -z, --zoom   Set zoom of the terminal if opening one  
 -h, --help   Show this help and exit  

Counts down to END, showing a graphical progressbar until q or esc is pressed.

The optional START parameter takes the form HOURS[:MINS[:SECS]]. If it is not
specified, the current time is used.

The END parameter takes the form [+]HOURS[:MINS[:SECS]]. With the leading plus,
it is interpreted as an offset relative to the START time. Without the leading
plus, it is interpreted as a time of day.

If no parameters are specified, the program runs in interactive mode and
prompts the user for time specifications until they enter "exit" or "quit".

The program checks if it is running in a terminal at startup and starts itself
in an xfce4-terminal, if it doesn't. Feel free to specify another terminal
emulator in the TERMINAL variable at the top of the program code.
