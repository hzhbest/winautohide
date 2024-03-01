This is a tiny utility that will add  an icon in the notification area of the
Windows  taskbar,  and  add  4  shortcut  keys (Windows+Left,  Windows+Right,
Windows+Up, Windows+Down).

When  you  press one of  the shortcuts  (say Windows+Right  for example), the
currently active window will "hide" to the right edge of your screen, showing
only  one  pixel of its border.  It will also  stay  "always on top" of other
windows,  so you will  always see this one pixel border.  Then when you hover
your mouse on that border,  the window will appear and take the focus, so you
can use it.  When you move back your mouse away from the window, it will hide
again.

In  effect the window will act like  the Windows taskbar when the "auto-hide"
setting is checked, or other similar bars (eg. the Google Desktop "sidebar").

This utility can be useful if you have a few small windows that you use often
(for  example  a terminal or  a command prompt)  and  you want to access them
quickly just by moving the mouse.

Limitations: 
  * Doesn't seem to work with a few "special" windows, like Winamp for 
    example. 
  * Multi-monitor setup is not supported / tested.
  * Tested only under Windows XP.

Note: this is actually an AutoHotkey script, compiled into an executable file
      (see http://www.autohotkey.com/).

Contact the author: BoD@JRAF.org.

This program and its source are in the public domain.

Version history: 
2008-06-13: v1.00
