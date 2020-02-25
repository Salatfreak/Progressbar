# Progressbar
A terminal based countdown with a progressbar

![Progressbar](https://salatfreak.github.io/images/progressbar/progressbar.jpg)

## Usage
progressbar [[START] END]

Counts down to END, showing a graphical progressbar until q or esc is pressed.

The optional START parameter takes the form HOURS[:MINS[:SECS]]. If it is not
specified, the current time is used.

The END parameter takes the form [+]HOURS[:MINS[:SECS]]. With the leading plus,
it is interpreted as an offset relative to the START time. Without the leading
plus, it is interpreted as a time of day.

If no parameters are specified, the program runs in interactive mode and
prompts the user for time specifications until they enter "exit" or "quit".
