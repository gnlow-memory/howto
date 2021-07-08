https://winaero.com/how-to-move-taskbar-in-windows-11-change-taskbar-location/
---
How to Move Taskbar in Windows 11 (Change Taskbar Location)
11 Replies

You can move Taskbar in Windows 11 and change its location. While Windows 11 doesn't yet include such a setting, this can be done with a Registry tweak.

Windows 11 is the newest operating system from Microsoft. It brought a drastically changed, completely new user interface. It includes a new Start menu which appears in the screen center. The change has also affected the taskbar, which is also centered.

Perhaps the worst change made to taskbar is its location. Windows 11 doesn't allow you to move it to the side or top, it always appears at the bottom of the screen.

This post will show you how to move the taskbar and change its location in Windows 11. You can either place it at the top or bottom.
Move Taskbar in Windows 11 and Change its Location

1. Press Win + R and type regedit in the Run dialog to open the Registry editor.
2. Navigate to the key HKEY_CURRENT_USER\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\StuckRects3​.
3. Right-click the StuckRects3 key and select Export... from the menu. Save the REG file to the Desktop folder.Windows 11 Export The StuckRects3 Key
4. Double-click the Settings value.
5. In the 0008 row, place your cursor to the fifth column, where you see the 03 value.Windows 11 Change Taskbar Location
   ![image](https://user-images.githubusercontent.com/27040628/124930899-abce0f80-e03c-11eb-84e8-a93683e56f2c.png)
6. Press DEL to remove 03, and type 01.type 01 instead of 03
7. Click on OK in the Edit binary value dialog.
8. Restart the Explorer shell using the Task Manager method.

You're done! The taskbar now appears at the top.

Windows 11 Move Taskbar
How to undo the change and move the taskbar back to bottom

To undo the change, double-click the exported REG file which you have created in the step #3. When prompted, click on the UAC confirmation prompt.

Alternatively, you can modify the above mentioned Settings binary value, and change its fifth column from 01 to 03, i.e. to its default value. Don't forget to restart the Explorer shell.

Note that restarting the Explorer shell is a mandatory step. You cannot simply sign out and sign in back to your user session. That's won't work!

To properly change the Windows 11 taskbar location, please restart Explorer as follows.

    Press Ctrl + Shift + Esc to open the Task Manager.
    In Task Manager, click on More details to make it show tabs with apps and services.Windows 11 More Details In Task Manager
    On the Processes tab, find Windows Explorer and click it.
    Click on the Restart button.Restart Explorer in Windows 11

You are done.

I will update this post once I figure out how to move the taskbar to the screen side. Currently, it is unknown.

That's it.
