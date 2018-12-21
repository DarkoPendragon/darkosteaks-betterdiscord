# Darko's Tweaks Theme for BetterDiscord
***
A theme I've thrown together and will continue to update over time. Below will list it's basic features and info.  
If you have and ideas for the theme, feedback, need help or just want to chat swing by my [Discord server](https://discord.gg/FKYrX4X)!

# Usage
1) Add the desired theme to the themes folder for BD (/BetterDiscord/themes).
2) Reload Discord (unless auto reload is on).
3) Turn it on and enjoy!

# The File
## darkostweaks.theme.css
_This is a basic preview that does not feature all of the theme._  
![Normal Theme Image](_images/theme.png?raw=true "Title")

### Features
* Custom friend's tab remade
* Majority of the app is transparent, allowing for custom backgrounds
* Custom profile backgrounds depending on if a user is playing a game, streaming or listening to Spotify
* Custom backgrounds can be set in the theme file
* Modified channels area
* Guild Icons are squared, rather than rounded
* More to come!

## Var Options Explained
Since not everyone will completely understand how to change options of the theme (unless you're using a plugin to edit them). All defaults are listed in the `theme.css` root. Some useful links to help with setting these for those who may be confused: [Backgrounds](https://www.w3schools.com/css/css_background.asp), [Colors](https://www.w3schools.com/cssref/css_colors.asp), [Borders](https://www.w3schools.com/css/css_border.asp). The below won't go over everything, as some things are pretty self explanatory in the file itself.

1. `--mainback`
This sets the background property of the Discord app. This will be the image at the very back of everything. Changing the url in `url( )` will replace it with something other than the default, keep in mind it _must_ be a direct image link. You can also change it to a solid color such as black, a #hex color and so on.  

2. `--userpop`
This sets the background of user pop outs, the things that show when you click on someone's avatar in chat or someone on the members list. Pretty much the same thing as `--mainback`. Set it to whatever you like.  

3. `--normalback`
This nifty thing sets the normal background for users profiles (when you click "view profile" on a user prop out or side list). Pretty much the same as above.  

4. `--playingback`
Same as `-=normalback`, but sets the background of someone who is playing a game.

5. `--spotify`
Same as `-=normalback`, but sets the background of someone who listening to spotify.

6. `--streamingback`
Same as `-=normalback`, but sets the background of someone who is streaming a game.

7. `--rootwidth` & `--rootheight`
Sets the user profiles width and height. This does not effect every root element.
