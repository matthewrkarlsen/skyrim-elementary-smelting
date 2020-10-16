
Mod Name:
    Elementary Smelting

Version:
    0.9.2 (Beta)
	
Important Upgrade Note:
    Please ensure that any of the ESPs below that you cannot use or do not wish to
      use are unchecked.

Author:
    Matthew R. Karlsen (quixoticynic)

Nexus Mods files page:
    http://www.nexusmods.com/games/users/3546091/?tb=mods&pUp=1

Mod Description:
    Provides reverse recipes for craftable metal items (i.e. enables you to smelt the 
      item back in to ingots). Provides the correct quantity of the most valuable ingot
      type (based on quantity x value). The mod depends upon PRUFEI (Protection for 
      Recipes Using Favorite and Equipped Items) in order to prevent smelting of favorite
      and equipped items.

Dependencies:
    PRUFEI (Protection for Recipes Using Favorite and Equipped Items)
    The Unofficial Skyrim Patch (USKP)
    The Skyrim Script Extender (SKSE)
    
Installation:
    Install USKP
    Install SKSE
    Install PRUFEI
    Copy "Elementary Smelting.esp" to your Skyrim data directory.
      Usually located at C:\Program Files\steam\steamapps\common\skyrim\Data\
      or C:\Program Files (x86)\steam\steamapps\common\skyrim\Data\
    Ensure that "Unofficial Skyrim Patch.esp", "PRUFEI.esp" and "Elementary Smelting.esp"
      are enabled in your Skyrim Data Files menu. Ensure that they are loaded in the 
      order listed here (i.e. USKP, followed by PRUFEI, followed by ES).
    IMPORTANT: ensure that any of the ESPs below that you cannot use or do not wish to
      use are unchecked.

Optional ESP files:
    Armor to Scale.esp                    Allows breakdown of dragon scale-based armors
                                            (~50% scale recovery).
    Elementary Dawnguard Smelting.esp     Allows breakdown of Dawnguard craftable items.
                                            Requires Dawnguard and the Unofficial Dawnguard Patch.
    Elementary Dragonborn Smelting.esp    Allows breakdown of Dragonborn craftable items. Requires
                                            Dragonborn and the Unofficial Dragonborn Patch.
    Elementary Hearthfire Smelting.esp    Allows breakdown of Hearthfire craftable items. Requires
                                            Dragonborn and the Unofficial Hearthfire Patch.
    Leather Again.esp                     Allows breakdown of leather armors. This recovers 50% of
                                            the total leather (leather and strips) in the form of
                                            leather strips.
    Clutter Cutter.esp                    Allows the breakdown of metal Skyrim clutter items (the
                                            number of ingots provided is based on the item weight).
	Elementary Smelting Extended.esp      This modification extends Elementary Smelting to include
                                            items that are, by default, non-craftable (such as the 
                                            Imperial Bow).

Changes:
    0.5.1 -- Initial public release
    0.6.1 -- Added optional support for dragon scale-based armors, leather armor, Dawnguard 
               craftable equipement, Dragonborn craftable equipment, and Hearthfire smeltable items
               (the ESPs for these extensions need to be downloaded separately).
    0.7.1 -- Added support for the breakdown of Skyrim metal clutter items.
    0.7.2 -- Fixed Clothes Iron breakdown recipe.
    0.8.1 -- Added recipes for non-craftable items via the "Elementary Smelting Extended" ESP.
    0.9.1 -- Tweaked to prevent users being presented with an incomplete smelting menu whilst
               the favorite update script is running.
    0.9.2 -- Fixed a bug that prevented the last item of any type from being smelted.


Credits:
    Created by Matthew R. Karlsen (quixoticynic)
    This mod would have been impossible without major assistance from 'mrpwn' and 
      'IsharaMeradin' on the PRUFEI mod. These mod authors are not responsible for
      any bugs that may remain). Thanks to InfamousNate for spotting the bug fixed
      in version 0.9.2.
        
Thanks:
    Thank you for downloading and trying this mod. If you have any feedback please 
      post it on the mod's forum thread. You can contact me directly using 
      firstname@lastname.me.uk using the firstname Matthew and the last name
	  Karlsen.

License:

Formally, the mod is released under the BSD 2-Clause License:

Copyright (c) 2014, Matthew R. Karlsen (quixoticynic)
All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.