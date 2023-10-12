# Font Installation Guide

This guide will instruct you on how to install and use Bouazzi Maghribi font on various operating systems including Mac, Windows, and Linux. Additionally, it provides a simple usage guide for using the font on web pages.

## Mac

1. Download the font package and locate the `.ttf` or `.otf` file.
2. Open the Font Book app.
3. Drag and drop the font file into Font Book.
4. The font will now be available across the system.

## Windows

1. Download the font package and locate the `.ttf` or `.otf` file.
2. Right-click on the font file, then select `Install` from the dropdown menu.
3. The font will now be available across the system.

## Linux

1. Download the font package and locate the `.ttf` or `.otf` file.
2. Copy the font file to `/usr/share/fonts` or `~/.fonts` (create the folder if it doesn't exist).
3. Run the command `fc-cache -fv` in the terminal.
4. The font will now be available across the system.

## Web Font Usage

To use the mono-weight font on a web page, follow these steps:

1. Add a `@font-face` rule in your CSS file and include the location of your font file. Be sure to define a name for the font:

```css
@font-face {
  font-family: 'BouazziMaghribi';
  src: url('BouazziMaghribi.woff');
}
```

2. Use the `font-family` property with the name you provided in the `@font-face` rule:

```css
body {
  font-family: 'BouazziMaghribi', monospace;
}
```
3. Your website will now display text in BouazziMaghribi font.
