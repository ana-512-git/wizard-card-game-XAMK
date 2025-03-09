# Merlin's Demon War
A desktop card game, where you have to defeat an enemy using attack cards, which I developed as an assignment for the XAMK Intro to Game Creation course.

## Description
In this fast-paced, card-based duel of magic and strategy, you step into the robes of a powerful wizard, battling relentless demons in a test of wit and resourcefulness. Your deck holds the key to survival—drag and drop spell cards to unleash devastating attacks, cast protective wards, or restore your dwindling health. Each move comes at a cost, forcing you to balance aggression with patience. Will you press the attack or bide your time, gathering resources for a game-changing play? Every choice shapes your fate in this high-stakes battle of sorcery and survival!

## How to play
### Controls
Left click and hold to pick up and move a card from the dealt deck. The player's deck is the one on the left, with its cards facing upwards.

![alt text](https://github.com/ana-512-git/wizard-card-game-XAMK/blob/main/readme-media/gameplay.png)

![alt text](https://github.com/ana-512-git/wizard-card-game-XAMK/blob/main/readme-media/attack.png)

### Gameplay
#### The cards
The cards in this game look something like this:

![alt text](https://github.com/ana-512-git/wizard-card-game-XAMK/blob/main/readme-media/card-types.png)

As you can see, they have different frame colors, numbers in the corners and a short description. The frame colors tell you which player they should be used on: a card with a green frame is a perk, and should be used on the player directly, while a red one is an attack, which damages the enemy. The number in the upper left corner shows the cost of the card, and the one on the right shows the attack damage. To make the game more intuitive, the cards also have a short description in the bottom text box.

#### In-game currency
On the left side of the screen, you'll be able to see the amount of coins you currently have. You earn one coin per round you survive, therefore, if you want to save up for a more powerful attack, you can use the "Skip Turn" button, right below your character's card.

![alt text](https://github.com/ana-512-git/wizard-card-game-XAMK/blob/main/readme-media/coins-and-skip.png)

#### Burning cards
If you're not happy with the cards you were dealt, you can choose to burn a card in order to be dealt another one. You can burn a maximum of one card per round, which will automatically skip your turn. To burn a card, drag and drop it on the "Burn Card" area, until it looks like this:

![alt text](https://github.com/ana-512-git/wizard-card-game-XAMK/blob/main/readme-media/burning-card.png)

#### Health
You can check how much health you or your enemy have by looking at the health indicator on the character cards, situated in the top-left corner.

![alt text](https://github.com/ana-512-git/wizard-card-game-XAMK/blob/main/readme-media/character-health.png)

#### Winning the game
The game goes on until the player loses. After that, you will be able to see how many enemies you've killed and the score you had.

## Tech stack
+ C# for game logic and scripts
+ Unity

## Installation
The game was made for Windows (a Linux/Mac option is still underway). To play, clone the repo locally, then go to the "Build" folder, find the .exe file and run it. That's it, enjoy!


