<!--

Hi there,

This is a modified version of Sax & PerfectlyCircularSeal Daggerheart Class template.

This version is a work in progress which includes a cover page, a credits page, and the configuration for the different colors of each chapter of the Daggerheart core rulebook + integration of the class theme which was the original homebrew used as base, allowing you to customize your brew and make it look like the DH rulebook as much as possible. In addition, there're various Brew Snippets to make formatting a bit easier and quicker.

Some details for using the features:

In the Brew Snippets you can find some templates for different parts of the brew, allowing you to quickly insert those parts into your brew.
- DH Homebrew Details & Information: This is what you're reading now! useful to have it available if for some reason you lost it.
- DH Front Cover: Inserts the code for the cover of your brew
- DH Credits Page: Inserts a clean credits page
- DH Tip: The Tip notes found in the DH Core Book.
- DH Footer + new page with Header Color option: Inserts the number of page and footer text in the current page you're. It also creates a new page with the markdown code for the color of headers and content of that new page.
- DH Class + Subclass pages: Adds preconfigured pages for a class with the subclasses + questions.
- DH White text footnote: Adds a footnote that uses white text instead of the standard black one (this is used on pages where you have a different background and the black text is hard to read).
- DH Adversaries Statblock: Generates a statblock using the Daggerheart Core Book format.
- DH Campaign Frame: Generates all the pages of a Campaign Frame.
- DH Domain Card Reference: Generates the list found at the appendix where you can find all the card details per domain. This can be configured to adjust the colors of each domain (domain "banners" not included).
- DH Style Editor options: Paste this in the Style Editor if you're looking to adjust the colors for chapters and homebrew classes. This is mostly for those who imported the theme using the theme properties.

I commented different parts in the Style Editor that should help to understand a bit the style code and which parts should be the ones you might want to modify.

Also, here're some tips from the original Sax & PerfectlyCircularSeal theme that also might be useful:
- The Subclass Sections need an additional class, which is either subRight or subLeft. These position the sections correctly on the page.
- Artist credit use the classes aRight or aLeft to place them right or left, and use the classes aLight to change the color to white for contrast purposes.

Credits: r/AeronDrake. Sax & PerfectlyCircularSeal for the amazing class theme I used as base to build all of this. You can find the original here: https://www.reddit.com/r/daggerheart/comments/1lh9pg8/daggerheart_homebrewery_class_template_created_by/

-------------- How to import this theme into your own brew --------------

If you want to use this theme in your brews, you can copy the Share link, then go to the Properties of your own brew, and in the Theme section paste the share link. This will apply automatically the style and import any snippets this theme have.

Note: If you import the theme this way, make sure to add the "DH Style Editor options" snippet to the Style Editor if you want to adjust or modify the colors for Chapters and Classes you're making.

Alternatively, you can create a copy of this brew and then modify that one, or copy and paste everything in the Style Editor and Snippets into a new brew.

-------------------------------------------------------------------------
-->

{{frontCover}}

# Daggertheme

{{logo}}

![CoverBanner](https://i.imgur.com/2VLgcUJ.png) {position:absolute,left:10%,bottom:130px,width:80%,z-index:1}

![Fantasy Castle](https://i.imgur.com/23HRmqv.jpeg){position:absolute,left:-50%,bottom:-15%,width:250%}

\page

{{CreditsPage}}

### Credits Page

**ORIGINAL THEME (CLASS TEMPLATE):** Sax [(Homebrewery](https://homebrewery.naturalcrit.com/user/Sax?sort=alpha&dir=asc)/[Reddit)](https://www.reddit.com/user/Sax-7777299/submitted/?sort=top) & PerfectlyCircularSeal [(Homebrewery](https://homebrewery.naturalcrit.com/user/Layoro?sort=alpha&dir=asc)/[Reddit)](https://www.reddit.com/user/The_Sad_Optimist/?sort=top)

**EXPANDED THEME:** AeronDrake [(Homebrewery](https://homebrewery.naturalcrit.com/user/draco?sort=alpha&dir=asc)/[Reddit)](https://www.reddit.com/user/AeronDrake/)

**COVER IMAGE:** Fantasy Castle by Bob Greyvenstein.

Some artwork © Grim Press, used with permission. All rights reserved.

**VERSION 1.3** (01/15/2026)

![DH SmallLogo](https://i.imgur.com/S4Dwwg0.png) {position:relative,height:1em,vertical-align:top,margin-right:0.24em} This product includes material from the Daggerheart System Reference Document 1.0, © Critical Role, LLC, under the terms of the Darrington Press Community Gaming License. 

More at [https://www.daggerheart.com](https://www.daggerheart.com)

:::

<!--
This is the big logo in case you want to use it.
-->

![DH BigLogo](https://i.imgur.com/0XZ2xIv.png) {position:relative,height:5em,margin-left:2em}

> **Tip:** You can delete the following section when you're ready to go, they're only instructions and details for using this theme template.

### Brew Details & Information
Hi there,

This is a modified version of Sax & PerfectlyCircularSeal Daggerheart Class template.

This version is a work in progress which includes a cover page, a credits page, and the configuration for the different colors of each chapter of the Daggerheart core rulebook + integration of the class theme which was the original homebrew used as base, allowing you to customize your brew and make it look like the DH rulebook as much as possible. In addition, there're various Brew Snippets to make formatting a bit easier and quicker.

**Some details for using the features:**

In the **Brew Snippets** you can find some templates for different parts of the brew, allowing you to quickly insert those parts into your brew.
- **DH Homebrew Details & Information:** This is what you're reading now! useful to have it available if for some reason you lost it.
- **DH Front Cover:** Inserts the code for the cover of your brew
- **DH Credits Page:** Inserts a clean credits page
- **DH Tip:** The Tip notes found in the DH Core Book.
- **DH Footer + new page with Header Color option:** Inserts the number of page and footer text in the current page you're. It also creates a new page with the markdown code for the color of headers and content of that new page.
- **DH Class + Subclass pages:** Adds preconfigured pages for a class with the subclasses + questions.
- **DH White text footnote:** Adds a footnote that uses white text instead of the standard black one (this is used on pages where you have a different background and the black text is hard to read).
- **DH Adversaries Statblock:** Generates a statblock using the Daggerheart Core Book format.
- **DH Campaign Frame:** Generates all the pages of a Campaign Frame.
- **DH Domain Card Reference:** Generates the list found at the appendix where you can find all the card details per domain. This can be configured to adjust the colors of each domain (domain "banners" not included).
- **DH Style Editor options:** Paste this in the Style Editor if you're looking to adjust the colors for chapters and homebrew classes. This is mostly for those who imported the theme using the theme properties.

I commented different parts in the Style Editor that should help to understand a bit the style code and which parts should be the ones you might want to modify.

Also, here're some tips from the original Sax & PerfectlyCircularSeal theme that also might be useful:
- The Subclass Sections need an additional class, which is either subRight or subLeft. These position the sections correctly on the page.
- Artist credit use the classes aRight or aLeft to place them right or left, and use the classes aLight to change the color to white for contrast purposes.

#### Importing the Theme
If you want to use this theme in your brews, you can copy the Share link, then go to the Properties of your own brew, and in the Theme section paste the share link. This will apply automatically the style and import any snippets this theme have.

> **Note:** If you import the theme this way, make sure to add the "DH Style Editor options" snippet to the Style Editor if you want to adjust or modify the colors for Chapters and Classes you're making.

Alternatively, you can create a copy of this brew and then modify that one, or copy and paste everything in the Style Editor and Snippets into a new brew.

\page
{{TableofContent}}

# Contents

{{toc,wide
- # [{{ Introduction}}{{ }}](#p4)
  - [{{ Action Rolls (H3)}}{{ 4}}](#p4)
  - [{{ OVERVIEW (H3)}}{{ 4}}](#p4)
- # [{{ Chapter One:}}{{}}](#p5)
  - [{{ Preparing for Adventure}}{{ 5}}](#p5)
  - [{{ World Overview}}{{ 5}}](#p5)
  - [{{ Core Realms}}{{ 5}}](#p5)
    - [{{ Choose your Class}}{{ 5}}](#p5)
    - [{{ Header}}{{ 6}}](#p6)
  - [{{ Homebrewer}}{{}}](#p7)
  - [{{ Homebrewer Subclasses}}{{ 7}}](#p7)
    - [{{ Hobby Game Dev}}{{ 7}}](#p7)
    - [{{ Forever GM}}{{ 8}}](#p8)
    - [{{ Background Questions}}{{ 8}}](#p8)
    - [{{ Connections}}{{ 8}}](#p8)
- # [{{ Chapter Two: Playing an Adventure}}{{}}](#p9)
  - [{{ Header}}{{ 9}}](#p9)
    - [{{ Step 1:}}{{ 9}}](#p9)
  - [{{ Header 1}}{{ 9}}](#p9)
    - [{{ Step 2:}}{{ 9}}](#p9)
  - [{{ Header 2}}{{ 9}}](#p9)
  - [{{ Header 3}}{{ 9}}](#p9)
- # [{{ Chapter Three: Running an Adventure}}{{}}](#p10)
  - [{{ Header}}{{ 10}}](#p10)
  - [{{ Header 1}}{{ 10}}](#p10)
  - [{{ Header 2}}{{ 10}}](#p10)
- # [{{ Chapter Four: Adversaries and Environments}}{{}}](#p11)
  - [{{ Header}}{{ 11}}](#p11)
  - [{{ Header 1}}{{ 11}}](#p11)
    - [{{ Primary Weapons}}{{ 11}}](#p11)
  - [{{ Header 4}}{{ 11}}](#p11)
  - [{{ Tier 4 Adversaries (Levels 8-10)}}{{ 12}}](#p12)
  - [{{ Arch-Necromancer}}{{ 12}}](#p12)
    - [{{ Tier 4 Leader}}{{ 12}}](#p12)
  - [{{ Fallen Shock Troop}}{{ 12}}](#p12)
    - [{{ Tier 4 Minion}}{{ 12}}](#p12)
  - [{{ Fallen Sorcerer}}{{ 12}}](#p12)
    - [{{ Tier 4 Support}}{{ 12}}](#p12)
  - [{{ Ambushed}}{{ 12}}](#p12)
    - [{{ Tier 1 Event}}{{ 12}}](#p12)
- # [{{ A Dagger to the Heart}}{{}}](#p13)
  - [{{ The Pitch}}{{ 13}}](#p13)
  - [{{ Tone & Feel}}{{ 13}}](#p13)
  - [{{ Themes}}{{ 13}}](#p13)
  - [{{ Touchstones}}{{ 13}}](#p13)
  - [{{ A Dagger to the Heart}}{{ 14}}](#p14)
  - [{{ Overview}}{{ 14}}](#p14)
    - [{{ A Dagger to the Heart}}{{ 15}}](#p15)
  - [{{ Communities}}{{ 15}}](#p15)
  - [{{ Ancestries}}{{ 15}}](#p15)
  - [{{ Classes}}{{ 15}}](#p15)
    - [{{ A Dagger to the Heart}}{{ 16}}](#p16)
  - [{{ Player Principles}}{{ 16}}](#p16)
  - [{{ GM Principles}}{{ 16}}](#p16)
    - [{{ A Dagger to the Heart}}{{ 17}}](#p17)
  - [{{ Distinctions}}{{ 17}}](#p17)
    - [{{ A Dagger to the Heart}}{{ 18}}](#p18)
  - [{{ The Inciting Incident}}{{ 18}}](#p18)
  - [{{ Campaign Mechanics}}{{ 18}}](#p18)
    - [{{ A Dagger to the Heart Starting Equipment}}{{ 18}}](#p18)
    - [{{ Primary Weapons}}{{ 18}}](#p18)
  - [{{ Session Zero Questions}}{{ 18}}](#p18)
- # [{{ Appendix}}{{}}](#p19)
  - [{{ Domain Card Reference}}{{ 19}}](#p19)
  - [{{ Arcana Domain}}{{ 19}}](#p19)
}}


\page

{{Intro}}

<!--

By changing the {{Intro}} will adjust the header, notes and side rectangle color will change to match the chapter you define. Each chapter have their own colors. You can adjust them or add new in the Style Editor if required. If you don't want to have the rectangle, remove the tab part (following the Daggerheart Core Book, introduction doesn't have a side rectangle).

- {{Intro}} Introduction (Yellow)   : #967b2f
- {{Ch1}} Chapter 1 (Green)         : #536537
- {{Ch2}} Chapter 2 (Orange)        : #b8551b
- {{Ch3}} Chapter 3 (Purple)        : #763a87
- {{Ch4}} Chapter 4 (Red)           : #ad2423
- {{Ch5}} Chapter 5 (Cyan)          : #317080
- {{app}} Appendix (Dark Gray)      : #231f20

- {{ClassBG}}{{tab}} : Adds the Class background color to the page + the side rectangle (green). There're additional options for this. More details in the Class snippet and the style editor.

-->

# Introduction
## Welcome to Daggerheart
A collaborative fantasy tabletop roleplaying game of incredible magic and heroic, heartfelt adventure.

## What is Daggerheart?
Daggerheart is a tabletop roleplaying game for one Game Master (“GM”) and 2-5 players. Each game session lasts about 2-4 hours, and Daggerheart can be played as a one-shot or a multi-session campaign of any length.

During a session of Daggerheart the GM describes situations, narrates events, and controls any adversaries or obstacles that the Player Characters (“PCs”) encounter. The players, in turn, roleplay their PCs’ reactions to the scenario presented by the GM. If the outcome of a player’s action depends on fate or fortune, the GM calls for an action roll.

When a player makes an action roll, they utilize Duality Dice—two differently colored 12-sided dice (“d12s”) representing Hope and Fear. The Duality Dice are rolled, relevant modifiers are added to the results, and the total is compared to a Difficulty set by the GM. If the total meets or beats the Difficulty, the player succeeds. If it’s lower, they fail. In addition, the situation changes based on which Duality Die rolls higher, either giving the player helpful Hope tokens or generating terrifying Fear tokens for the GM.

## The Golden Rule
The most important rule of Daggerheart is to make the game your own. The rules included in this SRD are designed to help you enjoy the experience at the table, but everyone has a different approach to interpreting rules and telling stories. The rules should never get in the way of the story you want to tell, the characters you want to play, or the adventures you want to have. As long as your group agrees, everything can be adjusted to fit your play style. If there’s a rule you’d rather ignore or modify, feel free to implement any change with your table’s consent.

## Rulings over rules
While playing Daggerheart, the GM and players should always prioritize rulings over rules. This SRD offers answers for many questions your table may have about the game, but it won’t answer all of them. When you’re in doubt about how a rule applies, the GM should make a ruling that aligns with the narrative.

For example, Daggerheart has a weapon called a grappler that lets you pull a target close to you. If you try to use it to pull an entire castle, the weapon text doesn’t forbid you from doing that—but it doesn’t make sense within the narrative. Instead, the GM might rule that you pull a few bricks out, or pull yourself toward the wall instead.

Similarly, if your character does something that would logically result in immediate death—such as diving into an active volcano without protection—you might not get to make one of Daggerheart’s death moves, which normally give you control of your character’s fate in their final moments. This kind of consequence should be made clear before the action is completed, and it should always follow the logic of the world.

As a narrative-focused game, Daggerheart is not a place where technical, out-of-context interpretations of the rules are encouraged. Everything should flow back to the fiction, and the GM has the authority and responsibility to make rulings about how rules are applied to underscore that fiction.

## Making Moves & Taking Action
Any time a character does something to advance the story, such as speaking with another character, interacting with the environment, making an attack, casting a spell, or using a class feature, they are making a move.

### Action Rolls (H3)
Any move where success would be trivial or failure would be boring automatically succeeds, but any move that’s difficult to accomplish or risky to attempt triggers an **action roll**.

### OVERVIEW (H3)
All action rolls require a pair of d12s called Duality Dice. These are two visually distinct twelve-sided dice, with one die representing Hope and the other representing Fear.

To make an action roll, you roll the Duality Dice, sum the results, apply any relevant modifiers, and compare the total to a Difficulty number to determine the outcome:

- **Success with Hope:** If your total meets or beats the Difficulty AND your Hope Die shows a higher result than your Fear Die, you rolled a “Success with Hope.” You succeed and gain a Hope.
- **Success with Fear:** If your total meets or beats the Difficulty AND your Fear Die shows a higher result than your Hope Die, you rolled a “Success with Fear.” You succeed with a cost or complication, but the GM gains a Fear.
- **Failure with Hope:** If your total is less than the Difficulty AND your Hope Die shows a higher result than your Fear Die, you rolled a “Failure with Hope.” You fail with a minor consequence and gain a Hope, then the spotlight swings to the GM.
- **Failure with Fear:** If your total is less than the Difficulty AND your Fear Die shows a higher result than your Hope Die, you rolled a “Failure with Fear.” You fail with a major consequence and the GM gains a Fear, then the spotlight swings to the GM.
- **Critical Success:** If the Duality Dice show matching results, you rolled a “Critical Success” (“Crit”). You automatically succeed with a bonus, gain a Hope, and clear a Stress. If this was an attack roll, you deal critical damage.

After resolving the action roll, the table works together to weave the outcome into the narrative and play continues.

{{footnote Introduction}}
{{pageNumber,auto}}

\page

{{Ch1,tab}}

# Chapter One:
## Preparing for Adventure
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ultricies faucibus orci. Nulla tortor arcu, condimentum ut tellus blandit, congue vulputate nisl. Nunc viverra sem bibendum enim tincidunt efficitur. Duis eget volutpat nulla, a imperdiet magna. Ut euismod, neque eu auctor porta, nibh nunc ultricies neque, in bibendum est velit non mi. Ut molestie nisl eget venenatis consequat. Pellentesque iaculis, nulla et cursus tempor, sapien nisi interdum ante, ac consectetur purus mi non neque. Praesent quis dui eget tellus aliquam commodo. Maecenas non vestibulum ante, id laoreet nulla. Nunc dapibus elit quis consectetur feugiat.

## World Overview
In suscipit arcu augue, non porttitor sem molestie maximus. Proin semper efficitur nulla vel hendrerit. Fusce eget convallis nibh, vitae porttitor mauris. Suspendisse ornare aliquet dui ac varius. Morbi egestas, erat vitae viverra egestas, erat dolor mattis massa, sit amet luctus justo mauris in velit. Etiam lobortis viverra tortor, a viverra est hendrerit sit amet. Donec mollis vel metus iaculis finibus. Mauris efficitur eleifend dolor vel cursus. Sed vehicula dapibus augue, eget varius nunc consectetur nec. Donec gravida purus libero.

{{note
##### YOUR VERY COOL HOUSE RULE
In the DH Core Book, notes are used for optional rules and as a sumary of steps for something (like in the section "Flow of the game" in Chapter Two)
}}

## Core Realms
Nunc a mauris a dolor mattis fringilla. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas mattis erat nisi, eget maximus augue lacinia sit amet. Curabitur bibendum lorem vel neque imperdiet, eget vehicula magna sodales. Pellentesque efficitur nisi sit amet neque eleifend, vel rhoncus erat faucibus. Praesent semper eu enim eget vulputate. Vestibulum posuere erat quis nunc pretium venenatis. Donec posuere consectetur orci quis luctus. Maecenas nulla eros, pellentesque fermentum malesuada et, consequat malesuada nunc. Ut hendrerit risus arcu, et pretium felis pharetra ac. Nunc varius dolor vitae ligula pellentesque, vel laoreet massa interdum. Cras convallis tempor risus vitae malesuada. Duis ornare ornare lorem. In sagittis bibendum ipsum non hendrerit. Suspendisse vitae ante augue.

### Step 1:
## Choose your Class
Vestibulum dictum lorem non diam fringilla venenatis. Aliquam erat volutpat. Aenean quis lectus orci. Vivamus commodo ac lorem at tristique. In ante leo, pretium ut nisi sed, sagittis sollicitudin erat. Vestibulum eleifend ex ac scelerisque suscipit. Nullam nulla felis, placerat a ultrices vel, scelerisque quis velit. Fusce sollicitudin eu lacus eget interdum. Fusce tempor dignissim ipsum. Aenean purus nunc, cursus eu velit quis, vehicula condimentum massa. Etiam ac nisi nisi. Mauris a aliquam mauris, sed consequat sem. Etiam eu euismod odio, eget fermentum mi. Ut feugiat tristique turpis, ut facilisis quam rutrum at.

#### Header 4
Aenean rhoncus commodo neque, ut viverra arcu ullamcorper eu. Interdum et malesuada fames ac ante ipsum primis in faucibus. Cras posuere neque erat, nec eleifend metus luctus sed. Etiam massa mi, aliquet ut pulvinar eget, lacinia a risus. Nullam dapibus efficitur elit, in dapibus eros. Sed cursus vehicula urna a tincidunt. Morbi arcu libero, commodo nec elementum et, iaculis id eros.

##### Header 5
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ultricies faucibus orci. Nulla tortor arcu, condimentum ut tellus blandit, congue vulputate nisl. Nunc viverra sem bibendum enim tincidunt efficitur. Duis eget volutpat nulla, a imperdiet magna. Ut euismod, neque eu auctor porta, nibh nunc ultricies neque, in bibendum est velit non mi. Ut molestie nisl eget venenatis consequat. Pellentesque iaculis, nulla et cursus tempor, sapien nisi interdum ante, ac consectetur purus mi non neque. Praesent quis dui eget tellus aliquam commodo. Maecenas non vestibulum ante, id laoreet nulla. Nunc dapibus elit quis consectetur feugiat.

In suscipit arcu augue, non porttitor sem molestie maximus. Proin semper efficitur nulla vel hendrerit. Fusce eget convallis nibh, vitae porttitor mauris. Suspendisse ornare aliquet dui ac varius. Morbi egestas, erat vitae viverra egestas, erat dolor mattis massa, sit amet luctus justo mauris in velit. Etiam lobortis viverra tortor, a viverra est hendrerit sit amet. Donec mollis vel metus iaculis finibus. Mauris efficitur eleifend dolor vel cursus. Sed vehicula dapibus augue, eget varius nunc consectetur nec. Donec gravida purus libero.

{{descriptive
**Example:** In the DH Core Book, this is used for presenting examples, but it can be used for other things too!
}}

###### Header 6
Nunc a mauris a dolor mattis fringilla. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Maecenas mattis erat nisi, eget maximus augue lacinia sit amet. Curabitur bibendum lorem vel neque imperdiet, eget vehicula magna sodales. Pellentesque efficitur nisi sit amet neque eleifend, vel rhoncus erat faucibus. Praesent semper eu enim eget vulputate. Vestibulum posuere erat quis nunc pretium venenatis. Donec posuere consectetur orci quis luctus. Maecenas nulla eros, pellentesque fermentum malesuada et, consequat malesuada nunc. Ut hendrerit risus arcu, et pretium felis pharetra ac. Nunc varius dolor vitae ligula pellentesque, vel laoreet massa interdum. Cras convallis tempor risus vitae malesuada. Duis ornare ornare lorem. In sagittis bibendum ipsum non hendrerit. Suspendisse vitae ante augue.

{{footnote Chapter 1: Preparing for Adventure}}
{{pageNumber,auto}}

\page

{{Ch1,tab}}

## Header
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam sit amet ex vitae sapien vestibulum tristique nec quis nisl. Curabitur tincidunt finibus sapien at feugiat. Ut at urna hendrerit lectus sodales pharetra. Aenean aliquet sagittis metus vel porttitor. Vivamus ullamcorper egestas placerat. Vivamus ac dignissim nisi. Vivamus sagittis mattis ex, quis placerat nunc laoreet eget. Morbi at sollicitudin leo. Donec vitae dapibus massa, id aliquam sem. Integer faucibus fermentum erat nec iaculis. In porttitor augue diam. Proin pharetra, ligula non pellentesque porta, nibh lorem gravida mauris, ut porta enim metus et dolor. Nam ut tortor maximus, ullamcorper magna quis, dictum sem. Pellentesque rutrum consequat eleifend. Curabitur non luctus augue, in semper purus.

#### Header
Nullam commodo porttitor urna vitae congue. Praesent magna eros, euismod et nisi at, viverra ullamcorper leo. Interdum et malesuada fames ac ante ipsum primis in faucibus. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Mauris aliquam semper diam ac euismod. Etiam condimentum commodo magna, consequat posuere dolor fringilla quis. Nam diam mauris, dapibus vel mauris at, faucibus facilisis felis. Donec luctus, orci et fringilla pharetra, dui lectus mollis sapien, quis sodales orci ante vel diam. Nunc suscipit nulla in elementum blandit. Sed imperdiet lacus vel lacus efficitur semper tincidunt eget risus. Maecenas laoreet arcu velit. Maecenas dictum ipsum sit amet condimentum fermentum. Mauris gravida molestie urna, vel vestibulum arcu cursus sit amet. Etiam bibendum tortor sem, non scelerisque nibh egestas nec. Mauris nec ligula cursus, laoreet mauris rhoncus, aliquam ligula. Proin convallis, augue in hendrerit accumsan, felis lacus pellentesque purus, non elementum sem leo at augue.

#### Header
Ut a condimentum ex, nec dictum justo. In accumsan, lectus eu condimentum semper, nisl quam suscipit dolor, eget tincidunt massa odio suscipit enim. Donec sodales nunc at ante bibendum, at consequat purus porttitor. Sed dui tellus, efficitur in finibus sit amet, consectetur sit amet ipsum. Donec a felis ut tortor feugiat tincidunt vitae ac purus. Curabitur non sapien eget ante iaculis ornare ut at magna. Aliquam vitae arcu feugiat, maximus dui sed, venenatis purus. Sed feugiat sollicitudin suscipit. Nullam mattis, metus vel tincidunt feugiat, purus tellus iaculis ante, a interdum quam sapien non lacus. Etiam hendrerit nisi sed felis faucibus tristique. Aenean scelerisque gravida est vel sollicitudin. Vestibulum efficitur sem vel massa hendrerit, id aliquam dolor rhoncus. Phasellus vitae tincidunt odio.

| Clank   | Firbolg   | Human    |
|:--------|:----------|:---------|
| Drakona | Fungril   | Infernis |
| Dwarf   | Galapa    | Katari   |
| Elf     | Giant     | Orc      |
| Faerie  | Goblin    | Ribbet   |
| Faun    | Halfling  | Simiah   |

#### Header
Maecenas ac arcu varius, condimentum eros vitae, porta erat. Praesent vel dui sit amet metus efficitur hendrerit a vitae nulla. Sed non eleifend lectus. Duis eget orci in nibh efficitur condimentum aliquam eu mi. Morbi consectetur lectus sit amet nisl molestie placerat. Maecenas aliquet scelerisque nunc, quis semper nibh semper non. Nulla rhoncus tincidunt turpis, sit amet eleifend metus consectetur quis. Sed vel nibh suscipit, ultrices eros eget, tincidunt magna. Nam mi ipsum, tempor in nisi quis, pellentesque finibus neque. Proin in sodales sem. Mauris non nulla tincidunt, iaculis nunc vitae, molestie leo.

> **Tip:** Remember to hydrate.

#### Header
Praesent ac felis vel lacus ornare porta. Fusce quis vehicula leo, nec lobortis risus. Integer in accumsan lacus, ac finibus risus. Etiam sit amet scelerisque enim. Maecenas condimentum suscipit fermentum. Fusce euismod purus non magna pretium, id bibendum enim dapibus. Aenean vulputate pellentesque urna ut maximus. Nullam quis iaculis arcu. Nulla facilisi. Donec molestie orci eu molestie lacinia.

{{DHTable,wide
### Primary Weapons
*The following primary weapons are also available in this campaign.*
| **Name**            | **Trait** | **Range** | **Damage** | **Burden**  | **Feature**                                                |
|:--------------------|:----------|:----------|:-----------|:------12%------|:---------------------------------------------------------|
|  **Curved Sword**   | Finesse   | Melee     |    d6 phy  | One-Handed  | **Mooncut:** Curved sword goes swoosh. Spend 1 Hope to gain advantage on an attack roll.  |
|  **Battle Axe**     | Strength  | Melee     |    d8 phy  | Two-Handed  | **Heartbreaker:** An axe strike to go deep to the heart.  |
|  **Plasma Rifle**   | Agility   | Far       |    d10 phy | Two-Handed  | **Charged Blast:** Careful with overheating.  |
|  **Composite Bow**  | Agility   | Far       |    d8 phy  | Two-Handed  | **Long Shot:** Just aim to the target far far away.  |
|  **Dual Dagger**    | Finesse   | Melee     |    d6 phy  | One-Handed  | **Heart Strike:** What's better than one dagger to the heart? a dual dagger to the heart.  |
}}


{{footnote, Chapter 1: Preparing for Adventure}}
{{pageNumber,auto}}

\page

{{ClassBG}}{{tab}}

<!--
Change the BG color by replacing the {{ClassBG}} to one of the following. These are based on the different DH classes colors in the book. If you want to modify these or add your own, you can do it on the Style Editor.

  - {{ClassBG}} : Homebrew color (Chocolate Dark Brown)
  - {{ClassBG1}}  : Bard (Dark Brown)
  - {{ClassBG2}}  : Druid & Ranger (Dark green)
  - {{ClassBG3}}  : Guardian (Gray + Dark blue gradient)
  - {{ClassBG4}}  : Rogue (Dark and Cool)
  - {{ClassBG5}}  : Seraph (Dark Brown with slight redish tint)
  - {{ClassBG6}}  : Sorcerer (Purple)
  - {{ClassBG7}}  : Warrior (Dark Red)
  - {{ClassBG8}}  : Wizard (Deep Sea Blue)
  
If you want to add an image as background (like the Rogue class from the Core Book), you can add it after the class "}}". There, in the image curly brackets, use the following: ClassBG-img,bottom:-50px,height:60%,z-index:-1,opacity:0.8. Change the bottom and height to fit your image, and adjust the opacity between 0 to 1 if you want to add or remove transparency to fit the background.
  
-->

{{Class

# Homebrewer
They say every story starts with a spark, but this one begins with a sideways glance, a broken compass, and a song no one remembers how to hum. What follows is entirely up to you, though this space right here is where the real introduction goes. The kind with drama, flavor, and a proper name drop. Copy your class intro here, let it strut, brood, or swagger as needed. Until then, consider this your official invitation to pretend something amazing was just said.
:
#### Domains
Splendor and Grace
:
#### Starting Evasion
10
:
#### Starting Hit Points
5
:
#### Class Items
An idea of something that doesn't exist yet or a nonsensical drawing on the back of an expired gift card
:
#### Homebrewer's Hope Feature
***Think:*** **Spend 3 Hope** to write something that Matt Mercer himself would be proud of. 
:
#### Class Feature
##### Brew A Home
Once per long rest, you can put all of your creative energy into a piece of text that someone at your table might find cool enough to try out.
:
> **Tip:** Remember to hydrate.

}}

![Fantasy Castle](https://i.imgur.com/23HRmqv.jpeg){ClassBG-img,bottom:-50px,height:60%,z-index:-1,opacity:0.8}


\column

{{subClass,subRight

## Homebrewer Subclasses
Choose either the Hobby Game Dev or Forever GM subclass.
:
### Hobby Game Dev
Play the Hobby Game Dev if you want to homebrew for internet points and play a little too sparsely in real life.
:
#### Spellcast Trait
Knowledge
:
#### Foundation Features
***Just For Fun:*** When you choose to start a new homebrew again, think to yourself if this will be for fun or feel like more work.
:
***Font of Creativity:*** When you lay in bed trying to sleep and you have something important in the morning, you gain an additional amount of cool ideas equal to your Knowledge.
:
#### Specialization Feature
***Invoke Feedback:*** Whenever an adversary on Reddit comments something hurtful about your homebrew, you can try to read between the lines and turn it into something useful for your next homebrew.
:
#### Mastery Feature
***Feel Revered:*** Once per session, when you post your homebrew online, it gains an unexpected amount of likes, granting you the benefits of happiness for 10 minutes.
:

}}

{{footnote,white Chapter 1: Character Creation}}
{{pageNumber,auto}}

\page

{{tab}}

{{subClass,subLeft

### Forever GM
Play the Forever GM if you want to channel the anguish of not being able to play your own brews yourself.
:
#### Spellcast Trait
Presence
:
#### Foundation Features
***God Amongst Men:*** You carry three handcrafted relics, each housing a force that empowers you. You can invoke each force once per session:

- ***NPC Relic:*** Choose an unnamed NPC within Close range of a player. They immediately gain a silly name and the unforeseen protection and emotional investment of all players until it either dies or the campaign ends.
- ***Rules Relic:*** When a player corrects you on a rule, you can overturn their correction by implementing a new rule on the spot and forego any damage to your ego.
- ***Shushing Relic:*** Make a player within Melee range temporarily *Shushed*. While *Shushed*, they have disadvantage on anything they try to say against your plans for the game.
:
#### Specialization Feature
***GM's Blessing:*** When a player does an exceptional job at playing by your rules, you can bestow them with the highest of blessings. While this player has this blessing, it is immune to any plot damage to their character.
:
#### Mastery Feature
***Not My First Rodeo:*** Your connections to the spirits of GMs across the history of the world and your subreddit subscriptions have granted you the ability to halve the time you spend to prepare for a session.
:

}}

\column

{{questionSection
{{block

### Background Questions
Answer any of the following background questions. You can also create your own questions.
- What moment made you fall in love with game design?
- You once poured your heart into a project no one ever used. What was it, and how did it change you?
- What unplaytested mechanic are you irrationally proud of?
:
### Connections
Ask your fellow players one of the following questions for their character to answer, or create your own questions.
- What part of my imagination do you admire the most?
- I once asked you to try something I made. What happened, and how did it affect our bond?
- What do you always ask me to homebrew, even though we both know it’s going to break the game?
}}
}}

{{footnote Chapter 1: Character Creation}}
{{pageNumber,auto}}

\page

{{Ch2,tab}}

# Chapter Two:
## Playing an Adventure
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ultricies faucibus orci. Nulla tortor arcu, condimentum ut tellus blandit, congue vulputate nisl. Nunc viverra sem bibendum enim tincidunt efficitur. Duis eget volutpat nulla, a imperdiet magna. Ut euismod, neque eu auctor porta, nibh nunc ultricies neque, in bibendum est velit non mi. Ut molestie nisl eget venenatis consequat. Pellentesque iaculis, nulla et cursus tempor, sapien nisi interdum ante, ac consectetur purus mi non neque. Praesent quis dui eget tellus aliquam commodo. Maecenas non vestibulum ante, id laoreet nulla. Nunc dapibus elit quis consectetur feugiat.

## Header
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam sit amet ex vitae sapien vestibulum tristique nec quis nisl. Curabitur tincidunt finibus sapien at feugiat. Ut at urna hendrerit lectus sodales pharetra. Aenean aliquet sagittis metus vel porttitor. Vivamus ullamcorper egestas placerat. Vivamus ac dignissim nisi. Vivamus sagittis mattis ex, quis placerat nunc laoreet eget. Morbi at sollicitudin leo. Donec vitae dapibus massa, id aliquam sem. Integer faucibus fermentum erat nec iaculis. In porttitor augue diam. Proin pharetra, ligula non pellentesque porta, nibh lorem gravida mauris, ut porta enim metus et dolor. Nam ut tortor maximus, ullamcorper magna quis, dictum sem. Pellentesque rutrum consequat eleifend. Curabitur non luctus augue, in semper purus.

### Step 1:
## Header 1
Nullam commodo porttitor urna vitae congue. Praesent magna eros, euismod et nisi at, viverra ullamcorper leo. Interdum et malesuada fames ac ante ipsum primis in faucibus. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Mauris aliquam semper diam ac euismod. Etiam condimentum commodo magna, consequat posuere dolor fringilla quis. Nam diam mauris, dapibus vel mauris at, faucibus facilisis felis. Donec luctus, orci et fringilla pharetra, dui lectus mollis sapien, quis sodales orci ante vel diam. Nunc suscipit nulla in elementum blandit. Sed imperdiet lacus vel lacus efficitur semper tincidunt eget risus. Maecenas laoreet arcu velit. Maecenas dictum ipsum sit amet condimentum fermentum. Mauris gravida molestie urna, vel vestibulum arcu cursus sit amet. Etiam bibendum tortor sem, non scelerisque nibh egestas nec. Mauris nec ligula cursus, laoreet mauris rhoncus, aliquam ligula. Proin convallis, augue in hendrerit accumsan, felis lacus pellentesque purus, non elementum sem leo at augue.

### Step 2:
## Header 2
Ut a condimentum ex, nec dictum justo. In accumsan, lectus eu condimentum semper, nisl quam suscipit dolor, eget tincidunt massa odio suscipit enim. Donec sodales nunc at ante bibendum, at consequat purus porttitor. Sed dui tellus, efficitur in finibus sit amet, consectetur sit amet ipsum. Donec a felis ut tortor feugiat tincidunt vitae ac purus. Curabitur non sapien eget ante iaculis ornare ut at magna. Aliquam vitae arcu feugiat, maximus dui sed, venenatis purus. Sed feugiat sollicitudin suscipit. Nullam mattis, metus vel tincidunt feugiat, purus tellus iaculis ante, a interdum quam sapien non lacus. Etiam hendrerit nisi sed felis faucibus tristique. Aenean scelerisque gravida est vel sollicitudin. Vestibulum efficitur sem vel massa hendrerit, id aliquam dolor rhoncus. Phasellus vitae tincidunt odio.

| Attack | Easy     | Bonus |
|:-------|:---------|:------|
| Defend | Medium   | +2    |
| Cover  | Easy     | +2    |
| Run    | Easy     | +2    |
| Aid    | Medium   | +2    |
| Hide   | Hard     | +3    |

## Header 3
#### Header
Maecenas ac arcu varius, condimentum eros vitae, porta erat. Praesent vel dui sit amet metus efficitur hendrerit a vitae nulla. Sed non eleifend lectus. Duis eget orci in nibh efficitur condimentum aliquam eu mi. Morbi consectetur lectus sit amet nisl molestie placerat. Maecenas aliquet scelerisque nunc, quis semper nibh semper non. Nulla rhoncus tincidunt turpis, sit amet eleifend metus consectetur quis. Sed vel nibh suscipit, ultrices eros eget, tincidunt magna. Nam mi ipsum, tempor in nisi quis, pellentesque finibus neque. Proin in sodales sem. Mauris non nulla tincidunt, iaculis nunc vitae, molestie leo.

###### Attack
Lorem ipsum dolor sit amet, consectetur adipiscing elit.

###### Defend
Nullam sit amet ex vitae sapien vestibulum tristique nec quis nisl. Curabitur tincidunt finibus sapien at feugiat. Ut at urna hendrerit lectus sodales pharetra. Aenean aliquet sagittis metus vel porttitor. Vivamus ullamcorper egestas placerat. Vivamus ac dignissim nisi. Vivamus sagittis mattis ex, quis placerat nunc laoreet eget. Morbi at sollicitudin leo. Donec vitae dapibus massa, id aliquam sem.

#### Header
Praesent ac felis vel lacus ornare porta. Fusce quis vehicula leo, nec lobortis risus. Integer in accumsan lacus, ac finibus risus. Etiam sit amet scelerisque enim. Maecenas condimentum suscipit fermentum. Fusce euismod purus non magna pretium, id bibendum enim dapibus. Aenean vulputate pellentesque urna ut maximus. Nullam quis iaculis arcu. Nulla facilisi. Donec molestie orci eu molestie lacinia.

{{footnote Chapter 2: Playing an Adventure}}
{{pageNumber,auto}}

\page

{{Ch3,tab}}

# Chapter Three:
## Running an Adventure
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ultricies faucibus orci. Nulla tortor arcu, condimentum ut tellus blandit, congue vulputate nisl. Nunc viverra sem bibendum enim tincidunt efficitur. Duis eget volutpat nulla, a imperdiet magna. Ut euismod, neque eu auctor porta, nibh nunc ultricies neque, in bibendum est velit non mi. Ut molestie nisl eget venenatis consequat. Pellentesque iaculis, nulla et cursus tempor, sapien nisi interdum ante, ac consectetur purus mi non neque. Praesent quis dui eget tellus aliquam commodo. Maecenas non vestibulum ante, id laoreet nulla. Nunc dapibus elit quis consectetur feugiat.

## Header
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam sit amet ex vitae sapien vestibulum tristique nec quis nisl. Curabitur tincidunt finibus sapien at feugiat. Ut at urna hendrerit lectus sodales pharetra. Aenean aliquet sagittis metus vel porttitor. Vivamus ullamcorper egestas placerat. Vivamus ac dignissim nisi. Vivamus sagittis mattis ex, quis placerat nunc laoreet eget. Morbi at sollicitudin leo. Donec vitae dapibus massa, id aliquam sem. Integer faucibus fermentum erat nec iaculis. In porttitor augue diam. Proin pharetra, ligula non pellentesque porta, nibh lorem gravida mauris, ut porta enim metus et dolor. Nam ut tortor maximus, ullamcorper magna quis, dictum sem. Pellentesque rutrum consequat eleifend. Curabitur non luctus augue, in semper purus.

## Header 1
Nullam commodo porttitor urna vitae congue. Praesent magna eros, euismod et nisi at, viverra ullamcorper leo. Interdum et malesuada fames ac ante ipsum primis in faucibus. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Mauris aliquam semper diam ac euismod. Etiam condimentum commodo magna, consequat posuere dolor fringilla quis. Nam diam mauris, dapibus vel mauris at, faucibus facilisis felis. Donec luctus, orci et fringilla pharetra, dui lectus mollis sapien, quis sodales orci ante vel diam. Nunc suscipit nulla in elementum blandit. Sed imperdiet lacus vel lacus efficitur semper tincidunt eget risus. Maecenas laoreet arcu velit. Maecenas dictum ipsum sit amet condimentum fermentum. Mauris gravida molestie urna, vel vestibulum arcu cursus sit amet. Etiam bibendum tortor sem, non scelerisque nibh egestas nec. Mauris nec ligula cursus, laoreet mauris rhoncus, aliquam ligula. Proin convallis, augue in hendrerit accumsan, felis lacus pellentesque purus, non elementum sem leo at augue.

{{note
##### YOUR VERY COOL HOUSE RULE
In the DH Core Book, notes are used for optional rules and as a sumary of steps for something (like in the section "Flow of the game" in Chapter Two)
}}

## Header 2
Ut a condimentum ex, nec dictum justo. In accumsan, lectus eu condimentum semper, nisl quam suscipit dolor, eget tincidunt massa odio suscipit enim. Donec sodales nunc at ante bibendum, at consequat purus porttitor. Sed dui tellus, efficitur in finibus sit amet, consectetur sit amet ipsum. Donec a felis ut tortor feugiat tincidunt vitae ac purus. Curabitur non sapien eget ante iaculis ornare ut at magna. Aliquam vitae arcu feugiat, maximus dui sed, venenatis purus. Sed feugiat sollicitudin suscipit. Nullam mattis, metus vel tincidunt feugiat, purus tellus iaculis ante, a interdum quam sapien non lacus. Etiam hendrerit nisi sed felis faucibus tristique. Aenean scelerisque gravida est vel sollicitudin. Vestibulum efficitur sem vel massa hendrerit, id aliquam dolor rhoncus. Phasellus vitae tincidunt odio.

#### Header
Maecenas ac arcu varius, condimentum eros vitae, porta erat. Praesent vel dui sit amet metus efficitur hendrerit a vitae nulla. Sed non eleifend lectus. Duis eget orci in nibh efficitur condimentum aliquam eu mi. Morbi consectetur lectus sit amet nisl molestie placerat. Maecenas aliquet scelerisque nunc, quis semper nibh semper non. Nulla rhoncus tincidunt turpis, sit amet eleifend metus consectetur quis. Sed vel nibh suscipit, ultrices eros eget, tincidunt magna. Nam mi ipsum, tempor in nisi quis, pellentesque finibus neque. Proin in sodales sem. Mauris non nulla tincidunt, iaculis nunc vitae, molestie leo.

| Attack | Easy     | Bonus |
|:-------|:---------|:------|
| Defend | Medium   | +2    |
| Cover  | Easy     | +2    |
| Run    | Easy     | +2    |
| Aid    | Medium   | +2    |
| Hide   | Hard     | +3    |

{{descriptive
##### Time to Drop Knowledge
Use descriptive boxes to highlight text that should be read aloud.

**Tables and lists** both work within a descriptive box.
}}

#### Header
Praesent ac felis vel lacus ornare porta. Fusce quis vehicula leo, nec lobortis risus. Integer in accumsan lacus, ac finibus risus. Etiam sit amet scelerisque enim. Maecenas condimentum suscipit fermentum. Fusce euismod purus non magna pretium, id bibendum enim dapibus. Aenean vulputate pellentesque urna ut maximus. Nullam quis iaculis arcu. Nulla facilisi. Donec molestie orci eu molestie lacinia.

{{DHTable
| **Scene**            | **Example**  |
|:---------------------|:-------------|
|  Overgrown Dungeon   | Goblin Cave  |
|  Forgotten Dungeon   | Undead Crypt |
|  Urban               | Town Center  |
}}

{{footnote Chapter 3: Running an Adventure}}
{{pageNumber,auto}}

\page

{{Ch4,tab}}

# Chapter Four:
## Adversaries and Environments
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ultricies faucibus orci. Nulla tortor arcu, condimentum ut tellus blandit, congue vulputate nisl.

## Header
Nunc viverra sem bibendum enim tincidunt efficitur. Duis eget volutpat nulla, a imperdiet magna. Ut euismod, neque eu auctor porta, nibh nunc ultricies neque, in bibendum est velit non mi. Ut molestie nisl eget venenatis consequat. Pellentesque iaculis, nulla et cursus tempor, sapien nisi interdum ante, ac consectetur purus mi non neque. Praesent quis dui eget tellus aliquam commodo. Maecenas non vestibulum ante, id laoreet nulla. Nunc dapibus elit quis consectetur feugiat.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam sit amet ex vitae sapien vestibulum tristique nec quis nisl. Curabitur tincidunt finibus sapien at feugiat. Ut at urna hendrerit lectus sodales pharetra. Aenean aliquet sagittis metus vel porttitor. Vivamus ullamcorper egestas placerat. Vivamus ac dignissim nisi. Vivamus sagittis mattis ex, quis placerat nunc laoreet eget. Morbi at sollicitudin leo. Donec vitae dapibus massa, id aliquam sem. Integer faucibus fermentum erat nec iaculis. In porttitor augue diam. Proin pharetra, ligula non pellentesque porta, nibh lorem gravida mauris, ut porta enim metus et dolor. Nam ut tortor maximus, ullamcorper magna quis, dictum sem. Pellentesque rutrum consequat eleifend. Curabitur non luctus augue, in semper purus.

## Header 1
Nullam commodo porttitor urna vitae congue. Praesent magna eros, euismod et nisi at, viverra ullamcorper leo. Interdum et malesuada fames ac ante ipsum primis in faucibus. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Mauris aliquam semper diam ac euismod. Etiam condimentum commodo magna, consequat posuere dolor fringilla quis. Nam diam mauris, dapibus vel mauris at, faucibus facilisis felis. Donec luctus, orci et fringilla pharetra, dui lectus mollis sapien, quis sodales orci ante vel diam. Nunc suscipit nulla in elementum blandit. Sed imperdiet lacus vel lacus efficitur semper tincidunt eget risus. Maecenas laoreet arcu velit. Maecenas dictum ipsum sit amet condimentum fermentum. Mauris gravida molestie urna, vel vestibulum arcu cursus sit amet. Etiam bibendum tortor sem, non scelerisque nibh egestas nec. Mauris nec ligula cursus, laoreet mauris rhoncus, aliquam ligula. Proin convallis, augue in hendrerit accumsan, felis lacus pellentesque purus, non elementum sem leo at augue.

{{DHTable,wide
### Primary Weapons
*The following primary weapons are also available in this campaign.*
| **Name**            | **Trait** | **Range** | **Damage** | **Burden**  | **Feature**                                                |
|:--------------------|:----------|:----------|:-----------|:------12%------|:---------------------------------------------------------|
|  **Curved Sword**   | Finesse   | Melee     |    d6 phy  | One-Handed  | **Mooncut:** Curved sword goes swoosh. Spend 1 Hope to gain advantage on an attack roll.  |
|  **Battle Axe**     | Strength  | Melee     |    d8 phy  | Two-Handed  | **Heartbreaker:** An axe strike to go deep to the heart.  |
|  **Plasma Rifle**   | Agility   | Far       |    d10 phy | Two-Handed  | **Charged Blast:** Careful with overheating.  |
|  **Composite Bow**  | Agility   | Far       |    d8 phy  | Two-Handed  | **Long Shot:** Just aim to the target far far away.  |
|  **Dual Dagger**    | Finesse   | Melee     |    d6 phy  | One-Handed  | **Heart Strike:** What's better than one dagger to the heart? a dual dagger to the heart.  |
}}

## Header 4
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ultricies faucibus orci. Nulla tortor arcu, condimentum ut tellus blandit, congue vulputate nisl. Nunc viverra sem bibendum enim tincidunt efficitur. Duis eget volutpat nulla, a imperdiet magna. Ut euismod, neque eu auctor porta, nibh nunc ultricies neque, in bibendum est velit non mi. Ut molestie nisl eget venenatis consequat. Pellentesque iaculis, nulla et cursus tempor, sapien nisi interdum ante, ac consectetur purus mi non neque. Praesent quis dui eget tellus aliquam commodo. Maecenas non vestibulum ante, id laoreet nulla. Nunc dapibus elit quis consectetur feugiat.

#### Header
Praesent ac felis vel lacus ornare porta. Fusce quis vehicula leo, nec lobortis risus. Integer in accumsan lacus, ac finibus risus. Etiam sit amet scelerisque enim. Maecenas condimentum suscipit fermentum. Fusce euismod purus non magna pretium, id bibendum enim dapibus. Aenean vulputate pellentesque urna ut maximus. Nullam quis iaculis arcu. Nulla facilisi. Donec molestie orci eu molestie lacinia.

| Attack | Easy     | Bonus |
|:-------|:---------|:------|
| Defend | Medium   | +2    |
| Cover  | Easy     | +2    |
| Run    | Easy     | +2    |
| Aid    | Medium   | +2    |
| Hide   | Hard     | +3    |

{{footnote Chapter Four: Adversaries and Environments}}
{{pageNumber,auto}}

\page

{{Ch4,tab}}

{{wide
## Tier 4 Adversaries (Levels 8-10)
}}

{{adversary,
## Arch-Necromancer
### Tier 4 Leader
*A decaying mage adorned in dark, tattered robes.*  
**Motives & Tactics:** Corrupt, decay, flee to fight another day, resurrect

{{descriptive
**Difficulty:** 21 | **Thresholds:** 33/66 | **HP:** 9 | **Stress:** 8  
**ATK:** +6 | **Necrotic Blast:** Far | 4d12+8 mag
___
**Experience:** Forbidden Knowledge +3, Wisdom of Centuries +3
}}

#### Features
**Dance of Death - Action: Mark a Stress** to spotlight **1d4** allies. Attacks they make while spotlighted in this way deal half damage, or full damage if you **spend a Fear**.

**Beam of Decay - Action: Mark 2 Stress** to cause all targets within Far range to make a Strength Reaction Roll. Targets who fail take **2d20+12** magic damage and you gain a Fear. Targets who succeed take half damage. A target who marks 2 or more HP must also mark **2 Stress** and becomes *Vulnerable* until they roll with Hope.

**Open the Gates of Death - Action: Spend a Fear** to summon a Zombie Legion, which appears at Close range and immediately takes the spotlight.

**Not Today, My Dears - Reaction:** When the Necromancer has marked 7 or more of their HP, you can **spend a Fear** to have them teleport away to a safe location to recover. A PC who succeeds on an Instinct Roll can trace the teleportation magic to their destination.

**Your Life Is Mine - Reaction:** *Countdown (Loop 2d6)*. When the Necromancer has marked 6 or more of their HP, activate the countdown. When it triggers, deal **2d10+6** direct magic damage to a target within Close range. The Necromancer then **clears a number of Stress or HP** equal to the number of HP marked by the target from this attack.
}}

{{adversary,
## Fallen Shock Troop
### Tier 4 Minion
*A cursed soul bound to the Fallen's will.*  
**Motives & Tactics:** Crush, dominate, earn relief, punish

{{descriptive
**Difficulty:** 18 | **Thresholds:** None | **HP:** 1 | **Stress:** 1  
**ATK:** +2 | **Cursed Axe:** Very Close | 12 phy
___
**Experience:** Forbidden Knowledge +3, Wisdom of Centuries +3
}}

#### Features
**Minion (12) - Passive:** The Shock Troop is defeated when they take any damage. For every 12 damage a PC deals to the Shock Troop, defeat an additional Minion within range the attack would succeed against.

**Aura of Doom - Passive:** When a PC marks HP from an attack by the Shock Troop, they lose a Hope.

**Group Attack - Action: Spend a Fear** to choose a target and spotlight all Fallen Shock Troops within Close range of them. Those Minions move into Melee range of the target and make one shared attack roll. On a success, they deal 12 physical damage each. Combine this damage.
}}


\column

{{adversary,
## Fallen Sorcerer
### Tier 4 Support
*A powerful mage bound by the bargains they made in life.*  
**Motives & Tactics:** Acquire, dishearten, dominate, torment

{{descriptive
**Difficulty:** 19 | **Thresholds:** 26/42 | **HP:** 6 | **Stress:** 5  
**ATK:** +4 | **Corrupted Staff:** Far | 4d6+10 mag
___
**Experience:** Ancient Knowledge +2
}}

#### Features
**Conflagration - Action: Spend a Fear** to unleash an all-consuming firestorm and make an attack against all targets within Close range. Targets the Sorcerer succeeds against take **2d10+6** direct magic damage.

**Nightmare Tableau - Action: Mark a Stress** to trap a target within Far range in a powerful illusion of their worst fears. While trapped, the target is Restrained and Vulnerable until they break free, ending both conditions, with a successful Instinct Roll.

**Slippery - Reaction:** When the Sorcerer takes damage from an attack, they can teleport up to Far range

**Shackles of Guilt - Reaction:** *Countdown (Loop 2d6)*. When the Sorcerer is in the spotlight for the fi rst time, activate the countdown. When it triggers, all targets within Far range become Vulnerable and must mark a Stress as they relive their greatest regrets. A target can break free from their regret with a successful Presence or Strength Roll. When a PC fails to break free, they lose a Hope.
}}

{{environment,
## Ambushed
### Tier 1 Event
*An ambush is set to catch an unsuspecting party off -guard.*  
**Impulses:** Overwhelm, scatter, surround

{{descriptive
**Difficulty:** Special (see "Relative Strenght")

**Potential Adversaries:** Any
}}

#### Features
**Relative Strength - Passive:** The Diffi culty of this environment equals that of the adversary with the highest Difficulty.

*Who cues the ambush? What makes it clear they’re in charge?*

**Surprise! - Action:** The ambushers reveal themselves to the party, you gain 2 Fear, and the spotlight immediately shifts to one of the ambushing adversaries.

*What do the ambushers want from the party? How do their tactics in the ambush reflect that?*
}}

{{footnote Chapter Four: Adversaries and Environments}}
{{pageNumber,auto}}

\page

{{Ch5,tab}}

<!--
For adjusting the vertical spacing of a campaign frame, add or remove ":". The circles in the complexity rating are the Unicode Character "⏺" (U+23FA).

Also rembember to use "footnote,white" for white text in the footnote!
-->

:::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::

{{CampaignFrame
{{wide
# A Dagger to the Heart
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed ultricies faucibus orci. Nulla tortor arcu, condimentum ut tellus blandit, congue vulputate nisl. Nunc viverra sem bibendum enim tincidunt efficitur. Duis eget volutpat nulla, a imperdiet magna. 

Designed by Name1, Name2

##### Complexity Rating: ⏺ ⏺ ⏺
}}

### The Pitch
*Read this section to your players to introduce them to the campaign.*

Ut euismod, neque eu auctor porta, nibh nunc ultricies neque, in bibendum est velit non mi. Ut molestie nisl eget venenatis consequat. Pellentesque iaculis, nulla et cursus tempor, sapien nisi interdum ante, ac consectetur purus mi non neque. Praesent quis dui eget tellus aliquam commodo. Maecenas non vestibulum ante, id laoreet nulla. Nunc dapibus elit quis consectetur feugiat. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nullam sit amet ex vitae sapien vestibulum tristique nec quis nisl. Curabitur tincidunt finibus sapien at feugiat. Ut at urna hendrerit lectus sodales pharetra. Aenean aliquet sagittis metus vel porttitor. Vivamus ullamcorper egestas placerat. Vivamus ac dignissim nisi. Vivamus sagittis mattis ex, quis placerat nunc laoreet eget. Morbi at sollicitudin leo. Donec vitae dapibus massa, id aliquam sem.

\column

### Tone & Feel
- *Epic, Heroic, High-Magic, Supernatural*

### Themes
- *Adventuring Guild, Good vs Bad, Zero to Hero*

### Touchstones
- *The Legend of Vox Machina*

}}

{{imageMaskEdge8,--offset:5%

<!-- Dont change the mask edge 8, which is used as gradient for Campaign Frames. Use --offset to shift the mask away from page center (can use cm instead of %) -->

![Fantasy Castle](https://i.imgur.com/23HRmqv.jpeg){position:absolute,right:0%,top:-5%,height:100%}
}}

{{artist,aLight,top:80px,right:30px
##### Fantasy Castle
[Bob Greyvenstein](https://www.vangoghmuseum.nl/en)
}}

{{footnote,white Chapter 5: A Dagger to the Heart}}
{{pageNumber,auto}}

\page

{{Ch5,tab,CFrame}}

{{FrameHeader,wide
### A Dagger to the Heart
## Overview
*If your group decides to play this campaign, give your players the following information before character creation.*
}}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer viverra pulvinar dignissim. Proin tristique imperdiet libero sed ultricies. Ut imperdiet odio sit amet elementum volutpat. Pellentesque congue egestas lacus, sed placerat justo aliquam ut. Sed lorem odio, facilisis vel odio sit amet, blandit sodales lectus. Vestibulum sapien nulla, interdum a viverra vel, blandit sed diam. Fusce tristique ante orci, eu feugiat dui lobortis eget. Pellentesque metus sem, rutrum nec consectetur eu, tristique vel sapien.

Pellentesque maximus iaculis ex, et efficitur enim euismod vel. Integer dignissim est ac nisi tempus, sit amet dignissim elit lobortis. Praesent id dui rutrum velit pretium eleifend a venenatis magna. Praesent feugiat diam at sapien elementum, at fermentum nunc condimentum. Donec viverra venenatis placerat. Integer eget euismod erat, in efficitur felis. Vivamus hendrerit eget magna at porttitor. Praesent commodo arcu ac aliquam luctus.

Phasellus mattis imperdiet neque vel bibendum. Phasellus vestibulum porta tellus. Aenean sollicitudin ullamcorper sapien ut ornare. Aliquam ac volutpat risus. Donec eget lacinia est, vel congue tortor. Sed sed enim non nisi dapibus imperdiet. Vivamus commodo in diam a facilisis. Sed ut velit ut erat sodales semper vitae vitae augue. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Vivamus laoreet odio eu ligula sodales, at facilisis odio elementum. Donec viverra laoreet turpis vitae faucibus. Ut vitae ipsum at arcu varius sollicitudin. Proin eros orci, accumsan nec eros eget, consectetur tincidunt nisi. Maecenas diam mauris, consequat ac neque id, porta tristique orci. Curabitur ut nibh nunc.

Cras et lacus gravida, viverra dolor nec, mollis mi. Morbi pulvinar enim auctor ligula tincidunt pretium. Fusce lectus libero, lacinia mollis sem sit amet, egestas placerat est. Quisque congue quis nisl imperdiet tristique. In aliquam pharetra nunc, non luctus magna aliquam eget. Sed dapibus turpis et neque pellentesque accumsan. Pellentesque sodales volutpat augue, et finibus lectus scelerisque in. Quisque sit amet est laoreet, efficitur elit at, tincidunt mauris. Integer convallis id velit ultricies bibendum.

Maecenas tincidunt est sed nisl scelerisque, et facilisis urna viverra. Vivamus pretium commodo metus sit amet dictum. Maecenas vestibulum risus quis massa commodo laoreet. Donec malesuada tincidunt tellus laoreet cursus. Donec imperdiet nunc enim, in aliquet mauris semper et. Pellentesque ac molestie massa, et posuere lorem. Pellentesque aliquam justo id mollis consequat.

Curabitur leo diam, cursus quis leo pharetra, varius facilisis dui. Pellentesque vitae consequat dui. Sed eget luctus odio. Mauris eget quam sem. In hac habitasse platea dictumst. Aliquam ac condimentum enim. Donec rutrum risus eu vulputate pellentesque. Nulla maximus pulvinar fringilla. Nullam diam orci, auctor ac velit nec, sollicitudin molestie sem.

Aenean tincidunt mauris arcu, ac dignissim mi eleifend in. Cras vel lectus pulvinar, eleifend ligula ac, semper nunc. Curabitur in sodales arcu. Pellentesque et metus maximus, elementum lectus et, bibendum risus. Vivamus facilisis lacinia ligula, eget fringilla dui ultricies varius. Proin eros ex, condimentum non aliquam quis, fringilla ac lacus. Proin sit amet ullamcorper nisi. Maecenas et ornare turpis.

In scelerisque aliquet nunc, faucibus efficitur libero commodo a. Vivamus efficitur elit in eros consectetur, non placerat ex pretium. Quisque pulvinar bibendum tellus, et vulputate tellus ornare a. Curabitur nibh ex, aliquet eu consequat et, rutrum ac ex. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla congue, metus id ullamcorper commodo, elit ex egestas leo, id imperdiet risus purus mollis dui. Donec facilisis fringilla elit, et vestibulum nisi molestie nec. Morbi aliquet augue a lacus luctus finibus. Nunc mollis dolor sapien, sit amet consectetur dolor viverra at. Duis hendrerit ante in magna consequat accumsan.

In et cursus tortor, et efficitur odio. Nam ultrices rutrum nunc vitae suscipit. Nulla accumsan dictum pretium. Donec ultrices tellus nec nisi fringilla, quis dignissim magna tempus. Duis luctus ac lorem et consequat. Curabitur fermentum risus quis velit porta, vel condimentum arcu semper. Duis a consectetur lacus. Integer ante elit, tincidunt et orci sit amet, bibendum porttitor magna. Donec vel neque tortor. Quisque volutpat nisl sed scelerisque rhoncus. Integer nec dui mollis, bibendum arcu venenatis, consequat felis. Vivamus maximus gravida tempor. Curabitur ante risus, vestibulum vulputate varius sit amet, ultrices a mi. Sed in felis urna. Aenean dictum arcu fermentum, gravida dolor ac, bibendum mi. Proin gravida neque ligula, quis dictum dolor pulvinar non.

Sed non sagittis erat, nec ultrices massa. Fusce ornare volutpat mi, quis tristique velit tempor et. Donec id dictum nunc, et ultrices mauris. Aliquam erat volutpat. Nullam est odio, viverra ut pulvinar vel, porta et nisi. Donec dignissim in ipsum eget tempus. Curabitur sed nibh feugiat, facilisis justo eget, posuere ipsum. Ut efficitur lorem lacus. Mauris eget purus sed justo sodales tempor. Etiam eu lorem commodo, imperdiet enim non, auctor tellus. Pellentesque velit lacus, vulputate vitae placerat at, porta et est.

{{footnote Chapter 5: A Dagger to the Heart}}
{{pageNumber,auto}}

\page

{{Ch5,tab,CFrame}}

{{FrameHeader,wide
### A Dagger to the Heart
## Communities
*All communities are available, but some have unique aspects within a Dagger to the Heart campaign. As needed, provide the following information to your players and choose one or more of the questions to ask them during your session zero.*
}}

#### All Communities
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer viverra pulvinar dignissim. Proin tristique imperdiet libero sed ultricies. Ut imperdiet odio sit amet elementum volutpat. Pellentesque congue egestas lacus, sed placerat justo aliquam ut. Sed lorem odio, facilisis vel odio sit amet, blandit sodales lectus. Vestibulum sapien nulla, interdum a viverra vel, blandit sed diam. Fusce tristique ante orci, eu feugiat dui lobortis eget. Pellentesque metus sem, rutrum nec consectetur eu, tristique vel sapien.

#### Underborne
Pellentesque maximus iaculis ex, et efficitur enim euismod vel. Integer dignissim est ac nisi tempus, sit amet dignissim elit lobortis. Praesent id dui rutrum velit pretium eleifend a venenatis magna. Praesent feugiat diam at sapien elementum, at fermentum nunc condimentum. Donec viverra venenatis placerat. Integer eget euismod erat, in efficitur felis. Vivamus hendrerit eget magna at porttitor. Praesent commodo arcu ac aliquam luctus.

\column

#### Ridgeborne
Phasellus mattis imperdiet neque vel bibendum. Phasellus vestibulum porta tellus. Aenean sollicitudin ullamcorper sapien ut ornare. Aliquam ac volutpat risus. Donec eget lacinia est, vel congue tortor. Sed sed enim non nisi dapibus imperdiet. Vivamus commodo in diam a facilisis. Sed ut velit ut erat sodales semper vitae vitae augue. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Vivamus laoreet odio eu ligula sodales, at facilisis odio elementum. Donec viverra laoreet turpis vitae faucibus. Ut vitae ipsum at arcu varius sollicitudin. Proin eros orci, accumsan nec eros eget, consectetur tincidunt nisi. Maecenas diam mauris, consequat ac neque id, porta tristique orci. Curabitur ut nibh nunc.

#### Loreborne
Cras et lacus gravida, viverra dolor nec, mollis mi. Morbi pulvinar enim auctor ligula tincidunt pretium. Fusce lectus libero, lacinia mollis sem sit amet, egestas placerat est. Quisque congue quis nisl imperdiet tristique. In aliquam pharetra nunc, non luctus magna aliquam eget. Sed dapibus turpis et neque pellentesque accumsan. Pellentesque sodales volutpat augue, et finibus lectus scelerisque in. Quisque sit amet est laoreet, efficitur elit at, tincidunt mauris. Integer convallis id velit ultricies bibendum.

___ 

<!-- The three underscores generates a wide dotted line to separate two parts -->

## Ancestries
*All ancestries are available, but some have unique aspects within a A Dagger to the Heart campaign. As needed, provide the following information to your players.*

#### Clanks
Curabitur leo diam, cursus quis leo pharetra, varius facilisis dui. Pellentesque vitae consequat dui. Sed eget luctus odio. Mauris eget quam sem. In hac habitasse platea dictumst. Aliquam ac condimentum enim. Donec rutrum risus eu vulputate pellentesque. Nulla maximus pulvinar fringilla. Nullam diam orci, auctor ac velit nec, sollicitudin molestie sem.

#### Humans
Curabitur leo diam, cursus quis leo pharetra, varius facilisis dui. Pellentesque vitae consequat dui. Sed eget luctus odio. Mauris eget quam sem. In hac habitasse platea dictumst. Aliquam ac condimentum enim. Donec rutrum risus eu vulputate pellentesque. Nulla maximus pulvinar fringilla. Nullam diam orci, auctor ac velit nec, sollicitudin molestie sem.

\column

## Classes
*All classes are available, but some have unique aspects within A Dagger to the Heart campaign. As needed, provide the following information to your players.*

#### All Classes
Cras et lacus gravida, viverra dolor nec, mollis mi. Morbi pulvinar enim auctor ligula tincidunt pretium. Fusce lectus libero, lacinia mollis sem sit amet, egestas placerat est. Quisque congue quis nisl imperdiet tristique. In aliquam pharetra nunc, non luctus magna aliquam eget. Sed dapibus turpis et neque pellentesque accumsan. Pellentesque sodales volutpat augue, et finibus lectus scelerisque in. Quisque sit amet est laoreet, efficitur elit at, tincidunt mauris. Integer convallis id velit ultricies bibendum.

{{footnote Chapter 5: A Dagger to the Heart}}
{{pageNumber,auto}}

\page

{{Ch5,tab,CFrame}}

{{FrameHeader,wide
### A Dagger to the Heart
}}

## Player Principles
*If your group decides to play this campaign, give your players the following information before character creation.*

#### Principle One
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer viverra pulvinar dignissim. Proin tristique imperdiet libero sed ultricies. Ut imperdiet odio sit amet elementum volutpat. Pellentesque congue egestas lacus, sed placerat justo aliquam ut. Sed lorem odio, facilisis vel odio sit amet, blandit sodales lectus. Vestibulum sapien nulla, interdum a viverra vel, blandit sed diam. Fusce tristique ante orci, eu feugiat dui lobortis eget. Pellentesque metus sem, rutrum nec consectetur eu, tristique vel sapien.

#### Principle Two
Pellentesque maximus iaculis ex, et efficitur enim euismod vel. Integer dignissim est ac nisi tempus, sit amet dignissim elit lobortis. Praesent id dui rutrum velit pretium eleifend a venenatis magna. Praesent feugiat diam at sapien elementum, at fermentum nunc condimentum. Donec viverra venenatis placerat. Integer eget euismod erat, in efficitur felis. Vivamus hendrerit eget magna at porttitor. Praesent commodo arcu ac aliquam luctus.

#### Principle Three
Phasellus mattis imperdiet neque vel bibendum. Phasellus vestibulum porta tellus. Aenean sollicitudin ullamcorper sapien ut ornare. Aliquam ac volutpat risus. Donec eget lacinia est, vel congue tortor. Sed sed enim non nisi dapibus imperdiet. Vivamus commodo in diam a facilisis. Sed ut velit ut erat sodales semper vitae vitae augue. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Vivamus laoreet odio eu ligula sodales, at facilisis odio elementum.

\column

## GM Principles
*Keep the following guidance in mind while you GM this campaign.*

#### GM Principle One
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer viverra pulvinar dignissim. Proin tristique imperdiet libero sed ultricies. Ut imperdiet odio sit amet elementum volutpat. Pellentesque congue egestas lacus, sed placerat justo aliquam ut. Sed lorem odio, facilisis vel odio sit amet, blandit sodales lectus. Vestibulum sapien nulla, interdum a viverra vel, blandit sed diam. Fusce tristique ante orci, eu feugiat dui lobortis eget. Pellentesque metus sem, rutrum nec consectetur eu, tristique vel sapien.

#### GM Principle Two
Pellentesque maximus iaculis ex, et efficitur enim euismod vel. Integer dignissim est ac nisi tempus, sit amet dignissim elit lobortis. Praesent id dui rutrum velit pretium eleifend a venenatis magna. Praesent feugiat diam at sapien elementum, at fermentum nunc condimentum. Donec viverra venenatis placerat. Integer eget euismod erat, in efficitur felis. Vivamus hendrerit eget magna at porttitor. Praesent commodo arcu ac aliquam luctus.

#### GM Principle Three
Phasellus mattis imperdiet neque vel bibendum. Phasellus vestibulum porta tellus. Aenean sollicitudin ullamcorper sapien ut ornare. Aliquam ac volutpat risus. Donec eget lacinia est, vel congue tortor. Sed sed enim non nisi dapibus imperdiet. Vivamus commodo in diam a facilisis. Sed ut velit ut erat sodales semper vitae vitae augue. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Vivamus laoreet odio eu ligula sodales, at facilisis odio elementum.

{{footnote Chapter 5: A Dagger to the Heart}}
{{pageNumber,auto}}

\page

{{Ch5,tab,CFrame}}

{{FrameHeader,wide
### A Dagger to the Heart
## Distinctions
*Use this information to prepare your campaign. You can also share it with your players as needed.*
}}

#### When the Dagger Strikes
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut viverra eros non sapien varius laoreet in vel tortor. Curabitur cursus eu urna sed congue. Vivamus suscipit lacinia neque, eget tristique orci facilisis fringilla. Ut egestas, diam eget gravida hendrerit, urna lectus aliquet nulla, quis blandit velit nisl nec augue. Aliquam erat volutpat. Mauris magna sem, condimentum et neque eu, facilisis porta nibh. In bibendum ante quis congue interdum. Aenean nec accumsan turpis. Curabitur leo odio, ornare eget hendrerit nec, accumsan nec enim. Sed ultricies justo sed quam aliquam, non sagittis neque venenatis. Quisque nunc risus, egestas quis ante quis, molestie pulvinar eros. Cras id tempus sem. Vivamus eu fermentum felis. Etiam posuere nisi eget odio fringilla tincidunt.

- **Pellentesque maximus** iaculis ex, et efficitur enim euismod vel. Integer dignissim est ac nisi tempus, sit amet dignissim elit lobortis. Praesent id dui rutrum velit pretium eleifend a venenatis magna. 
- **Praesent feugiat** diam at sapien elementum, at fermentum nunc condimentum. Donec viverra venenatis placerat. Integer eget euismod erat, in efficitur felis. Vivamus hendrerit eget magna at porttitor. Praesent commodo arcu ac aliquam luctus.
- **Phasellus mattis** imperdiet neque vel bibendum. Phasellus vestibulum porta tellus. Aenean sollicitudin ullamcorper sapien ut ornare. Aliquam ac volutpat risus. Donec eget lacinia est, vel congue tortor. Sed sed enim non nisi dapibus imperdiet. Vivamus commodo in diam a facilisis. Sed ut velit ut erat sodales semper vitae vitae augue. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Vivamus laoreet odio eu ligula sodales, at facilisis odio elementum.

#### Daggers and Hearts
Maecenas egestas vel eros elementum pulvinar. Praesent felis risus, luctus nec viverra in, sodales in neque. Phasellus posuere dui quis laoreet tempor. Nulla facilisi. Quisque ultrices eros velit. Suspendisse consequat eros ut orci ornare fermentum. Integer aliquet at ligula id aliquam. Suspendisse ornare mollis condimentum.

Cras nec dolor non lacus finibus rutrum. Curabitur at aliquet nunc, vel convallis neque. Pellentesque ornare augue in neque lacinia, ut eleifend leo elementum. Morbi vehicula diam vitae nunc vulputate, nec ultricies arcu venenatis. Morbi egestas eleifend pulvinar. Donec et dui et velit semper dignissim. Quisque at consectetur elit.

Pellentesque lobortis pulvinar elementum. Quisque tincidunt, nisl commodo interdum dictum, nibh turpis iaculis magna, ut efficitur mi metus at erat. Nam mauris tortor, consequat ac purus eget, facilisis tempus ipsum. Quisque arcu mi, scelerisque nec pharetra eu, faucibus id lorem. Curabitur sapien leo, facilisis non nisl nec, ultrices bibendum neque. Proin fringilla ullamcorper erat vitae laoreet. Nunc id sem mattis felis porta molestie et nec orci. Vivamus lobortis sed neque quis pretium. Maecenas maximus rhoncus arcu. Maecenas suscipit metus et augue viverra dapibus eget ac elit. Donec aliquet odio at urna dictum, ut hendrerit enim posuere. Nunc placerat hendrerit diam in pulvinar. Sed consectetur sapien elit, vitae faucibus augue tincidunt non. Suspendisse molestie rhoncus neque eget lobortis. Sed semper ac odio in iaculis.

| Attack | Easy     | Bonus |
|:-------|:---------|:------|
| Defend | Medium   | +2    |
| Cover  | Easy     | +2    |
| Run    | Easy     | +2    |
| Aid    | Medium   | +2    |
| Hide   | Hard     | +3    |

#### Getting a Dagger
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vestibulum vel imperdiet dolor, non ultrices felis. Donec viverra nisi et magna varius maximus. Morbi hendrerit sem quis malesuada volutpat. Integer consequat, nisi blandit pharetra egestas, lectus nibh feugiat eros, quis vestibulum ipsum libero quis erat. Fusce ligula odio, consectetur vitae tempus vitae, porta id sem. Sed id nibh quis sem vulputate consequat. Nunc convallis quam viverra, luctus purus a, egestas magna. Vivamus id purus bibendum, semper ante et, consectetur mi. Integer ac cursus lectus. Proin fermentum placerat quam eu commodo. Donec non nibh feugiat, dignissim diam egestas, luctus urna. Sed enim sem, luctus nec turpis in, interdum dignissim dolor. Phasellus efficitur massa eu est laoreet, eu ultricies turpis imperdiet. Phasellus convallis sit amet ipsum eu auctor.

{{footnote Chapter 5: A Dagger to the Heart}}
{{pageNumber,auto}}

\page

{{Ch5,tab,CFrame}}

{{FrameHeader,wide
### A Dagger to the Heart
## The Inciting Incident
*You can use the prompt below to start your campaign, or create your own.*
}}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut viverra eros non sapien varius laoreet in vel tortor. Curabitur cursus eu urna sed congue. Vivamus suscipit lacinia neque, eget tristique orci facilisis fringilla. Ut egestas, diam eget gravida hendrerit, urna lectus aliquet nulla, quis blandit velit nisl nec augue. Aliquam erat volutpat. Mauris magna sem, condimentum et neque eu, facilisis porta nibh. In bibendum ante quis congue interdum. Aenean nec accumsan turpis. Curabitur leo odio, ornare eget hendrerit nec, accumsan nec enim. Sed ultricies justo sed quam aliquam, non sagittis neque venenatis. Quisque nunc risus, egestas quis ante quis, molestie pulvinar eros. Cras id tempus sem. Vivamus eu fermentum felis. Etiam posuere nisi eget odio fringilla tincidunt.

Maecenas egestas vel eros elementum pulvinar. Praesent felis risus, luctus nec viverra in, sodales in neque. Phasellus posuere dui quis laoreet tempor. Nulla facilisi. Quisque ultrices eros velit. Suspendisse consequat eros ut orci ornare fermentum. Integer aliquet at ligula id aliquam. Suspendisse ornare mollis condimentum.

{{wide
## Campaign Mechanics
*The following mechanics are unique to this campaign.*

### A Dagger to the Heart Starting Equipment
Cras nec dolor non lacus finibus rutrum. Curabitur at aliquet nunc, vel convallis neque. Pellentesque ornare augue in neque lacinia, ut eleifend leo elementum. Morbi vehicula diam vitae nunc vulputate, nec ultricies arcu venenatis. Morbi egestas eleifend pulvinar. Donec et dui et velit semper dignissim. Quisque at consectetur elit.
}}

{{DHTable,wide
### Primary Weapons
*The following primary weapons are also available in this campaign.*
| **Name**            | **Trait** | **Range** | **Damage** | **Burden**  | **Feature**                                                                                |
|:--------------------|:----------|:----------|:-----------|------------:|:-------------------------------------------------------------------------------------------|
|  **Curved Sword**   | Finesse   | Melee     |    d6 phy  | One-Handed  | **Mooncut:** Curved sword goes swoosh. Spend 1 Hope to gain advantage on an attack roll.   |
|  **Battle Axe**     | Strength  | Melee     |    d8 phy  | Two-Handed  | **Heartbreaker:** An axe strike to go deep to the heart.                                   |
|  **Plasma Rifle**   | Agility   | Far       |    d10 phy | Two-Handed  | **Charged Blast:** Careful with overheating.                                               |
|  **Composite Bow**  | Agility   | Far       |    d8 phy  | Two-Handed  | **Long Shot:** Just aim to the target far far away.                                        |
|  **Dual Dagger**    | Finesse   | Melee     |    d6 phy  | One-Handed  | **Heart Strike:** What's better than one dagger to the heart? a dual dagger to the heart.  |
}}

###### RELICS
Cras et lacus gravida, viverra dolor nec, mollis mi. Morbi pulvinar enim auctor ligula tincidunt pretium. Fusce lectus libero, lacinia mollis sem sit amet, egestas placerat est. Quisque congue quis nisl imperdiet tristique. In aliquam pharetra nunc, non luctus magna aliquam eget. Sed dapibus turpis et neque pellentesque accumsan. Pellentesque sodales volutpat augue, et finibus lectus scelerisque in. Quisque sit amet est laoreet, efficitur elit at, tincidunt mauris. Integer convallis id velit ultricies bibendum.

## Session Zero Questions
*Ask any of these questions to your players, or make your own.*

- Cras et lacus gravida, viverra dolor nec, mollis mi. Morbi pulvinar enim auctor ligula tincidunt pretium. Fusce lectus libero, lacinia mollis sem sit amet, egestas placerat est. Quisque congue quis nisl imperdiet tristique. In aliquam pharetra nunc, non luctus magna aliquam eget. Sed dapibus turpis et neque pellentesque accumsan.
- Pellentesque sodales volutpat augue, et finibus lectus scelerisque in. Quisque sit amet est laoreet, efficitur elit at, tincidunt mauris. Integer convallis id velit ultricies bibendum.
- Maecenas egestas vel eros elementum pulvinar. Praesent felis risus, luctus nec viverra in, sodales in neque. Phasellus posuere dui quis laoreet tempor. Nulla facilisi. Quisque ultrices eros velit. Suspendisse consequat eros ut orci ornare fermentum. Integer aliquet at ligula id aliquam. Suspendisse ornare mollis condimentum.

{{footnote Chapter 5: A Dagger to the Heart}}
{{pageNumber,auto}}

\page

{{app,tab}}

# Appendix
This section contains additional information and reference sheets

## Domain Card Reference

<!-- 
This section changes the colors of the squares next to the card references and the banner border of the domain:

- {{CardRef1}} Arcana Domain (Purple)       : #753d89
- {{CardRef2}} Blade Domain (Red)           : #af2526
- {{CardRef3}} Bone Domain (Gray)           : #9aa0a4
- {{CardRef4}} Codex Domain (Blue)          : #174b8a
- {{CardRef5}} Grace Domain (Pink)          : #b33b7d
- {{CardRef6}} Midnight Domain (Black)      : #232729
- {{CardRef7}} Sage Domain (Green)          : #0f6e3a
- {{CardRef8}} Splendor Domain (Yellow)     : #d9b227
- {{CardRef9}} Valor Domain (Orange)        : #e16b26
- {{CardRef10}} Dread Domain (Blue-purple)  : #463f8c

You can copy/paste to create new domains if needed with custom colors and/or modify the colors here to adjust them to whatever you require.
 -->
 
 
{{CardRef1,wide,column-count:3
## Arcana Domain
#### Rune Ward
**Level 1 Arcana Spell** ::
**Recall Cost: 0** ::

You have a deeply personal trinket that can be infused with protective magic and held as a ward by you or an ally. Describe what it is and why it’s important to you. The ward’s holder can spend a Hope to reduce incoming damage by **1d8**.

If the Ward Die result is 8, the ward’s power ends after it reduces damage this turn. It can be recharged for free on your next rest.

#### Unleash Chaos
**Level 1 Arcana Spell** ::
**Recall Cost: 1** ::

At the beginning of a session, place a number of tokens equal to your Spellcast trait on this card.

Make a Spellcast Roll against a target within Far range and spend any number of tokens to channel raw energy from within yourself to unleash against them. On a success, roll a number of **d10s** equal to the tokens you spent and deal that much magic damage to the target. **Mark a Stress** to replenish this card with tokens (up to your Spellcast trait).

At the end of each session, clear all unspent tokens.

#### Wall Walk
**Level 1 Arcana Spell** ::
**Recall Cost: 1** ::

Spend a Hope to allow a creature you can touch to climb on walls and ceilings as easily as walking on the ground. This lasts until the end of the scene or you cast Wall Walk again.

\column

#### Cinder Grasp
**Level 2 Arcana Spell** ::
**Recall Cost: 1** ::

Make a Spellcast Roll against a target within Melee range. On a success, the target instantly bursts into flames, takes **1d20+3** magic damage, and is temporarily lit On Fire.

When a creature acts while On Fire, they must take an extra **2d6** magic damage if they are still On Fire at the end of their action.

#### Floating Eye
**Level 2 Arcana Spell** ::
**Recall Cost: 0** ::

Spend a Hope to create a single, small floating orb that you can move anywhere within Very Far range. While this spell is active, you can see through the orb as though you’re looking out from its position. You can transition between using your own senses and seeing through the orb freely. If the orb takes damage or moves out of range, the spell ends.

#### Counterspell
**Level 3 Arcana Spell** ::
**Recall Cost: 2** ::

You can interrupt a magical effect taking place by making a reaction roll using your Spellcast trait. On a success, the effect stops and any consequences are avoided, and this card is placed in your vault.

#### Flight
**Level 3 Arcana Spell** ::
**Recall Cost: 1** ::

Make a **Spellcast Roll (15)**. On a success, place a number of tokens equal to your Agility on this card (minimum 1). When you make an
action roll while flying, spend a token from this card. After the action that spends the last token is resolved,
you descend to the ground directly below you.

\column

#### Blink Out
**Level 4 Arcana Spell** ::
**Recall Cost: 1** ::

Make a **Spellcast Roll (12)**. On a success, **spend a Hope** to teleport to another point you can see within Far range. If any willing creatures are within Very Close range, spend an additional Hope for each creature to bring them with you.

#### Preservation Blast
**Level 4 Arcana Spell** ::
**Recall Cost: 2** ::

Make a **Spellcast Roll** against all targets within Melee range. Targets you succeed against are forced back to Far range and take **d8+3** magic damage using your Spellcast trait.

#### Chain Lightning
**Level 5 Arcana Spell** ::
**Recall Cost: 1** ::

**Mark 2 Stress** to make a **Spellcast Roll**, unleashing lightning on all targets within Close range. Targets you succeed against must make a reaction roll with a Difficulty equal to the result of your Spellcast Roll. Targets who fail take **2d8+4** magic damage. Additional adversaries not already targeted by Chain Lightning and within Close range of previous targets who took damage must also make the reaction roll. Targets who fail take **2d8+4** magic damage. This chain continues until there are no more adversaries within range.

#### Premonition
**Level 5 Arcana Spell** ::
**Recall Cost: 2** ::

You can channel arcane energy to have visions of the future. Once per long rest, immediately after the GM conveys the consequences of a roll you made, you can rescind the move and consequences like they never happened and make another move instead.

}}

{{footnote Appendix: Domain Card Reference}}
{{pageNumber,auto}}