# SotcBonusStuff
A module for the foundry SotC game system. Various features, WIP, to be expanded as needed

New to developement for foundry. I referenced the Stars Initiative Overlay by vani_th to understand how to make modules for SotC.

All features are off by default, and can be turned on in the settings menu. 

Toggleable features:
- Light Display Over characters
- HP/Stagger bar (needs character to set up their HP/sttager as bars in the resources of their token)
   - Can also be ??? instead of numbers, set in the token sheet Resources section
- Revealed / Rolled skills show up as images in chat
   - You can click on the images for these skills to pull up a full screen version
   - You can write {tag:"NoImage"} in the skill description to make a skill not show any image 
   - You can write {tag:"JustImage"} in the skill description to make a skill show only the image with no text on the image
- Characters can reveal singular skills / passives / biography parts, to everyone
   - On Characters that are not yours, you can view a preview sheet of their revealed skills / passives etc.
   - You can Hide a characters name on the reveal sheet in the reveal config
   - You can toggle between completely hiding unrevealed passives or having them show up as ???
- "Cutscene maker" Simple slide like thingy for the DM to use
- Option for others to quick add customs statuses to their sheet when printing statuses
- Advanced skill text formatting, to include colors and icons
   - Use {"Status effect name"} (These use the icons included in the sotc foundry system (found in systems/sotc/assets/statuses), if you want to use an icon from a subfolder use a / like in a filepath) to put an icon into a skill
   - Alternatively use {file:"filepath"} to specify an image file from anywhere in your foundry files, like if you uploaded an extra file into your assets
   - Use {color:#F54927}Bleed{/color} to color test
- Add Next Scene reminder (or just generally reminders) to characters, from the top of the character sheet
- Quick add button for printed statuses, so players can quickly add printed statuses to their sheet
- Easy status inflictor, create presets of statuses and select who they are inflicted to, for when you f.e. have a skill that inflicts multiple statuses, so you can do them more quickly
   - You can only add statuses you have access to, the dm can add every status, players can only add those in their sheet or inventory
- Silly bonus features
   - blackjack


   manifest: "https://raw.githubusercontent.com/Zivono/SotC-Bonus-Stuff/main/module.json"
