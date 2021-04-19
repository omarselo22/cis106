## Exploring Desktop Environments
1.  A desktop environment is the bundle of components that provide you common graphical user interface (GUI) elements such as icons, toolbars,wallpapers. Your laptop is going to operate faster and more functionally if the desktop environment has less flashy effects.
   
2. Functionality is always more important than the flashy effects.
   
3. A graphical user interface (GUI) is a type of user interface through which users interact with electronic devices via visual indicator representations.
   
4. Windows and MacOS’s users are limited to one single DE and GUI unlike linux’s users which have plenty of options to their DE and GUI.
   
   * a. Desktop settings: Programs that allow you to make configuration changes to your desktop environment.
   * b. Display manager = Login screen
   * c. File manager: allows user to perform maintenance activities graphically.
   * d. Icons: how files and programs pictured
   * e. Favorite bar: window bar for popular icons and the ones that are used frequently.
   * f. Launcher: program that allows user to search for applications and files.
   * g. Menus
   * h. A panel is an area in your desktop environment from which you can run applications and applets, and perform other tasks
   * i. A system tray is usually attached to a panel; it allows access to programs which allow users to logout, lock screen, view notifications.
   * j. Widgets represents virtual things on desktop, Clock, Sticky notes,weather, Calculator, Calendar…
   * k. Window manager: is a powerful program that tells the computer what to do with the window. 
5. **The GNOME DE:**
It is a desktop environment that is default for ubuntu. It is used for Unix like operating systems. The official GUI for GNOME is called GNOME shell.

6. **The KDE desktop environment:**
The Cool Desktop Environment’s first release was 1998. In 2009 it was branded to become KDE PLASMA.

7. **The XFCE desktop environment:**
XFCE (which was very heavy) is a free and open-source desktop environment for Linux. XFCE is lightweight and fast, it is at the same time user friendly and appealing.
**Ubuntu** is a bit easier to use when it's first installed, but Manjaro's smaller overhead allows for a speedier system and more granular control.

8. **Mate desktop environment:**
It is the best desktop environment for raspberry pi. It is a continuation for GNOME 2.

9. **The Cinnamon desktop environment:** 
Cinnamon is a desktop environment which combines a traditional desktop layout with modern graphical effects. The underlying technology was forked from the GNOME desktop. Cinnamon is the best desktop environment for Windows 10.

10. **Lubuntu:**
Very fast and light weight; it is not featureless.

##  What is a shell?
shell is a program that takes commands from the keyboard and gives them to the operating system to perform.
* That shell allows the user to give external and internal commands
* The default shell in most linux distributions is the bash shell

## Managing Software
* To update any Debian distro: **Sudo apt update;Sudo apt upgrade-y**
  * Sudo:it allows you to run any command 
  * apt : manages software and update to run multiple commands use;
  * -y is used to pass a yes answer to any question
  
* How to install several programs in a single command: **Sudo apt install firefox flameshot caffeine -y**
  
* How to remove several programs ina single command: **Sudo apt remove firefox flameshot caffeine -y**
  
* How to install and remove programs install single command: **Sudo apt install firefox+ flameshot-caffeine-vlc+**

* How to search for all programs that matches the text in quotes: **apt search “web browser”**
  
* How to remove programs and all remaining traces: **Sudo apt purge firefox+ flameshot-caffeine-vlc+**

## The Linux Filesystem 

* **Some commands that need to be mastered :**
  * pwd : displays the present working directory
  * cd : change your working directory
  * to go to home directory:
    cd
    cd ~
    cd $HOME
  * two periods mean cd ../ the previous working directory one way back     
  * two way back cd ../../ we can also go the root of the file system
  * one period mean cd ./ the present working directory
  * Arrow keys to up and down to go back to the commands that you typed
  * Cat .bash_history : this command will open a list of all the commands that you typed in the shell

* **Ls command to list the files and directories**
    * Ls downloads to show what is inside downloads
    * Ls -a :to list all the files including the hidden in your pwd
    * Ls -R :to list all the files recursively in your pwd
    * Ls -a ~/Downloads: to list all the files in a given directory
    * Ls -la is for long listing
    * Ls -t : lists files by last date modified
    * Ls -S : lists files by size
    * Ls -X :lists files by extension
    * Ls –help : lists all the options of the ls command

* **Important Link for Linux Commands** 
  * [Linux Commands](https://robertalberto.com/linuxcommands/home.html)

