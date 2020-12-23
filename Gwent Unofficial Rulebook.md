These rules are effective as of **December 10, 2019.**
# Contents <!-- omit in toc -->
- [1. Introduction](#1-introduction)
- [2. Game Concepts](#2-game-concepts)
  - [2.1. General](#21-general)
  - [2.2. The Golden Rules of Gwent](#22-the-golden-rules-of-gwent)
  - [2.3. Start of the Game](#23-start-of-the-game)
  - [2.4. Turns and Rounds](#24-turns-and-rounds)
  - [2.5. Ending the Game](#25-ending-the-game)
  - [2.6. Factions](#26-factions)
  - [2.7. Numbers and Calculations](#27-numbers-and-calculations)
  - [2.8. Cards](#28-cards)
  - [2.9. Objects](#29-objects)
  - [2.10. Abilities](#210-abilities)
  - [2.11. Leader Abilities](#211-leader-abilities)
- [3. Card Types](#3-card-types)
  - [3.1. General](#31-general)
  - [3.2. Units](#32-units)
  - [3.3. Specials](#33-specials)
  - [3.4. Artifacts](#34-artifacts)
  - [3.5. Stratagems](#35-stratagems)
- [4. Zones](#4-zones)
  - [4.1. General.](#41-general)
  - [4.2. Deck](#42-deck)
  - [4.3. Hand](#43-hand)
  - [4.4. Battlefield](#44-battlefield)
  - [4.5. Graveyard](#45-graveyard)
  - [4.6. Banish](#46-banish)
- [5. Abilities and Effects](#5-abilities-and-effects)
  - [5.1. General](#51-general)
  - [5.2. Abilities](#52-abilities)
  - [5.3. Handling Triggered Abilities.](#53-handling-triggered-abilities)
  - [5.4. Effects](#54-effects)
  - [5.5. One-Shot Effects](#55-one-shot-effects)
  - [5.6. Weather Effects](#56-weather-effects)
  - [5.7. Status Effects](#57-status-effects)
- [6. Non-gameplay related](#6-non-gameplay-related)
  - [6.1. General](#61-general)
  - [6.2. Experience](#62-experience)
  - [6.3. Kegs](#63-kegs)
  - [6.4. Gameplay modes](#64-gameplay-modes)
  - [6.5. Ranked and Pro Rank](#65-ranked-and-pro-rank)
  - [6.6. Seasons](#66-seasons)
  - [6.7. Rewards, Currencies and the Reward Book](#67-rewards-currencies-and-the-reward-book)
  - [6.8. Hiding/Unhiding UI](#68-hidingunhiding-ui)

# 1. Introduction

This document is the unofficial collection of rules for the behaviour of Gwent: The Witcher Card Game® client, which governs a standard game of Gwent. It consists of a series of numbered rules. Many of the numbered rules are divided into subrules, and each separate rule and subrule of the game has its own number.

CDPR Gwent development team can overrule any and all of these rules as the original maker of the game.

Changes may have been made to this document since its publication. If you have questions, you can get the answers from us at [r/gwent](https://www.reddit.com/r/gwent/) or [on the official forums](https://forums.cdprojektred.com/index.php?forums/gwent.23/)

#  2. Game Concepts
## 2.1. General
1. Game of Gwent is played between 2 players using the Gwent: The Witcher Card Game client.
2. Each player uses a deck of at least 25 cards, a leader ability and a stratagem. Some of the cards will refer to this as “the starting deck”
3. In constructed play (a way of playing in which each player creates their own deck ahead of time) the provisional cost sum total of all cards in the deck should not exceed the provisional limit of 150 plus the provisional power of a leader ability. Constructed decks may contain up to 2 of any bronze card and up to 1 of any gold card. Cards that can be used in constructed deck are limited to the faction [(see 2.6. Factions)](#26-factions) selected during the process of deck creation and neutral cards.
   1.  A constructed deck should have at least 13 unit cards.
4. In limited play (a way of playing in which each player creates their own deck by selecting the desired cards from a limited choice of cards; currently represented only by arena mode) decks are limited only to the cards selected during the draft. A limited deck may contain as many duplicates of a card as the player has drafted. There is no provisional limit in limited play.
5. A game of gwent is played in 2-3 rounds. 3rd round is played depending on the outcome of the first 2.

## 2.2. The Golden Rules of Gwent
1. If a card text directly contradicts one of these rules, card text takes precedence. The card overrides only the rule that applies to that specific situation.
2. If there are multiple eligible targets for a certain condition that exceed the allowed number for the said condition, targets are chosen at random. Example. If a card states “destroy the highest unit on the battlefield” and there are multiple highest units on the battlefield, the target will be chosen at random. [(on the definition of the highest unit see point 5.1 in 3.2. Units)](#32-units)

## 2.3. Start of the Game
1. At the start of the game each players deck is shuffled and put aside (to the right). Some of the cards will refer to this as “the deck”.
2. After the deck have been shuffled the client determines who goes first by flipping a coin. The player who goes first may be referred to as a blue coin player, his opponent - the red coin player.
3. The blue coin player starts round 1 with a stratagem object in the melee row of the battlefield.
4. Each player draws card up to their starting hand size (currently 10). This is the start of a mulligan phase.
5.  Players can put aside up to 2 cards from their starting hand and replace each of those cards by drawing 1 from the deck. This process is called mulliganning. After player no longer can’t or wishes to replace any more cards the mulligan phase ends. The cards that were set aside are shuffled back into the deck.
    1.  Putting the card aside does not prevent a copy of a card from being drawn from the deck.
    2.  The player who goes first gets one extra mulligan in round 1, allowing him to mulligan up to 3 cards.
6. Should player exit their mulligan phase before their opponent, they should wait for their opponent to exit theirs. Mulligan phase has a time limit of 20 seconds.
7. After both players are done with the mulligan phase the round 1 starts.
8. Blue coin player takes their first turn.

## 2.4. Turns and Rounds
1. Players take their turns to play one after another.
2. Players cannot perform actions outside of their turn.
3. During their turn players can play a card (i.e. only one) from their hand and activate order abilities.
   1.  There are cards and leaders that overrule this. For example Dandelion: Poet allows the player to play a second card from their hand after playing Dandelion: Poet.
   2.  Instead of playing the card on the battlefield player can play the card on the graveyard. This effectively discards a card.
   3.  Start of the turn effects resolve before player gets to act.
4. Players do not draw cards from their deck at the start of their turn.
5. Player’s turn ends when they declare so, take longer than 70 seconds [citation needed] to take their turn or when the client decides there is no more actions for the player to make.
   1. Players can end their turn by pressing and holding end turn button (right side of the screen, in the middle) or their spacebar (PC).
   2. If the turn has ended due to turn timer running out, current selection target and subsequent selection targets are chosen at random.
   3. If the turn has ended due to turn timer running out and the player hasn’t played a card from their hand yet, the player discards a random card.
6. End of the turn effects trigger after the player has ended their turn. [(for more info see point 3. in 5.4. Effects)](#54-effects)
7. If player has ended their turn without taking any actions from the start of it. They pass the round.
   1. A player cannot pass the round if they have taken any action from the start of their turn and should wait for their next turn to pass the round if they want to.
8. If player has played his last card in hand and has no more orders, the player passes the round instead of ending the turn.
9. Once the player has passed the round they cannot perform any actions for that round.
   1.  The effects from their cards resolve as normal as long as the game progresses.
10. The round ends once both players have passed the round.
11. The player with the most points on their side of the battlefield after both players have passed the round and all the end turn effects of the last turn have resolved is considered the winner of that round. (this is marked by half-crown on the ui on the right side of the screen).
    1. If number of points in the same, the round is considered a draw, and both players are the victors.
12. At the end of the round all eligible cards are put from the battlefield into the graveyard, unless a card has an effect that allows it to persist on the battlefield.
13. At the start of the round, with the exception of round 1, both players draw 3 cards from their deck, up to the hand size limit (currently 10). Players enter the mulligan phase once again. Any extra cards that the player could have drawn but couldn’t due to hand size limitations add one extra mulligan, up to a total of 3 extra mulligans, if the player has entered the round with 10 cards.
14. After the mulligan phase, the winner of the last round goes first.
    1.  If the previous round ended in a draw the red coin player goes first.

## 2.5. Ending the Game
1. Once any player has achieved Victory in 2 rounds he is considered the victor of the game and the game ends.
   1. If both players have achieved the victory in 2 rounds at the same due to a draw result of the final round, the game is considered a draw.
2. Player can forfeit the game at any point. This ends the game and gives the other player the victory of the game and up to two round victories.

## 2.6. Factions
1. There are currently 6 Factions in Gwent: Scoia’tael (ST), Skellige (SK), Monsters (MO), Northern Realms (NR), Nilfgard (NG) and Syndicate (SY).
2. A card can belong to one of the factions, be neutral or be shared between syndicate and one of the 5 other faction.
3. A constructed deck can consist only of cards that are a part of the selected faction or neutral cards.

## 2.7. Numbers and Calculations
1. The only numbers the Gwent game uses are integers.
   1. You can’t choose a fractional number, deal fractional damage, gain fractional life, and so on. If a card or ability could generate a fractional number, [that number is rounded up.](https://www.twitch.tv/videos/391330599?t=37m55s)

## 2.8. Cards
1. Cards are used to build a deck for a gwent game.
2. There are 4 card types in gwent: Artifacts, Specials, Stratagems and Units.
   1. Stratagem is not considered a card for the purposes of card interaction. [(see 3.5. Stratagems)](#35-stratagems)
3. Cards may have a primary and secondary category. These can be checked by inspecting a card (right-click on the card, on PC)
   1. Primary categories are usually types or races, such as dwarf, dragon, witcher, alchemy, trap, nature, or spell.
   2. Secondary categories are usually “professions” such as mage, soldier or agent.
4. All cards can be inspected in the client to check base stats of the said card as well as associated glossary terms.

## 2.9. Objects
1. An object is a card or a marker representing a card in any of the zones. [(see 4. Zones)](#4-zones)
2. Some effects put tokens onto the battlefield. A token is a marker used to represent an object that isn’t represented by a card.
   1. If an object is a token it'll be listed after primary and secondary categories, if there are any.
   2. All tokens are considered to have 0 provisions.

## 2.10. Abilities
1. An ability is a characteristic of any object. An object without any text has no abilities
2. Abilities that should resolve at the same time are resolved from left to right, melee row to ranged row
3. Deploy abilities resolve before trigger abilities are activated, unless the card states otherwise.

## 2.11. Leader Abilities
1. Leader abilities are not considered to be a part of the deck
2. Each deck should have exactly one leader ability.
3. Leader ability is represented by the icon next to the leader on the side of the battlefield and cannot be interacted with by the opponent.
4. Leader abilities have either a passive ability, an order ability, or combination of both.
   1. Order abilities can be activated by clicking on the leader.
5. Leader abilities increase the provisional limit of the deck by the number in the yellow hexagon.

# 3. Card Types
## 3.1. General
1. The card types are Artifact, Special, Stratagem and Unit.
2. Card categories are displayed by the icon in the top left corner of the card in a rhombus.
   1. Goblet means it is an artifact card.
   2. Flame means it is a special card.
   3. Flag means it is a stratagem card.
   4. A number means it is a unit card (see 201)
3. The background of the icon in the top left displays the faction alignment of the card.
   1. Purple is Skellige
   2. Green is Scoia’tael
   3. Red is Monsters
   4. Black is Nilfgard
   5. Blue is Northern Realms
   6. Beige/Brown is Neutral
   7. Orange is Syndicate
4. Card may have a primary and secondary category and can be checked by right-clicking the card (PC).
   1. Primary categories are usually types or races, such as dwarf, dragon, witcher, alchemy, trap, nature, or spell.
   2. Secondary categories are usually “professions” such as mage, soldier, agent.
5. Artifact, Special and Unit cards have provision cost in the bottom right.

## 3.2. Units
1. When Unit cards are played they remain on the battlefield.
2. All unit cards have a strength characteristic.
   1. Unit’s base strength is equal to the number in the top left of the card.
   2. Unit’s base strength can always be checked by right-clicking (PC) the card on the battlefield.
3. A unit’s strength is the amount of damage needed to destroy it as well as how many points it contributes the side of the battlefield it is on.
4. Damage dealt to a unit by a source is marked on that unit. If the total damage marked on that unit is greater than or equal to its strength, that creature has been dealt lethal damage and is destroyed.
   1. If the unit’s current strength is below their base value it is displayed in red and the unit is considered damaged.
   2. If the unit’s current strength is above their base value it is displayed in green and the unit is considered boosted.
5. Unit is considered higher than the other unit if its strength value is higher than that of the other unit in the same zone. (see 3. Zones)
   1. Unit is considered highest if there are no unit that are higher than it. There could be multiple highest units at the same time.
6. Unit is considered lower than the other unit if its strength value is lower than that of the other unit in the same zone.
   1. Unit is considered lowest if there are no unit that are lower than it. There could be multiple lowest units at the same time.

## 3.3. Specials
1. When a Special card resolves the actions stated in its rules text are followed. Then it’s put into its owner’s graveyard.
2. Specials can’t enter the battlefield.

## 3.4. Artifacts
1. When artifact cards are played they remain on the battlefield.
2. Artifact cards have no strength and cannot be destroyed by damage.
3. Only abilities that state destroy and artifact or the end of the round can destroy artifacts.
## 3.5. Stratagems
1. A Stratagem can be selected during the deck creation process.
2. A Stratagem is not considered to be a part of the deck.
3. Each deck should have exactly one Stratagem.
4. Stratagems can be acquired like any other card, but is not considered as one by the game.
   1. This is only relevant for cards that care about other cards on the board like The Great Oak (Scoia’tael) and Magne Division (Nilfgard).
5. Blue Coin player starts the game with a Stratagem in the melee row.
6. If a stratagem have not been used during the round, it is banished at the end of the round instead of being moved to the graveyard.

# 4. Zones
## 4.1. General.
1. A zone is a place where objects can be during a game. There are normally five zones: deck, hand, battlefield, graveyard, and banish. Each player has their own deck, hand graveyard and banish. The Battlefield is shared by all players.
2. Public zone are zones in which all players can see the cards’ faces, except for those cards that some rule or effect specifically allow to be face down. Graveyard, battlefield and banish are public zones. Hidden zones are zone in which not all players can be expected to see the cards’ faces. Deck and hand are hidden zones, even if all the cards in one such zone happen to be revealed.
3. If an object would go to a graveyard or a banish from being destroyed it goes to the graveyard or a banish on the side it was destroyed.
4. The order of objects in any zone can’t be changed except when effects or rules allow it.
5. If an object moves between deck, hand and battlefield it retains its characteristics and statuses.
6. If an object moves from any zone to a graveyard or banish, it is effectively reset and has no memory of, or relation to, its previous existence.
##  4.2. Deck
1. When a game begins, each player’s “starting deck” becomes their “deck”.
2. Any player can check the remaining number of cards in any players deck at any time.
3. Players can view cards that remain in their deck. Those cards are shown in random order.
##  4.3. Hand
1. The hand is where a player hold cards that have been drawn. Cards can be put into a player’s hand by other effect as well. At the beginning of the game each player draws a number of cards equal to that player’s starting hand size, currently 10. [(see 2.3. Start of the Game)](#23-start-of-the-game)
2. Each player has a maximum hand size, which is normally 10 cards. If a player were to exceed this number during the round all the extra cards are put in the graveyard. Extra cards that would be drawn during the mulligan phase are not drawn and instead increase the number of available mulligans. Example. If a player with 10 cards in hand were to play Birna Bran, whose ability states: “Deploy: Draw 2 cards, then discard 2 cards”. That player would draw 1 card, put 1 card in the graveyard because the 2nd drawn card would be 11th card in their hand and then forced to discard 2 cards.
3. A player may look at his hand at any time. A player can’t look at the cards in another player’s hand but may count those cards at any time.
## 4.4. Battlefield
1. Most of the area between the players represents the battlefield.
2. Battlefield consists of 4 playable rows: opponent’s ranged row, opponents’ melee row, player’s melee row and player’s ranged row.
3. 2 opponent’s row are considered opponents side of the battlefield and 2 player’s rows are consider player’s side of the battlefield.
4. Artifacts and units can be only played on your side, on one of two rows, unless specified otherwise.
5. Each row can have no more than a total of 9 objects on it. A row that has 9 objects is considered full.
6. Neither player can play artifacts or units of a full row.
## 4.5. Graveyard
1. A player’s graveyard is their discard pile. Any object that’s discarded, destroyed or consumed is put into the graveyard on the side it was, as is any special cards that resolved. Each player’s graveyard starts out empty.
2. Each graveyard is kept in a single face-up pile. A player can examine the cards in any graveyard at any time.
3. If a card would is consumed in a graveyard it enters the banish zone instead of the graveyard.
4. Cards that enter graveyard reset to their base state and lose any boosts, damage taken, statuses or other effects gained before entering the graveyard.
## 4.6. Banish
1. The banish zone is essentially a zone of no return for objects. Some specials and abilities banish an object without any way to return that object to another zone.
2. To banish an object is to put it into the banish zone from whatever zone it’s currently in. A banished card is a card that’s been put into the banish zone.
3. Banish zone cannot be viewed.

# 5. Abilities and Effects
##  5.1. General
## 5.2. Abilities
1. An abilities is a characteristic of any card or token. A card or token without any text has no abilities.
2. A card or token that has a status “locked”, has no abilities until the locked status is removed.
3. “Order” abilities can be activated at any time during the player’s turn, except on the turn the card was played.
   1. Zeal effect overrules this.
4. If an ability requires to select a target or multiple target, source of the ability cannot be selected as an eligible target.
5. All effects need to be acted upon once they are activated. Example playing a card with deploy ability "deal X damage to a unit" without any opponent units on the battlefield will force the player to damage their own units for X damage.
6. If there is no eligible target for the ability, the ability fizzles out.
   1. Certain cards have abilities with consecutive effects, indicated by "[effect] ,then [effect]" structure of the text. If the requirements of the first effect can't be fully met, the ability fizzles out.

## 5.3. Handling Triggered Abilities.
1. Triggered Abilities have a trigger condition and an effect. The are written as “[When/Whenever/At] [trigger condition or event], [effect].” Some ability’s conditions have a key word instead of when/whenever/at statement. Examples include dominance and deploy.
2. Whenever a game event or game state matches a triggered ability’s trigger event, that ability automatically triggers. The ability doesn’t do anything at this point.
   1. Because they aren’t played or activated, triggered abilities can trigger even when it isn’t allowed to play cards and activate abilities.
   2. When a phase or step begins, all abilities that trigger “at the beginning of” that phase or step trigger.
   3. If several abilities would be triggered at the same time they are triggered left to right, melee row to ranged row.
3. Deploy abilities trigger when card or token is played on the battlefield.
   1. Deploy abilities do not trigger when card or token is summoned.
   2. Deploy abilities trigger before other trigger abilities, unless specified otherwise.
4. An ability triggers only once each time its trigger event occurs. However, it can trigger repeatedly if one event contains multiple occurrences. Example: A Vran Warrior has an ability, which trigger condition reads, “Whenever a unit is destroyed during your turn, boost yourself by 1.” If a player plays a card that destroys all allied units, but the vran warrior, vran warrior will boost itself for each unit destroyed.
   2. If ability would trigger in response to an effect. The ability doesn’t trigger until all instances of the effect occur and the ability can still trigger.

## 5.4. Effects
1. An effect is something that happens in the game as a result of a card or ability. When a card, activated ability, or triggered ability resolves, it may create one or more one-shot or status effects. Static abilities may create one or more status effects. Text itself is never an effect.
2. If an effect attempts to do something impossible, it does only as much as possible. Example: If a player is holding only one card, an effect that reads “Discard two cards” causes them to discard only that card.
3. Order of turn end effects is as follows: effects from turn end abilities first, status turn end effects second, and then effects that had counters that reached 0 on this turn. Example: A Villentretenmerth is to the left of a boosted mahakam defender with vitality on the same row. First Villentretenmerth will show 0 on his card, then mahakam defender will boost himself, then Villentretenmerth's counter will be reduced by 1, then mahakam defender will be boosted by vitality, and then Villentretenmerth' "destroy the highest unit" effect will work.

## 5.5. One-Shot Effects
1. A one-shot effect does something just once and doesn’t have a duration. Examples include dealing damage, destroying an object, creating a token, and moving an object from one zone to another.

## 5.6. Weather Effects
1. Certain cards can apply an effect to whole row on the battlefield such as Ragh Nar Roog (Neutral). A counter to the right side of that row will show the remaining duration of the effect, if the effect has duration.
2. A player cannot manually apply negative Weather Effects to their side of the battlefield.
3. There can be only 1 Weather effect on the row.
4. If a Weather effect would be applied on the row that already has a weather effect, the new effect replaces the older visuals, effect and duration.

## 5.7. Status Effects
1. Certain Abilities and cards apply Status effects to units and tokens.
2. Lock removes any card abilities for as long as the card has a lock status effect.
   1. Entering the graveyard removes the lock effect, but this happens after “when enters/moves to graveyard…” effect.
3. Shield prevents a single instance of damage from being applied to the unit possessing shield status effect. It is then removed from the Unit.
4. If a unit is affected by a second poison effect it is destroyed. First poison effect only applies the poison effect and doesn’t do anything else.
5. Vitality status effect boost the unit by 1 at the end of the turn after which it reduces the vitality counter by 1. If vitality counter reaches 0 vitality effect is removed.
6. Bleed status effect damages the unit by 1 at the end of the turn after which it reduces the bleed counter by 1. If bleed counter reaches 0 bleed effect is removed.
   1. Bleed status effect deals damage as if affected unit doesn't have armour, leaving armour unaffected.
7. Bleed and Vitality status effects reduce the counter of each other when applied to the unit already affected by the other equal to the strength of Bleed or Vitality effect. If the strength exceed the counter the effect is then applied with the counter equal to the difference between effect. Example: applying a 5 vitality to a unit with 3 Bleeding, removes Bleeding and applies 2 Vitality to the Unit. Applying 3 Bleeding to a unit with 5 Vitality, removes 3 counters of Vitality and leaves the unit with 2 Vitality.
   1. Bleed and Vitality status effects resolve in their own phase at the end of the turn after other end of the turn effects have resolved.
8. Immunity status effect prevents the unit from being targeted by any cards or abilities.
   1. The card can still be affected by cards and abilities that don’t target it.
9. Counter status effect reduces the counter by 1 every time the assosiated ability is supposed to trigger such as at the end of the turn for abilities that state “after X allied turns”. When the counter goes from 1 to 0 the ability triggers.
   1.  Counter can not be purified.
10. Resilience status effect allows the unit to remain on the board after the round end. At which point the resilience effect is removed and unit loses any boosted strength above the base strength value.
11. Doomed status effect moves the target to the banish zone, when it enters the graveyard.
12. Defender status effect prevents the cards on the same row without defender status from being targeted.

# 6. Non-gameplay related
## 6.1. General
## 6.2. Experience
1. For each completed game player receives experience.
2. Upon reaching certain amounts of experience player increases their level by 1 and receives 1 reward point.
3. Amount of experience player needs to reach next point increases with levels and prestige.
4. If the player would reach level 61, they instead increase their prestige level by 1 and reset their level to 1.
5. Prestige levels have various no-gameplay related bonuses.
6. Prestige levels currently can only be checked by seeing what prestige related contracts have been completed.
## 6.3. Kegs
1. Kegs are a primary way of acquiring cards for the constructed modes of the game.
2. Kegs can be purchased with in-game currency or real life money. Certain kegs can only be purchased with one and not the other.
3. Each non-faction specific keg contains cards from only the specific set.
4. Each faction keg contains card only from the specific faction and can be from any set.
5. There may be kegs in the shop not listed in this part of the ruleset. They usually have description of what they contain.
6. Each keg contains 4 cards of at least common quality and a choice of a card of rare or higher quality. Some cards in the keg might upgrade to a higher quality or become premium.
   1. The choice of card is presented between 3 random cards, that satisfy the limitations of a keg. All cards in the choice are of the same quality.
7. If a player hasn't receive a card of Epic quality in 19 kegs, he'll receive at least one in the 20th keg. If a player hasn't receive a card of Legendary quality in 39 kegs he'll receive at least one in the 40th keg. This is referred to as Pity Timer.
   1. Each keg type tracks the pity timer on its own. Opening an epic or legendary card in one type of a keg does not reset the pity timer of the other keg types.
   2. Pity timer affects only non-premium base and expansion kegs.[citation needed]

## 6.4. Gameplay modes
1. Gwent client currently supports 5 gameplay modes: Seasonal, Ranked, Unranked, Arena and Training.
   1. Gameplay modes under Play section of the main menu are Seasonal, Ranked, Unranked and Training modes and are constructed gameplay modes.
   2. Arena is a draft gameplay mode.
2. Ranked mode is accessed by selecting Classic Mode under Play section of the main menu and unchecking “Unranked” check box. In ranked mode players are matched based on their rank.
3. Unranked Mode is accessed by selecting classic mode under play section of the main menu and checking “Unranked” check box.
   1. Unranked mode is accessible only after reaching rank 25. Author’s note: New/starting players should stick to ranked as unranked is worse experience for starting players due to skill and card collection gaps.
4. Seasonal mode is accessed by selecting seasonal mode under play section of the main menu. Seasonal mode has additional gameplay rules based on the season.
5. Training mode is accessed by selecting training mode under play section of the main menu. Training mode is the only mode where people can play against AI. AI uses Arachas Queen deathwish-consume deck. Players gain no rewards or account progression by playing in this mode.
6. Arena mode can be accessed by selecting Arena in the main menu of the game. This is the only mode with entrance fee. Entrance fee is 150 ore or 1 arena ticket.
   1. Players start their “run” with making their deck by selecting a leader from a choice of 3 random leaders and then selecting a card from a choice of 4 random cards 26 times.
   2. Players are matched based on their wins and losses of their current run.
   3. Player’s run ends at 9 wins, 3 losses or if player decides to concede the run. At the end of the run player receives various rewards based on their performance. Rewards include kegs, currencies and cards.
   4. Occasional seasonal effects may modify the gameplay rules of the Arena or limit the drafting card pools.
   5. Players do not receive crowns or daily quest progress during Arena matches.

## 6.5. Ranked and Pro Rank
1. During Ranked Progression players are matched against each other based on their rank.
   1. Players start from rank 30 and progress towards rank 1. Ranks are split into 5 pieces — if player wins a match, they get a piece of a stained glass avatar, if they lose — they lose a piece. Winning three or more matches in a row grants the player an additional piece of the avatar. Once the player has all 5 pieces, they unlock that avatar and progress to the next rank.
   2. For Ranks 30-26, dropping down a rank isn’t possible.
   3. For Ranks 25-15, player can only drop down a rank if they lose twice in a row.
   4. For Ranks 14-8, there are no special conditions — the progression follows a linear pattern.
   5. For Ranks 7-1, there’s a linear pattern of progression, however, win streaks no longer give the player two pieces of the avatar.
2. Starting from Rank 25 faction MMR becomes available and matches start affecting player’s Ranked score. This is only important for the Players’ Ladder and Pro Rank position.
   1. Faction MMR is Players performance with that faction.
   2. Players position on the Ladder or Pro Rank is based on the sum of 4 highest faction MMRs.
   3. Faction MMR contributes 0% to the sum at the start of the season and after 25 games 100% of it.
   4. Faction MMR is capped at 2400 outside of Pro Rank.
3. Players that would reach Rank 0 are instead placed into Pro Rank.
   1. Players cannot drop from Pro Rank mid season.
4. At the end of the season players above rank 25 are demoted.
   1. Rank 25-21 are demoted to Rank 25.
   2. Rank 20-1 are demoted 4 Ranks.
   3. Players from Pro Rank are demoted to Rank 5 unless they are in the top 500 of Pro Rank.

## 6.6. Seasons
1. There are 12 seasons in Gwent, roughly related to months in the calendar.
2. The seasons are:
    | Month     | Season                  |
    | :-------- | :---------------------- |
    | January   | Season of the Wolf      |
    | February  | Season of Love          |
    | March     | Season of the Bear      |
    | April     | Season of the Elf       |
    | May       | Season of the Viper     |
    | June      | Season of Magic         |
    | July      | Season of the Griffin   |
    | August    | Season of the Draconid  |
    | September | Season of the Dryad     |
    | October   | Season of the Cat       |
    | November  | Season of Mahakam       |
    | December  | Season of the Wild Hunt |
3. Seasons end a few days before the calendar month does and last until next Season.
4. Seasons influence the seasonal mode and seasonal reward trees.
5. Ladders reset at the end of the season and end of the season rewards are awarded.

## 6.7. Rewards, Currencies and the Reward Book
1. There are 4 currencies in the Gwent: Ore, Scraps, Meteorite Powder and Reward Points (RP).
   1. Ore is used to purchase most types of kegs and enter into Arena.
   2. Scraps are used to craft cards and purchase Premium Kegs.
   3. Meteorite Powder is used to craft premium versions of the cards and purchase various cosmetic options such as Boards.
   4. Reward Points are used to unlock rewards in the Reward Book.
2. Players receive daily rewards based on the number of rounds won during that day.
   1. Players may receive 15 Ore, 15 Scraps, 15 Meteorite Powder or a Card for 2, 4, 10, 14, 22, 26, 30, 34, 38, 46 and every 4 round wins after that.
   2. Players receive 2 RP for 6 round wins, 2 RP for 18 round wins, 1 RP for 42 round wins and 1 RP for every 24 round win after that.
   3. Daily progress is reset at midnight GMT/8 PM EST/5PM PST.
   4. Round wins can be referred to as crowns (as two rounds won form a crown).
   5. Crowns are not awarded during arena matches.
3. Players receive 1 RP every time they level-up.
4. After each match players can GG their opponent this will give their opponent 5 Ore, Scraps or Meteorite Powder.
5. If player have not received a daily quest for that day yet, they’ll receive a daily quest day on log-in.
   1. Daily quests reward 40 Ore, 60 Ore, 1 RP or 2 RP depending on the quest.
   2. A quest can be rerolled once a day into a different quest.
   3. A total of 3 quests can be “saved up”. It is possible to have similar quests at the same time.
   4. Daily quests do not gain progress during Arena Matches
6. At the end of the season players receive RP based on their Rank. 
   1. Rank 30-26 receive 5 RP.
   2. Rank 26-15 receive 7 RP.
   3. Rank 14-8 receive 10 RP.
   4. Rank 7-1 receive 15 RP.
   5. Pro Rank receive 25 RP.
7. To unlock rewards in the Reward Book players must spend RP on the specific node or unlock all the nodes, if the reward is associated with the full tree.
   1. Players can’t unlock nodes not connect to the already unlocked node.
   2. A note with a quest is not considered unlocked until the quest is completed.
   3. Seasonal Reward trees are rotating based on the season, and keep their progress from year to year.
   4. Yearly Reward trees are not rotating and are not removed at the end of their respective year.
8. Contracts are long term tasks/achievements that award RP, cosmetic rewards and various non-gameplay related bonuses based on the Prestige level.
9. On the first login after the daily reset the player will receive a daily log-in reward.
   1. Daily rewards are as follows:
        | Day  | Reward                |
        | :--- | :-------------------- |
        | 1    | 30 Scraps             |
        | 2    | 1 Basic Keg           |
        | 3    | 1 Reward Point        |
        | 5    | 25 Ore                |
        | 6    | 30 Scraps             |
        | 7    | A random Premium Card |
   3. On the 8th day the daily reward progression resets and the player will receive the rewards of the day 1.
   4. Daily rewards do not stack and can be received only once per day.
   5. Daily reward progression does not reset on skipping/missing a daily log-in.

## 6.8. Hiding/Unhiding UI
1. Certain UI features can be hidden or unhidden.
2. Clicking on the player’s portrait during match switches between hiding and unhiding name and title.
3. Clicking on the Battlefield point counter switches between hiding and unhiding row point counters.
4. The change of Visibility does not carry over between matches.
