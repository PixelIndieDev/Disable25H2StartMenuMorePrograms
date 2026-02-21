# Disable 25H2 Start Menu "MorePrograms" Section
![Registry](https://img.shields.io/badge/File-.reg-orange)

A Windows Registry to remove the "More Programs" section from the Windows Start Menu introduced in 25H2.

This repository provides a .reg file that modifies the Windows Registry to hide this section, forcing the Start Menu to only show pinned tiles.

## Installation / Usage
- [Download](https://github.com/PixelIndieDev/Disable25H2StartMenuMorePrograms/releases/download/V1/Disable25H2StartMenu.reg) the Disable25H2StartMenu.reg file from this repository.
- Double-click the file to run it.
- Click **Yes** when the User Account Control (UAC) prompt appears.
- Click **Yes** to confirm you want to add the information to the registry.
- Restart Windows Explorer or sign out and back in for the changes to take effect.

<sub>Sometimes it also takes effect without restarting or signing out<sub>

## How to Undo
Change the 'NoStartMenuMorePrograms' value from 1 to 0 or delete the 'NoStartMenuMorePrograms' key entirely
