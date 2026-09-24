# [Yale Explorer](https://code.theonlygreenleaf.com/yale-explorer)
An interactive point-and-click style game that lets you explore all (eventually) of Yale University.
This project aims to capture the majority of campus including secret areas you wouldn't normally know about... but you still have to find them yourself!

### Keybinds
|Key|Function|
|---|--------|
|Right Arrow|Turn around|
|Click|Interact/Go to room|
|L|Switch the layout (Landscape\|Portrait\|Fullscreen)|

### URL Scheme
Usage Example: https://code.theonlygreenleaf.com/yale-explorer?param1=123&param2=456
|Parameter|Function|
|---------|--------|
|scene|The scene ID to go to after the project starts|
|developer-mode|Start the project with developer mode enabled|

### Progress
Farnam Hall (o-fr)
- Basement
- Stairways
- A32 & A31
Lawrence Hall (o-lr)
- Basement and Entranceways
Battell Chapel (o-chpl)
- Basement
- Main Entranceway
Old Campus Courtyard (o-ctyd)
- Farnam Doors
- Lawrence Doors
- One of the chapel doors
Berkeley College (r-bk)
- Steam Tunnels (currently inaccessible, warp to r-bk:T00S-1 to see them)
<br><br><br>
> [!TIP]
> If you don't want to make your own asset pack but want to contribute to the project, reach out to me and I can let you know how to take the photos and send them.
<details>
  <summary><h2>Making your own point and click asset pack</h2></summary>
### Package System
Each building of campus has its own zip file that contains pictures for each room/corridor.
For example "o-fr.zip" contains assets for Old Campus — Farnam Hall.
Most importantly, each zip file contains an assets.json file that lists every room and the points in the room that can be clicked on to take you to adjacent room.
Use the schema file to help you make your own assets file.
Yes, this took a lot of time, thank you for asking.

### Developer Mode Keybinds
|Key|Function|
|---|--------|
|W|Warp to a specific scene|
|A|Add a debug click point|
|S|Remove the most recent debug click point|
|C|Copy the current debug click points as a "points" key array (+shift to copy a transition action as well)|
|D|Remove all debug click points|
|J|Show all click points for the current scene while held|
|P|Show additional scene data (+shift to hide)|
|O|Open an asset zip file from local storage|
|6|Show the assets list (+shift to hide)|
|7|Purge all stored assets|
|G|Invert the locked state of everything while held|
|1|Restart the project (not functional on web)|
|D|Toggle develeoper mode if held when the project starts (not functional on web)|

You can also type "developermode" to toggle developer mode, or on mobile, rest 5 fingers on the screen, then lift 3, then lift 4.

### Importing an asset zip file
1. Enable Developer Mode
2. Press O
3. Enter the name of the asset (Ex: o-fr) or enter a link to a zip file hosted somewhere
4. Upload the zip file
5. Use W to warp to your scene if you are not there already (o-fr:A190-1)
If this is not working, try purging the assets with 7 and then repeat from step 2.

</details>

### Project Details
Created using PenguinMod and various extensions and packaged to html using PenguinMod Packager. For more info, just send me an email and ask me idk..

Disclaimer: Yale Explorer is not directly affiliated or associated with Yale University and is not an official yale.edu website.
