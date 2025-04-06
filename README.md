# notice

you can use the [inter font](https://fonts.google.com/specimen/Inter) from [google fonts](https://fonts.google.com) for better compatibilty (looks v similar to this and 100% legal)

# macfonts

these are the fonts used throught all modern apple systems (macos, ios, etc.)

i made this just because i was tired of having to sign into my onedrive every time i needed one of these

---

# installation

the `San Francisco` folder contains every  SF style `.otf` file

the `New York` folder contains every NY style `.otf` file

## global

this method works across most OSes/distros

download the zip (you dont have to extract the files depending on your os but you can if you want to)

open an `.otf` file (double-click)

click install

repeat for all desired files

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

### method 3 (windows 10+ only)

download the zip and extract its contents

open settings

go to [personalisation](ms-settings:personalization-colors) and select the fonts tab

drag and drop all appropriate .otf font files into this section:

![Drag and drop to install](WindowsDragDrop.png)

## linux

the installation method is different for all distributions, but this is the most common

open a terminal (ctrl+alt+t) and type:

```
cd ~/.fonts
git clone https://github.com/froggeboi/macfonts.git
```

(if `~/.fonts` does not exist, use `mkdir ~/.fonts` to create it)

**please refer to your distro's docs for proper installation instructions**

## mac os x

go to [developer.apple.com/fonts/](https://developer.apple.com/fonts/)

download the fonts you want

open the .dmg file(s)

drag and drop the thing into the folder

# legal

i am not associated or affiliated in any way with [Apple, Inc.](https://apple.com/legal/)

these fonts are created by Apple and i am simply here to pass them onto you

also i used [7-zip](7-zip.org) to extract files from the official .dmg files that Apple supplies (for free)
