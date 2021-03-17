# Marvel Heroic Roleplaying
Character sheet(s) for Marvel Heroic Roleplaying. 

To use this character sheet, be sure to disable Legacy Sanitation under Character Sheet Template in Settings.

To see an example of how it all works, check out the Roll20 game at: https://app.roll20.net/join/9344152/nM9tKQ

## The Dice Pool

The dice pool controls are at the top of the character sheets. They are inspired in part by the DiceStream app that was once available in Google Hangouts. 

The controls on the left are the dice pool itself and the buttons to manually add, remove, roll, and clear dice.

To roll any single die, click on the picture of that die. That die will be rolled in the Roll20 Chat window.

To add dice to the pool, click the roller wheel below the picture of a die to increase to counter below the chosen die type.

Once you've selected how many of each type of die you want in your pool, press the `ROLL` button. Your dice will be rolled in the Roll20 Chat window.

There is also a `CLEAR` button to clear your old pool, or clear the pool if you need to start fresh. The `CLEAR` button has pop up `Confirm` and `Cancel` buttons to help avoid inadvertently erasing a nice large dice pool you have just lovingly created.

## XP Counter

There is an `XP` counter on the upper right to use for tracking experience gained during play.

## The Dice Pool Actions

The controls on the right are for dice pool manipulation according to the Cortex System rules. The radio buttons in the top row are selected first, then the appropriate action button is clicked.

NOTE: These dice pool functions check to confirm that you have the right dice already in your pool to take these actions. If you lack the appropriate dice for the action to complete, or you try to take an action against a die type that it is not defined for, the button will do nothing.
The buttons are

`2X` - Doubles a die of the selected size. This function should only be used when there is at least one of the selected dice in the pool.

`UP` - Steps Up a die of the selected size. This function should only be used when there is at least one of the selected dice in the pool. Stepping up a d12 results in a d12 being replaced with a d12 and a d6.

`DN` - Steps Down a die of the selected size. This function should only be used when there is at least one of the selected dice in the pool. Stepping down a d4 removes it from the pool.

`/2` - Split a Die into Two Smaller Dice. This function removes a die and replaces it with 2 dice one step down. Using this on a d4 just removes it from the pool.

`/3` - Split a Die into Three Smaller Dice. This function removes a die and replaces it with 3 dice two steps down. Using this on a d4 or d6 just removes it from the pool.

`/4` - Split a Die into Four Smaller Dice. This function removes a die and replaces it with 4 dice three steps down. Using this on a d4, d6, or d8 just removes it from the pool.

`2->1` - Combine Two Dice Into a Larger Die. This function removes 2 dice and replaces them with 1 die one step up. Using this on a pair of d12s just removes them from the pool. 

The character sheets themselves have additional interfaces to the dice pool roller that are explained in their handouts.

Also, in the event that you just want to use ROLL20 and this dice pool roller and not the specific character sheets, there is a `Dice Pool Roller Only` button available for just that scenario. I use a `Dice Pool Roller Only` page as a "character sheet" for my Doom Pool.

# The Character Sheets

The MHRP Character Sheet has four "pages": `Build/Create`, `Classic`, `Dice Pool Roller Only`, and `NPC`.

## The `Build/Create` Page

The `Build/Create` page allows the player to both build their character and also to play from this sheet.

When you create the character, you enter all the Distinctions, Powers, SFX, Limits, Specialties, Milestones for your character, and set all of the die sizes for your Affiliations, Powers, and Specialties. You can have up to 5 dice (of the same type) in a trait. This is to accomodate MOBs, Large Scale Threats (LSTs), and PCs with mob-like or other multi-die powers.

For Powers, SFX and Limits, and Specialties, use the `+Add` button to add new powers, etc. depending on how many the character needs. The `Modify` button will allow you to delete unneeded rows, or to reorder existing rows.

I have not integrated temporary traits (Stress, Complications, Stunts, etc.) into the sheet. We are using Roll20 card decks to implement these. See **Plot Points and Temporary Trait Dice** below for more details.

When using this page for play, clicking the `USE` button adds a trait die to the dice pool roller above the sheet. The only exception is the Distinctions. Since they can be taken as either a d8 or a d4 (to earn a PP), they have a `d8` and `d4` button to select which you want to add to your pool.

Once you've selected all of your dice, you can edit your dice pool to implement any SFX or Limits (stepping up or down, doubling dice, etc.) either manually or using the Dice Pool Options tool, and then manually add any external Complication, Stress, Scene Distinction, Asset, Resource, Push, or Stunt dice.

At the top of the sheet there are 4 check boxes. These hide or reveal the 3 Power Sets and the Milestones. This is to simplify the appearance for characters that only have 1 or 2 Power Sets. Often, when running one-shot games we do not use Milestones, so I made them hide-able as well to give people more options when managing limited screen space in Roll20.

**Note:** These check boxes will also hide the Power Sets and Milestones on the `Classic` page.

## The `Classic` Page

The `Classic` page configures the character sheet to emulate the look and feel of the original hero datafiles from the MHR rulebooks. This page is designed for play, whiel edits are made form the `Build/Create` page.

## The `Dice Pool Roller Only` Page

The `Dice Pool Roller Only` page has no associated character sheet, just the dice controls at the top. It is low profile from a screen usage perspective, and can be used for other dice pool driven games that do not have existing Roll20 character sheets yet. This page can also be used as the Doom Pool for MHR games, which requires an independent dice pool and dice management but no character sheet.

## The `NPC` Page

The `NPC` page works the same as the `Build/Create` page, and is a legacy function to support early adopters who have already built a bunch of NPCs with a previous version. Originally, I did not allow multiple dice in the traits, which are required for the Affiliations of Large Scale Threats and Mob NPCs. I had added a multiplier entry in front of the Affiliation dice to allow these. This is no longer necessary, since the standard sheet now allows up to 5 dice in a trait, but the `NPC` page is included so NPC characters built previously do not require conversion to use. Edits to the `NPC` page will modify the `Build/Create` page entries, and should not be used if the `Build/Create` or `Classic` pages are to be used in play.

# Plot Points and Temporary Trait Dice (Stress, Complications, etc.)

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
