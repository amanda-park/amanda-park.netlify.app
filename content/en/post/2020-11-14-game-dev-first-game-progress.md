---
layout: post
title: "Adventures in Game Development: First Game Progress"
date: 2020-11-14
tags: [reflections, game-dev] 
---

I know I haven't given much of an update on what I've been working on or how I've been doing - 2020 has definitely been a doozy on staying consistent with the blogging front. However, I have made a lot of progress on developing that skillset by working on a small game project. It's based on a hypothetical sidequest happening for a long-standing D&D campaign I've been a part of, called Edge of Chaos.

I settled on having that be my first project because to me the stakes were a lot lower than going straight to the dream project that initially motivated me to make a game.  

## Development Process - Game Engine

If you've followed my blog posts, you'll know that after experimenting with Godot that I eventually went to RPG Maker as a game engine for its ease of use as a solo developer. What took a couple of months to create in Godot happened in only a few minutes in RPG Maker, which made it much easier to focus on the meat and bones of the gameplay and other game development skills that I needed (and continue to need) to develop.

While using RPG Maker is certainly much faster than using a full-fledged coding language, to do what I actually want to do it's pretty heavily dependent on external code people have written for the engine, called plugins. Plugins help to extend the functionality of the engine, and since RPG Maker is written in JavaScript, I've been relying on those who have made plugins to get my game to have some of the functionality it would otherwise not have. 

(I hope someday to learn JavaScript in order to make the "perfect" game I have in my head, but right now I'm professionally trying to learn Python and further develop my R skills. I don't need another programming language competing for my attention right now.)

## Development Process - Combat

At its core, I'm working on a turn-based RPG, given that D&D also works in that capacity. I've always preferred turn-based RPGs anyway, so I didn't feel a loss knowing that active-turn battle systems in RPG Maker generally didn't work well. Through a plugin, I've changed the default battle system to allow for agility to influence turn order, which helped combat feel more dynamic. The characters in combat are based entirely off the characters that are in the D&D campaign, which made developing their combat skills and balancing them much easier.

Overall, there are 5 characters, and they each play as follows:

* Sorcerer: The protagonist. Magic DPS.
* Cleric: Healer and tank 
* Wizard: Elemental magic damage and status effects
* Rogue: AOE healing, turn order manipulation, status effects
* Ranger: Physical DPS

Normally in a JRPG there aren't so many magical casters, let alone having two prioritize in shooting fire at things (which is what the Sorcerer and Cleric do in the actual D&D campaign). Their classes thankfully allowed for enough differentiation between the two, though in an ideal RPG I'd have each character have a unique primary element and then a secondary element they could train up. As a way to help buff up the wizard I gave him access to all the different elemental skills short of Holy magic, which offers him versatility in exploiting enemy weaknesses compared to the other characters. The Rogue was pretty underpowered until I gave her turn manipulation powers, which made her much more useful. And the Ranger just does the vast majority of the damage in the actual D&D campaign, so playing him like that made sense.

In general, through this journey something I've learned is that I work better when I have specific constraints set around me. Having to work with preset characters and make it work made things much faster than me trying to create new characters and balance them accordingly.

## Development Process - Noncombat

I didn't realize that after a handful of months in RPG Maker that I'd hate mapping so much, but it's proven to be something I don't care for doing. Creating a map that is visually interesting but also practical from a game design standpoint is challenging, far more than I would have thought prior to making this game. I would only consider my mapping skills average at this point, despite making a lot of maps, just because that design has had such a steep learning curve.

However, something I feel like I've gotten much better at is creating cutscenes for the game. I've understood how to use events in RPG maker, conditional branches for character choices, and switches and variables to track game progress. It takes time to make a cutscene more compelling by adding in the little movements and reactions of characters, but I consider it worth it so the story is more likely to grab the player's attention. 

There's certainly many other aspects needed to make a game feel whole beyond just creating good maps and cutscenes, and I've been trying to improve my skills there as well. Game development requires competence in a lot of different areas, and I'm sure with time I will get a lot better at making a cohesive and compelling game.

## Conclusion

Overall I'm very happy with the progress I've made with this beginner's project, and I hope to finish in the next few months. When it is released, I will post it for anyone interested to try out - rest assured, it will be free!

Whenever I take on one of these new projects I always learn something about myself. Compared to my last project (building a mental health app), this time around I've been much better at using version control to maintain my project's code. I've also structured my project in such a way that the code is more modular than in past projects and more of it is reusable. (Admittedly you can only do so much of this with RPG Maker, but I do it where I see the possibility.)

However, I've still noticed some ways to make this process more efficient. I once again was sucked into scope creep, which made a project that should've just been a very simple RPG adventure turn into something much more interesting, but much more time-consuming. I have tried to mitigate these effects when I realize I'm considering doing something far too intensive, so it's still a project I believe I can finish. But it has gone beyond its initial case due to my ambitious ideas, for better or for worse.

For the time being I think I will go back to posting about different topics on the blog, but I hope you enjoyed this miniseries where I've begun learning game design!

### Game Development Resources

#### RPG Maker

Some of these specify they only work in MV due to plugin compatibility. However, even older videos on RPG Maker can be helpful if they're just working with the base engine to learn how to do things.
	
[SRDude](https://www.youtube.com/playlist?list=PLMcr1s5MjsiTky6KB4ML-q_QoBE_ZYJk5)

[Echo607](https://www.youtube.com/playlist?list=PLTcc-t1_NNLUzIUVRDyNWyGkfT-TBRtkG)

[Driftwood Gaming](https://www.youtube.com/playlist?list=PLGxLMLE3NfnJ2wm59fAYdxfRptRuKfvRA)

[BenderWaffles](https://www.youtube.com/playlist?list=PLFx_7sHrMlWUr6Kuk5FCHj6xsCncZVWYN)

#### Pixel Art

RPG Maker comes with stock assets, so you can just rely on those for the art. But if you want to make some of your own stuff and have your game stand out a bit more, I'd recommend checking these channels out:

[Pixel Art Tutorial - written guide](http://pixeljoint.com/forum/forum_posts.asp?TID=11299)

[MortMort](https://www.youtube.com/playlist?list=PLR3Ra9cf8aV06i2jKmgKvcYVHI86-4K_b)

[PixelPete](https://www.youtube.com/playlist?list=PLmac3HPrav-9UWt-ahViIZxpyQxJ2wPSH)
