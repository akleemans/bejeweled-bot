bejeweled-bot
==============

Plays an automated game of Bejeweled.

![](https://raw.github.com/captainfox/bejeweled-bot/master/playing.png)

## Requirements

- [Autopy](http://www.autopy.org/) (OS independent. Windows installers available)

## Anchor
The game is automatically detected by its border colour, as long as it is in the following range:

- Horizontally: 1/3
- Vertically: 1/2

![](https://raw.github.com/captainfox/bejeweled-bot/master/screen.png)

The bot starts playing from the "Play now" screen, and will start the game itself from then on.


## "Algorithm"
There's only one rule: If a possible move has been found, the program will try to do it.
The algorithm is really simple/stupid and _not_ optimized in any way.

Here, it would drag down the matching yellow gem:

![](https://raw.github.com/captainfox/bejeweled-bot/master/example.png)

Still, it should get 400'000 - 600'000 points on average, more if you'll use Phoenix or another power-up.


## Demo

[![](https://raw.github.com/captainfox/bejeweled-bot/master/1million.png)](http://www.youtube.com/watch?v=jUvYuqbRO-I)
