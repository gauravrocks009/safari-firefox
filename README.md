# Safari-firefox
A highly refined, premium CSS theme that brings the sleek, flawless macOS Safari aesthetic to Firefox and Firefox based browsers. Built on top of the WhiteSur theme, this project fixes common visual glitches, perfects the UI elements, and introduces true Safari-like "Compact Mode" to firefox

SAFARI-FIREFOX

Instructions:

    This theme is compatible with the latest release of Firefox and works on windows and linux
    To enable adaptive colors, you need to install the Adaptive Tab Bar Color extension. If not, the tabs will appear transparent.

<img width="1920" height="1200" alt="Screenshot (1103)" src="https://github.com/user-attachments/assets/577860d5-5896-45ed-9a06-d53d6ad0839a" />

# 🚀 Installation

Follow these steps to install the Safari Firefox theme.

## 1. Open your Firefox profile

1. Open **Firefox**.
2. Type **`about:profiles`** in the address bar and press **Enter**.
3. Under the profile marked **Default**, click on the Root Directory  **Open Folder**.

![Open Firefox Profile](images/about-profiles.png)

---

## 2. Download the theme

Go to the GitHub repository:

**https://github.com/gauravrocks009/safari-firefox**

1. Open the **Releases** page.
2. Download the latest release.
3. Extract the archive if needed.
4. You'll find two files:

* `userChrome.css`
* `userContent.css`

![Download Release](images/releases.png)

---

## 3. Create the `chrome` folder

Inside your Firefox profile folder:

1. Create a new folder named:

```text
chrome
```

> **Important:** The folder name **must** be lowercase.

2. Copy both files into the `chrome` folder.

```
Profile Folder
│
└── chrome
    ├── userChrome.css
    └── userContent.css
```

---

## 4. Enable custom stylesheets

Open a new tab and go to:

```text
about:config
```

Accept the warning if prompted.

Search for each of the following preferences and set them to **`true`**:

| Preference                                            | Value    |
| ----------------------------------------------------- | -------- |
| `toolkit.legacyUserProfileCustomizations.stylesheets` | ✅ `true` |
| `svg.context-properties.content.enabled`              | ✅ `true` |
| `widget.non-native-theme.use-theme-accent`            | ✅ `true` |

![about Preferences](images/about-config.png)

---

## 5. Restart Firefox

Go back to **`about:profiles`** and click **Restart Normally**.

![Restart Firefox](images/restart-profile.png)

---

# ✅ Done!

Your browser should now be using the Safari Firefox theme.

If the theme doesn't apply:

* Make sure the folder is named **`chrome`** (all lowercase).
* Verify both CSS files are inside the `chrome` folder.
* Confirm all three `about:config` preferences are set to **`true`**.
* Restart Firefox again after making any changes.
