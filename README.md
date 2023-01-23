# firefox-onebar [[ Skip to Installation ]](#user-content-installation)
My version of a single-bar layout for Firefox.

# Installation

#### In Firefox
1. Visit `about:config` 
    - Search for `toolkit.legacyUserProfileCustomizations.stylesheets`, set it to **true**
2. Visit `about:support`
3. In the `Profile Directory` row, copy the full path
    - May look something like: `/home/{username}/.mozilla/firefox/...`

#### Then, in a Terminal
```sh
cd #paste the path you copied before here

git clone https://codeberg.org/Freeplay/firefox-onebar.git
```

#### Restart Firefox, and enjoy :)