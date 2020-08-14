# Relax

Relax is a sound mixer full of relaxing and focusing sounds.

## Usage

To use it you will have to clone this repository and host the files yourself.

You can do this for now:

```
git clone ...
cd ...
python3 -m http.server
```

In the future I'm hoping to have it hosted on github.io or maybe even a full
application.

### Contributing / Developing

If you want to be able to produce the uglified/minified sources, you'll have to install the required dependencies like this:

```shell
npm install
```

The Makefile allows you to minify the js and the css files, using the following command:

```shell
make minify
```

Or you may chose to minify the JS or the CSS files:

```shell
make minify_js
make minify_css
```

## Why this project?

I've been listening to static-like noise for a long time to help me focus. I've
gone through a smorgasbord of programs and have rarely been entirely satisfied.

Noisli was the first application that really hit the money, albeit limited in
it's sound library. I was extremely disappointed to see them put up such a
massive paywall.

I found this project developed by Bruno Bord and decided to fork it and develop
it into a more comprehensive application dedicated to listening to sounds. I
don't find a need to have an integrated editor when you can just use other
editors while listening to sounds.

The goal is to have a self-contained application that anyone can just setup and
use.

## License

This project uses:

* [Editor.js, derived from this project](https://github.com/lepture/editor),
  by Hsiaoming Yang.
* [icomoon icons](https://icomoon.io/),
* [Glyphicons icons](https://glyphicons.com/),
* [Meteocons icons](http://www.alessioatzeni.com/meteocons/),
* The other font icons are made using the great
  [Fontello tool](http://fontello.com/), and come from Font Awesome, Entypo,
  Typicons, Maki, Elusive,
* [JQuery](https://jquery.com),
* [JPlayer](http://jplayer.org/),
* Fonts are [Ubuntu Mono](http://font.ubuntu.com/),
  [Lato](http://www.latofonts.com/lato-free-fonts/),
  [Roboto Slab](https://fonts.google.com/specimen/Roboto+Slab), provided by
  [Google Webfonts](https://www.google.com/fonts/)
* Responsive grid by the [.fitgrd project](http://www.fitgrd.com/)

## Sounds:

* [Rain in forest](https://www.freesound.org/people/inchadney/sounds/22132/) - by inchadney CC-BY,
* [rbh thunder storm](https://www.freesound.org/people/RHumphries/sounds/2523/) (storm with rain) - by RHumphries, CC-BY,
* [Storm](https://www.freesound.org/people/Erdie/sounds/23221/) by Erdie, CC-BY,
* [SummerEveningInMyGarden](https://www.freesound.org/people/acclivity/sounds/30832/), by acclivity - CC-BY-NC,
* [AMBIENT LOOP - Perfectly Clear - Wilderness Hillside - FILTERED](https://www.freesound.org/people/Arctura/sounds/39829/), by Arctura - CC-BY,
* [Vent - wind(1)](https://www.freesound.org/people/Glaneur%20de%20sons/sounds/104952/) by Glaneur de sons - CC-BY,
* [oceanwavescrushing.wav](https://www.freesound.org/people/Luftrum/sounds/48412/) by Luftrum - CC-BY,
* [fireplace](https://www.freesound.org/people/martats/sounds/138018/) by martats - CC-0,
* [131024_brook_black_forest.wav](https://www.freesound.org/people/reinsamba/sounds/204195/) by reinsamba - CC-BY,

All these sounds were suggested by [Jean-Michel Armand](https://github.com/mrjmad).

Apart from that, the rest of the code (HTML/CSS/JS) is mine and is published
under the terms of the [WTFPL](http://www.wtfpl.net/).
