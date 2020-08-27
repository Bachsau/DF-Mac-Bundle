macOS launcher for Dwarf Fortress
==================================

![Dock screenshot](/screenshots/dock.png)

The current Mac version of this awesome game is not a single application
bundle. Instead, like the Windows version, it consists of a directory
containing the application along with data files.

This bundle provides a launcher you can put in your "Applications" folder to
start the game from your Dock or Launchpad without a terminal window.

Installation
-------------
1. Download the Mac version of Dwarf Fortress:
   http://www.bay12games.com/dwarves/
2. Download the launcher:
   https://github.com/Bachsau/DF-Mac-Launcher/archive/v2.1.2.zip
3. Extract the game files to "Library/Application Support/Dwarf Fortress"
   within your home directory
4. Put "Dwarf Fortress.app" in your "Applications" folder or wherever you like
   and open it (e.g. using double-click from Finder)
5. Strike The Earth!

Retina issues
--------------
Dwarf Fortress has some known bugs related to retina support
(e.g. http://www.bay12games.com/dwarves/mantisbt/view.php?id=6031).
Some of them are already solved by using this launcher, which designates Dwarf
Fortress as high-resolution incapable, so it is scaled up on retina displays.
If you want to play fullscreen though or if you have some other bugs consider
changing "PRINT_MODE" to "STANDARD" in "data/init/init.txt".

Configuration, modding, tileset, etc.
--------------------------------------
Nothing special here. You can change or update the game as normal.

There is no perfect-for-everyone config. A suggested colorscheme and tileset
can be found in the "optional" directory. This is very close to vanilla Dwarf
Fortress but looks much better on some MacBooks.

Supported versions
-------------------
The application bundle was tested with classic 0.44.12 version of the game.
Other versions should work as well.
