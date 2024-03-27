# MacRun
An Automator-based solution to bring Windows Run to macOS

Installation:
1. Download the .zip file above and extract it. It turn into an Automator workflow.
2. Double click on the workflow. It will ask whether to install or not. Accept.
<img width="483" alt="Screenshot 2024-03-27 at 7 12 00 AM" src="https://github.com/matthewyang204/MacRun/assets/141765903/64cf19bc-6268-4b1b-8151-c174c68a6212">

3. It will open the following System Settings window. Click on the arrow next to "General".
<img width="713" alt="Screenshot 2024-03-27 at 7 15 08 AM" src="https://github.com/matthewyang204/MacRun/assets/141765903/735bdb5e-7448-4a8f-87c5-232f3640b67d">

4. Click double click on the shortcut (it will say "none") at first, double click on it and press your keyboard shortcut. Afterward, it say the keyboard shortcut that you entered. In my case, it said CMD+R.
<img width="717" alt="Screenshot 2024-03-27 at 7 15 53 AM" src="https://github.com/matthewyang204/MacRun/assets/141765903/673a2ae0-0d0b-4186-ad0c-6543c65b0e21">

5. Click on "Done" and close the window. Now you can use it.

To use, just press the keyboard shortcut that you entered, or go to the Services menu in the menubar and click on MacRun. If you want to launch an app, you need to enter the full path to the binary executable within the .app bundle of the program in question. You need to know the full path. For GIMP (GNU Image Manipulation Tool), for example, the path is 
```
/Applications/GIMP.app/Contents/MacOS/gimp
```
If you have Wine installed, you can enter "wine64" and then add a space and then type the Windows program. For Notepad, for example, enter
```
wine64 notepad
```
You can also run other arbitrary terminal commands, such as brew, curl, mv, cp, etc.
After typing out your query, press Enter.
