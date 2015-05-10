# Ninja Quest

## About

The idea started with optional Lab 15 of [edX UT.6.02x Embedded Systems - Shape the World](https://courses.edx.org/courses/UTAustinX/UT.6.02x/1T2015/info) course. However it overgrows the lab in several ways.

First of all, the original lab was intended as simple implementation of one of several 80's 8-bit games. Though my idea started with Mario, it evolved quite a bit.

Second, I spent quite some time on studying the background materials, the datasheets (the original library for the display totally ignored some stuff, etc.), made custom sprites... All of it took me some time (and most possibly will take me some more time before I'm "done") and I missed the regular deadlines for this optional lab.

Third, I'm thinking about adding some online features, which will break the original requirements in several ways. First, the C3100 wi-fi boosterpack was optional for the course (and will stay optional for this game) and wasn't used in the gamesystem at all, second the pin configuration on the original game system didn't allow for add of the boosterpack, so some pins will most probably be shifted around.

## Theme

You're a shinobi, a member of secretive ninja clan. You've got your mission. And quite some enemies to pass to fulfill it.

## Gameplay

The original idea evolved from Mario, so it's essentially a platformer. A special kind. It should be fast, action-packed, with lots of jumping, multi-jumping, wall climbing and of course throwing shurikens and stuff. A bit like Mario meets Liero.

The levels are generated progressively on fly as well as enemies and about everything. Providing the same seed (game number) will provide the same gameplay, so you can compete with others. The online features are centered around this idea.

## Graphics

As good as 84x48 monochromatic display allows. :)

## State

The game is still WIP, files in the repo right now are placeholders and represent the initial state the lab came in. Those files are licenced as noted in their respective headers (essentially MIT licence, but I'm not a lawyer and all that jazz).

Initial version of this game should appear in coming weeks including schematics etc. There's still quite some work to do on it and there's not yet much to see.

If you trampled on this page by accident and feel interested, you should visit the [course kit page](http://users.ece.utexas.edu/~valvano/edX/worldwide.html) to get the right parts. Don't forget the Nokia LCD (I got mine cheap out of [DealExtreme](http://www.dx.com/p/arduino-1-6-lcd-display-screen-for-nokia-5110-red-silver-140226)), the stereo jack port (wasn't in my shopping cart for some obscure reason), some wiring (got myself a 24G wire and cut it into 5-20cm pieces) and if you wanna try the online features, you'll need the C3100 as well.

## Features (to appear in initial version)

* Progressive level generation
* Enemies
* Possibility to seed the game
* High-scores (Will initially probably be power-cycle dependent. If you power off the device, the high-scores will disappear. I'd like to fix this later.)
* Menu
* Boost items (weapons, shields, ...)

## Future Plans (not to appear in initial version)

* Intro sequence
* Bosses (The big ones, composed of several sprites. Like a dragon. Woot!)
* Music (I've got some samples, but I don't really have licence to use them legally. I'll either buy the licence or try to compose something I guess.)
* More environments (I'll probably start with just one, but would like to differentiate a bit later.)
* More everything (except bugs ;) )
* Less bugs :)

## I wanna help!

Cool! At this point, I'm still putting the code together and there's not much you can do in this manner, but if you can and want to supply some pixel art (a very small and delicate one, that is) or some music (I plan for 8-bit DAC and maybe an optional Yamaha chip later on), you're welcome!
