# LyricText
An FL Studio / ZGameEditor Visualizer plugin for displaying Lyrics

This is heavily based off Rado1's HUD Text and uses his ZgeNanoVG
 library.  It is intended to greatly simplify scripting text animations for 
lyric-style videos.

You'll need to automate the "Text line" control to pick lyrics from the
"Add content->Text" page in ZGE Visualizer.

When the text changes, it starts an Attack, which lasts for the
specified length (the slider is a multiplier on beats).

After the attack effect, it goes to hold, then to release.

On top of the A/H/R effects, the Beat FX will be applied if one
is selected.
