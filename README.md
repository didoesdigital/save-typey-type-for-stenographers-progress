# Save Typey Type Progress

This project is for saving progress from [Typey&nbsp;Type for Stenographers](https://didoesdigital.com/typey-type/).

# Features

- Script for macOS to save text from clipboard to a text file with a timestamp e.g. `./steno-progress/Wed-31-Oct-2018-1540935304.txt`.
- [Alfred workflow](https://www.alfredapp.com/) for macOS to run the script.

# Installation

1. Download the script, `typey-type-progress`
2. Update the script with your own paths where it says `"$HOME/Dropbox/steno/steno-progress/"`
3. Download the Alfred workflow. Double-click to install it.
4. Update path in Alfred workflow "Run Script" to the location of your script.

Optionally, choose an Alfred hotkey, such as `⌃⌥⌘⇧T`, and add an entry to your steno dictionary, such as `"TAO*EUPZ": "{#Control_L(Alt_L(Super_L(Shift_L(t))))}",`

To make the script executable, you can run `chmod +x ./typey-type-progress`.

When choosing a path for your script and saving your Typey Type progress, you might consider saving it to a location shared across devices, such as Dropbox.

If you want git versioning, initialise a git repo in the folder with your script and uncomment the git lines in the script.



# Usage

Every time you finish a study session on Typey&nbsp;Type, copy your progress from the [progress](https://didoesdigital.com/typey-type/progress) page and run the Alfred workflow (or script) to save it automatically to a file.

