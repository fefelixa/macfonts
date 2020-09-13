# macfonts

these are the fonts used throught all modern apple systems (macos, ios, etc.)

i made this just because i was tired of having to sign into my onedrive every time i needed one of these

---

# installation

the `San Francisco` folder contains every single `.otf` file for convenience.

## windows

using an account with administrative privileges is recommended

### method 1

download the zip and extract its contents

copy all desired `.otf` font files (not the folders) into `C:/Windows/Fonts`

### method 2

download the zip and extract its contents

double click on an `.otf` file

click install

repeat this for every font desired

### method 3 (not recommended - windows 10 only)

download the zip and extract its contents

open settings

go to [personalisation](ms-settings:personalization-colors) and select the fonts tab

drag and drop all appropriate .otf font files into this section:

![Drag and drop to install](WindowsDragDrop.png)

## linux

the installation method is different for all distributions, but this is the most common

open a terminal (usually ctrl+alt+t) and type:

`cd ~/.fonts`

`git clone https://github.com/froggeboi/macfonts.git `

(if `~/.fonts` does not exist, use `mkdir ~/.fonts` to create it)

## mac os x

go to [developer.apple.com/fonts/](https://developer.apple.com/fonts/)

download sf pro, sf mono and sf compact

install it (i dont know how)

# todo

- [ ] find out how to install fonts on a mac (making a pull request/issue/contacting me in any way to let me know how would be great <3)

# notice

i am not associated or affiliated in any way with [Apple, Inc.](https://apple.com/)

these fonts are created by Apple and i am simply here to pass them onto you

also i used [7-zip](7-zip.org) to extract files from the official .dmg files that Apple supplies (for free)
