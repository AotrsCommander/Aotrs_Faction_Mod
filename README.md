# Aotrs Liches and Skeletons
Rimworld mod for creating skeletal undead xenotypes and faction.

Note for anyone stumbling across this: Functional as far as testing has gone (I haven't had enough raids to check the faction composition), but this in tenatively green for use.

This mod introduces liches and animated skeletons as a xenotype.

This is a modifiction to a small, unreleased mod in 1.4, which was heavily based on Wa! Real Skeletons (Continued). As Mile has discontinued support for that mod, I have attempted to make this one.

Credits:

RedMattis, Oskar, Sarg, Erdelf and Mile, whose mods (in the dependant list) I am standing on the shoulders of; RedMattis in particular can be credited with about 80% of the mod's code (and with some additional help to boot!) I have merely attempted to paste this together into a hopefully-functional unit.

Contents:

Two skeleton xenotypes: Spirit-Bound Lich and Animated Skeleton

Animated skeletons are fundementally negative-energy powered constructs. They are mindless, with their only capabilities derived from whatever default "programming" their animating spell had, and some limited psychic echoes from the corpse itself.

They have no blood, no not eat or sleep and are immune to poisons, diseases and most other effects.

Spirit-Bound Liches are skeletons whose bodies are "haunted" by a bound spirit (usually, but not always, the original owner) in a way not dissimilar to a location-bound huant, like a haunted house. On top of the traits they share with skeletons, liches produce a cold aura, and heal from damage rapidly. They can consue, but do not need to. While strictly, they do not need sleep, liches typically require some hours of meditation per day to regain their mana. (This is represented in game-currently as still having the sleep need, but functioanlly with the Fast Sleeper trait.)

Three additional simple endogene xenotypes:

Elf, Orc and Dwarf. Kalanothi Elves, Orcs and Dwarves. So-named for the elves from the Aotrs planet Kalanoth where the definitions were codified. Due to the prevalence of Harbinger Retrocasual Probability Engineering, these types of leves, orcs and dwarvesis quite common in the galaxy and possibly beyond, even when arising from apparently otherwise entirely unrelated worlds.

Two factions, The Army of The Red spear faction (the titular Aotrs) and the Skeleton Horde, comprising masses of animated skeletons, with some more advanced lich commanders. Both lichs and skeletons from thes factions may be of various endogene xenotypes, including the above.

General notes:

The colour of a skeleton is defined by hair colour. At the moment, it is set to a fixed value in the Gene defs, due to the only way I could get the eyeglows was to paint them on the forced head types. (I looked at the plausibility of doing facial animations, using just eyes (i.e. eyeglows), but ultimately concluded that it is beyond me. I toyed with a varaint of eye colour genes - but that doesn't work with Facial animation, unfortunately.) If that problem could be fixed, bone-as-hair-colour would in theory allow liches to paint their bones (to diversify skeleton pawns).

Liches sleep: Liches meditate to regian their mana, so sleep has been left enabled (with fast sleeper) in lieu.

Liches can eat: needs are set to 90%, so they should be able to eat (for fun and drugs etc.), but do not require it.


Known Issues:

Additional body parts (tails, tentacles) will not be skeletal. I have managed to disable noses and ears, to obviate the worst of the issues (those genes will be removed by the race type, to at least mollify the worst of this.

No facial animation: As noted, beyond my capabilities to have the eyes animated, sorry.

Butchering: You CAN butcher spiritbound and animated skeleton corpses, but it won't return anything. (In theory, once they become rotten, if you have Rim of Madness Bones, you can butcher them as rotten corpse for some bones.) It was either that or be unable to get rid of the corpses. I have yet to find the coding to either a) make a recipe for butchering their corpses (requiring Rim of Madess Bones) to drop bones or b) make them instantly rotten.


Future Possibilites:

Maybe a way to create your own animated liches and skeletons from corpses (perhaps a tome-learned ability). This would require graphics (which I am terrible at) and probably a fair bit more coding beyond my current abilitiy.

Better way to handle eyeglows (and weight the chances of which head (and therfore colour) they spawn with). (In turn, potentially allowing bone colour to be dyed.)

Way to butcher corpses for bones as above.

Meditation instead of sleep...? This might only be pertinent for psycasting, and would be a fairly significant buff.
