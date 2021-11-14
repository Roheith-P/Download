XBOX 360 ISO Extract
--------------------
2010/10/11
created by somski
version 0.6

________________________________________________________________________________
changelog:

-- version 0.6 (2010/10/11)
* $SystemUpdate directory is now skipped instead of deleted afterwards
* log window is now updated regularly
+ new progressbar to indicate the progress of the current file
+ new button to invert the extraction checkboxes

-- version 0.5 (2010/10/09)
* order of queue can be changed by drag and drop (right mouseclick)
- extra button for up and down are removed
+ changable extraction name (F2 or double click)
+ now finds *.iso, *.000, *.360, *.img
+ FTP support (just standard username & password (xbox:xbox) for now)

-- version 0.4 (2010/08/24)
+ order of the queue is changeable now
+ last iso and extraction dir are saved now 
+ scans the iso directory on change and startup (needs a bit longer to load)
* some error handling added

-- version 0.3 (2010/02/16)
* first public release
________________________________________________________________________________
general information:

This program allowes you to extract multiple xbox360 isos based on exiso.

+ you can scan recursively through a directory and pick every iso
  (every iso must be in a seperate dir or you need to manually extraction name)
+ each iso will be extracted to the target_dir\!the dir you CHOOSE :))!
    (standard: directoryname of the iso)
+ skips extracting if target_dir already has the directory 
+ "remove iso afterwards" functionality (be careful! maybe some bugs)
+ statusbar and log window
+ skipping of the $SystemUpdate directory (since it's not needed)
+ FTP support

________________________________________________________________________________
howto:

1. click on "choose ISO-Folder" and select a directory with isos in it.
e.g. if you have games in Y:\Console\Medal.of.Honor , Y:\Console\Enslaved
     select Y:\Console
2. you choose between ftp mode or locale extract mode (checkbox with name ftp)
3. with ftp:
      you choose your xbox ip and as destination e.g. \hdd1\Games or \usb0\Games
   without ftp:
      you can press on the button to choose a directory or type it in by hand
4. you hit the rescan button
5. you can rearrange the extraction queue (right click and drag and drop)
6. you can rename the extraction names (by pressing F2 or clicking on the name)
   this will be used as full path e.g. you used as destination \hdd1\Games
   and the game name you choose was Medal.Of.Honor than the full path would be
   \hdd1\Games\Medal.Of.Honor
7.optional: if an iso was found that you don't want to extract hit the checkbox
            in front of the name to deselect it (it won't get extracted then)
            to invert the chechboxes click invert
8 optional: deselect skip $SystemUpdate and/or select delete iso
9. hit go
10. lean back and let the software do the rest.
    Now it shows you the current status (statusbars at the bottom).
    For more information on the current extraction you can go to the current tab

________________________________________________________________________________
special thanks:

* in <in@fishtank.com> for the initial extract-xiso build
* aiyyo for his modifications to support xbox360 and making it more user friendly
  (skipping of $SystemUpdate and progress for current file)
* and everyone else who told me what to do better ;)
