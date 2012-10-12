Chrome-Dev-tools-dark-theme
===========================

Using CSS filter `invert` function I was able to make a really quick "dark theme" for Chrome dev tools.
Some elements needed to revert back from being color inverted. List of elements that are required to 
revert back maybe is more than what I've found. Please let me know if you see any unusually colored element 
after applying this theme.

You can also "config" your source code colors using `hue-rotate()` or `brightness()` function at
`#-webkit-web-inspector .source-code` selector.

Replace the `Custom.css` file in your `"User Stylesheets"` folder. Here is how to find `Custom.css`:

* Mac:`~/Library/Application Support/Google/Chrome/Default/User StyleSheets/Custom.css`

* PC: `C:UsersYourUsernameAppDataLocalGoogleChromeUser DataDefaultUser StyleSheetsCustom.css`

* Ubuntu (Chromium): `~/.config/chromium/Default/User StyleSheets/Custom.css`