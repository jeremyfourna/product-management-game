# Game configuration

* From 2 to 10 players
* From 7 to 77 years old
* Prior software development knowlegde is not mandatory

# How to win

At the end of the release(s), the player with the most points wins.

## Equality

If players have the same number of points at the end of the game/release, you can decide the winner by following the rules below:

1. The player who has released more features wins
2. The player who has the highest `Team Spirit`
3. The player who released the feature with the highest `Estimation for development`

If players are still equals after that... each player rolls a die, the one with the highest score wins.

Repeat until one player wins.

# Game length

Up to 4 releases.
1 release equals 13 turns (weeks) for each player.

# Setup the game

Place the time marker on week n°1 on the release calendar.

## shuffle the cards

You need to shuffle the following decks of cards:

* Actions
* Features

## Character selection

Each player roll a die. Player select in order the character they wish to incarnate.

### Example

Player A rolls a die... 4. Player B rolls a die... 3. Player C rolls a die... 6.

Player will select their caracters in order

1. Player C select CEO
2. Player A select Developer
3. Player B select Product Manager

## Cards distribution

* Distribute to each player 3 cards `Action`
* Distribute to each player 5 carts `Feature`
  * Player must keep at least 1 card `Feature` to build during the release

## Setup your team

Each player gets at the start of the game:

* 4 developers
* 1 QA

On your `Team Spirit` scale put the marker on the square `N` for neutral.

# Game turn

One turn equals one week in the release.

During a turn each player will plays his/her hand. Player who rolled the highest die during the player selection will start, then player on the left plays.

## Player's turn

During a player's turn we will have the following phases:

1. Player draw an `Action` or a `Feature` card
2. Opponents can mess with the current player by playing `Action`cards. Opponent on the left of the current player start first then the one on his/her left continue until all opponents have played
  * During this phase the player can counters the `Action` cards played by the Opponents if he/she have `Nope` cards in his/her hand
3. Player can, draw a new `Feature` card OR play his/her `Action` cards

When both phases have been played, the player's turn is over. It is now at the player on his/her left to play his/her turn.

## End of the week

Advance features completion
Adjust Team Spirit if devs have nothing to do

# Characters

Each player incarnate a `Character`, each `Character` has its own set of advantages and disadvantages.

## CEO - Chief Executive Officer

Only 1 player can incarnate the CEO.

Unique skill: 1 time per release, the CEO can remove all features requested from one customer. During the rest of the game the features from this customer can not build from any player.

Advantages: None

Disadvantage: The CEO must build all the `Feature` cards that he/she draw.

## VPP - Vice President of Product

Only 1 player can incarnate the VPP.

Unique skill: 1 time per release, the VPP define for each player the order in which the player must build their features. Example: If a player has 3 features to build for the release (Feature A, B and C), the VPP can decide that feature C must be build first, then feature A and then feature B. If the player do not respect this order, he/she loose the game.

Advantages: None

Disadvantage: ???

## CTO - Chief Technical Officer

Only 1 player can incarnate the CTO.

Unique skill: None

Advantages:

* The time needed to complete the `Technical Specification` for a feature is halved
* When a `Developer` or a `QA` is send to formation, the CTO can send 1 more `Developer` or `QA` to formation

Disadvantage: ???

## Software Developer

The Software Developer can be incarnated by an unlimited number of players.

Unique skill: None

Advantages: Start with one more `Developer`.

Disadvantage: The time needed to complete the`Functional Specification` for a feature is doubled.

## PM - Product Manager

The PM can be incarnated by an unlimited number of players.

Unique skill: None

Advantages:

Disadvantage: When the PM wants to counter an `Action` card played by the CEO, VPP or CTO, the player must roll a die, if the result is even (2, 4 or 6), the counter is effective. If the roll is odd (1, 3 or 5) the counter has failed.

## QA - Quality Assurance

The QA can be incarnated by an unlimited number of players.

Unique skill: None

Advantages:

Disadvantage: ???

# Cards

## Flue infection

## Team event

## No internet

## Increase estimation

## Decrease estimation

## Improve team spirit

## Worsen team spirit

## Customer strategic change

## Crunch mode

## Steal a developer

## Hire new developer

## Hire new QA

## Design sprint

## Be agile!

## Disagree

## The CEO disagree

## Espionage

## New competitor in town

## Bug found during QA


# Features

A `Feature` has the following properties:

* Name
* Description
* Customer requesting the feature
* Number of MD (Man Days) to do the `Functional Specification`
  * Can only be completed by the player
* Number of MD to do the `Technical Specification`
  * Can only be completed by 1 developer
* Number of MD to do the `Development`
  * Can be completed by the whole development team
* Number of MD to do the `QA`
  * Can only be completed by the QA in the team
* Points that this feature will bring to the player

Example:

Property | Value
--- | ---
Name | Split Delivery
Description | Customer can ask to deliver their order to multiple addresses
Customer | ACME
Functional Specification | 10 MD
Technical Specification | 10 MD
Development | 90 MD
QA | 10 MD
Points | 70



