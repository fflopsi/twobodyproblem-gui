# Two Body Problem &ndash; GUI

### The GUI to the simulation

**Welcome!**

This is the repository for the graphical user interface of
[this repository](https://github.com/fflopsi/twobodyproblem) containing the
base simulation. For more information about the whole program, go there.

In this additional GUI, there are more possibilities than in the normal (CLI)
program. For example, you can choose from presets instead of typing in your own
parameters, have a more convenient interface to edit them, and more.

## Installation

*(You may need Microsoft Visual C++ to be able to run the program, so install
it from [here](https://visualstudio.microsoft.com/visual-cpp-build-tools) if
needed.)*

### Via PyPi

*The Python package manager pip will install the last uploaded version from the
Python Package Index [PyPi](https://pypi.org/project/twobodyproblem_gui). This
will not always be the latest version, so if you want to install all the latest
features, install it from GitHub (see [below](#via-github)).*

1. Make sure [Python](https://www.python.org/downloads) and pip are installed
   correctly.
1. Run these commands from a command line:
    1. `pip install --upgrade pip setuptools wheel`
    1. `pip install --upgrade twobodyproblem_gui`
1. Now, the program is usable with `python -m twobodyproblem_gui`.

### Via GitHub

1. Install the
   [base program](https://github.com/fflopsi/twobodyproblem#via-github)
1. Run these commands from a command line:
    1. `cd TwoBody` (or whatever folder you stored the base program files in)
    1. `git clone https://github.com/fflopsi/twobodyproblem-gui.git`
    1. `pip install ./twobodyproblem-gui/`
1. Now, the program is runnable with `python -m twobodyproblem_gui`.

## Usage

*To learn more about how to run the program with different options,
run `python -m twbodyproblem_gui -h`.*

*To learn more about the base program / the simulation itself, read
[this](https://github.com/fflopsi/twobodyproblem#usage) first.*

Run the program with `python -m twobodyproblem_gui` on a command line.

The program will open a window with some input fields. This is the main window
where you input the values. To save values, press <kbd>Ctrl</kbd>+<kbd>S</kbd>.
The values will then be saved into a file. If you do this action repeatedly,
the previous contents of the file (i.e. the saved values) will be
**overwritten**! To load saved values from this file, press
<kbd>Ctrl</kbd>+<kbd>L</kbd>. To save or load values through a file dialog,
press <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>S</kbd> or
<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>L</kbd>. It works the same way for saving
and loading settings from the settings window (open it with
<kbd>Ctrl</kbd>+<kbd>I</kbd>).

You can also select from a few presets (e.g. Sun, Moon, Earth) to fill in some
values instead of typing your own. To do so, press <kbd>Ctrl</kbd>+<kbd>E</kbd>
to select from the drop-down menus and press one of the two buttons in the
lower right corner.

To start the simulation, press the button in the lower right corner in the main
window.
