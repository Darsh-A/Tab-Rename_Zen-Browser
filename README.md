# Tab Rename - Zen Browser

Adds a Rename Tab option in the Right-Click Menu for the tabs.


https://github.com/user-attachments/assets/e9720fd2-4df1-4c29-af6c-9bef67e3e7b6


## Method 1 (Recommended):
***Through [Sine](https://github.com/CosmoCreeper/Sine)***

Settings Can be configured through the mod settings through the Sine UI
*This also allows for Auto-Updates :D

## Method 2 (Manual):

### Pre-requisites:
- Enable userChrome Customizations: In `about:config` go to `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to True.
- Install and Setup the userChrome.js Loader from [Autoconfig](https://github.com/MrOtherGuy/fx-autoconfig/tree/master)
    - To verify the installation, see if the [test script](https://github.com/MrOtherGuy/fx-autoconfig/blob/3b04baa24a53b8bddb14e7bcf76f105026c6416c/profile/chrome/JS/test.uc.js) loads in the browser console (Ctrl+Alt+J) or (in Menu>More Tools>Browser Console)

### Install:
- Place (only) the script in your chrome/JS folder. (You would know where chrome folder is if you installed the userChrome manager)
- Go to `about:config` tab and reset `Startup Cache`

### Known Bugs:
- Name Persistent for non-pinned (temporary) tabs dont work if the user has set the option for "Dont close tabs at browser closer/restart"
    - This will result in a blank name, renaming this tab after browser restart will work.
- Duplicating the tab fails to load the renamed tab name and will just say `New Tab`

Contributions are appreciated 
