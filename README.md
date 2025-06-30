![alt text](https://github.com/girlcalledblu/ares-blu_in_space-theme/blob/main/homepage.png)

# Blu In Space! An Ares Theme...
This theme is very adaptable and flexible for whatever color scheme or font families you would like to use for your game. The core of this theme is derived from the Basic Blu theme, but adds lots of glow, provides a different icon, and has small sci-fi touches here and there. There's lots of room here to grow, but also a great place to start if you want any kind of science fiction theme. This theme has been adapted for rowdy Mandalorian games with deep brown and red accents, but also clean and crisp high-tech themes. The glow is easy to change and adapt, or remove entirely.

## Images
Unlike the Basic Blu package, this package includes some lovely starting places for images. Uniquely designed fav icons, box image, and a background image helps you get started with a general feel. These images are easy to replace within the `theme_images` folder on your game's files.

![alt text](https://github.com/girlcalledblu/ares-blu_in_space-theme/blob/main/favicons.png)

## Changing Colors
Use the built-in Theme Colors in the setup options. It will automatically update (almomst) all the colors in the theme. The muted rainbow colors and shades-of-grey can be tweaked in the CSS style file itself. Please note, there are two specific places where you are going to need to change using RGBA (this is a color-styling that uses red, green, blue, and opacity identifiers instead of hex code).

These two places uses the themes BOX-BACKGROUND-COLOR with opacity. You will find these in log-box and profile-box. If you're looking to change these RGBA values, you'll want to use a website like www.colorhexa.com to look up the RGB value; the A value is the level of opacity from 0 (invisible) to 1 (100% opacity).

## Changing Fonts
Select your favorite fonts from Google Fonts. You can import them using the @import feature. To update the fonts across the game, merely update the fonts in the top section of the CSS style file where you see "$body-font," "$primary-font," and "$secondary-font."

## Unique Features
This theme package has some unique features!

* If you use FS3, the Attribute, Skill, and Advantage dots on both the character sheet and character scene card will match the color scheme in the client;
* Job categories have been colored in rainbow order;
* Mobile response has been added and updated in a variety of elements;
* Calendar will utilize your theme colors.
* ProseMirror input styled to fit BasicBlu theme.

## A Couple Notes for Light Themes
As this theme was developed as a dark theme, there are a few small changes I recommend you make for themes with lighter backgrounds, the major one being I recommend you change all iterations of $DARK-GREY to $LIGHTER-GREY and $DARKER-GREY to $LIGHT-GREY. If you need help, you can find me in the Ares Discord server.
