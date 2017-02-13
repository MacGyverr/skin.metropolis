# Metropolis for Kodi 18 and also RetroPlayer

## So this is not official and very Alpha, but it should work with Kodi 18.

It will need a special version of script.skinshortcuts which in turn needs script.module.simpleeval.
I have included the most current versions of those I could find available on Feb 12 2017 in this version, 
all files will need to be installed via "Install from zip" using the zips in the "extras" folder.

I would download them separate from here https://github.com/MacGyverr/skin.metropolis/tree/Retroplayer18/extras
and then download the Git zip from here https://github.com/MacGyverr/skin.metropolis/archive/Retroplayer18.zip

it will name the download "skin.metropolis-Retroplayer18.zip", this is the file used to install the skin after
the dependencies have been installed.

So:
script.module.simpleeval.zip      First
script.skinshortcuts-1.9.0.zip    Second
skin.metropolis-Retroplayer18.zip Last


Failing to do so in that order will give you a version that has no menus and will be a pain to undo.



If you wish to use the Retroplayer features built into Kodi remember to add the following to advancedsettings.xml

	<gamesgeneral>
		<enable>true</enable>
	</gamesgeneral>
