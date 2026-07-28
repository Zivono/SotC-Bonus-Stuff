# SotcBonusStuff
A module for the foundry SotC game system. Various features, WIP, to be expanded as needed

New to developement for foundry. I heavily referenced the Stars Initiative Overlay by by vani_th to understand how make modules for SotC.

Toggleable features:
- Light Display Over characters
- HP/Stagger bar (needs character to set up their HP/sttager as bars in the resources of their token)
   - Can also be ??? instead of numbers, set in the token sheet Resources section
- Revealed / Rolled skills show up as images in chat
   - You can click on the images for these skills to pull up a full screen version
- Characters can reveal singular skills / passives / biography parts, to everyone
   - On Characters that are not yours, you can view a preview sheet of their revealed skills / passives etc.
- "Cutscene maker" Simple slide like thingy for the DM to use
- Option for others to quick add customs statuses to their sheet when printing statuses
- Advanced skill text formatting, to include colors and icons
   - Use {"Status effect name"} (These use the icons included in the sotc foundry system (found in systems/sotc/assets/statuses), if you want to use an icon from a subfolder use a / like in a filepath) to put an icon into a skill
   - Alternatively use {file:"filepath"} to specify an image file from anywhere in your foundry files, like if you uploaded an extra file into your assets
   - Use {color:#F54927}Bleed{/color} to color test
- Silly bonus features
   - blackjack
