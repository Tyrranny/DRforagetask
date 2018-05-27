# DRforagetask
Welcome! 

This script is very useful for training the Trading skill on a Trader. It will also generate some profit at lower levels if you let it run awhile. My tester made 5 platinum before I ever even hunted with him, and he is a Ranger.

INSTRUCTIONS:
1. Download the foragetask.lic to your scripts folder.
2. Open your Setup YAML (ex:Tyrranny-setup.yaml) and add a new line for forage_container: {your bag name here}
3. In game type ;foragetask

There may be missing forage targets. If you see one that I missed, there are instructions in the script on how to add it, but please also post a comment here letting me know so I can fix the main script.
DO NOT ADD TARGETS THAT ARE SEASONAL OR NOT IN ZOLUREN. note: I have a couple that are seasonal, if they are out of season and it fails to find them, the script will go cancel task and get a new one. In the future I may look at intelligently checking against seasons, night/day etc.

If you find any other issues, or have suggestions, please let me know. I am new to Ruby so also please excuse the poor code :/

Tyrranny

Notes:
Sometimes you can have multiple Targets for the same Forage Item. An example is below. As you can see they both with forage limbs, but they have different assignments from Mags. 

{"name" => "limb", "room" => "792", "target" => "limbs"},
{"name" => "limb", "room" => "792", "target" => "sticks, branches or limbs"},
