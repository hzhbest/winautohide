This is a tiny utility that utilizes 4 shortcut keys (Win+Left, Win+Right, Win+Up, Win+Down) to hide windows to screen sides.
 
This utility can be useful if you have a few small windows that you use often (for example a terminal or a command prompt) and you want to access them quickly just by moving the mouse.

When you press one of the shortcuts (say Windows+Right for example), the active window will "hide" to the edge of screen assigned by the arrow key in the shortcut (right edge as in example), showing only one pixel of its border. It will also stay "always on top" so you can always "touch" this one pixel border with your cursor, then you can make the window appear and take the focus for you to use it. When you move your mouse away from the window, it will hide again.

In effect the window will act like the Windows taskbar when the "auto-hide" setting is checked, or other similar bars.

This utility also adds an icon in the notification area of the Windows taskbar, which you can click with right mouse button to show a menu with a command to un-autohide all hidden windows.

Tested under Windows10.

Limitations: 
 * Doesn't seem to work with a few "special" windows, like Winamp for 
  example. 
 * Multi-monitor setup is not supported / tested.

Note: this is an AutoHotkey script, install AutoHotkey before running "winautohide.ahk"
   (see http://www.autohotkey.com/).

Original author: BoD@JRAF.org.

This program and its source are in the public domain.

Version history: 
2008-06-13: v1.00
2024-03-01: v1.01 Modded by hzhbest
