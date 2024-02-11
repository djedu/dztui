## What this is
This is a modified fork of the GUI version of [DZTUI](https://github.com/aclist/dztui/tree/dztui) for Linux.

### Modifications:

1. Mods now get linked to a subdirectory (!dzworkshop) instead of the root game directory.

To install this version follow the instructions in the original [manual](https://aclist.github.io/dzgui/dzgui.html) and replace the github url with this one.  
  
For auto mode:
```
curl -s "https://raw.githubusercontent.com/djedu/dztui/dzgui/install.sh" | bash`
```

For manual mode:  
```
git clone https://github.com/djedu/dztui.git  
chmod +x dzgui.sh`
```

For further information regarding this tool see the original repository at [DZTUI](https://github.com/aclist/)

## About DZGUI

DZGUI allows you to connect to both official and modded/community DayZ servers on Linux and provides a graphical interface for doing so. This overcomes certain limitations in the Linux client and helps prepare the game to launch by doing the following:

1. Search for and display server metadata in a table (server name, player count, ping, current gametime, distance, IP)
2. Add/delete/manage favorite servers by IP or ID
3. Find and prepare mods being requested by the server (choose from manual or automatic installation)
4. Concatenate launch options to pass to Steam

Other options include the ability to connect by IP or ID or  set a favorite server.

## Setup and usage

Refer to the [manual](https://aclist.github.io/dzgui/dzgui.html) for installation and setup instructions, a feature-by-feature breakdown, and Steam integration tutorials.

![Alt text](/images/example.png)
