---
title: 'Learning Commander'
date: 2024-10-20T12:41:49-04:00
draft: true
categories:
- hobby
tags:
- tcg
- learning
- guide
image: ghalta-header.jpg
---

# Learning Commander

I've been somewhat interested in Magic since middle school, but for one reason or another, never really
got in to actually _playing with others_ until recently. I learned the basic mechanics way back then,
did one sealed constructed and one draft event in college, and beyond that, mostly just impulse bought
packs of the fancy shiny or alt art ones. One of the recent sets, [Bloomburrow](), caught my eye - it 
was nature-y and had cute critters - and I succumbed to the urge and got a box to crack and add to my
existing collection.

For whatever reason, though, for one of the first times, I'd actually started picking up more on the
game mechanics as well, finally, and not just buying expensive cardboard for the looks. My best guess
as to what actually motivated the interest was getting and playing the [Slay the Spire board game](bgg link).
In any event, I was already familiar with Commander being a popular and fairly casual format, so I
started watching videos and reading guides on building a commander deck for the first time. Putting
some basic learnings here.

## Deck Construction

### Goals
With Commander being such a broad format, folks have different goals when it comes to constructing
decks and playing games. Some folks are more in to solitaire, building up complex board
states and engines over the course of several turns with the hopes of swinging big in mid-to-late game.
Others prefer more interaction - responses to big plays, politics, and general mayhem. I tend to think
the latter is more interesting. The solitaire style is a neat form of puzzle solving that you can indeed
do alone, but to me magic and commander specifically are meant to be social and interactive, and I
really enjoy chaotic games :) So, my first goal is building a deck that is **interactive** - a deck that can respond to threats and answer plays from opponents.

I'd also like a deck that is reasonably focused, but isn't cEDH level or overly sweaty. From my 
admittedly limited experience so far, the general "meta" for casual Commander doesn't like playing with
land destruction and [stax][1]. I think it's a nuanced discussion - you can defend against both with
removal, mana dorks, etc, and it can be similar to creature/enchantment/artifact wipes. That said - I
think I agree that for a casual format, land wipes and stax are both somewhat difficult to recover from,
and each possible scenario you need to plan for is another card package you can't run in your deck. So
with that in mind, I'll **avoid land destruction and stax effects.**

In a similar vein, I can spend huge sums of money on cards like {{< autocard "Mana Vault" >}} or
{{< autocard "Urza's Saga" >}}, but those are generally prohibitively expensive for other casual
players. So I'd like to **avoid most expensive cards** to keep the game accessible for folks. A lot of
those cards also tend to ramp super quickly and lead to both snowballing and shorter games, neither of
which I really want. As an aside, these are generally staples in the competitive commander format
(cEDH), so could also just phrase this as no cEDH cards.

**tl;dr**:
- Interactive
- No major resource destruction or taxing
- No cEDH

### Rough Card Role Breakdown
A commander deck has 100 cards in it. There are a few broad roles we want to have a package of:
- **Interaction** - as mentioned in the goals, we want the deck to be responsive. That'll include both
  counterspells and protection for your own.
- **Ramp** - Rounds are slow in commander, with four folks playing at once. With one land per turn, it
  takes awhile to play cards. We also want to break parity and eventually be able to play cards in
  advance of the curve. So we'll run a set of cards that let us ramp - cards to put lands on the board
  in advance of curve, mana dorks, fetch lands for mana fixing, etc.
- **Draw** - Card draw offers big advantages in any game - more cards you can draw, more likelihood that
  you'll have the cards you need in a given scenario

Lets say we want somewhere in the range of 5-10 of each, so roughly 7.5*3 = 22 or so of these. That
leaves 77 left.

There are a few other utilities we want to have available to us:
- **Board wipes** - We want to be able to reset the board state if things get too out of hand. 3-5 of
  these seems to be the rough standard.
- **Graveyard hate** - Generally useful category for any decks that build off of graveyard usage.
  Probably just need 2-3.
- **Recursion** - The ability to retrieve cards we already played from the graveyard. 1-2 each.
- **Tutor** - The ability to search for a specific card you may need in the moment. 1-2 each.

That brings us to 71.

### Lands
The magic number I keep reading about for lands is landing around 38 or so, depending on the deck.
The breakdown will vary again depending on the deck, with a few considerations:
- We'll probably be running some 5 or so utility lands.
- If we're running a monocolored deck, we may have an easy time of mostly basics, with a few
  specialized ones for ramping.
- Multicolored decks are much more interesting, as we end up with:
  - Dual lands
  - Multicolored utility lands
  - Fetch lands for fixing
- We may also have some colorless ramp-y lands like a {{< autocard "Mana Crypt" >}}

From the 71 cards we had left, this leaves us around 30 cards for the "core" of the deck. This doesn't
seem like a lot initially, but keep in mind we can be creative with the other card roles so they fit
in with the deck theme too.

## My Deck
I've always enjoyed big green creatures, so I initially started planning around
{{< autocard "Ghalta, Primal Hunger" >}} as the primary commander. This gave me a mono-green base and
a pretty easy starting point for focusing on mana ramp, especially via dorks, and then just bring a
bunch of beefy creatures.

From there, I think I followed a roughly iterative process:
- Use a combination of [EDHRec][2], [Scryfall][3], and a variety of reddit posts and existing decks
  to build up a large base pool of cards to work with
- Using [Archidekt][4], go through each card we added to the initial pool and add tags indicating
  their deck role
- For each category, view the options for that category, and start cutting cards.
  - Obvious ones get removed, less obvious are moved to a maybeboard
  - Cut by
    - Importance to any core strategy or combo
    - Converted Mana Cost
    - If I own it or not
    - Price in USD
    - Rough relative power compared to other cards

### The Initial Attempt
There were a number of fun cards and interactions I discovered and really liked from my
[first draft][4].

#### Doubling
I'd found cards that double attack and defense for a turn, such as{{< autocard "Unnatural Growth" >}}
and {{< autocard "Zopandrel, Hunger Dominus" >}}:

<!-- TODO embed the images -->

I really wanted to lean in to this initially, so aimed for cards that could try to double multiple
times, and use +1/+1 counters, to attempt to increase power exponentially.

#### Powerful Draw
{{< autocard "Sylvan Library" >}} provided a powerful (and pricey) form of card draw - access to 
multiple possible additional cards each turn, and at minimum guaranteed viewing the top 2 cards,
is exceptional.

{{< autocard "Guardian Project" >}} is another easy choice since the condition of unique naming
is a default in the Commander format.

#### Powerful Ramp
{{< autocard "Selvala, Heart of the Wilds" >}} was an excellent source of both card draw (leaning
in to Green's penchant for large creatures) and mana ramp based on the power of those creatures.

{{< autocard "Castle Garenbrig" >}} and {{< autocard "Nykthos, Shrine to Nyx" >}} are both great
land-based sources of ramp - the former giving two free, and the latter taking a bit of time to
get off the ground but eventually providing enormous big mana.

{{< autocard "Ashaya, Soul of the Wild" >}} is a really cool form of ramp that makes all creatures
Forests as well, a quick way to hugely increase mana available. I'm possibly hesitant here - weak
greens are already dorks and expensive ones won't be worth tapping (and it doesn't work on tokens) -
but will give it a shot.

{{< autocard "Growing Rites of Itlimoc" >}} is another fun land-based ramp that takes a few turns
to pop off, but then grants mana per creature, another huge bump.

### Initial Attempt Concerns
I wrapped up the first deck, and while I was satisfied with how the initial set of turns played in
playtesting - ramped well and get dorks on the board - it got a bit uninteresting in mid-to-late
game. It had interesting finishers, but felt like it was just grabbing a couple of cool looking
singles from the right color that were _individually_ powerful but with no real synergy or specific
end goal.

One thing I'd noticed though was that 1) I really enjoyed ramping to try to get enormous amounts of
mana, and 2) there's a creature type called a Hydra that typically costs some variant of X and then
has power that scales with X. This led me to reevaluate this approach and instead move towards a
Hydra deck instead.

### Hydra Deck, First Attempt
After pivoting to focus primarily on Hydras, I was able to start from scratch and get a [more tightly
focused deck][5] that scales naturally on ramp based on the X costing.

#### Commander - Magus Lucea Kane
Despite some of the more obvious hydra-specific commanders, I found a popular option in
{{< autocard "Magus Lucea Kane" >}}. This gives us basically two of every hydra, which is remarkable.
It also gives us access to red and blue colors. Blue I enjoy for the more interactivity. Red I'm
usually not the biggest fan of, but there are a few higher cost red cards that work well with big
mana, and in particular X costs, such as {{< autocard "Crackle with Power" >}}.

#### Landbase
Since we've delved in to red and blue, at least to a small degree, we need to update the landbase
appropriately. 
- Update a good number of the Forests to be dual lands in either red or blue.
- Add a few multicolored utility lands such as {{< autocard "Command Tower" >}}
- Add in some fetch lands for fixing like {{< autocard "Misty Rainforest" >}}

I also added in{{< autocard "Yavimaya, Cradle of Growth" >}} to further turn all the lands into
Forests as well, to provide a bit of extra green source.

#### Fun Finds
Both moving to hyrdas and introducing the new colors give us some fun new cards:

{{< autocard "Rhythm of the Wild" >}} gives us an excellent form of protection with a mild buff,
for fairly cheap.

{{< autocard "Comet Storm" >}}, {{< autocard "Chain Reaction" >}}, and
{{< autocard "Crackle with Power" >}} all give some really nice burn spell slinging with cost and
output X.

Blue gave us cards like {{< autocard "Counterspell" >}} and {{< autocard "Negate" >}}, for easy cheap
interaction.

Cards like {{< autocard "The Ozolith" >}}, {{< autocard "Unbound Flourishing" >}},
{{< autocard "Doubling Season" >}}, and {{< autocard "Kalonian Hydra" >}} all provide excellent
counter increase/double/retention, which work phenomenally with Hydras.

#### Issues
This was a fun deck to build and felt a lot more focused, and wasn't too bad on curve, but was
really expensive in paper, which isn't really great for a first-time deck. I followed the advice
from someone on my LGS's Discord channel to find cheaper alternates, so I spent some time on
scryfall (and occasionally reddit, when I failed at that) to look for replacement options to bring down the cost.

### Third Attempt
The [third attempt][6], which brought the cost down to 1/4 of the original value, is what I settled
on and ultimatley ended up buying the singles for. Those have yet to arrive, but I'll do some
real-world playtesting soon and follow up :)

## References
- Prof videos, commanders quarters
- Few sites I'd found
- Discord for Mox, person who was helpful

[1]: https://www.mtgsalvation.com/forums/magic-fundamentals/magic-general/324210-what-is-stax
[2]: https://edhrec.com
[3]: https://scryfall.com
[4]: https://archidekt.com/decks/9031947/commander_dino_stompy
[5]: https://archidekt.com/decks/9588316/too_many_heads_more_optimized
[6]: https://archidekt.com/decks/9620434/too_many_heads_affordable
