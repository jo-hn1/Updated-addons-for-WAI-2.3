**************************************************************
* Credit to the developers of WAI, JasonTM, f3cuk and others *
*                                                            *
* All I did was update the files to make these work with the *
*           latest version of WAI 2.3 for Epoch 1.0.7        *
**************************************************************

***Thanks to Caveman2019 for creating these missions, I just changed them to suit what I needed them to do***

Caveman's post on Epoch forums: https://epochmod.com/forum/topic/45420-outdated-release-5-new-missions-for-wai-223-update-will-be-posted-soon/?tab=comments#comment-305647


UNPACK your dayz_server.pbo then:


1.  Open your config.sqf file in your WAI folder

    Add this to your list of missions at the top or bottom (if bottom remove the comma)
	of missions in both bandit AND hero:

							["satellite",1],
							["oil_reserve",1],
							["hostage",1],
							["gold_mine",1],
						    ["cargo",1],
							
2. Copy the 5 missions into your dayz_server\WAI\missions\missions folder.

3. Merge or copy the "mission_loot.sqf" to WAI\configs or edit your own file.


UNPACK your mission.pbo then:

4. Add the stringtable additions found in "StringTable Additions.txt" to your
   stringtable.xml in your MPMissions\DayZ_Epoch_24.Napf folder.
   
   You can change the announcements to your liking, if you don't like mine :)

5. All done!

Easy to set up and configure to your liking :)


