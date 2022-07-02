# virgo-icon
Change [Virgo](https://github.com/henkman/virgo) system tray icon by using `ico` format file.  
Download [here](https://github.com/enria/virgo-icon/releases/download/v.1.4.2.1/virgo.zip).

## Demonstration

### Number

#### Simple

![simple](images/number.jpg)

#### Square

![simple](images/square_number.jpg)

#### Circle

![simple](images/circle_number.jpg)

### Function

![simple](images/function.jpg)

## Method of Making Icon

1. Download svg format icon from [iconfont](https://www.iconfont.cn/)  
2. Convert svg to ico at [convertico](https://convertico.com/svg-to-ico/)
3. Rename the ico file to desktop number, e.g., `1.ico`, and put it together with `virgo.exe` in the same fole.  
![structure](icons/structure.png)


***

Virtual Desktop Manager for Windows

Features:
- resource friendly, exe is <10kb on disk and uses <1mb memory while running
- 4 virtual desktops (more if you change a constant and recompile the code)
- shows only a tray icon with the number of the desktop you are on

Hotkeys:

        ALT + 1..4             -> changes to desktop 1..4
        CTRL + 1..4            -> moves active window to desktop 1..4
        ALT + CTRL + SHIFT + Q -> exits the program
        ALT + CTRL + SHIFT + S -> starts/stops handling of other hotkeys

