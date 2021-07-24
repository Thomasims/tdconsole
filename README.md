# tdconsole
An extremely simple DLL to open a console in Teardown.

All this does is run `AllocConsole()` immediately when the DLL is attached.

# installation
1. Get winmm.dll from the [release page](https://github.com/Thomasims/tdconsole/releases/latest).
2. Put it next to Teardown.exe in your game folder.

# building
If you prefer to compile the DLL yourself, everything needed is provided in this repository:
1. Clone this repo locally.
2. Open tdconsole.sln in visual studio (I used VS Community 2019).
3. Build the solution for your desired target (Release x64).
4. You'll find the path of the DLL in the build logs.
