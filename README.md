# Pong iPxs Collection

[![Icestudio](https://img.shields.io/badge/collection-icestudio-blue.svg)](https://github.com/FPGAwars/icestudio)
![Version](https://img.shields.io/badge/version-v0.1.0-orange.svg)

Icestudio PiXel Stream collection for a game Pong.

## Install

* Download the collection from github in a [Zip format](https://github.com/juanmard/collection-Pong/archive/master.zip).
* Install the collection from _icestudio_: *Tools > Collections > Add*
* Load the collection: *Select > Collection*

## General blocks:
_Control_
  * **CtlPong-Buttons** - Control position of player with buttons.
  * **CtlPong-ADC** - Not defined yet.

_Dynamic:_
  * **DynPon** - Dynamic of the complete Game's Pong.

_Sound:_
  * **SndPong** - A basic sound card of Game's Pong.

_Display:_
  * See next iPxs blocks...

## iPxs Blocks:
_Overlay (static):_
  * **PxsDigit** - Draw a digit in a screen.
  * **PxsPlayer** - Draw a player in a screen.
  * **PxsVerticalPlayers** - Draw two vertical players in a screen.
  * **PxsBall** - Draw a squared ball in a screen.

_Overlay (dynamic):_
  * **PxsNumber** - Draw an increment a decrement single number.
  * **PxsCounter** - Draw an increment counter with two digits.
  * **PxsBigCounter** - Draw an increment counter with four digits.
  * **PxsScoreboard** - Draw a scoreboard for Game's Pong.
  * **PxsPong** - Draw a Game's Pong.
  * **PxsFronton** - Draw a Game's Fronton.
  
_Utils:_
  * **PxsSyncGen** - VGA signal generator.
  * **PxsVGAComp** - VGA component extractor.
  * **PxsVGAEndframe** - VGA end frame signal generator.

_Videogen:_
  * **PxsCourt** - Draw a court tennis background.

## Examples:
* **Example 1** - Draw a tennis court (PxsCourt).
* **Example 2** - Draw a static Overlay block (PxsDigit).
* **Example 3** - Draw a dynamic Overlay block (PxsNumber).
* **Example 4** - Draw a dynamic big number (PxsBigNumber).
* **Example 5** - Test the player (PxsPlayer).
* **Example 6** - Test two players (PxsVerticalPlayers).
* **Example 7** - Test two players with control buttons.
* **Example 8** - Test a ball with control (PxsBall).
* **Example 9** - Test simple dynamic bouncing ball (PxsBall).
* **Example 10** - Test scoreboard (PxsScoreboard).
* **Example 11** - Test sound card (SndPong).
* **Example 12** - Test game Fronton (PxsFronton).
* **Example 13** - Test complete game (PxsPong).
* **Example 14** - Test two games together.

## Authors
* [Juan Manuel Rico](https://github.com/juanmard)
* [Sergio Cuenca](https://github.com/sergicuen)

## License

Licensed under [GPL-2.0](https://opensource.org/licenses/GPL-2.0).
