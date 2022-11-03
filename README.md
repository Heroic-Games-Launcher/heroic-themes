# Heroic Themes

A collection of community-made themes for [Heroic Games Launcher](https://github.com/Heroic-Games-Launcher/HeroicGamesLauncher)

## For Users
Change Heroic's appearance by choosing from a unique set of themes created by other users.

### Adding Themes to Heroic
(Explanation & Screenshots)

## For Contributers
Share custom-made themes for Heroic using CSS.

### Creating Themes
Refer this [guide](https://github.com/Heroic-Games-Launcher/HeroicGamesLauncher/wiki/Custom-Themes) for instructions and tips on how to create a theme.

### Submitting Themes
Stick to the following guidelines before submitting your theme -

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
      "screenshots" : ["screenshot_name.png", "another_screenshot_name.png"]
    }
    ```
 3. Fork this repository and add the theme folder
 4. Create a pull request
