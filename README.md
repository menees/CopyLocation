# Copy Location
This shell extension adds the following right-click menu items in Windows Explorer:
* Copy File Path
* Copy File Name

It originally came from the [Copy Location Shell Extension](https://www.codeproject.com/Articles/460/Copy-Location-Shell-Extension) article on CodeProject. I rebuilt it in 2007 using VS2005 to get a version for x64, and I changed the source to turn off the bitmaps on the menu items.

The original author is Itay Szekely (grebulon@gmail.com), and the current official version is available at https://www.grebulon.com/software/copylocation.php. The official version was updated in 2010 to support x64, but it still uses menu item bitmaps.

## Installation
1. Open a command prompt using Run as Administrator.
1. Change to the 32-bit or 64-bit folder based on your OS.
1. Run: `regsvr32.exe CopyLocation.dll`