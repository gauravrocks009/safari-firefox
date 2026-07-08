# Safari-firefox
A highly refined, premium CSS theme that brings the sleek, flawless macOS Safari aesthetic to Firefox and Firefox based browsers. Built on top of the WhiteSur theme, this project fixes common visual glitches, perfects the UI elements, and introduces true Safari-like "Compact Mode" to firefox

SAFARI-FIREFOX

Instructions:

    This theme is compatible with the latest release of Firefox and works on windows and linux
    To enable adaptive colors, you need to install the Adaptive Tab Bar Color extension. If not, the tabs will appear transparent.

<img width="1920" height="1200" alt="Screenshot (1103)" src="https://github.com/user-attachments/assets/577860d5-5896-45ed-9a06-d53d6ad0839a" />

 
# How to Install the Safari Firefox Theme

1. Open **Firefox**.

2. In the address bar, type **`about:profiles`** and press **Enter**.

3. Under the profile marked as **Default**, click **Open Folder**.

4. Download the latest CSS files from my GitHub repository:

   * Go to: **https://github.com/gauravrocks009/safari-firefox**
   * Open the **Releases** page.
   * Download the latest versions of:

     * `userChrome.css`
     * `userContent.css`

5. In the Firefox profile folder that you opened earlier, create a new folder named:

   ```text
   chrome
   ```

   > Make sure the folder name is all lowercase.

6. Copy both `userChrome.css` and `userContent.css` into the `chrome` folder.

7. Open a new Firefox tab and go to:

   ```text
   about:config
   ```

8. Enable the required preference shown in the screenshot:

   * Search for `toolkit.legacyUserProfileCustomizations.stylesheets`
   * Set it to **true**.

9. Go back to the **`about:profiles`** page.

10. Click **Restart Normally**.

That's it! The theme should now be applied.
