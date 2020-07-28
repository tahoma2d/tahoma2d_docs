.. _using_ffmpeg_with_tahoma:

Using FFmpeg with Tahoma
===========================

What is FFmpeg?
---------------
| To render your animation as an **mp4** or **webm**, or also as a **gif** on Mac, Tahoma requires the FFmpeg multimedia framework to be installed on your machine.
| For more information, please visit this page: `About FFmpeg <https://www.ffmpeg.org/about.html>`_

Tahoma ships with a version of FFmpeg that is licensed under the LGPL license.  This version can export .mp4 videos, but may not deliver as high quality videos as the GPL version of FFmpeg.
You may want to change the version of FFmpeg that is used in Tahoma.  To do so, follow the instructions below.

Installing FFmpeg for Windows
-----------------------------

Downloading
~~~~~~~~~~~

| To download FFmpeg, first visit this page: `Download FFmpeg <https://www.ffmpeg.org/download.html>`_

|get_the_packages|

| Select the Windows icon and then select the **Windows builds** link:

|packages_windows|

| You will be taken to an **FFmpeg Builds** page with some options for the version of FFmpeg that you want to download:

|ffmpeg_builds_windows|

| In the majority of cases, the default choices are fine.
| Click on the blue **Download Build** button, this will begin downloading a zip archive containing FFmpeg.

Installing
~~~~~~~~~~

| Once you have downloaded the FFmpeg zip archive, open it and double-click on the first folder.

| Within the **bin** folder are the executable files that you will need.

- Create a new folder on your computer, the recommended location is **C:\\**.
- Name the new folder **FFmpeg**.
- Drag the contents of the **bin** folder from the archive into the newly created folder.

|ffmpeg_extracted_windows|

- Next, start Tahoma and open the **Preferences** window with File  →  **Preferences...**
- Navigate to the **Import/Export** category; at the top you will see a box with the text **FFmpeg path**.
- Insert the path to your FFmpeg folder that you created earlier, if you have used the recommended path, this will be **C:\\FFmpeg\\**:

|ffmpeg_path_windows|

- Restart Tahoma.
- Open the **Output Settings** window with Render  →  **Output Settings...**

| In the **File Settings** subsection, you should now see **mp4** and **webm**.

|output_settings_windows|

Installing FFmpeg for Mac
-------------------------

Downloading
~~~~~~~~~~~

| To download FFmpeg, first visit this page: `Download FFmpeg <https://www.ffmpeg.org/download.html>`_

|get_the_packages|

| Select the Apple icon and select the **Static and Shared builds** link.

|packages_mac|

| You will be taken to an **FFmpeg Builds** page with some options for the version of FFmpeg that you want to download:

| Make sure **macOS 64-bit** is selected under the **Architecture** column.

|ffmpeg_builds_mac|

| Click on the blue **Download Build** button, this will begin downloading a zip archive containing FFmpeg.

Installing
~~~~~~~~~~

| Once you have downloaded the FFmpeg zip archive, open it and double-click on the first folder.

| Within the **bin** folder are the executable files that you will need.

- Open Finder and create a new folder, the **Applications/Tahoma** folder is the recommended location.

|ffmpeg_finder|

- Name the new folder **FFmpeg**
- Drag the contents of the **bin** folder from the archive into the newly created folder.

|ffmpeg_extracted_mac|

.. tip:: For macOS 10.15 and later, each executable within the FFmpeg folder needs to be opened before using Tahoma (this only needs to be done one time, due to security features). In Finder, right-click on each executable (ffmpeg, ffprobe, and etc.) and select ``Open With → Terminal``. Once the Terminal windows have launched successfully, Terminal can be closed.


- Next, start Tahoma and open the **Preferences** window with File  →  **Preferences...**
- Navigate to the **Import/Export** category; at the top you will see a box with the text **FFmpeg path**.
- Insert the path to your FFmpeg folder that you created earlier, if you have used the recommended path, this will be **/Applications/Tahoma/FFmpeg**:

|ffmpeg_path_mac|

- Restart Tahoma.
- Open the **Output Settings** window with Render  →  **Output Settings...**

| In the **File Settings** subsection, you should now see **mp4**, **webm** and **gif**.

|output_settings_mac|

.. Images

.. |get_the_packages| image:: /_static/using_ffmpeg_with_tahoma/get_the_packages.png


.. Windows images
.. |packages_windows| image:: /_static/using_ffmpeg_with_tahoma/windows/ffmpeg_packages.png
.. |ffmpeg_builds_windows| image:: /_static/using_ffmpeg_with_tahoma/windows/ffmpeg_builds.png
.. |ffmpeg_extracted_windows| image:: /_static/using_ffmpeg_with_tahoma/windows/ffmpeg_extracted.png
.. |ffmpeg_path_windows| image:: /_static/using_ffmpeg_with_tahoma/windows/ffmpeg_path.png
.. |output_settings_windows| image:: /_static/using_ffmpeg_with_tahoma/windows/output_settings.png


.. Mac images
.. |packages_mac| image:: /_static/using_ffmpeg_with_tahoma/mac/ffmpeg_packages.png
.. |ffmpeg_builds_mac| image:: /_static/using_ffmpeg_with_tahoma/mac/ffmpeg_builds.png
.. |ffmpeg_finder| image:: /_static/using_ffmpeg_with_tahoma/mac/ffmpeg_finder.png
.. |ffmpeg_extracted_mac| image:: /_static/using_ffmpeg_with_tahoma/mac/ffmpeg_extracted.png
.. |ffmpeg_path_mac| image:: /_static/using_ffmpeg_with_tahoma/mac/ffmpeg_path.png
.. |output_settings_mac| image:: /_static/using_ffmpeg_with_tahoma/mac/output_settings.png

.. Need new output_settings_mac image

.. Credits:
.. Windows section contributed by Wolf_In_A_Bowl
.. Mac section contributed by Jane Eyre

