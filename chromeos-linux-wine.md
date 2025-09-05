# How to get `wine` on `chromeos` (linux `wine`, not that "wine")
This will allow you to run .exe files.
## Section 1: Opening `Vim` and installing `wine`
1. Enable `linux`.
2. Open Vi` (You probably want to pin this to the taskbar; your going to use it a lot.)
3. Press the "+" button in the top middle-ish position on the window.
4. A line of text shold appear with a `-$` at the end. This is the `shell`. Now, type `sudo apt-get install wine winetricks -y`. Continue to section 2.
## Section 2: Configuring `wine` with `winetricks`
1. In `Vim`, type `winetricks`.
2. A window should open. Click "Select the default wineprefix". Then, click "OK"
3. Another window should open. Click "Run winecfg". Then, click "OK"
4. Now, close this window. Continue to section 3.
## Section 3: Running a `.exe` file
1. Obtain your `.exe` file.
2. Open `winetricks`. It may or may not be in the menu that shows all your apps.