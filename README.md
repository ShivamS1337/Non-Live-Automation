# Non-Live-Automation

Prerequisites / precondition:
-----------------------------------------------------------------------------------

Asset Uploaded and Downloaded to the player
Playlist should be available as per the Test coverage


Configuration details
-----------------------------------------------------------------------------------
Configuration >>> Configs >>> Playlist_config >>> based on feed eg. thor

Always_pick_asset_duration = Enable/disabled
Always_pick_asset_som = Enable/disabled

------------
Configuration >>> Triggers >>> 

scte35 should be configured for type(program)
scte35 for all scenairos

------------
Configuration >>> Logos >>> Enable feed logo

Channel logo should be enable
------------
Audio Tracks = 8



Test case coverage list
----------------------------------------------------------------------------------
Duration_mismatch
Hole Management
Fixed_asset
Soft Segment
SOM(DURATION & SOM FROM PLAYLIST)
Always Pick Asset Duration 
Always Pick Asset SOM
Dynamic Graphics
Static Graphics
Asrun report
SCTE
DST
Subtitle
Voiceover
Break


How to Download a particular file from git.
------------------------------------------------------------

Navigate to the repository and find the file you want to download,use the "Raw" button to download the file.It will redirect you to new tab, hit ctrl+S
and you will be able to save in your local machine

or

Download using Git client : You can also use Git client like GitKraken, SourceTree, GitExtensions to clone the repository and download the particular file you want.

or 

Download using the Git API: If you are working with a Git hosting service that provides an API, you can use the API to download a specific file from a repository. For example, GitHub's API allows you to download files using a URL in the following format: https://raw.githubusercontent.com/<OWNER>/<REPO>/<BRANCH>/<FILEPATH>.
