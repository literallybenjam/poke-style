# POKÉ-STYLE

Adds POKÉMON style effects to a webpage via pure CSS.

## INDICATING TYPE

You can add type-colouring to an element via the `data-pkmn-type` attribute. This will add a background to the element indicating the POKÉMON type. You can also use a combined type, in which case a gradient will be produced.

### examples:

- `<span data-pkmn-type="fire">FIRE BLAST</span>`
- `<span data-pkmn-type="fire-flying">FLETCHINDER</span>`

## POKÉ BALLS

You can display a POKÉBALL before an element using the `data-pkmn-ball` attribute (an empty `<span>` can be used to display only the ball). The following values are accepted:

| value         | ball          |
| :------------ | :------------ |
|  "poké"       |  POKÉ BALL    |
|  "great"      |  GREAT BALL   |
|  "ultra"      |  ULTRA BALL   |
|  "master"     |  MASTER BALL  |
|  "safari"     |  SAFARI BALL  |
|  "level"      |  LEVEL BALL   |
|  "lure"       |  LURE BALL    |
|  "moon"       |  MOON BALL    |
|  "friend"     |  FRIEND BALL  |
|  "love"       |  LOVE BALL    |
|  "heavy"      |  HEAVY BALL   |
|  "fast"       |  FAST BALL    |
|  "sport"      |  SPORT BALL   |
|  "premier"    |  PREMIER BALL |
|  "repeat"     |  REPEAT BALL  |
|  "timer"      |  TIMER BALL   |
|  "nest"       |  NEST BALL    |
|  "net"        |  NET BALL     |
|  "dive"       |  DIVE BALL    |
|  "luxury"     |  LUXURY BALL  |
|  "heal"       |  HEAL BALL    |
|  "quick"      |  QUICK BALL   |
|  "dusk"       |  DUSK BALL    |
|  "cherish"    |  CHERISH BALL |
|  "park"       |  PARK BALL    |
|  "dream"      |  DREAM BALL   |

POKÉ BALLS are inserted using a DATA URI, so they won't display on IE 7 or older.
