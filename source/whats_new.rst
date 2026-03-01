.. _whats_new:

What's New in Tahoma2D
======================

Tahoma2D includes a number of improvements from OpenToonz.  It also includes the latest features and bug fixes from OpenToonz.

In this section you can find a list of Highlights in the latest release of Tahoma2D; these may include New Features, Bug Fixes or Enhancements to already existent features.
Here, you can also find links to past versions' Release Notes, to keep track of Tahoma2D development history throughout time.

.. _v1.6:

New in Tahoma2D 1.6
---------------------


Added
'''''
- Brush Tips (Raster/Smart Raster)
- Stylus Settings Popup (Raster Brush & MyPaint styles)
- Stylus Settings Popup (Smart Raster - Standard Brush, Vector)
- Column Alpha Lock
- Loop Frames
- Add Raster Tool Option - Paint Behind
- Smart Raster Selection - Selective mode
- Add marker and soft round vector styles.
- Contiguous cell selection shortcut
- Show image in cell tooltip
- Special Modifier Key: Viewer Scrub
- Canon SDK for Linux

Changed
'''''''
- MyPaint Brush Tilt Support
- New and updated shortcuts
- Refactored and Improved Preproduction Board
- Reverse Clipping Mask Stacking Placement
- Rhubarb Recognizer option
- Shift markers with Cell Insert/Delete
- Add color and fill support to raster pattern brush.
- Allow Touch Screen zoom and rotate combo
- List All GPhoto config button and critical error handling
- Enhance input validation and clamping in DoubleValueField *(OpenToonz port)*
- Existing scenes list in Startup Popup *(OpenToonz port)*

Fixed
'''''
- SVG load fixes
- Add missing Hook Tool status bar description
- Autoclose: Limit Two Points Spot Research Angle to 0°~36°
- Capitalize Spanish Fx doc directory
- Compress high frequency MyPaint drawing events
- Fix backing up of scene icon
- Fix Capture Image using Canon EDSDK Linux
- Fix changing geometry opacity back to 100
- Fix column status toggling and display of folder items
- Fix controlling Smart Raster/Vector brush resize
- Fix Export Vector Level Bad Resolution Crash
- Fix File Browser New Folder creation
- Fix File Browser Rename logic and UI
- Fix fill loss due to ghost grouping changes
- Fix flipped vector color picker
- Fix folding column folders and other operations
- Fix image capture default folder
- Fix key as last scene frame
- Fix last Stop Frame Hold
- Fix load svg crash
- Fix loading unknown style id
- Fix missing Checkboard Fx settings (Linux)
- Fix missing MSVC DLLs
- Fix missing QString arg
- Fix missing viewer title bar level info
- Fix reading corrupted PNG crash
- Fix saving escaped apostrophe (linux)
- Fix saving TIF files in scene subfolder
- Fix Show Column Parent's Color context menu option
- Fix some Vector Inspector issues + some refactoring
- Fix sound cells extender controls and move selection
- Fix sound extender targeting when zoomed
- Fix starting Animate Tool mode
- Fix starting in unicode path
- Fix stop frame placement on OCA import
- Fix styleeditor not updating on colorswatch switch
- Fix SVG stroke-width at lower resolutions
- Fix to prevent looping 1 frame
- Fix to stop writing unfilled regions to SVG
- Fix vector fill loss due to ghost grouping changes
- Fix Vector Ungroup/Group undo issue
- Fix Zerary Fx input preview status in Schematic
- Fix(autoclose): Add intersection check for spotRearchTwoPoints
- Fixes for Preproduction Board and File Browser
- Force startup tips window to the top
- Restore disabled file writer types
- Fix bounds issue
- Fix blank canvas
- Fix brush size input for non-English locales *(OpenToonz port)*
- Fix color wheel pointer and replace layout margins *(OpenToonz port)*
- Fix dummy ink pixel (Tone =255) ink texture crash *(OpenToonz port)*
- Fix memory leaks by replacing 'delete' with 'delete[] *(OpenToonz port)*
- Fix Mesh Memory Leak *(OpenToonz port)*
- Fix New Folder refresh issue in File Browser *(OpenToonz port)*
- Fix order of beginInsertRows/beginRemoveRows in ExportSceneDvDirModel *(OpenToonz port)*
- Fix registering multiple system var paths with command line qualifiers *(OpenToonz port)*
- Fix SVG import crash with non-ASCII file paths on Windows *(OpenToonz port)*
- Fix unreachable code and duplicate VEC array initialization *(OpenToonz port)*
- Fix -Wreturn-type warnings in iocommand and igs_rotate_blur *(OpenToonz port)*
- Fix(OCA): correct endTime *(OpenToonz port)*
- Fix(Scene Depth/Quicktoolbar): Invisible after startup *(OpenToonz port)*
- Fix: Add missing fclose calls for proper file handling *(OpenToonz port)*
- fix: handle MSVC warnings C4723 and C4552 *(OpenToonz port)*
- fix: initialize popup, firstW, and lastW *(OpenToonz port)*
- fix: ODR violations (# 241) by adding flipbooksettings.h for toggle vars *(OpenToonz port)*
- Fix: Premultiply background color for Export Level Commands *(OpenToonz port)*
- fix: Preview not Updating for New Toonz Raster Levels editted with Fill Tool *(OpenToonz port)*
- fix: remove duplicate and unreachable 'stylepages' case *(OpenToonz port)*
- fix: remove std::iterator to resolve deprecation warning *(OpenToonz port)*
- fix: resolve C4018 signed/unsigned mismatch warnings *(OpenToonz port)*
- fix: typo *(OpenToonz port)*
- fix: unreachable code in tscannerepson.cpp and Naa2TlvConverter.cpp *(OpenToonz port)*
- Fix: Use sig_atomic_t for signal-safe shutdown flag *(OpenToonz port)*
- Prevent OS/theme background mismatch *(OpenToonz port)*
- Set proper window flag on preferences pop-up for Mac OSX *(OpenToonz port)*

Other
'''''
- Update translation files for v1.6
- Fix macOS build CMake version
- Fix removing unnecessary files in Windows builds
- Github build on macos-15-intel (Sequoia)/Fix Linux build
- Feature: Report missing/unknown XML tags during scene loading *(OpenToonz port)*


For more detailed information of these changes, visit the links provided in the `v1.6 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.6>`_ hosted in GitHub.


Previous Versions
-----------------

Here you can find links to previous versions' full Release Notes, hosted in GitHub:

`v1.5.4 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.5.4>`_

`v1.5.3 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.5.3>`_

`v1.5.2 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.5.2>`_

`v1.5.1 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.5.1>`_

`v1.5 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.5>`_

`v1.4.5 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.4.5>`_

`v1.4.4 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.4.4>`_

`v1.4.3 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.4.3>`_

`v1.4.2 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.4.2>`_

`v1.4.1 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.4.1>`_

`v1.4 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.4>`_

`v1.3.1 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.3.1>`_

`v1.3 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.3>`_

`v1.2 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.2>`_

`v1.1 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.1>`_

`v1.0.1 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.0.1>`_

`v1.0 Release Notes <https://github.com/tahoma2d/tahoma2d/releases/tag/v1.0>`_




.. |new| image:: ./_static/whats_new/new.png
.. |enhancement| image:: ./_static/whats_new/enhancement.png
.. |fix| image:: ./_static/whats_new/fix.png
.. |removed| image:: ./_static/whats_new/removed.png

.. |new_es| image:: ./_static/whats_new/es/new.png
.. |enhancement_es| image:: ./_static/whats_new/es/enhancement.png
.. |fix_es| image:: ./_static/whats_new/es/fix.png