This is a bookmarklet to run on any page to analyse the contrast of the text on a page and highlight elements which may have readability issues.

Full Details: https://ada.is/blog/2016/02/12/contrast-bookmarklet/

## Build instructions for the Contrast Widget

```
npm install
npm run build
```

Open up `build/index.html` in Chrome to test the widget, it runs automatically on that page.

## Developing

`npm run watch` to build automatically.

## Building

Only update the version number if the bookmarklet has changed. The bookmarklet will compare against this number for prompting the user to update the widget.

## Todo

## Algorithmic improvements

* Handle semitransparent backgrounds better
* Ignore 0 area elements

## Usage improvements

* Option to turn off update checking.
