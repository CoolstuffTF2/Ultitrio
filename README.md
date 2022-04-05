# Ultitrio
TF2 3v3 Comp Format Made By Coolstuff

What is Ultitrio?
---
Ultitrio (previously called Ultiduo + 1) is a new competitive format created by Coolstuff that consists of Soldier, Medic, and Scout. Good Ultitrio maps consist of lots of mobility opportunities for all 3 classes and less punishment for getting knocked off of the point. Good maps that have been tested consist of Ulti_Fira_b1 and Ultiduo_Grove_b4. The addition of Scout is to add more dynamic gameplay for both teams. Before the finalization of the roster, Demoman was considered in place of Scout, but being as most Ultiduo maps have 2 exits and close quarters, Demoman would be able to lock down every inch of a map for free and subsequently deny everyone, so Scout was chosen for his flexibility and high mobility. With the addition of Scout, it allows for more strategic gameplay because of Scout's added dynamic play styles with weapons like the Fan O' War and Wrap Assassin, leaving Soldier to be more of a "clean up" class after a Scout marks someone or hits that player with a Wrap Assassin ball. Not only that, it's possible to split up your team to perform pincer maneuvers with Soldier and Medic pushing on one side and a fully buffed Scout pushing on the other, which became a common theme in our testing.

While Ultitrio is still in the testing phases for a whitelist and as a competitive format in general, in limited testing, its more dynamic small team roster allows it to serve as a good bridge between the formats Ultiduos and 4s as it's very heavily DM skill-based, much like Ultiduos 



Thank you for your interest in the use of Coolstuff's Ultitrio competitive format!
For installation instructions, please follow the guide below, otherwise, have fun!

Installation instructions:

Step 1: Navigate to the following path in your TF2 server using your browser or FTP/SFTP client of choice, "\tf\cfg"
---
Step 2: Extract this .zip files' contents to your Desktop or another readily available workspace on your computer.
---
Step 3: Copy and paste all the config and whitelist files to "\tf\cfg"
---
Step 4: Reboot your TF2 server and then you're done!
---
A bit on the configs for beginners:

It's important to remember to not exec the cs_UT_base config at all. This is used to set up all other required commands for the Ultitrio format, nothing more nothing less. Only exec the cs_ut_ultiduo or _bo5 varrient. When finished, exec the cs_off config to remove all of the config's changes.

To exec configs:

Step 1: Either rcon into your server using TF2's console or use the console in your server hoster (if any)
---
Step 2: Type in "exec cs_ut_ultitrio" for the best of 3 varrient or "exec cs_ut_ultitrio_bo5" for the best of 5 gamemode varrient.
---
Step 3: Profit? No, fraggage and destruction. Go have fun!
---
Step 4: Once you are done, type "exec cs_off" and that reverts your server to normal. If you have issues with the whitelist, see below.
---
Note: If you're having whitelist issues, make sure you DO NOT use "map" to change maps but use "changelevel" instead, you will need to do "changelevel" every time you exec a new whitelist because source is funny lmao.
