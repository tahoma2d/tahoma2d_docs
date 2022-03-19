.. _troubleshooting:

Troubleshooting
===========================

Windows
---------------

The code execution cannot proceed because MSVCP140.dll was not found. Reinstalling the program may fix the issue
~~~~~~

**Cause:** Newer systems no longer ship with these DLLs

.. tip:: Download and install the Microsoft Visual C++ 2015 Redistributable Update 3 RC. (https://www.microsoft.com/en-us/download/details.aspx?id=52685)





The code execution cannot proceed because VCRUNTIME140.dll was not found. Reinstalling the program may fix the issue
~~~~~~


**Cause:** Newer systems no longer ship with these DLLs

.. tip:: Download and install the Microsoft Visual C++ 2015 Redistributable Update 3 RC. (https://www.microsoft.com/en-us/download/details.aspx?id=52685)




The code execution cannot proceed because Qt*.dll was not found. Reinstalling the program may fix the issue
~~~~~~
**Cause 1:** You did not unzip the Tahoma2D-win.zip but tried to run it from within the zip'd folder instead

.. tip:: Uncompress the Tahoma2D-win.zip to create the Tahoma2D folder

**Cause 2:** You moved the Tahoma2D.exe out of the Tahoma2D folder and away from the tahomastuff folder

.. tip:: Move the Tahoma2d.exe back to the Tahoma2D folder so it's in the same directory as the tahomastuff folder







Undefined or empty: "SOFTWARE\Tahoma2D\Tahoma2D\TAHOMA2DROOT" Installing Tahoma2D 1.x again could fix the problem.
~~~~~~
**Cause 1:** You moved the Tahoma2D.exe out of the Tahoma2D folder and away from the tahomastuff folder

.. tip:: Move the Tahoma2d.exe back to the Tahoma2D folder so it's in the same directory as the tahomastuff folder

**Cause 2:** If the directory path to Tahoma2D contains your username, certain special characters in your username may cause the path to the tahomastuff folder to not be found

.. tip:: Move the entire Tahoma2D folder to a directory whose path does not contain your username, like C:\\ or C:\\Program Files







The Tahoma2D splash screen shows then disappears but never opens
~~~~~~
**Cause 1:** Anti-virus software may be blocking it

.. tip:: Temporarily disable anti-virus software and attempt to start again.  If it starts normally, then add Tahoma2d.exe as an exception in your anti-virus

**Cause 2:** The tahomastuff folder does not have the proper permissions

.. tip:: Right-click the Tahoma2D\tahomastuff folder, select Properties, click on the Security tab and make sure your username exists in the list and has full permissions.  If not found, add it.  Alternatively, run Tahoma2D.exe as Administrator

**Cause 3:** Unknown

.. tip:: Open Window's Event Viewer, click Windows Logs, click on Application.  Look for an Error log for Tahoma2D and see what it says.  If you are not sure what it means or how to resolve it, open an issue here: https://github.com/tahoma2d/tahoma2d/issues






Linux
---------------




Undefined or empty: "SOFTWARE\Tahoma2D\Tahoma2D\TAHOMA2DROOT" Installing Tahoma2D 1.x again could Solution the problem.
~~~~~~
**Cause 1:** You moved the Tahoma2D.app out of the Tahoma2D folder and away from the tahomastuff folder

.. tip:: Move the Tahoma2d.AppImage back to the Tahoma2D folder so it's in the same directory as the tahomastuff folder

**Cause 2:** If the directory path to Tahoma2D contains your username, certain special characters in your username may cause the path to the tahomastuff folder to not be found

.. tip:: Move the entire Tahoma2D folder to a directory whose path does not contain your username, like /usr/local/bin or some appropriate directory.


