# Heroic Themes

A collection of community-made themes for [Heroic Games Launcher](https://github.com/Heroic-Games-Launcher/HeroicGamesLauncher)

## For Users
Change Heroic's appearance by choosing from a unique set of themes created by other users.

### Adding Themes to Heroic
Setup Heroic to look for custom themes:

1. Create a new folder, like "Heroic Themes", which is going to hold `.css` files of the themes.
2. In Heroic, go to **Accessibility**.
3. Under _Custom Themes Path_, click the folder icon.
4. Navigate to the path where you've created the folder and select the folder.

Now, you just need to add the `.css` files of themes to this folder. You can explore the different themes in the repository.

1. Choose a theme's folder.
2. Select _theme_name.css_ present in the folder.
3. Click **Raw**
4. Save the file to the folder you've setup. For example, just right-click and choose "Save" from the context menu.

Repeat the above steps for any theme.

Heroic should now show the newly added custom themes under _Select Theme_ in **Accessibility**! 

## For Contributers
Share custom-made themes for Heroic using CSS.

### Creating Themes
Refer this [guide](https://github.com/Heroic-Games-Launcher/HeroicGamesLauncher/wiki/Custom-Themes) for instructions and tips on how to create a theme.

### Submitting Themes
Stick to the following guidelines before submitting your theme:

1. The folder structure should look like this:

   ```bash
   Theme Name 
    ├── screenshot_name.png
    ├── theme_name.css 
    └── theme_name.json 

   ```

   Make sure to add two screenshots ateast.
   
 2. The `.json` file should share the same name as the `.css` file and include the following contents:
    
    ```json
    {
      "name" : "Theme Name",
      "filename" : "theme_name.css",
      "screenshots" : ["screenshot_name.png", "another_screenshot_name.png"],
      "author": "GitHub_username"
    }
    ```
 3. Fork this repository, create a new branch and add your theme's folder.
 4. Create a pull request.
