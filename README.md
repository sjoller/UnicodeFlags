# UnicodeFlags

Say goodbye to tiny pixelated flags from a sprite, and enjoy scaleable and detailed flags.

## Usage

This uses the CSS `:before` pseudo-element to add unicode flags to html elements.

Simply include the css file 

```html
<link href="https://path/to/css/unicode-flags.min.css" rel="stylesheet" type="text/css">
```

As Windows does not seem to include unicode flags in system fonts, the `NotoColorEmojiLimited` Google font is used to make sure it works everywhere. If you're not going to serve Windows users, the `no-fonts` css files can be used to skip the Google font

```html
<link href="https://path/to/css/unicode-flags-no-font.min.css" rel="stylesheet" type="text/css">
```

Then just add the `flag-[xy]` class to any HTML element (except `img` elements, where pseudo-elements won't work)

```html
<span class="flag-dk"></span>
```

Unicode country list extracted from [https://www.alt-codes.net/flags](https://www.alt-codes.net/flags)
