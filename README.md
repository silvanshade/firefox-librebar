<div align="center">

![Firefox Onebar](https://codeberg.org/Freeplay/pages/raw/branch/master/project-assets/onebar/images/header.png)


<details>
<summary>

# What can it do?

</summary>

![Singe Tab as Titlebar](https://codeberg.org/Freeplay/pages/raw/commit/38b258e541938bcea7ad2e758b08f676343a8ac1/project-assets/onebar/images/single_tab.png)
![Compact Window Support](https://codeberg.org/Freeplay/pages/raw/commit/38b258e541938bcea7ad2e758b08f676343a8ac1/project-assets/onebar/images/compact_window.png)
![Works with _almost_ all customizations](https://codeberg.org/Freeplay/pages/raw/commit/38b258e541938bcea7ad2e758b08f676343a8ac1/project-assets/onebar/images/customizations.png)

</details>


</div>
<br><br>

---

<br>

# Installation

#### In Firefox
- Firstly, make sure you are on the latest firefox stable version.
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