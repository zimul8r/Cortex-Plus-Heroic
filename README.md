# CortexPrime
Character sheet(s) for Cortex Prime focusing on a Cortex Plus Marvel Heroic-compatible implementation. To see an example of how it all works, check out the Roll20 game at: https://app.roll20.net/join/9344152/nM9tKQ

The dice pool controls are at the top of the character sheets. They are inspired in part by the DiceStream app that was once available in Google Hangouts. 
Buttons on the sheet add dice to your pool, or you can add them in the roller itself.
The d20 button in the roller rolls your dice into the chat.
The sheet requires the ChatSetAttr API script to function properly.

The Dice Pool

The controls on the left are the dice pool itself and the buttons to manually add, remove, roll, and clear dice.

To roll any single die, click on the picture of that die. That die will be rolled in the Roll20 Chat window.

To add dice to the pool, click the roller wheel below the picture of a die to increase to counter below the chosen die type.

Once you've selected how many of each type of die you want in your pool, press the ROLL button. Your dice will be rolled in the Roll20 Chat window.

There is also a CLEAR button to clear your old pool, or clear the pool if you need to start fresh. The CLEAR button has a pop up "Are you sure" window to avoid inadvertently erasing a nice large dice pool you have just lovingly created.

The Dice Pool Actions

The controls on the right are for dice pool manipulation according to the Cortex System rules. The radio buttons in the top row are selected first, then the appropriate action button is clicked.

NOTE: These dice pool functions do not check to confirm that you have the right dice already in your pool to take these actions. As such, it is up to you to make sure you don't click an action button when there are not enough dice of the selected size in the pool to complete that action. Doing so can produce "spurious" results.
The buttons are

2X - Doubles a die of the selected size. This function should only be used when there is at least one of the selected dice in the pool.

UP - Steps Up a die of the selected size. This function should only be used when there is at least one of the selected dice in the pool. Stepping up a d12 results in a d12 being replaced with a d12 and a d6.

DN - Steps Down a die of the selected size. This function should only be used when there is at least one of the selected dice in the pool. Stepping down a d4 removes it from the pool.

/2 - Split a Die into Two Smaller Dice. This function removes a die and replaces it with 2 dice one step down. Using this on a d4 just removes it from the pool.

/3 - Split a Die into Three Smaller Dice. This function removes a die and replaces it with 3 dice two steps down. Using this on a d4 or d6 just removes it from the pool.

/4 - Split a Die into Four Smaller Dice. This function removes a die and replaces it with 4 dice three steps down. Using this on a d4, d6, or d8 just removes it from the pool.

2->1 - Combine Two Dice Into a Larger Die. This function removes 2 dice and replaces them with 1 die one step up. Using this on a pair of d12s just removes them from the pool. 



The character sheets themselves have additional interfaces to the dice pool roller that are explained in their handouts.

Also, in the event that you just want to use ROLL20 and this dice pool roller and not the specific character sheets, there is a Dice Pool Roller Only button available for just that scenario. I use a Dice Pool Roller Only as a "character sheet" for my Doom Pool.

The Character Sheet

The MHRP Character Sheet allows the player to step through their character details, selecting dice that are relevant to their current action, then roll their dice pool.
When you create the character, you enter all the Distinctions, Powers, SFX, Limits, Specialties, Milestones for your character, and set all of the die sizes for your Affiliations, Powers, and Specialties.

To build a dice pool, clicking the "ADD" button adds a trait die to the dice pool roller above the sheet. The only exception is the Distinctions. Since they can be taken as either a d8 or a d4 (to earn a PP), they have a d8 and d4 picture button to select which you want to add to your pool.

Once you've selected all of your dice, you can manually edit your dice pool to implement any SFX or Limits (stepping up or down, doubling dice, etc.), or to add any external Complication, Stress, Scene Distinction, Asset, Resource, Push, or Stunt dice.

At the top of the sheet there are 4 check boxes. These hide or reveal the 3 Power Sets and the Milestones. This is to simplify the appearance for characters that only have 1 or 2 Power Sets. Often, when running one-shot games we do not use Milestones, so I made them hide-able as well to give people more options when managing limited screen space in Roll20.

For Powers, SFX and Limits, and Specialties, only the first row exists on a new blank character sheet. The "+Add" button allows you to add new rows of powers, etc. depending on how many the character needs. The "Modify" button will allow you to delete unneeded rows, or to reorder existing rows (except for the first).

Do not confuse the "+Add" button for adding rows with the "ADD" button for adding a trait's die to your dice pool.

I have not integrated Plot Points, nor temporary traits (Stress, Complications, Stunts, etc.) into the sheet. We are using Roll20 card decks to implement these. See the "Plot Points and Temporary Trait Dice" handout for more details.

In addition to the character sheet and the dice roller only sheet, there is an NPC sheet button. This uses all the same conventions, but I have added a multiplier entry in front of the Affiliation dice. This allows for NPC mob or LST dice. For example, the Copy of Nebula's Mercs (NPC MOB) is a 4d8 mob, which you can see in their Solo affiliation if you select the NPC Sheet button at the top when viewing them.

Plot Points and Temporary Trait Dice (Stress, Complications, etc.)

In my games, we don't use the character sheets to manage plot points and temporary traits like stress. We do these with the Roll20 card decks. We use 2 decks.

The first is our Plot Points deck.

The cards have the Avengers logo front and back and the deck is an infinite supply of them.

To take a PP, simply pull a card from the deck and drop it on your player avatar/name at the bottom of the Roll20 screen.

Above each player's avatar you will see a copy of the PP card image and the number of PP they currently have.

To spend a PP, click on the card image above your avatar to open the window, drag a PP card onto the virtual table top, then click the card image again to close the PP window.

Because we used cards for this application, if the Watcher wants to retain control of when PP are taken, they can change the permissions on the deck to only allow the GM to deal cards, i.e. hand out PP.

The second is our dice deck.

This deck contains cards for all of the dice that represent temporary traits that come and go during a game session. The image files for these cards are in this file repository. 
(We did not create Distinction cards for Scene Distinctions because we use a simple text box to convey those.)

To add one to the game, hover over the deck and click "Choose". This opens a window of all the cards and allows the user to drag one onto the virtual tabletop.

Unlike the PP cards, which are just images, these cards are implmeneted as tokens, so they can be given names and show those names on a nameplate.

In our game, I have enabled the permission to allow players to pull those cards and to change their names so that they can name their assets, complications, etc.

The cards are color coded by type and include some non-MHRP types (like Hero dice) for use in other Cortex Classic/Plus/Prime games.

A common problem we have experienced is forgetting to use stress, complications, etc. These cards are brightly colored to draw attention to themselves so players remember to use those dice in their pools. 
