# Uno Extreme mod
Uno Extreme mod for tabletop simulator

Over 2000 subscribers and a 5 star rating

In the classic game of uno a player may need to draw a card when they cannot play on their turn. In this 'extreme' variant the player must instead press a button and receive a random amount of cards that are expelled from a card launcher device.

## Approach
Scripted in Lua using Atom IDE

Machine object created in Blender

#### Stats
I have a tested a real version of this game to analyse how often cards are expelled.
These results are based on 800 button presses and these statistics have been coded into the game. 

Players are most likely to get cards on a second button press.

The amount of cards players are dealt ranged from 0 to 13.

The average amount of cards expelled are fairly even across the board except for any player unlucky enough to reach five button presses who will likely get more than average.

| Presses since cards*  | % times cards expelled| % cumulative | Avg cards expelled |
| ----------------------| ----------------------|--------------|--------------------|
| 1                     | 17.96%                | 17.96%       | 4.66               |
| 2                     | 40.87%                | 58.82%       | 5.39               |
| 3                     | 24.15%                | 82.97%       | 4.72               |
| 4                     | 9.29%                 | 92.26%       | 5.07               |
| 5                     | 7.74%                 | 100.00%      | 7.20               |

\* Cards are not expelled on every button press. This data is the amount of times the button has been pressed since the last time cards were expelled.


## How to play
Tabletop Simulator on Steam is required

To play, subscribe to the mod then start Tabletop Simulator

[You can find the mod here](https://steamcommunity.com/sharedfiles/filedetails/?id=2261802618)

![A screenshot of the mod. A clunky red machine sits in the middle of a table with a playing card on top. Next to it is a spread of other cards from the game. On the left is a button that is labeled Deal Cards. ](https://github.com/ruvans/tts-uno-extreme/blob/master/unoExtreme.png?raw=tru)
