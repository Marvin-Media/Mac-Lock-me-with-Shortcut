# macOS lock with Shortcut (Windows+L):
macOS lock with shortcut (Windows+L)

1.  You download the "Lock.scpt" and open it with Script-Editor.
2.  You export the Script as Lock.app and copy that to Programms.
3.  Run Automater and create a new document and there an new service.
4.  Select Run Programm an select the "Lock.app" then safe that.
5.  Open Settings -> keyboard -> Short Cuts -> Service -> Lock.App -> ⇧⌘L
6.  Press the short cut and it works fine.




# This is the Lock.scpt Code:
```
do shell script "/System/Library/CoreServices/Menu\\ Extras/User.menu/Contents/Resources/CGSession -suspend"
```
