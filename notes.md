# Truffula Notes
As part of Wave 0, please fill out notes for each of the below files. They are in the order I recommend you go through them. A few bullet points for each file is enough. You don't need to have a perfect understanding of everything, but you should work to gain an idea of how the project is structured and what you'll need to implement. Note that there are programming techniques used here that we have not covered in class! You will need to do some light research around things like enums and and `java.io.File`.

PLEASE MAKE FREQUENT COMMITS AS YOU FILL OUT THIS FILE.

## App.java
summary:
this file looks to be a type of core script. It does a lot of facilitating and communicating between a few of the other scripts ( TruffulaOptions, TruffulaPrinter). It looks to do this by defining some perameters of what files should be shown in the tree that is created and whether or not to color the text of some of the output. to do this the file defines "flags" "to denote the specifics for text with  [-h] for hidden files amd [-nc] for no color.

Question:
none.

## ConsoleColor.java
This file is an enum containing the ANSI codes for different colors available for text color changing functionality of the program. This enum also has some helper functions to communicate and transfer necessary information between it and other scripts. These helper functionns are ConsoleColor() which returns a Ansi color code, getCode() which returns the Ansi code for current color, and the to stringFunction prints the Node color code to the console.

Question:
Im not familiar with helper functions being a part of enums, can you explain how this works? I was under the impression enums could contain onlys simple values belonging to one variable.

## ColorPrinter.java / ColorPrinterTest.java
THis file seems to actually print the file tree or message given to it. it als does it in a specified color.
## TruffulaOptions.java / TruffulaOptionsTest.java

## TruffulaPrinter.java / TruffulaPrinterTest.java

## AlphabeticalFileSorter.java