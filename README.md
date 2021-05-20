# Move All Windows to Screen

This KWin script provides user definable shortcuts that let you move all your
windows to a specific screen. If you want to quickly move all windows from one
screen to another this is for you.


## Motive

I like to work with two screens, the laptop screen and my external monitor(s).
When I disconnect my monitor all windows are automatically moved to the laptop
screen which is nice, but when I reconnect the monitor all windows remain on
the laptop screen. This is inconvenient as I mostly want my windows on the
external screen when I have it connected. This KWin script solves that issue by
providing shortcuts for moving all windows to a specific screen.


## Installation

First clone this repo and run the following command in the root directory of the
repo.

	plasmapkg2 --type kwinscript -i .

After that open KWin Scripts (System Settings -> Window Management ->
KWin Scripts) and enable "Move All Windows to Screen". This won't yet enable
any shortcuts, you can define your own key bindings. See Setup for details.

If you need to update the script to a new version pull the repo again and run:

	plasmapkg2 --type kwinscript -r .
	plasmapkg2 --type kwinscript -i .


## Setup

Open System Settings and go to Shortcuts -> Global Shortcuts -> Kwin. You
should see new shortcuts available there (for moving windows to screen 0, 1, 2
and 3). Just add shortcuts for the ones you need and that's it.
