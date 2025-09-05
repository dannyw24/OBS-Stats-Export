**OBS Stats Export Plugin**
RuneLite plugin that exports your OSRS hitpoints, prayer, and run energy to text files for OBS streaming overlays.
What it does
Creates three text files that update in real-time:

hitpoints.txt - Your HP (e.g., "99/99")
prayer.txt - Your prayer points (e.g., "85/99")
energy.txt - Your run energy (e.g., "100%")

**Setup**

Install the plugin in RuneLite
In OBS, add Text sources that read from these files:

%USERPROFILE%\.runelite\obs-stats\hitpoints.txt
%USERPROFILE%\.runelite\obs-stats\prayer.txt
%USERPROFILE%\.runelite\obs-stats\energy.txt


Style and position your overlays

That's it! Your stats will now show on stream automatically.

**Configuration**
Configure display formats in RuneLite Settings → "OBS Stats Export"
