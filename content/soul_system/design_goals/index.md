+++
title = "Soul System Design Goals"
date = 2026-03-28
weight = 3
path = "soul-system-design-goals"
description = "The design goals for my generic TTRPG system, Soul System, that powers Small Souls."

[extra]
image = "small_souls.svg"

[taxonomies]
tags = ["Tabletop Roleplaying Games", "Small Souls", "Soul System", "Design", "WIP", "Tiny Epics"]
ttrpg = ["Small Souls", "Soul System", "Design", "WIP", "Tiny Epics"]
+++

I've been wanting to share my personal TTRPG project here for a while.
As I'm hosting the RPG Blog Carnival with the theme of "[Tiny Epics](@/community/rpg-blog-carnival/tiny_epics/index.md)", now is as good a time as ever given I started designing for a game within this genre.
I started a year ago designing my game called "Small Souls" from which I separated the generic system from the small souls specifics.
The relative nature of one's abilities as the scale of the task increases or decreases started in Small Souls, but I found it to be useful as a generic system that emphasizes dramatic tension, informs roleplaying direction, and fleshes out the spectrum of possibilities and agency.
Here are some of my macro design goals for the "Soul System", which involves a counted dice pool with "push your luck" resolution mechanics as you pay resources that embody your character's use of stamina or energy.
A post on the mechanics as of versions 0.1.0 and 0.2.0a is soon to follow, along with some playtest reflections.

<!-- more -->

<img
    src="small_souls.svg"
    alt=""
    style="display:block; margin-left: auto; margin-right: auto; width: 100%;"
    loading="lazy"
    decoding="async"
/>
<p style="text-align:center;">
Small Souls logo as of version 0.2.0a.
</p>

## Types of Agreements & Guidelines

I consider three types of agreements and guidelines that are for ensuring consistency in their respective areas during play:
1. Social Agreement
2. Narrative
3. Game Mechanics

These are my preferred ordering, though you can order them to your tastes however you want.
For my games, and especially Small Souls and the Soul System, I specifically prioritize the following:

$$\text{Social} > \text{Narrative} \ge \text{Game}$$

The social agreement is not social game mechanics. <!--like in [Good Society](https://rpggeek.com/rpg/46959/good-society-a-jane-austen-role-playing-game) or [Pasión de las Pasiones ](https://rpggeek.com/rpg/48579/pasion-de-las-pasiones).-->
This is the meta discussion that happens before the game or during session zero, and during play when necessary.
The social agreement is between the players and focuses on why they are here, what is the kind of fun they intend to have, what are the desired experiences and outcomes in play?
The social agreement also includes the boundaries of the players, which may be clearly communicated or not, but if not then clear communication and respect in navigating a situation once someone's boundary is crossed is expected.
For me, I find it near impossible for the social agreement to not be the first and utmost priority as it is the meta agreement outside of the game.

Narrative consistency is next as I want my roleplaying games to focus on the players collaboratively creating stories that are enjoyable to play and to recount afterwards.

The importance of consistency in game mechanics being significantly higher than narrative consistency can result in games like chess, competitive games, or videogames.
The game mechanics should help create the narrative and lead players to the intended play experience while ensuring consistency in how their actions effect the game state.
**The game mechanics establish the computable game state and dynamics**, which are akin to say a physics simulation, but they need not be so complex and exact as the computers running these are humans (heh heh).
I personally want some *opt-in complexity* in the game mechanics and I enjoy the puzzles they can provide, but ultimately I want the game to be simple and intuitive to play with low to no burden in maintaining game state by default.

These three types of rules are my personal renaming of the "[Three Layers of RPG Rules](https://pretendo.games/2022/04/15/three-layers-of-rpg-rules/)" to be more informative to me.

## Game Design Objectives

Given the communicated and agreed upon social contract between the players, these game mechanics help create and direct the roleplay of the desired type of narrative.
I'm seeking high "**ludonarrative resonance**", the opposite of [ludonarrative dissonance](https://en.wikipedia.org/wiki/Ludonarrative_dissonance).
The more the game mechanics thematically emphasize what's happening in the narrative, the better, while maintaining emphasis on the story being told rather than the mechanics themselves.

Speaking of resonant game mechanics,
I want the game mechanics to not get in the way of playing if they match your chosen play style, and can help gently direct people towards a type of play style, while ultimately leaving the choice up to the player.
The "Keys" from "[Lady Blackbird](https://ladyblackbird.org/)" and other "Tales from the Wild Blue Yonder" games fit this idea where they reward the player for acting in a certain way, but also let the player opt out and redirect their character to fit their desired roleplay.
These Keys are an example of player chosen roleplay direction that I want to include in my game.

I seek game mechanics that keep the story moving forward and avoid stagnant state through positive reinforcement.
I started with the roll under 1d20 resolution mechanics from [Mausritter](https://mausritter.com/), as I like [Into the Odd](https://rpggeek.com/rpg/23882/into-the-odd)'s simplicity of character state and resolution.
However, I ended up choosing counted dice pool mechanics for the mixed outcomes and fail forward resolution that they provide as per [Blades in the Dark](https://rpggeek.com/rpg/26952/blades-in-the-dark), [CBR+PNK](https://rpggeek.com/rpg/68271/cbr-plus-pnk), and [Shadowrun](https://rpggeek.com/rpg/312/shadowrun-4th-and-twentieth-anniversary-editions).

### Mechanical Guides for Play Principles

The more I can get the game mechanics themselves to help achieve my design goals without having to rely on play principles the better.
Play principles are essentially things the players are supposed to keep in mind for the designer's intended play experience, but they aren't like rules of a board game that are required to play the game.
However, the more complex the principles are, the more easily they can be forgotten.

When a TTRPG system states the intended play principles, it is useful to the players to know what the designer intended, but ultimately mechanics that support those principles and gently guide the players to play that way are more desirable from a designer's perspective of consistency.
That is, if those principles are actually important to the play experience.
I suspect that I will not be able to remove play principles entirely from my game (nor should they be), and I will certainly include them up front (as they already are in my early versions), but the more we can have a consistent and gentle guide towards those principles *in play*, the better.


### Minimal Irrelevant Computation
To keep the game simple and quick to play, I seek minimal computational complexity that is outside the ludonarrative.
That is, minimal to no math or human computation outside of the narrative, especially during the vast majority of play.
Using computational design of machines from computer science theory can help model and minimize this complexity.

Computational actions of machines involve reading and writing to some state. The locality of that state becomes another concern. Where that state is or what other machines can access it help

- In TTRPGs, reading & writing becomes: read, communicate, compare, count, addition or other mathematics.
- Read is further specified by the locality of the information read and time or energy spent reading.
    - **Recall**: when you remember something without having to look it up
        - *Reflexive recall*: you know it off the top of your head. Minimal thinking time.
        - *Recollection*: when it takes time to collect your thoughts and recall.
    - **Aided Recall** is using the character sheet or notes to speed up recollection.
        - This is like a local external cache to your internal memory. Easily accessible at a glance.
    - **Search**: To search through many notes or to search through a book for the answer.
        - Ideally the book is made for ease of reference and search
            - good information design in organization at local and global levels
            - indices, table of contents, memorable writing or figures

Given this, I'll...

- Prioritize counting and comparison of few items, instead of math.
    - otherwise, keep the math to simple addition of addition under +5.
- Minimize the memory and space requirements as well.
- Minimize the required communication of game state and changes.
- Aid recall by having an informative and intuitive character sheet, which serves as the User Interface for the game state, besides maps and of course player communication.
    - All the state of the character should be on that sheet and easy to read and understand
    - All of the state of the character should inform roleplaying decisions and direct acting.
    - Easy to update & store.
- Distribute the workload across players while maintaining the desired information access, which is often desired in information asymmetric games, such as your typical Dungeon Master and Players separation.

This is what led me to counted dice pools and what I liked about the players knowing their character's threshold for the resolution of rolls as in Into the Odd-likes.
The players can simply state "X of Y" for counting X successes of Y dice rolled.
With two thresholds, say one for both boons and banes, they simply say "X of Y with Z banes".

### Simple & Intuitive Design
Besides simplicity in design from minimizing the computational complexity, I also seek
a simple and intuitive genre agnostic system for character roleplaying.
- Intuitive in that if you are playing your character, then the system resonates with how you play, rather than causing discord, slowing, or stopping your playing.
    - Changes in flow of roleplaying a character should be due mostly to the character changing their own path. Otherwise, as per the whims of the players.
- If a part of the system is not used, then it subtly fades to the background until desired in play.
    - For Soul System, I expect this will commonly occur for the survival mechanics when not in immediate survival situations.
    - Similarly, I expect this to happen to inventory as well until you run into the limits of what you can hold.
    - And relationships and bonds may not matter as much in traditional combat scenarios, although I personally would provide teamwork benefits to players who share stronger bonds of trust.
    - This happens to most skills and feats in DnD, and sometimes people forget that which would have been helpful!
        - We absolutely want to try to avoid the latter, although the former is not a bad thing as elements not in play simply won't be focused on.  Of course, to avoid forgetting useful things, optimizing the use of space on a character sheet for relevant information is important.
            - For these cases, character sheets tuned to the intended play style could be quite helpful.
            - Thus we either create specific sheets for games of different focus, or we enable a modular design of character sheets that lets it be modified by the user as they need.  The modular design would work well in an interactive digital form, but not so much for pen and paper... unless... we get smart with it!
- If something is desired to be extended, then the game mechanics at least offer a solid foundation, if not a means to build that extension.
    - If Soul System cannot generalize a style of play or a game, it better be because that style of play is quite unique and requires a specific or complex construction for that play style to occur at the cost of other play styles.
    For example, specific resolution mechanics that closely fit the theme of the game.

### Play Objectives
Play that
- emphasizes the narrative and helps provide dramatic tension and moments
- rewards the players' critical thinking and problem solving as their characters
    - Play that emphasize actions and consequences and rewards learning from experiences as both player and character.
        - Character progression beyond only equipment, limited meta-knowledge, or traditional class-based XP leveling.
    - Reward cooperative behavior among players to build an interesting story
    - Rewards perspective taking
- lets the player decide the outcome within reason and at a significant but reasonable cost.
    - Otherwise, they get to shift things in their favor proportional to their paid cost.
- inspires and encourages healthy curiosity and exploration in and out of game.

### Never Take Away Without Purpose
Never take away something without good reason. Instead, provide more things that need done and reward more for being done.
The reasoning for this is psychological.
It tends to feel worse when you get something and then lose it instead of only being given so much at a time from the beginning.
So, I am staying aware of when we take away something and want to ensure it has narrative or thematic justification such that loss is the proper and intended experience.
For example, taking away player agency is a key part of Horror games. When done within reason in the narrative, then this is good design.

### Generic Support within the Design

Soul System is a *generic* TTRPG system.
While I have my above design goals I am attempting to implement, I also would like to maintain the system's ability to support general play within this design.
I am ultimately making the TTRPG I would like to play where I have taken inspiration from the parts of many different games that I enjoyed and adding in my own spin as I combine them together.
Also avoiding some pains or limitations I experienced in other games.
My hope is that this will be a strong and fun foundation to play out general adventures and scenarios.
Whenever it is lacking, the ideal would be to add on a module for the specific experience of play, otherwise to play a bespoke game tailored from the ground up for that experience, such as [Ten Candles](https://rpggeek.com/rpg/31186/ten-candles) or Jenga block time & tension mechanics some games use.

## Conclusion

That's the majority of my macro design goals for Soul System and the games it powers such as Small Souls.
I'll soon release the ash can version 0.1.0 of Small Souls and an overview of v0.2.0a.
