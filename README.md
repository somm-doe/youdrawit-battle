# You Draw It - Battle Edition

## About:
"You Draw It - Battle Edition" generates interactive charts that let users draw their guesses on how data changed over time, compare it to the actual data and the data of a rival city, sports club etc. You can see [a live demo here](https://youdrawit.schwaebische.de/fn-lindau/tippspiel/).

## Credits

Simon Haas

Bryony Miles (D3.js)

"You Draw It - Battle Edition" is [based on code](https://github.com/wdr-data/you-draw-it) published by the German public broadcaster WDR. A live demo of the "standard" edition [is available here](https://youdrawit.schwaebische.de/land-unter-merkel/tippspiel/).

[About us](https://www.schwaebische.de/impressum.html)

## License

"You Draw It - Battle Edition" is available under the terms of the [MIT License](/LICENSE).
Copyright (c) 2018 Schwäbische Zeitung

## Installation

### Dependencies
- [NodeJS](https://nodejs.org/), v4.x recommended
- Bower `npm install -g bower`
- Gulp `npm install -g gulp`
- Build tools `npm install` (within the project folder)
- Front-end libraries `bower install` (within the project folder)

### Configuration
- Replace mayor names in `app.js` or leave blank. Years define the term length and the start of user guesses.
- Replace city names in `app.js`
- Replace city names in `index.html` and adjust HTML
- Change CSS/Sass in `styles/` and HTML in `partials/`
- Replace images in `/images`
- Download [fonts](https://fonts.google.com/)
- Adjust font URL in `Gulpfile.js` (dlFonts)
- Replace data and city names in the YAML documents in `data/`
- Optional: Redirect users to `dist/` in `.htaccess` with `Redirect /youdrawit-battle/index.html https://youdrawit.schwaebische.de/youdrawit-battle/dist/`

## Usage

### Development server
```
gulp serve
```

### Live build under `dist/`
```
gulp build
```
