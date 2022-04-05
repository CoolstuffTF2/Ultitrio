# Ultitrio
TF2 3v3 Comp Format

Thank you for downloading and planning to use Coolstuff's Ultitrio competitive format!
For installation instructions, please follow the guide below, otherwise, have fun!

Installation instructions:

Step 1: Navigate to the following path in your TF2 server using your browser or FTP/SFTP client of choice, "\tf\cfg"
Step 2: Extrat this .zip files' contents to your Desktop or other redily avaible workspace on your computer.
Step 3: Copy and paste all the config and whitelist files to "\tf\cfg"
Step 4: Reboot your TF2 server and then you're done!

A bit on the configs for beginers:

It's important to remember to not exec the cs_UT_base config at all. This is used to set up all other required commands for the Ultitrio format, nothing more nothing less. Only exec the cs_ut_ultiduo or _bo5 varrient. When finished, exec the cs_off config to remove all of the config's changes.

To exec configs:

Step one: Either rcon into your server using TF2's console or use the console in your server hoster (if any)
Step two: Type in "exec cs_ut_ultitrio" for the best of 3 varrient or "exec cs_ut_ultitrio_bo5" for the best of 5 gamemode varrient.
Step 3: Profit? No, fraggage and destruction. Go have fun!
Step 4: Once you are done, type "exec cs_off" and that reverts your server back to normal. If you have issues with whitelist, see below.

Note: If you're having whitelist issues, make sure you DO NOT use "map" to change maps but use "changelevel" instead, you will need to do "changelevel" every time you exec a new whitelist because source is funny lmao.
