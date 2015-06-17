..  Titling
    ##++::==~~--''``

Sound capture
:::::::::::::

Device
    Roland R-05
Sample rate
    48.0 KHz
Encoding
    16bit WAV
Low-stop filter
    100Hz
Mic gain
    36 (High)

Screen capture
::::::::::::::

Platform
    Gigabyte P34
Display adapter
    Nvidia GTX 860M
Operating system
    MS Windows 8.1
Software
   OBS 0.651b
Resolution
    1280 x 720
Frame rate
    30 fps
Encoder
    x264
Max bit rate
    6000 kbps
Options
    * enable CFR
    * crf=18
Output format
    MP4

See the `OBS guide`_ for more details.

.. OBS guide: https://obsproject.com/forum/resources/how-to-make-high-quality-local-recordings.16/

Transcode video
:::::::::::::::

Be careful editing from sources with variable frame rates. At some point you
might encounter video or audio artifacts. When this happens you'll need to
transcode those sources to more resilient formats, eg:

Software
    ClipToolz Convert V2.1.10
Video
    1280 x 720p 30fps
Audio
    None
Output
    10bit ProRes 4:2:2
Output format
    .mov

Edit
::::

Platform
    Gigabyte P34
Display adapter
    Nvidia GTX 860M
Operating system
    MS Windows 8.1
Software
   Lightworks 12.02
Video
    720p 30.0 fps
Audio
    48 KHz 
Import
    Transcode to AVI YUYV ? Not needed for simple example.
Output
    1080p (sf) 30fps
