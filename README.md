bejeweled-bot
==============

Plays an automated game of Bejeweled. Be sure to read the _CAUTION_ section below before using.

![](https://raw.github.com/captainfox/bejeweled-bot/master/playing.png)

## 1. Dependencies

- [autopy](http://www.autopy.org/) - used for accessing mouse/screen (OS independent. Windows installers available)
- [pygame](http://www.pygame.org/) - used for displaying recognized gems

## 2. Anchor
The game is automatically detected by its border colour, as long as the border of the game is in the following range:

- Horizontally: 1/3 of screen width
- Vertically: 1/2 of screen height

![](https://raw.github.com/captainfox/bejeweled-bot/master/screen.png)

The bot starts playing from the "Play now" screen, and will start the game itself from then on. Don't move the game after you started the bot or no gems will be recognized.


## 3. "Algorithm"
There's only one rule: If a possible move has been found, the program will try to do it.
The algorithm is really simple/stupid and _not_ optimized in any way.

Here, it would drag down the matching yellow gem:

![](https://raw.github.com/captainfox/bejeweled-bot/master/example.png)

Still, it should get somewhat around 300'000 - 600'000 points on average, more if you use Phoenix or another power-up.


## 4. Demo

[![](https://raw.github.com/captainfox/bejeweled-bot/master/1million.png)](http://www.youtube.com/watch?v=jUvYuqbRO-I)

## CAUTION

Use at your own risk. Be aware that your mouse **will not be controllable** while the game is running!
The program is provided "as is" without warranty of any kind.

Normally the end of the game should be recognized.
There are 2 fallbacks if the end of the game is not recognized properly:

* The bot will stop automatically after 75 seconds (which should be enough in regular mode. You might tweak that when using sepcial gems.)
* The bot will stop when you scroll down and big parts of the recognized area are white.

