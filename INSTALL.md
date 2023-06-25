### [Files](https://github.com/files-community/Files)

#### Install Using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:


git clone https://github.com/dracula/files.git

#### Install Manually

Download using the [GitHub .zip download](https://github.com/dracula/files/archive/master.zip) option and unzip them.

#### Activating Theme (when Installed Using Windows Store)

1. Go to `%userprofile%\AppData\Local\Packages\49306atecsolution.FilesUWP_et10x9a9vyk8t\LocalState\`
2. Create `Themes` folder
3. Move `Dracula.xaml` into `Themes` folder
4. Open files and go to settings, under appearance, there will be a drop-down menu labeled "color scheme". Use that to select your theme.
5. Restart Files

#### Activating Theme (when Installed Using The Community Version)

1. Go to the Files `settings` and click `Advanced`.
2. Inside advance click the `Edit Settings File`, which will open the `user_settings.json` 
3. Close Files before editing the `user_settings.json`. 
4. Inside the `user_settings.json` change the values of   
    ```json 
    "AppThemeBackgroundColor": "#00000000",
    "AppThemeAddressBarBackgroundColor": "",
    "AppThemeSidebarBackgroundColor": "",
    "AppThemeFileAreaBackgroundColor": "",
    ```
   to

   ```json
    "AppThemeBackgroundColor": "#282a36",
    "AppThemeAddressBarBackgroundColor": "#44475a",
    "AppThemeSidebarBackgroundColor": "#44475a",
    "AppThemeFileAreaBackgroundColor": "#282a36",
   ``` 
5. Open Files 🧛