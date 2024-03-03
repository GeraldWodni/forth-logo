# Forth Logo
Official Logo of the [Forth Standard](https://forth-standard.org), [EuroForth](http://euroforth.org) and [theForth.net](https://theforth.net).

![Forth Logo](https://github.com/GeraldWodni/forth-logo/raw/master/forth-standard.org/forth.png "Forth Standard Logo")

## Motivation
When creating [the Forth net](https://theforth.net), I wanted a simple and sleek looking Logo and was inspired by [Haskell's simple lambda Logo](https://www.haskell.org/).
In Forth the only unchangeable syntax element is whitespace - which does not make a great logo ;)

So what is more iconic than the colon definition's `:` and `;` - let's use that!

## Construction
The Logo is pixelized and should not use any soft gradients for the Text and the shadow.
When scaling the logo use no interpolation to keep the hard edges.

The colon and the upper dot of the semicolon consist of a rectangle ` ` by ` ` units.
The shadow is inset by `1unit` and `1unit` tall.

The rectangle of the comma of the semicolon is `1unit` less tall.

The Logo consists of 3 colors:

__Background Color__: Use a simple color or a colorful gradient. Do not soften the gradient.

__Text Color__: Make sure to have enough contrast. For light backgrounds use `#424242`, for dark backgrounds use `#FFFFFF`.

__Shadow Color__: Match with background color, but keep it closer to the text's brightness.

Examples:
| Usecase                                      | Text      | Shadow    | Background | Comment                     |
|----------------------------------------------|-----------|-----------|------------|-----------------------------|
|[Forth Standard](https://forth-standard.org)\*| `#424242` | `#b71c1c` | `#ef5350`  | Uses material design 'red'  |
|[the Forth net](https://theForth.net)         | `#424242` | `#827717` | `#c6ff00`  | Uses material design 'lime' |
|[EuroForth](http://www.euroforth.org/)        | `#ffffff` | `#c6c6c6` | `#337ab7`  | Also intended for printing  |

\* intended as the main logo for `Forth`

![Forth Logo](https://github.com/GeraldWodni/forth-logo/raw/master/forth-standard.org/forth.png)

![the Forth net Logo](https://github.com/GeraldWodni/forth-logo/raw/master/theforth.net/forth.png)

![EuroForth](https://github.com/GeraldWodni/forth-logo/raw/master/euroforth/logo.png)

## License
`tl;dr:` Public Domain

`long:`
Although I would prefer a copyleft license I want to enable widespread usage also in cases where it might be considered comercial use. So I think Public Domain should give you the freedom you need. That being said, I would appreciate attribution if it suits your use case ;)

## Author
[Gerald Wodni](https://github.com/GeraldWodni)

